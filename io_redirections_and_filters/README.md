# Shell, I/O redirections and filters

Linux I/O redirections, pipes, and filters scripts.

## Scripts Description

- `0-hello_world`: Print "Hello, World".
- `1-confused_smiley`: Print `"(Ôo)'`.
- `2-hellofile`: Display content of `/etc/passwd`.
- `3-twofiles`: Display content of `/etc/passwd` and `/etc/hosts`.
- `4-lastlines`: Display the last 10 lines of `/etc/passwd`.
- `5-firstlines`: Display the first 10 lines of `/etc/passwd`.
- `6-third_line`: Display the third line of `iacta`.
- `7-file`: Create a file with a specific special-character filename containing "Best School".
- `8-cwd_state`: Write the current directory listing (ls -la) into a file named ls_cwd_content.
- `9-duplicate_last_line`: Duplicate the last line of the file iacta.
- `10-no_more_js`: Delete all regular files with a .js extension in the current directory and all subfolders.
- `11-directories`: Count the number of directories and sub-directories in the current directory, excluding current and parent directories, including hidden ones.
- `12-newest_files`: Display the 10 newest files in the current directory, one per line, sorted from newest to oldest.
- `13-unique`: Display only words that appear exactly once from input, sorted alphabetically.
- `14-findthatword`: Display lines containing the pattern "root" from the file /etc/passwd.
- `15-countthatword`: Display the number of lines that contain the pattern "bin" in the file /etc/passwd.
- `16-whatsnext`: Display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd.
- `17-hidethisword`: Display all lines in the file /etc/passwd that do not contain the pattern "bin".
- `18-letteronly`: Display all lines of the file /etc/ssh/sshd_config starting with a letter (capital or lowercase).
- `19-AZ`: Replace all characters 'A' and 'c' from input to 'Z' and 'e' respectively.
- `20-hiago`: Remove all letters c and C from input.
- `21-reverse`: Reverse its input line by line.
- `22-users_and_homes`: Display all users and their home directories, sorted by users, based on /etc/passwd.
