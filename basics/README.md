# Shell, basics

This directory contains shell scripts for basic Linux system commands.

## Scripts Description

* `0-current_working_directory`: Prints the absolute path name of the current working directory using `pwd`.
* `1-listit`: Displays the contents list of the current directory using `ls`.
* `2-bring_me_home`: Changes the working directory to the user's home directory using `cd`.
* `3-listfiles`: Displays current directory contents in a long format using `ls -l`.
* `4-listmorefiles`: Displays current directory contents, including hidden files, in a long format using `ls -la`.
* `5-listfilesdigitonly`: Displays current directory contents in long format, including hidden files, with numeric user and group IDs using `ls -lan`.
* `6-firstdirectory`: Creates a directory named `my_first_directory` in the `/tmp/` directory using `mkdir`.
* `7-movethatfile`: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory/` using `mv`.
* `8-firstdelete`: Deletes the file `betty` from `/tmp/my_first_directory/` using `rm`.
* `9-firstdirdeletion`: Deletes the directory `my_first_directory` from `/tmp/` using `rmdir`.