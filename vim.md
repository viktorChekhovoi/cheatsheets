# Vim 

### Exiting
| Shortcut       | Description                      |
| -------------- | -------------------------------- |
| `:w`           | Save                             |
| `:wq` OR `:x` | Save and close file              |
| `:q`           | Close file                       |
| `:q!`          | Close file, abandon changes      |

### Navigating 
*Regular arrow keys work too*

| Shortcut            | Description       |
| ---                 | ---               |
| `h` `j` `k` `l` | Arrows (left, down, up, left) |
| `0` _(zero)_ | Start of line                      |
| `$`          | End of line                        |
| `gg`     | First line     |
| `G`      | Last line      |
| `:n`     | Go to line `n` |


### Modes

| Shortcut | Description                         |
| ---      | ---                                 |
| `i`      | Enter insert mode ()                             |
| `a`      | Append (enter insert + go one character to the right) |
| `o`      | Enter insert + next line                           |
| `O`      | Enter insert + previous line                       |
| `s`      | Delete char and enter insert              |
| `S`      | Delete line and enter insert              |
| `Esc`    | Exit insert mode |
| `:set paste` | Enter pasting mode (for pasting from clipboard) |
| `:set nopaste` | Exit pasting mode
| `u`      | Undo changes                        |
| `ctrl + r`  | Redo changes                        |


### Search

| Shortcut  | Description                         |
| ---       | ---                                 |
| `/[string]` | Sear for [string] in the document |
| `n`       | Next matching search pattern        |
| `N`       | Previous match                      |


### Clipboard
*Tip: entering a number before the command (like `100dd`) executes it that number of times*

| Shortcut        | Description                 |
| ---             | ---                         |
| `dd`            | Delete line _(Cut)_         |
| `yy`            | Yank line _(Copy)_          |
| `p`             | Paste                       |
| `P`             | Paste before                |
| `"*p` OR `"+p` | Paste from system clipboard |
| `"*y` OR `"+y` | Paste to system clipboard   |
| `CMD + v`       | Paste from system clipboard (Mac) |
| `ctrl + shift + v` | Paste from system clipboard (non-Mac) |