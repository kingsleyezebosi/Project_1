## LinuxPracticeProject
## File Manipulation
## 1. sudo Command
sudo: Shot for superuser do, this is used to perform tasks that requires administartive or root permissions
```javascript
sudo apt update
```

## 2. pwd command
pwd means "Print Working Directory". This command is used to find the path of your current /present working directory. 
```javascript
pwd
```
```javascript
pwd [-L]
```
```javascript
pwd [-P]
```
```javascript
pwd [-LP]
```

## 3. cd command
```javascript
cd CommandLinux
```
```javascript
cd ~
```
```javascript
cd -
```
```javascript
cd ..
```

## 4. ls command
```javascript
ls CommandLinux
```
```javascript
ls -R
```
```javascript
ls -a
```
```javascript
ls -lh
```
## 5. cat command
```javascript
cat sqlite_commands.sh
```
```javascript
cat filename1.txt filename2.txt > filename3.txt
```
```javascript
tac filename3.txt
```

## 6. cp command
```javascript
cp sqlite_commands.sh /home/kingsley/unixcommands/
```
```javascript
cp filename1.txt filename2.txt filename3.txt /home/kingsley/Documents/
```

## 7. mv command
```javascript
mv sqlite_commands.txt /home/kingsley/unixcommands
```
```javascript
mv DevOps /home/kingsley/Downloads/
```

## 8. mkdir command
```javascript
mkdir Album
```
```javascript
mkdir Album/List
```

## 9. rmdir command:
This command is used to permanently delete an empty directory.
```javascript
rmdir Album/List
```

## 10. rm command:
This command is used to delete files within a directory.
```javascript
rm Linux
```
```javascript
rm filename1.txt filename.txt2 filename3.txt
```
## 11. touch command:
```javascript
touch Linux
```
## 12. locate command:

```javascript
touch Linux
```

## 13. find command:
This command is used to find a file or folder within a directory. 
```javascript
find /home -name CommandLinux
```
## 14. grep command:
This command is used to find a word by searching through all the texts in a specific file.
```javascript
grep values CommandLinux
```

## 15. df command:
This command is used to report the system disk space usage.
```javascript
df -h
```
## 16. du command:
This command is used to check how much space a file or a directory takes up.
```javascript
du /home/kingsley/CommandLinux
```

## 17. head command:
This command allows you to view the first 10 lines in a text.
```javascript
head DevOps
```

## 18. tail command:
This command allows you to view the last 10 lines of a file. It shows whether a file has a new data or read error messages.
```javascript
tail DevOps
```

## 19. diff command:
This command is used to compare two contents of a file line by line. After analyzing them, it will display the part that do not match.
```javascript
diff DevOps Linux
```
```javascript
diff -c DevOps Linux
```

## 20. tar command:
This command is used to archive multiple files into a TAR file. A common Linux format similar to ZIP.
```javascript
tar -cvf filename1.txt.tar /home/kingsley
```

## File Permissions and Ownership
## 21. chmod command:
This is a command that modifies a file or directory's read, write and execute permissions.Each file in Linux is associated with 3 user classes - Owner, group member, and others.
```javascript
ls -ltr
```
```javascript
chmod 777 DevOps  
```
```javascript
chmod 777 LinuxCommand
```

## 22. chown command:
This is used to change the ownership of a file, directory or symbollic link to a specified username.
```javascript
chown kingsley Linux
```

## 23. jobs command:
This command will display all the running processes along with their statuses. This command is only available in csh, bash, tcsh, and ksh shells.
```javascript
job jobID
```
## 24. kill command:
This command is used to termite an unresponsive program manually by identifying the application's PID number. This will signal misbahaving applications and instruct them to close their processes.
To check their PID Number, please run the command below.
```javascript
ps ux
```
To terminate the program, please type the below command.
```javascript
kill SIGKILL PID
```
## 25. ping command:
This command is used to check if a network or server is reachable. This is mostly used to troubleshoot connectivity issues.
```javascript
ping google.com
```
## 26. wget command:
This command allows you to download files from the internet using the wget command. This works without hindering any running processes. 
```javascript
wget https://wordpress.org/latest.zip 
```

## 27. uname command:
This is either called uname or unix name. A command that prints detailed information about your Linux system and hardware, inclusive of the machine name, Operating System, and Kernel.
```javascript
uname -a
```
```javascript
uname -s
```
```javascript
uname -n
```
## 28. top command:
This command is used to display all running processes and a dynamic real-time view of the current system.
```javascript
top
```
## 29. history command:
With history, the system will list up to 500 previously executed commands allowing you to reuse them without re-entering.
```javascript
history
```
## 30. man command.
this command will provide the user manual of any command or utilities you can run in the terminal including name, description and options.
```javascript
man ls
```
```javascript
man 2 ls
```

## 31. echo command.
This command is a built in utility that displays a line of text or string using the standard output.
```javascript
echo "How are you?"
```
```javascript
echo \A DevOps
```
```javascript
echo -e DevOps
```
```javascript
echo -n DevOps
```

## 32. zip, unzip commands:
This command will compress files and directories into a zip file, to archive or reduce disk space usage.
```javascript
zip archive.zip blog
```
```javascript
zip archive.zip text
```
```javascript
unzip archive.zip
```
## 33. hostname command:
This command will show the system's hostname or ip address
```javascript
hostname
```
```javascript
hostname -i
```
```javascript
hostname -A
```
```javascript
hostname -alias
```
## 34. useradd, userdel command
The useradd command will create a new account the passwd command allows you to add a password
```javascript
sudo useradd Kelvin
```
Before I proceed to create a password for Kelvin, I have to type in sudo -i, and then type, id Kelvin
```javascript
sudo passwd Kelvin 
```
To delete the user 
```javascript
userdel John
```
To return back to the previous user account, run the "exit" command, then run "logout"

## 35. apt-get command
This command handles advanced package tools (APT) in Linux. It lets you retrive information and bundles from authenticated sources.
```javascript
apt-get update
```
```javascript
sudo apt-get update
```

## 36. nano, vi, jed commands:
The nano command denotes keywords and can work with most languages.
```javascript
nano DevOps
```
The vi command works in two modes insert and command: this can edit and create a text file perform operations such as copying, saving, openig and pasting a file.

```javascript
vi Linux
```
The jed has a dropdown interface that allows users to perform tasks without entering keyboard combinations or commands.

```javascript
jed Linux
```

## 37. alias, unalias command
This command allows you to create a shortcut with the same functionality as a command, file name or text.
```javascript
alias dv='DevOps'
```
The unalias command deletes an existing alias
```javascript
unalias dv
```

## 38. su command:
This command allows you to switch user or run a program as a different user. It is beneficial for accessing the system through SSH or GUI display when root user is unavailable. 
```javascript
su
```

## 39. htop command:
This command monitors system resources and server processes htop command has additional features and improvements than the top command. Before you can run the below command, you have to install the htop service using the command "sudo snap install htop" or "sudo apt install htop". 
```javascript
htop -d
```
```javascript
htop -C
```
```javascript
htop -h
```

## 40. ps command:
This command produces a snapshot of all the processes on your system.
```javascript
ps -T
```
```javascript
ps -u
```
```javascript
ps -A
```
```javascript
ps -e
```

## THANK YOU!










































