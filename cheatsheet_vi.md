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
0            # move to beginning of line
$            # move to end of line
W            # move forward one space-delimited word 
w            # move forward one word
B            # move backward one space-delimited word
b            # move backward one word
Backspace    # move backward one character
enter        # move to beginning of next line
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
u            # undo
Ctrl r        # redo
```

### Saving and quitting
```
:w          # write, 'save'
:q          # quit
:q!        # force quit without saving (hence the exclamation)
```
