# libft
## Description
School 21 (Ecole 42) project which goal is to recreate some functions from C standard library.
## Install
```
git clone https://github.com/fedor-postnikov/libft.git
cd libft
make
```
## Usage
1) Include libft.h in your program  
2) Set proper path to include directory with -I compiler option.  
3) Specify path to library with -L compiler flag.  
4) Link your executable with libft library with -lft compiler option.  
5) Now you can call libft functions in your code.
  
How to compile example:
```
gcc -I./libft/ main.o -L ./libft/ -lft -o main
```
