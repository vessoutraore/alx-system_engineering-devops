# 0x00-shell_basics

All your scripts should be exactly two lines long in the differents files

![Shell](https://user-images.githubusercontent.com/126578500/224369569-150e047b-6f6d-4fd6-8ceb-8dc77c2977c3.jpg)

[0. Where am I?](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/0-current_working_directory "0-current_working_directory"): Script that prints the absolute path name of the current working directory.

[1. What’s in there?](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/1-listit "1-listit"): Script that display the contents list of your current directory.

[2. There is no place like home?](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/2-bring_me_home "2-bring_me_home"): Script that changes the working directory to the user’s home directory. You are not allowed to use any shell variables.

[3. The long format](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/3-listfiles "3-listfiles"): Script that display current directory contents in a long format.

[4. Hidden files](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/4-listmorefiles "4-listmorefiles"): Script that display current directory contents, including hidden files (starting with .). Use the long format.

[5. I love numbers](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/5-listfilesdigitonly "5-listfilesdigitonly"): Script that Display current directory contents.
* Long format
* with user and group IDs displayed numerically
* And hidden files (starting with .)

[6. Welcome](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/6-firstdirectory "6-firstdirectory"): Script that create a script that creates a directory named my_first_directory in the /tmp/ directory.

[7. Betty in my first directory](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/7-movethatfile "7-movethatfile"): Script that move the file betty from /tmp/ to /tmp/my_first_directory.

[8. Bye bye Betty](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/8-firstdelete "8-firstdelete"): Script that delete the file betty. The file betty is in /tmp/my_first_directory

[9. Bye bye My first directory](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/9-firstdirdeletion "9-firstdirdeletion"): Script that delete the directory my_first_directory that is in the /tmp directory.

[11. Lists](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/11-lists "11-lists"): Script that write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

[12. File type](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/12-file_type "12-file_type"): Script that write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

[13. We are symbols, and inhabit symbols](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/13-symbolic_link "13-symbolic_link"): Script that create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

[14. Copy HTML files](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/14-copy_html "14-copy_html"): Script that Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html

[15. Let’s move](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/100-lets_move "100-lets_move"): Script that create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your script.

[16. Clean Emacs](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/101-clean_emacs "101-clean_emacs"): Script that create a script that deletes all files in the current working directory that end with the character ~.

[17. Tree](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/102-tree "102-tree"): Script that create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.

[18. Life is a series of commas, not periods](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/103-commas "101-103-commas"): Script that Write a command that lists all the files and directories of the current directory, separated by commas (,).
* Directory names should end with a slash (/)
* Files and directories starting with a dot (.) should be listed
* The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
* Only digits and letters are used to sort; Digits should come first
* You can assume that all the files we will test with will have at least one letter or one digit
* The listing should end with a new line

[19. File type: School](https://github.com/vessoutraore/alx-system_engineering-devops/blob/master/0x00-shell_basics/school.mgc "school.mgc"): Script that create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
