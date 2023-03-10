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

[8-true_knowledge](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/8-true_knowledge "8-true_knowledge"): Script  that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.

[9-divide_and_rule](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/9-divide_and_rule "9-divide_and_rule"): Script that prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables

[10-love_exponent_breath](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/10-love_exponent_breath "10-love_exponent_breath"): Script that displays the result of BREATH to the power LOVE. BREATH and LOVE are environment variables. The script should display the result, followed by a new line

[11-binary_to_decimal](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/11-binary_to_decimal "11-binary_to_decimal"): Script that converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable BINARY. The script should display the number in base 10, followed by a new line

[12-combinations](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/12-combinations "l2-combinations"): Script that prints all possible combinations of two letters, except oo. Letters are lower cases, from a to z. One combination per line. The output should be alpha ordered, starting with aa. Do not print oo. Your script file should contain maximum 64 characters

[13-print_float](https://github.com/vessoutraore/alx-system_engineering-devops/tree/master/13-print_float "l3-print_float"): Script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM.
