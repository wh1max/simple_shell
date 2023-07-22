![Shell!](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg)

# Description
This project is an implementation of a custom shell, also known as a command-line interpreter or CLI (Command-Line Interface). A shell is a fundamental component of most operating systems, providing a user interface to interact with the system through commands and scripts.

# Resources

### Read or watch:

1. [Unix shell](https://intranet.alxswe.com/rltoken/f0YU9TAhniMXWlSXtb64Yw)
2. [Thompson shell](https://intranet.alxswe.com/rltoken/7LJOp2qP7qHUcsOK2-F3qA)
3. [Ken Thompson](https://intranet.alxswe.com/rltoken/wTSu31ZP1f7fFTJFgRQC7w)


### man or help:

sh (Run sh as well)

## This shell was built and tested on Ubuntu 18.04

#### Your code will be compiled this way:
    gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

# Testing
### Your shell should work like this in interactive mode:

    $ ./hsh
  
     ($) /bin/ls
  
     hsh main.c shell.c
  
     ($)
  
     ($) exit
    $
### But also in non-interactive mode:

    $ echo "/bin/ls" | ./hsh
    
    hsh main.c shell.c test_ls_2
    
    $
    
    $ cat test_ls_2
    
    /bin/ls
    
    /bin/ls
    
    $
    
    $ cat test_ls_2 | ./hsh
    
    hsh main.c shell.c test_ls_2
    
    hsh main.c shell.c test_ls_2
    
    $
