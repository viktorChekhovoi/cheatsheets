# Terminal Cheatsheet

_Letters are shown capitalized for readability only._  

### SHORTCUTS

| Key/Command | Description |
| ----------- | ----------- |
| Ctrl + A   | Go to the beginning of the line you are currently typing on.   |
| Ctrl + E   | Go to the end of the line you are currently typing on.  |
| **Ctrl + W**   | Cut one word backwards using white space as delimiter |
| Ctrl + Y   | Paste whatever was cut by the last cut command |
| **Ctrl + C**   | Kill whatever you are running.  Also clears everything on current line |
| Ctrl + _   | Undo the last command. |
| Ctrl + B   | Move cursor one character backward |
| Option + →  | Move cursor one word forward |
| Option + ←  | Move cursor one word backward |
| **Tab**  | Auto-complete files and folder names |
| Up/down arrow| Navigate recent commands

### CORE COMMANDS

| Key/Command | Description |
| ----------- | ----------- |
| cd [folder] | Change directory e.g. `cd Documents` |
| cd OR cd ~ |  Home directory ('~' is automatically substituted for home directory)|
| cd /  | Root of drive |
| cd .. | Previous directory ('..' is previous directory. 'cd ../..' goes back twice)|
| ls | List files in current directory |
| ls -a | List files including hidden files |
| ls -;h| List files with file sizes |
| sudo [command] | Run command as an admin (Super User DO) |
| open [file] | Opens a file ( as if you double clicked it ) |
| vim [file] | Opens the file using the vim editor or creates new file|
| clear |  Clears the screen |
| !! |  Execute the last command typed |
| !!:p |  Print to the console the last command typed |

<br>
<br>
<br>
<br>



### CHAINING COMMANDS

| Key/Command | Description |
| ----------- | ----------- |
| A; B | Run command A and then B, regardless of success of A |
| A && B | Run command B if A succeeded |
| A \|\| B | Run command B if A failed |
| A & | Run command A in background |
| A \| B | Run command A and pass the result to command B |
| A > [file] | Run command A and save output into a file |

### FILE MANAGEMENT

| Key/Command | Description |
| ----------- | ----------- |
| touch [file] |   Create a new file (use vim [file] whenever possible|
| mkdir [dir] | Create new directory |
| pwd | Full path to working directory |
| rm [file] |  Remove a file, e.g. `rm data.tmp` |
| rm -r [dir] | Remove a directory and contents |
| rm -f [file] | Force removal (use rm -rf for directories)|
| cp [file] [newfile] | Copy file to file |
| cp [file] [dir] | Copy file to directory |
| mv [file] [newfile] |  Move/Rename, e.g. `mv file1.ad /tmp` |

### HELP

| Key/Command | Description |
| ----------- | ----------- |
| [command] -h OR info [command]|  Offers help |
| man [command] |  Show the help manual for [command] |
| whatis [command] | Gives a one-line description of [command] |

