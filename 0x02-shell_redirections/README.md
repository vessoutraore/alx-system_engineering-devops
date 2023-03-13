# 0x02. Shell, I/O Redirections and filters

## Resources
### Read or watch:

[Shell, I/O Redirection](http://linuxcommand.org/lc3_lts0070.php "Shell, I/O Redirection")
[Special Characters](http://mywiki.wooledge.org/BashGuide/SpecialCharacters "Special Characters")
### man or help:

* echo
* cat
* head
* tail
* find
* wc
* sort
* uniq
* grep
* tr
* rev
* cut
* passwd (5) (i.e. man 5 passwd)

## Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/?fbclid=IwAR2K5_BGPVo0QjJXkOIIqNsqcXK4lTskPWJvA0asKQIGtCPWaQBdKmj1Ztg "explain to anyone"), without the help of Google:

1. Shell, I/O Redirection

* What do the commands head, tail, find, wc, sort, uniq, grep, tr do
* How to redirect standard output to a file
* How to get standard input from a file instead of the keyboard
* How to send the output from one program to the input of another program
* How to combine commands and filters with redirections

2. Special Characters

* What are special characters
* Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them

3. Other Man Pages

* How to display a line of text
* How to concatenate files and print on the standard output
* How to reverse a string
* How to remove sections from each line of files
* What is the /etc/passwd file and what is its format
* What is the /etc/shadow file and what is its format

## Requirements
### General
* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable
* You are not allowed to use sed or awk
### More Info
Read your /etc/passwd and /etc/shadow files.

Note: You do not have to learn about fmt, pr, du, gzip, tar, lpr, sed and awk yet.

*All your scripts should exactly be two lines* 

[0.Hello World](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world "0-hello_world"): Script that prints “Hello, World”, followed by a new line to the standard output.
[1.Confused smiley](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley "1-confused_smiley"): script that displays a confused smiley "(Ôo)'.

[2-hellofile](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile "2-hellofile"): Script that displays the content of the /etc/passwd file.

[3-twofiles](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles "3-twofiles"): Script that displays the content of the /etc/passwd and /etc/hosts.

[4-lastlines](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles "3-twofiles"): Script that displays the last 10 lines of /etc/passwd.