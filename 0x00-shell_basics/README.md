# alx-system_engineering-devops / 0x00-shell_basics

This directory contains a collection of shell scripts that cover basic shell commands and operations. Here's a description of each script:

## 1. 0-current_working_directory

This script prints the current working directory using the `pwd` command.

## 2. 1-listit

This script lists the contents of the current directory using the `ls` command.

## 3. 2-bring_me_home

This script changes the working directory to the user's home directory using the `cd ~` command.

## 4. 3-listfiles

This script lists all files in the current directory, including hidden files, using the `ls` command with the `-la` options.

## 5. 4-listmorefiles

This script lists all files in the current directory in a long format, including hidden files, using the `ls` command with the `-lA` options.

## 6. 5-listfilesdigitonly

This script lists only the names of files/directories in the current directory that contain only digits using the `ls` command with the `-l` option and a pipe to `grep` with a regular expression pattern.

## 7. 6-firstdirectory

This script creates a directory named `holberton` in the `/tmp/` directory using the `mkdir` command.

## 8. 7-movethatfile

This script moves the file `betty` from the current directory to the `/tmp/holberton` directory using the `mv` command.

## 9. 8-firstdelete

This script deletes the file `betty` located in the `/tmp/holberton` directory using the `rm` command.

## 10. 9-firstdirdeletion

This script deletes the `holberton` directory located in the `/tmp/` directory using the `rmdir` command.

These scripts provide a foundation for working with shell commands and navigating the file system.


## School.mgc
* compile this file first using this command  ==> file -C -m school.mgc *

#### Note 
all scripts start with `#!/bin/bash`
