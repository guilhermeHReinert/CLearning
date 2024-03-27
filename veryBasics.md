# Run code in GCC
To setup your file as an indentifier on the terminal (without brackets), or after any change was made in it's code
```
gcc -o <code_name> <file_name.c>
```
To run it
```
./<code_name>
```
# Libraries
```
#include <library>
```
## Built-in
```
#include <stdio.h>
```
## External

# Functions
## Printing
```
printf() //prints a string without "\n"
```
### Format Specifiers
```
int numI = 13;
float numF = 1.3;
double numD 2.6;
char charizard = 'G';
char texto[] = "texto?";

printf("%d", numI); //or %i
printf("%f", numF); //or %F
printf("%lf", numD);
printf("%c", charizard);
printf("%s", texto);

printf("The int %d, the float %f, the double %lf, the char %c and the string %s",
        numI, numF, numD, charizard, texto);

```
### Escape sequences
```
\n //new line
\t //horizontal tab
\\ //backslash character
\" //double quote character
```
# Variables

## Types

```int``` (2-4 bytes), ```float``` (4 bytes), ```double``` (8 bytes) and ```char``` (1 byte)

Notation for big or small numbers
```
24,000 == 24e3 == 24E3
0.0024 == 24e-3 == 24E-3
```

## Strings


## Arrays


