# Testing


#### Unit Testing
A unit test is a type of software test that focuses on components of a software product. The purpose is to ensure that each unit of software code works as expected. A unit can be a function, method, module, object or other entity in an application's source code. 

##### Unit tests usually consist of three phases: 

1) Planning—developers consider which units in the code they need to test, and how to execute all relevant functionality of each unit to test it effectively.
2) Test cases and scripts—developers write the unit test code and prepare the scripts to execute the code.
3) Unit testing and results—finally, the unit test runs and developers can identify errors or issues in the code and fix them.

Test-driven development (TDD) is a common approach to unit testing. It requires the developer to create the unit test first, before the application code actually exists. Naturally, that initial test will fail. Then the developer adds the relevant functionality to the application until the tests pass. TDD usually results in a high quality, consistent codebase.

#### Integration Testing
Integration testing involves testing software modules and the interaction between them. It tests groups of logically integrated modules
Integration tests are also called thread testing, because they focus on communication between software components. Integration testing is important because most software projects consist of several independent, connected modules

#### The main difference between unit tests and integration tests is what and how they test: 

- Unit tests test a single piece of code, while integration tests test modules of code to understand how they work individually and interact with each other.
- Unit tests are fast and easy to run because they “mock out” external dependencies. Integration tests are more complex and require more resources to run because they must consider both internal and external dependencies (“real” dependencies).

#### Functional Testing
Evaluating the software's functionality from the user's viewpoint 

- Focuses on entire software
- Covers performance and functionality
- No need be the same programming language as the application 
- Both authomation and manual testing is required for functional testing

#### White Box Testing
is a form of application testing that provides the tester with **complete knowledge** of the application being tested, including access to source code and design documents

- Sample of White Box testing is Unit Testing
- Testing the output based on the input

#### Black Box Testing
is a form of testing that is performed with **no knowledge** of a system's internals,

- Sample of Black Box Testing is Functional Testing

#### Regression Testing
Regression testing is a type of software testing that evaluates whether a change in the application introduced defects.
It is used to determine if code changes can harm or interfere with the way an application behaves or consumes resources. In general, unit tests are regression tests, but not all regression tests are unit tests. 


Regression tests are primarily used after a programmer has completed a certain feature. Regression testing serves as a system-wide check to ensure that components that were not affected by a recent change continue to work as expected. It can include several types of tests. As part of a regression test suite, developers can run unit tests, to verify that individual features and variables behave as expected even after the change. 



