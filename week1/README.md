# C


Include the input output library
```c
#include <stdio.h>
```

Hello world program
```c
int main(void)
{
  printf("hello, world\n");
}
```
Then compile and run
```bash
# Compile into hello file
clang -o hello hello.c
# Or the shorter version
make hello
# Run machine code
./hello
```

Declaring a variable
```c
// DataType VariableName = Value; for example
int integer = 5;
```

Primitive data types

Data Type | Role | Size | Range
--- | --- | --- | ---
int | Integer number | 4 B | 2<sup>-31</sup> to 2<sup>31</sup> - 1
unsigned int | Integer number | 4 B | 0 to 2<sup>32</sup> - 1
float | Float number (with decimal points) | 4 B | N/A
double | bigger Float | 8 B | N/A
char | a single character | 1 B | -128 to 127

printf arguments

shortcut | meaning
--- | ---
%s | String
%i | Integer
%f | Float
%d | Double
%c | Char

Operators

Operator | Meaning
--- | ---
+ | Plus
- | Minus
/ | Division
* | Multiplication
% | Modulus

Conditional if statement
```c
if ( condition )
{
  // Task....
}
else if
{
  // Task...
}
else
{
  // Task...
}
```

Conditional Switch
```c
switch(option)
{
  case option_1: // Do something
  case option_2:
        // Do something for both cases
        break;
}
```

Conditions

Condition | Meaning
--- | ---
== | Equal to
\> | Greater than
< | Less than
\>= | Greater or equal to
<= | Less or equal to
!= | Not equal to
&& | And
&#124;&#124; | Or
! | Not

Loops

```c
// While loop
while(condition)
{
  // Do repeatedly
}
// Do - while loop
do
{
  // Do repeatedly
}
while(condition)
// For loop
for ( start; condition; counter )
{
  // Do repeatedly
}

```


Other terminal commands
```bash
# View files in a directory
ls
# View files + hidden files
ls -a
# Move into a sub directory
cd [name of directory]
# Move into parent directory
cd ..
# Make a new directory
mkdir [name of directory]
# Make directory and make appropriate parent directories
mkdir -p [/name of parent directory / name of directory]
# Remove an empty directory
rmdir [name of directory]
# Show current working directory path
pwd
# Copy a file
cp <source file> <destination file>
# Copy a directory recursively
cp -r <source dir> <destination dir>
# Remove a file
rm <filename>
# Remove with force
rm -f <filename>
# Remove a directory with contents recursively
rm -rf <directory name>
# Move a file
mv <source file> <destination file>
# Create a new file
touch <filename>
# Open a file
open <filename>
# Get root access
sudo <command...>
# Change access permissions
chmod ...
# Clean screen
ctrl + l
# Kill program
ctrl + c
```
