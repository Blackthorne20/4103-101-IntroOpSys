# Bash Homework 1
Due: Tuesday September 13th by Class time.


### Prep Work

1. Make sure there is a user: `griffin` on your server with the password `2D2016!!!` and sudo access (if there is not it will mean an automatic zero for this assignment).
2. Clone your github repository in the folder: `/usr/opt/`. Make sure the permissions on this folder are `755`.
3. Make a folder called `assignments` in your repo.
4. Make another folder called `homework-01` in the `assignments` folder.
5. All scripts below will be in the `homework-01` folder.


### Script 1

- Create a script called `command_args.sh` which will read in all command line arguments and print them out.
- For example `$ ./command_args.sh arg1 "hello" 44` would print out:

```
command_args.sh
(contents of arg1)
hello
44
```



### Script 2


- Create a script which will print a random word. There is a file containing a list of words on your system (usually /usr/share/dict/words or /usr/dict/words). Hint: Piping will be useful here.
- Name this script: `myrandom.sh` and when run, should print out 1 random word to std out.


### Script 3 

- Create a script which will take a filename as its first argument and create a dated copy of the file. eg. if the file was named `file1.txt` it would create a copy such as `2016-01-28_file1.txt`. (To achieve this you will probably want to play with command substitution and the command date).
- Name this script `versiona.sh`.

### Script 4

- Using the script from `versiona.sh`, see if you can get it so that the date is after the name of the file (eg. file1_2016-01-28.txt (The command `basename` can be useful here.)
- Name this script `versionb.sh`. 