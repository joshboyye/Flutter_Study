# Bash commands 
**Getting Help in Linux**
MAN Pages

`man command` # => Example: `man ls`

### **SHORTCUTS**:
- `h`=> getting help 
- `q` => quit 
- `enter`=> show next line 
- `space`=> show next screen 
- `/string` => search forward for a string 
- `?string` => search backwards for a string 
- `n / N` => next/previous appearance 

**checking if a command is a shell built-in or an executable file**
- type rm  # => rm is /usr/bin/rm 
- type cd  #=> cd is a shell builtin
  
**getting help for shell built-in commands** 
- help command  # => Example: help cd 
- command --help  # => Example: rm --help 

**searching for a command, feature or keyword in all man pages**
- man -k uname 
- man -k "copy files" 
- apropos passwd 


## Keyboard Shortcuts 
**autocompletes the command or the filename if its unique** 
-TAB  

**displaying all commands or filenames that start with written letters** 
- TAB TAB (press twice)  
    
**clearing the current line** 
- CTRL + L 

**closing the shell (exit)** 
- CTRL + D 

**cutting (removing) the current line**
- CTRL + U 
**moving the cursor to start of the line** 
- CTRL + A 
**moving the cursor to the end of the line** 
- Ctrl + E 
**stopping the current command** 
- CTRL + C 
**sleeping a the running program** 
- CTRL + Z 
**opening a terminal** 
- CTRL + ALT + T 


# Bash History 
**displaying the history** 
- history 
**removing a line (example: 100) from the history** 
- history -d 100 
**removing the entire history**
- history -c 
**printing the number of commands saved in the history file (~/.bash_history)** 
- echo $HISTFILESIZE 
**printing the number of history commands saved in the memory** - echo$HISTSIZE 
**rerunning the last command from the history** 
- !! 
**running    a specific command from the history (example: the 20th command)** 
- !20 
**running the last nth (example: 10th) command from the history** - !-10 
**running the last command starting with abc** 
- !abc 
**printing the last command starting with abc** 
-abc:p 
**reverse searching into the history** 
- CTRL + R 
**recording the date and time of each command in the history** 
- ISTTIMEFORMAT="%d/%m/%y %T " # => write it in ~/.bashrc to make it persistent 


