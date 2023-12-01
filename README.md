﻿# tasks-github


## Question 1
Write a bash script such that:
  1) It installs git in a system, if it not already installed.
  2) The script exits if the user is not a root.
  3) The script echoes the version of git installed.


## Question 2
Write a bash script such that:
  1) The script should exit with error code if the user is not a root user.
  2) The script switches to /var/log directory.
  3) If the directory does not exsists, it exits.
  4) The script deletes the content of syslog file inside /var/log. 
  5) The script delete the content of wtmp file inside /var/log. 
  6) The script echoes the number of lines in the syslog and wtmp file it cleared.


## Question 3
Write a bash script such that:
  1) The script exits if it is not a root user.
  2) The script takes the input from user as user name.
  3) The script sets the default password of user inside script.
  4) The script exits if the parameter is not provided.
  5) The script exits if the user already exsists.
  6) The script creates user, home directory of user, change ownership of home directory from root to user.
  7) The scripts gives sudo rights to user.
  8) The script changes the default shell from "sh" to "bash".
  9) The scrit echoes success message if the user is created.
  10) The scrit echoes error message if the user is not created. 


## Question 4
Write a bash script such that:

   NOTE: Test this script to other directory. not in this directory to avoid duplicate
  git repositories (git inside git). If you don't understand this, talk to me before 
  executing this task (Gulraiz)    

  1) The script exits if it is not a root user.
  2) The script is run inside a directory which is to tested.
  3) The script tests if the current directory is already a git repository, it exits.
  4) The script takes the input from the user as commit message.
  5) The script exits if no parameter is provided.
  6) The script initialize the git repositoy.
  7) The script adds files to staging area.
  8) The script commits the changes with commit message provided in parameter.
  9) The script echoes the commit hash and author name.


## Question 5
Write a bash script such that:
  1) The script exits if user is not a root.
  2) The script zips all the scipts files with .sh extention in current directory.
  3) The name of zip file should be same as script name.
