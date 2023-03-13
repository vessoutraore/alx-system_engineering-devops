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

[4-lastlines](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines "4-lastlines"): Script that displays the last 10 lines of /etc/passwd.

[5-firstlines](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines "5-firstlines"): Script that displays the first 10 lines of /etc/passwd.

[6-thirdlines](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line "6-third_line"): Script that displays the third line of the iacta.

[7-file](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file "7-file"): Write a shell script that creates a file named exactly "\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)" containing the text Best School ending by a new line.

[8-cwd_state](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state "8-cw_state"): script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

[9-duplicate_last_line](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line "9-duplicate_last_line"):  script that duplicates the last line of the file iacta. The file iacta will be in the working directory 

[10-no_more_js](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js "10-no_more_js"):  script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its. 

[11-directories](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories "11-directories"):Script that counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account. Hidden directories should be counted 

[12-newest_files](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files "12-newest_files"): Script that displays the 10 newest files in the current directory. Requirements: One file per line. Sorted from the newest to the oldest 

[13-unique](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique "13-unique"): script that takes a list of words as input and prints only words that appear exactly once. Input format: One line, one word. Output format: One line, one word. Words should be sorted

[14-findthatword](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword "14-findthatword"): script that displays lines containing the pattern "root" from the file /etc/passwd .

[15-countthatword](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-counthatword "15-counthatword"): script that displays the number of lines that contain the pattern "bin" in the file /etc/passwd .

[16-whatsnext](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext "16-whatsnext"): Script that display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

[17-hidethisword](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword "17-hidethisword"): Script that display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

[18-letteronly](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly "18-letteronly"): Script that display all lines of the file /etc/ssh/sshd_config starting with a letter.include capital letters as well.

[19-AZ](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ "19-AZ"): Script that replace all characters A and c from input to Z and e respectively 

[20-hiago](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago "20-hiago"): Script that creates removes all letters c and C from input.
