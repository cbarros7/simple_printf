# Simple Printf - Holberton School :octocat:

## Synopsis :thought_balloon:
It is a simple prototype of the original printf function used in the C.

## Description :speech_balloon:
This function is designed to output according to a format as detailed below. This function writes its output to the standard output, the standard output stream. 


## Requeriments :bookmark_tabs:

* Allowed editors: ```vi```, ```vim```, ```emacs```
* Programs and functions will be compiled with ```gcc 4.8.4``` using the flags ```-Wall``` ```-Werror``` ```-Wextra``` ```and -pedantic```
* All files should end with a new line
* Code should use the ```Betty``` style. it will be checked using [betty-style.pl](https://github.com/holbertonschool/Betty/blob/master/betty-style\
.pl) and [betty-doc.pl](https://github.com/holbertonschool/Betty/blob/master/betty-doc.pl)
* No more than 5 functions per file
* All your header files should be include guarded
* Authorized functions and macros: 

    * ```write```(man 2 write)
    * ```malloc``` (man 3 malloc)
    * ```free``` (man 3 free)
    * ```va_start ``` (man 3 va_start)
    * ```va_end``` (man 3 va_end)
    * ```va_copy``` (man 3 va_copy)
    * ```va_arg``` (man 3 va_arg)


## Quick start :runner:
Git clone the repository:

```
git clone https://github.com/cbarros7/simple_printf.git
```

## Usage :computer:
All the files are to be compiled on an Ubuntu 14.04 LTS machine with:
```
gcc -Wall -Werror -Wextra -pedantic *.c -o printf
```

Once compiled, to start the program, run:
```./printf```
  
  
## Options :computer:
To use _printf you have to use the following key characters preceeded by **%** symbol.

| Function Name | Description |
|---------------- | -----------|
|%c | To be used to print characters.|
|%s | To be used to print strings.|
|%i | To be used to print number integers.|
|%d | To be used to print number integers.|
|%x | To be used to print number in octal .|
|%% | To be used to print a porcentage symbol.|


## List of functions :page_facing_up:

| Function Name | Description |
|---------------- | -----------|
|[find_match](https://github.com/cbarros7/printf/blob/master/find_match.c) | Find coincidences in the string.|
|[_printf](https://github.com/josevallejo1984/printf/blob/master/_printf.c) | Copy of funtion boult.in printf.|
|[print_int](https://github.com/cbarros7/printf/blob/master/function.c) | Print integer and length. |
|[print_char](https://github.com/cbarros7/printf/blob/master/function.c) | Print character and length. |
|[print_str](https://github.com/cbarros7/printf/blob/master/function.c) | Print character to character and length. |
|[print_porcent](https://github.com/cbarros7/printf/blob/master/function.c) | Print simbol %%. |
|[_write_char](https://github.com/cbarros7/printf/blob/master/_write.c) | Writes the character c to stdout. |

## Examples program :notebook_with_decorative_cover:
| Use cases|
|----------------|
|_printf("%c", 'S');
|_printf("A char inside a sentence: %c. Did it work?\n", 'F');
|_printf("Let'see if the cast is correctly done: %c. Did it work?\n", 48);
|_printf("%s", "This sentence is retrieved from va_args!\n");
|_printf("Complete the sentence: You %s nothing, Jon Snow.\n", "know");
|_printf("Complete the sentence: You %s nothing, Jon Snow.\n", (char *)0);
|_printf("%c%cth %s%s a%cg%s: Y%sou %s no%ching%s Snow.%c", 'W', 'i', "some ", "more", 'r', "s", "", "know", 't', ", Jon", '\n');]
|_printf("%%");
|_printf("Should print a single percent sign: %%\n");
|_printf("%s%c%c%c%s%%%s%c", "Loading ", '.', '.', '.', " 99", " Please wait", '\n');
|_printf("css%ccs%scscscs\n", 'T', "Test");
|_printf(NULL);
|_printf("%c", '\0');
|_printf("%");
|_printf("%!\n");
|_printf("%K\n");


## Return :clap:

The function will always return an integer, corresponding to the symbol, without countingthe null string. 

## Bugs :loudspeaker:
No known bugs.

## Authors :black_nib:
**Carlos Barros** [Github](https://github.com/cbarros7)
                  [LinkdIn](https://www.linkedin.com/in/carlosbarros7/)

## Acknowledgements :pray:
Thanks to all the software engineers, colleagues from different cohorts of the Holberton School, for all the learning we have been able to acquire in this project, it has undoubtedly allowed us to expand our knowledge in the C programming language. 

For more information about Holberton, visit this [link](https://www.holbertonschool.com/).

<p align="center">
<img src="http://www.holbertonschool.com/holberton-logo.png" alt="Holberton School logo">
</p>
