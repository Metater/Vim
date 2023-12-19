# Vim
## Editing
- o - new line below
- O - new line above
- x - delete under cursor
- X - delete left of cursor
- d - delete
- p - paste register
## Navigation
- hjkl - main
- % - jump between matching {, (, [
### Word:
- w - start of next word
- e - end of current word
- b - start of current word
- * - next occurrence of word under cursor
- # - previous occurrence of word under cursor
### Line:
- 0 - start of line
- $ - end of line
### Screen:
- H - highest part of screen
- M - middle of screen
- L - lowest part of screen
### File:
- gg - start of file
- gG - end of file
- nG - jump to line 'n'
### Finding:
- fx - find next occurrence of char 'x'
- Fx - find previous occurence of char 'x'
## Examples
- 3w - go to start of 3rd word
- 3iho <Esc>|jk - type hohoho
- /hello - search for hello; n for previous occurrence and N for next occurrence
- rx - replace cursor character with 'x'
- 3dw - delete words to right 3 times

# Dump
d2e - delete 2 words
. - to repeat the last command
v - visual mode toggle, select text, 'd' to delete selected
:w, :q, :q!, save, quit, quit without saving
u - undo
ctrl+r - redo

https://superuser.com/a/884981

