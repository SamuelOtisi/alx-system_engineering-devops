d_state: script that writes into the file ls_cwd_content the result of the command ls -la-hello_world: This script prints “Hello, World”, followed by a new line to the standard output
1-confused_smiley: This script displays a confused smiley
2-hellofile: script to display the content of /etc/passwd
3-twofiles: script to display the content of /etc/passwd and /etc/hosts
4-lastlines: script to display the last 10 lines of /etc/passwd
5-firstlines: script to display the first 10 lines of /etc/passwd
6tsnext: script to display lines containing the pattern “root” and 3 lines after them in the file
17-hidethisword: script to display all the lines in the file /etc/passwd that do not contain the pattern “bin”
18-letteronly: script to display all lines of the file /etc/ssh/sshd_config starting with a letter-third_line: script that displays the third line of the file iacta
7-file: Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
8-cwd_state: script that writes into the file ls_cwd_content the result of the command ls -la
9-duplicate_last_line: script that duplicates the last line of the file iacta
10-no_more_js: script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
11-directory: Write a script that counts the number of directories and sub-directories in the current directory.
The current and parent directories should not be taken into account Hidden directories should be counted
12-newest_files: Create a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest
13-unique: script that takes a list of words as input and prints only words that appear exactly once
14-findthatword: script that displays lines containing the pattern “root” from the file /etc/passwd
15-countthatword: script to display the number of lines that contain the pattern “bin” in the file /etc/passwd

16-whatsnext: script to display lines containing the pattern “root” and 3 lines after them in the file
17-hidethisword: script to display all the lines in the file /etc/passwd that do not contain the pattern “bin”
18-letteronly: script to display all lines of the file /etc/ssh/sshd_config starting with a letter#!/bin/bash
grep -v bin /etc/passwd
19-AZ: script to replace all characters A and c from input to Z and e respectively
20-hiago: script that removes all letters c and C from input
21-reverse: script that reverse its input
22-users_and_homes: script that displays all users and their home directories, sorted by users
