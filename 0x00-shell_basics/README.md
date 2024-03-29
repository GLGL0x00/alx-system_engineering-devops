# alx-system_engineering-devops / 0x00-shell_basics

This directory contains a collection of shell scripts that cover basic shell commands and operations. Here's a description of each script:

## 1. 0-current_working_directory

This script prints the current working directory using the `pwd` command.

## 2. 1-listit

This script lists the contents of the current directory using the `ls` command.

## 3. 2-bring_me_home

This script changes the working directory to the user's home directory using the `cd ~` command.

## 4. 3-listfiles

This script lists all files in the current directory, including hidden files, using the `ls` command with the `-l` options.

## 5. 4-listmorefiles

This script lists all files in the current directory in a long format, including hidden files, using the `ls` command with the `-la` options.

## 6. 5-listfilesdigitonly

The command  `ls` command with the `-na` options used to list the contents of a directory, including hidden files and directories, with additional information such as file permissions, ownership, and group information. 

## 7. 6-firstdirectory

This script creates a directory named `my_first_directory` in the `/tmp/` directory using the `mkdir` command.

## 8. 7-movethatfile

This script moves the file `betty` from the current directory to the `/tmp/my_first_directory/` directory using the `mv` command.

## 9. 8-firstdelete

This script deletes the file `betty` located in the `/tmp/my_first_directory/` directory using the `rm` command.

## 10. 9-firstdirdeletion

This script deletes the `/tmp/my_first_directory/` directory located in the `/tmp/` directory using the `rmdir` command.

## 11. 10-back
 command `cd -` Changes the working directory to the previous directory.
   
## 12. 11-lists
command `ls -la . .. /boot` Lists detailed information about files and directories in the current directory, the parent directory, and the `/boot` directory.

## 13. 12-file_type
command `file /tmp/iamafile` Determines the file type of the `/tmp/iamafile` file.

## 14. 13-symbolic_link
command  `ln -s /bin/ls __ls__` Creates a symbolic link named `__ls__` in the current directory, pointing to the `/bin/ls` command.
   
## 15. 14-copy_html
command `cp -un *.html ../` Copies all files with the `.html` extension to the parent directory (`../`) while preserving the original file's attributes and only copying if the destination file doesn't exist.

## 16. 100-lets_move
This command `mv [[:upper:]]* /tmp/u` Moves all files starting with an uppercase letter to the `/tmp/u` directory.

## 17. 101-clean_emacs
command `rm *~` Removes all files ending with a tilde (~) character.

## 18. 102-tree
command  `mkdir -p welcome/to/school` Creates the directory `welcome/to/school` with the `-p` option, which creates parent directories if they don't exist.
   
## 19. 103-commas
command `ls -mpa` Lists files and directories in the current directory with a comma-separated format, including hidden files and directories.

## School.mgc
* compile this file first using this command  ==> `file -C -m school.mgc *`

#### Note 
all scripts start with `#!/bin/bash`
