# LEARNING VIM

1. _Exit out of vim using:_ _`:q`_
2. _Dismiss changes:_ _`:q!`_
3. _TO try out command line utility:_ _`:!`_
4. _To save changes to a file:_ _`:w`_
5. _TO save changes to a file and quit:_ _`:wq`_
6. _There are about like 3 keys that can be used to enter the INSERT mode:_ _`o i a`_

- `a:` _a key_ enters INSERT mode by allowing typing after the point where cursor is focused
- `i:` _i key_ enters INSERT mode by allowing typing before the point where cursor is focused
- `o:` _o key_ enters INSERT mode by allowing typing on the next line after the line cursor is focused
- `A:` Opens the line above the cursor
- `I:` Moves the cursor the beginning of the line
- `O:` Moves cursor to the end of the line

## VIM KEYBINDINGS

- `Ctrl r`: Redo actions
- `u`: Undo actions

- _To delete, copy, and paste:_, we have to be in `VISUAL MODE`
  We can move to visual mode, by moving to normal mode(pressing ESC) and pressing `v`

- `right arrow` to select a body of text in visual mode
- `y`(_yanking_) to copy after text selection
- `p` for pasting and or perhaps `d` for deletion
- `dd` for deleting all text on a line
- `r` for replacing a body of text
- `w` for moving cursor word by word(either based on hyphen/spaces) in forward direction.
  However, `b` performs the operation in backward direction
- `W` for moving cursor word by word based solely on spaces
  However, `B` performs the operation in backward direction
- `dw` deletes a word
- `diw` deletes inner word
- `ciw` change inner word
- `yiw` yank(copy) inner word
- `ci"` change inner (word) in quotation mark
- `%` to jump between parentheses or curly braces
- `t*` jump one spot before symbol(\*)
- `dt(` delete everything before opening bracket
- `T*` jump one position after symbol(\*)
- `gg` jump to start of a file
- `shift-g` jump to end of line
- `:500` jump to line number 500

## INTERMEDIATE KEYBINDINGS

- `/name-of-search-term`. Use n key to go forward to next search term. N to go back to next search term
- `:%s/character/symbol/g` . This searches the word _character_ and replace it with _symbol_.
  This is effected globally. that is, every single occurence of characters is replaced with symbol in the file
