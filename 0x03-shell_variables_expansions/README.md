# 0x03. Shell, init files, variables and expansions

## Resources
### Read or watch:

* Expansions
* Shell Arithmetic
* Variables
* Shell initialization files
* The alias Command
* Technical Writing

### man or help:

* printenv
* set
* unset
* export
* alias
* unalias
* .
* source
* printf

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

* What happens when you type $ ls -l *.txt

## Shell Initialization Files

* What are the /etc/profile file and the /etc/profile.d directory
* What is the ~/.bashrc file

## Variables

* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update and delete shell variables
* What are the roles of the following reserved variables: HOME, PATH, PS1
* What are special parameters
* What is the special parameter $??
## Expansions

* What is expansion and how to use them
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with $() and backticks

## Shell Arithmetic

* How to perform arithmetic operations with the shell

## The alias Command

* How to create an alias
* How to list aliases
* How to temporarily disable an alias

## Other help pages

* How to execute commands from a file in the current shell

## Requirements

### General

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use &&, || or ;
* You are not allowed to use bc, sed or awk
* All your files must be executable

## More Info

Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

Look at some files in the /etc/profile.d directory.

Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.

# All your scripts should be two lines

[0-alias](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/0-alias "0-alias"): Script that create an alias. Name: ls et valeur :rm *

[1-hello_you](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/1-hello_you "1-hello_you"): Script that prints hello user, where user is the current Linux user. 

[2-path](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/2-path "2-path"): Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

[3-paths](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/2-paths "2-paths"): Script that counts the number of directories in the PATH.

[4-global_variables](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/4-global_variables "4-global_variables"): Script that lists environment variables.

[5-ocal_variables](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/5-local_variables "5-local_variables"): cript that lists all local variables and environment variables, and functions.

[6-create_local_variable](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/6-create_local_variable "6-create_local_variable"): Script that creates a new local variable.

[7-create_global_variable](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/7-create_global_variable "7-create_global_variable"): Script that creates a new global variable.
