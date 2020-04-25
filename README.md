# Simple Shell - Holberton School :robot:

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
gcc -Wall -Werror -Wextra -pedantic *.c printf
```

Once compiled, to start the program, run:
```./printf```
  
  
The **Mr. Robot** supports most shell commands, such as ```cat```, ```pwd```, ```ls -la``` and more.


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

## Syntax :notebook_with_decorative_cover:
**Mr. Robot** the user can have the experience in an interactive and non-interactive way. On the one hand, if it is invoked with a standard input that is not connected to the terminal, *Mr. Robot* reads and executes the received commands in order.

To use the **Mr. Robot** interactive mode use isatty(3). Immediately the user will see a warning $ indicating that our shell is ready to read the command.

On the other hand, in non-interactive mode the user will enter command line arguments, so **Mr. Robot** treats the first argument as a file from which to read the commands.
In interactive mode, you can type commands from the keyboard:

Example:
```
$ ./hsh
$ /bin/ls
```
In non-interactive mode, you can pipe commands into the program using echo or cat:

Non-interactive:

Example:
```
$ echo "/bin/ls" | ./hsh
$ cat file_name | ./hsh
```

You can use the same syntax for running commands in other shells:
```
<command> <flags or options> <argument 1> <argument 2> ...
```

In non-interactive mode:
```
<command> | ./hsh
```


## Return :clap:

The function will always return an integer, corresponding to the symbol, without countingthe null string. 

## Bugs :loudspeaker:
No known bugs.

## Annotations :loudspeaker:
We have written an [**article**](https://www.linkedin.com/pulse/ls-l-command-understanding-what-happens-shell-carlos-barros/) in which we deepen the internal processes within the shell by typing the command "ls -l". We talk about fundamental elements such as the PATH, and conclude with the permission structure with some examples. 

## Authors :black_nib:
* **Carlos Barros** [Github](https://github.com/cbarros7) [LinkedIn](https://www.linkedin.com/in/carlosbarros7/]

## Acknowledgements :pray:
Thanks to all the software engineers, peers from different cohorts of the Holberton School, for all the learning that we have been able to acquire in this academic period culminating in this shell emulation. 

For more information about Holberton, visit this [link](https://www.holbertonschool.com/).

<p align="center">
<img src="http://www.holbertonschool.com/holberton-logo.png" alt="Holberton School logo">
</p>
