# 0x02. Shell, I/O Redirections and filters

### Learning Objectives

* What do the commands head, tail, find, wc, sort, uniq, grep, tr do
* How to redirect standard output to a file
* How to get standard input from a file instead of the keyboard
* How to send the output from one program to the input of another program
* How to combine commands and filters with redirections
* What are special characters
* Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them

#### 0. Hello World
[Write a script that prints “Hello, World”, followed by a new line to the standard output.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world)

#### 1. Confused smiley
[Write a script that displays a confused smiley "(Ôo)'.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley)

#### 2. Let's display a file
[Display the content of the /etc/passwd file.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile)

#### 3. What about 2?
[Display the content of /etc/passwd and /etc/hosts](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles)

#### 4. Last lines of a file
[Display the last 10 lines of /etc/passwd](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines)

#### 5. I'd prefer the first ones actually
[Display the first 10 lines of /etc/passwd](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines)

#### 6. Line 2
[Write a script that displays the third line of the file iacta.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line)

#### 7. It is a good file that cuts iron without making a noise
[Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file)

#### 8. Save current state of directory
[Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state)

#### 9. Duplicate last line
[Write a script that duplicates the last line of the file iacta](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line)

#### 10. No more javascript
[Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js)

#### 11. Don't just count your directories, make your directories count
[Write a script that counts the number of directories and sub-directories in the current directory.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories)

#### 12. What’s new
[Create a script that displays the 10 newest files in the current directory.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files)

#### 13. Being unique is better than being perfect
[Create a script that takes a list of words as input and prints only words that appear exactly once.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique)

#### 14. It must be in that file
[Display lines containing the pattern “root” from the file /etc/passwd](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword)

#### 15. Count that word
[Display the number of lines that contain the pattern “bin” in the file /etc/passwd](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-countthatword)

#### 16. What's next?
[Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext)

#### 17. I hate bins
[Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword)

#### 18. Letters only please
[Display all lines of the file /etc/ssh/sshd_config starting with a letter.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly)

#### 19. A to Z
[Replace all characters A and c from input to Z and e respectively.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ)

#### 20. Without C, you would live in hiago
[Create a script that removes all letters c and C from input.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago)

#### 21. esreveR
[Write a script that reverse its input.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/21-reverse)

#### 22. DJ Cut Killer
[Write a script that displays all users and their home directories, sorted by users.](https://github.com/YasminKinawi/alx-system_engineering-devops/blob/master/0x02-shell_redirections/22-users_and_homes)






