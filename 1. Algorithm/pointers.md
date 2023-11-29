# Pointers
- is defined as an object that stores a memory address
- A pointer is a variable which holds the address of other variable of the specified data type(like int,float,char). In programming we basically use pointers to store the other variable’s address
- A pointer variable is declared with a `*` before it. 


#### Examples
```
int x = 4 // integer named x is set to 4
int * pX = &x; // integer pointer named pX is set to the address of x;


int * pX = &x; 
int y = *pX; // integer named y is set to the address of pX;
~``