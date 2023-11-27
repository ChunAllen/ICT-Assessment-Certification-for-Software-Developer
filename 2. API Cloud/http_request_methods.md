# HTTP

HTTP defines a set of request methods to indicate the desired action to be performed for a given resource. Although they can also be nouns, these request methods are sometimes referred to as HTTP verbs. Each of them implements a different semantic, but some common features are shared by a group of them: e.g. a request method can be safe, idempotent, or cacheable.

##### HTTP Request Method
- **GET** - The GET method requests a representation of the specified resource. Requests using GET should only retrieve data.

- **HEAD** - The HEAD method asks for a response identical to a GET request, but without the response body.

- **POST** - The POST method submits an entity to the specified resource, often causing a change in state or side effects on the server.

- **PUT** - The PUT method replaces all current representations of the target resource with the request payload.  is a technique of altering resources when the client transmits data that revamps the whole resource

- **PATCH** -  is a technique for transforming the resources when the client transmits partial data that will be updated without changing the whole data

- **DELETE** - The DELETE method deletes the specified resource.

- **CONNECT** - method establishes a tunnel to the server identified by the target resource.

- **OPTIONS** - The OPTIONS method describes the communication options for the target resource.

- **TRACE** - The TRACE method performs a message loop-back test along the path to the target resource.