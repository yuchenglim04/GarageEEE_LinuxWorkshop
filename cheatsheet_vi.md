vi starts off in command mode. you can't type anything. To go into insert mode, you press 'i' or several other characters. To escape back into command mode, 'esc'

## Command mode
### going into insert mdoe
```
i             # insert at position o cursor 'edit mode'
a              # insert, move cursor one character forward
O              # open newline above and insert
o              # open newline below and insert
```


### navigation
```
h          # <
j          # down
k          #^
l          #>
Backspace    # move backward one character
0            # move to beginning of line
$            # move to end of line
enter        # move to beginning of next line
W            # move forward one space-delimited word 
w            # move forward one word
B            # move backward one space-delimited word
b            # move backward one word
G          	  # go to last line of file
nG            # nth line
```

### Searching
```
?<your search pattern>            # search lines before current line, press enter
\<your search pattern>            # search lines after current line, press enter
n                              # after pressing enter, to move to next line containing search pattern, i.e. repeat last search  
```

### Paging
```
Ctrl b        # back one screen of text
Ctrl f        # forward one screeen of text
Ctrl u        # move up half a page
Ctrl d        # move down half a page
```

### dangerous
```
x  	        # delete single character
dd           # delete line
dw            # delete word, delete not backspace! (after cursor)
D            # delete from cursor to end of line
u            # undo
Ctrl r        # redo
```

### Saving and quitting
```
:w          # write, 'save'
:q          # quit
:q!        # force quit without saving (hence the exclamation)
```
