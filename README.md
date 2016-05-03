## Vi Cheat Sheet

### Quitting

* `:x` - Exit, saving changes
* `:q` - Exit as long as there have been no changes
* `ZZ` or `:qw` - Exit and save changes if any have been made
* `:q!` - Exit and ignore any changes

===

### Inserting Text

* `i` - Insert before cursor
* `I` - Insert before line
* `a` - Append after cursor
* `A` - Append after line
* `o` - Open a new line after current line
* `O` - Open a new line before current line
* `r` - Replace one character
* `R` - Replace many characters

===

### Motion

* `h` - Move left
* `j` - Move down
* `k` - Move up
* `l` - Move right
* `w` - Move to next word
* `W` - Move to next blank delimited word
* `b` - Move to the beginning of the word
* `B` - Move to the beginning of blank delimted word
* `e` - Move to the end of the word
* `E` - Move to the end of Blank delimited word
* `(` - Move a sentence back
* `)` - Move a sentence forward
* `{` - Move a paragraph back
* `}` - Move a paragraph forward
* `0` - Move to the begining of the line
* `$` - Move to the end of the line
* `1G` - Move to the first line of the file
* `G` - Move to the last line of the file
* `nG` - Move to nth line of the file
* `:- n` - Move to nth line of the file
* `fc` - Move forward to c
* `Fc` - Move back to c
* `H` - Move to top of screen
* `M` - Move to middle of screen
* `L` - Move to botton of screen
* `%` - Move to associated ( ), { }, [ ]

===

### Deleting Text

* `dw` - Delete word
* `x` -  Delete character to the right of cursor
* `X` -  Delete character to the left of cursor
* `D` -  Delete to the end of the line
* `dd` -  Delete current line
* `:d`  Delete current line

===

### Yanking Text

* `y$` - Yank to the end of the line
* `yy` - Yank the current line
* `:y` - Yank the current line

===

### Putting text

* `p` - Put after the position or after the line
* `P` - Put before the poition or before the line

===

### Search for strings

* `/string` - Search forward for string
* `?string` - Search back for string
* `n` Search for next instance of string
* `N` Search for previous instance of string

===

### Replace

* `:s` - Search and replace 
* `g`  -Flag - Replace all occurences of pattern
* `c` - Flag - Confirm replaces.
* `&` - Repeat last `:s` command

===

### Ranges

* `:n,m` - Range - Lines n-m
* `:.` - Range - Current line
* `:$` - Range - Last line
* `:'c` - Range - Marker c
* `:%` - Range - All lines in file
* `:g/pattern/` - Range - All lines that contain pattern

===

### Files

* `:w` - file Write to file
* `:r` - file Read file in after line
* `:n` -  Go to next file
* `:p` -  Go to previos file
* `:e` - file Edit file
* `!!program` - Replace line with output from program

===

### Other

* `~` - Toggle upp and lower case
* `J` - Join lines
* `.` - Repeat last text-changing command
* `u` - Undo last change
* `U` - Undo all changes to line

===

#### Credits
 - http://www.lagmonster.org/docs/vi.html