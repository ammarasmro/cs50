# C

Source code ---> Compiler ---> Machine code

```bash
clang hello.c -lcs50 # To link a library
```

Access manual pages for commands
```bash
man <command>
```

To get the length of the string
```c
strlen("text")
```

> Null value at the end of a string in C is represented by `'\n'`

## Arrays
Items stacked back to back to back to back. Contiguous memory locations.

Example
```c
// type name[size];
string names[5];
// type name[size] = {e1,e2,...}
int sizes[] = {1,2,3};
// Two dimensional
// type name[size][size]
int board[10][10];
// Access
// array[index]
arr[0];
```
To copy arrays, they need to be copied element by element.

> Arrays are **passed by reference**. The **callee** gets the actual array.

To pass arguments to the program
```c
int main(int argc, string argv[]){}
```

## Cryptography

plain text ---> cryptic text

a -> b ...
b -> c
.
.
z -> a

key * text --> encrypted text

## Variables

Example
```c
float global = 2.3;
```

function to change string to integer
```c
int a = atoi(string);
```

> Local variables in C. local variables are **passed by value**. When means functions receive a copy of the variables and not the variables themselves.

## Magic numbers
Symbolic constants are declared by
```c
// #define NAME REPLACEMENT
#define PI 3.14
```
