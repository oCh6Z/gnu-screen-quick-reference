# GNU Screen quick reference

## Getting in

| Description | Command |
| :--- | :--- |
| creating a new session with sessionname | `screen -S <sessionname>` |
| does not start screen, but prints a list of your screen sessions | `screen -ls` |
| attach to a not detached screen session | `screen -x` |
| resumes a detached screen session | `screen -r <pid.sessionname>` |
| reattach a session and if necessary detach or create it<br>use the first session if more than one session is available | `screen -dRR` |

## Getting out

| Description | Command |
| :--- | :--- |
| detach screen from this terminal | <kbd>Ctrl-a</kbd> <kbd>d</kbd> |
| detach and logout | <kbd>Ctrl-a</kbd> <kbd>D</kbd> <kbd>D</kbd> |
| kill all windows and terminate screen | <kbd>Ctrl-a</kbd> <kbd>\\</kbd> |
| kill current window | `kill` |
| getting out of the screen session | `exit` |

## Window management

| Description | Command |
| :--- | :--- |
| create a new window with a shell and switch to that  | <kbd>Ctrl-a</kbd> <kbd>c</kbd> |
| toggle to window displayed previously | <kbd>Ctrl-a</kbd> <kbd>Ctrl-a</kbd> |
| switch to window number 0 -9, or to the blank window | <kbd>Ctrl-a</kbd> <kbd>0-9</kbd> |
| prompt for a window name or number to switch to | <kbd>Ctrl-a</kbd> <kbd>'</kbd> |
| switch to the next window | <kbd>Ctrl-a</kbd> <kbd>n</kbd> or <kbd>Ctrl-a</kbd> <kbd>Space</kbd> |
| switch to the previous window | <kbd>Ctrl-a</kbd> <kbd>p</kbd> or <kbd>Ctrl-a</kbd> <kbd>Backspace</kbd> |
| present a list of all windows for selection | <kbd>Ctrl-a</kbd> <kbd>"</kbd> |
| show a list of window | <kbd>Ctrl-a</kbd> <kbd>w</kbd> |
| destroy current window | <kbd>Ctrl-a</kbd> <kbd>k</kbd> |
| kill all windows and terminate screen | <kbd>Ctrl-a</kbd> <kbd>\\</kbd> |
| allow the user to enter a name for the current window | <kbd>Ctrl-a</kbd> <kbd>A</kbd> |

## Split screen

| Description | Command |
| :--- | :--- |
| split the current region horizontally into two new ones | <kbd>Ctrl-a</kbd> <kbd>S</kbd> |
| split the current region vertically into two new ones | <kbd>Ctrl-a</kbd> <kbd>\|</kbd> |
| switch the input focus to the next region | <kbd>Ctrl-a</kbd> <kbd>Tab</kbd> |
| kill the current region | <kbd>Ctrl-a</kbd> <kbd>X</kbd> |
| delete all regions but the current one | <kbd>Ctrl-a</kbd> <kbd>Q</kbd> |

## Clipboard and navigation

| Description | Command |
| :--- | :--- |
| enter command line mode | <kbd>Ctrl-a</kbd> <kbd>:</kbd> |
| enter copy/scrollback mode | <kbd>Ctrl-a</kbd> <kbd>\[</kbd> or <kbd>Ctrl-a</kbd> <kbd>Esc</kbd> |
| write the contents of the paste buffer to the stdin queue of the current window | <kbd>Ctrl-a</kbd> <kbd>\]</kbd> |


## Help

| Description | Command |
| :--- | :--- |
| show key bindings | <kbd>Ctrl-a</kbd> <kbd>?</kbd> |
