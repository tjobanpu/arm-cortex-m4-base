# Introduction
This project should give a good starting point to develop a bare metal embedded program with gcc. 
The target architecture of this project is the cortex m4 from arm, but the project can easily be adapted to 
other architectures as well.

# Toolchain
On windows the following programs can be used to compile the project:
* [Gcc arm embedded compiler (4.9.3)](https://launchpad.net/gcc-arm-embedded) 
* Make:
** (Cygwin)[https://www.cygwin.com/]
** (MinGW - MSYS)[https://www.cygwin.com/] 

# GCC
The gcc manual (4.9.3) can be found [here](https://gcc.gnu.org/onlinedocs/gcc-4.9.3/gcc/index.html#toc_Top). Its quite usefull as 
reference for the used compiler switches.

For this project the following topics in this manual are of special interest:
* [Optimize-Options](https://gcc.gnu.org/onlinedocs/gcc-4.9.3/gcc/Optimize-Options.html#Optimize-Options)
* [Preprocessor Options](https://gcc.gnu.org/onlinedocs/gcc-4.9.3/gcc/Preprocessor-Options.html#Preprocessor-Options) - They are used for automatic dependency generation.

# Makefile 
The gnu make manual can be found [here](http://www.gnu.org/software/make/manual/html_node/index.html).

For this project the following topics in this manual are of special interest:
* [Recipe Echoing](http://www.gnu.org/software/make/manual/make.html#Echoing)
* [Automatic Variables](http://www.gnu.org/software/make/manual/html_node/Automatic-Variables.html)
* [Functions for String Substitution and Analysis](http://www.gnu.org/software/make/manual/html_node/Text-Functions.html#Text-Functions)
* [Substitution References](http://www.gnu.org/software/make/manual/html_node/Substitution-Refs.html#Substitution-Refs)