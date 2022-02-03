#!/bin/bash
su <username> command to switch to another user, just add the specific username to the su command.
whoami prints the effective username of the current user
groups prints all the groups the current user is part of
chown user file changes the owner of the file
touch file creates an empty file
chmod u+x file adds execute permission to the owner of the file
chmod code file adds execute permission to the owner and the group owner, and read permission to other users, to the file
chmod a+x file adds execution permission to the owner, the group owner and the other users, to the file
chmod code file sets the permission to the file
chmod code file sets the mode of the file
chmod --reference=file2 file1 sets the mode of the file the same as second file
chmod -R a+x */$xcldfile adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users without changing regular files
mkdir -m751 directory creates a directory with permissions
chgrp group file changes the group owner
