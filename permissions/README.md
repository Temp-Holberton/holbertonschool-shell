# Shell, permissions

This directory contains shell scripts focused on Linux file permissions, user switching, and identity management.

## Scripts Description

* `0-iam_betty`: Switches the current user to the user `betty` using `su betty`.
* `1-who_am_i`: Prints the effective username of the current user using `whoami`.
* `2-groups`: Prints all the groups the current user is a member of using `groups`.
* `3-new_owner`: Changes the owner of the file `hello` to `betty` using `chown betty hello`.
* `4-empty`: Creates an empty file called `hello` using `touch hello`.
* `5-execute`: Adds execute permission to the owner of the file `hello` using `chmod u+x hello`.
* `6-multiple_permissions`: Adds execute permission to the owner and group owner, and read permission to others on the file `hello` using `chmod u+x,g+x,o+r hello`.
* `7-everybody`: Adds execute permission to the owner, group owner, and other users on the file `hello` using `chmod a+x hello`.
* `8-James_Bond`: Sets file permissions on `hello` so the owner and group have no permissions, and others have full permissions using `chmod 007 hello`.
* `9-John_Doe`: Sets the mode of the file `hello` to `-rwxr-x-wx` using `chmod 753 hello`.