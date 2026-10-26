# Shell, permissions

This directory contains shell scripts focused on Linux file permissions, user switching, and identity management.

## Scripts Description

* `0-iam_betty`: Switches the current user to the user `betty` using `su betty`.
* `1-who_am_i`: Prints the effective username of the current user using `whoami`.
* `2-groups`: Prints all the groups the current user is a member of using `groups`.
* `3-new_owner`: Changes the owner of the file `hello` to `betty` using `chown betty hello`.
* `4-empty`: Creates an empty file called `hello` using `touch hello`.