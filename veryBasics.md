# Run code in GCC
To setup your file as an indentifier on the terminal (without brackets), or after any change was made in it's code
```
> gcc -o <code_name> <file_name.c>
```
To run it
```
> ./<code_name>
```
# Libraries
```
#include <library>
```
## Built-in
```
#include <stdio.h> //standard in and out
#include <stdlib.h> //other unsorted functions
#include <string.h> //basic and necessary tools for string manipulation
#include <math.h> //everything mathematical
```

### stdlib
```atoi()``` converts an elegible string to integer

### string
```strlen()``` returns an integer with the amount of characters on a string

```strcmp(str1, str2)``` returns 0 if ```str1``` and ```str2``` are the same

```strncopy(str1, str2, pos)``` copies a piece of ```str1```, from the character in position ```pos``` to its last character, to ```str2``` 

## External

# Functions
```sizeof()``` returns the size in bytes occupied by the variable

```sprintf(var2 + pos, typeStr, var1)``` converts ```var1``` to ```var2``` based on the format specifier at ```typeStr```. If the first parameter is given as ```var2 + pos```, and ```var1``` and ```var2``` are strings, then ```var1``` will be converted to ```var2``` on the position pos.
## Printing
```printf()``` prints a string, without ```"\n"``` on it's end.

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
To specify the decimal precision (rounding) of a float or a double number, use ```%.nf``` or ```%.nlf```, with n meaning the number of digits to be displayed:
```
float numf1 = 5.4564, numf2 = 8.12423; //
double numd1 = 12.3265, numd2 = 2.12475;

    printf("Float: num1: %.1f, num2: %.2f\n", numf1, numf2);    //5.5 and 8.12
    printf("Double: num1: %.3lf, num2: %.4lf\n", numd1, numd2); //12.326 and 2.1248
```
### Escape sequences
```\n``` new line

```\t``` horizontal tab

```\\``` backslash character

```\"``` double quote character

### Special characters
Porcentagem: ```%%```

M. delta: ```\u0394```

# Variables

## Types

```int``` (2-4 bytes), ```float``` (4 bytes), ```double``` (8 bytes) and ```char``` (1 byte)

Notation for big or small numbers
```
24,000 == 24e3 == 24E3
0.0024 == 24e-3 == 24E-3
```
Keyword for the variable manipulation:

```const int```, ```const double```, ```const char```, ... Defines the variable as constant on the code.

## Strings

```
char frase[9];
```
declarates a string with a maximum space of 9 characters
```
int i;
char phrase[i];
```
declarates a string with a maximum space of i characters

## Arrays


