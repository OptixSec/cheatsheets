# VIM Motions Cheatsheet

## Movement

```h```, ```j```, ```k```, ```l``` - Move left, down, up, right
```w```, ```b``` - Move one word forward or back
```e``` - Move to the end of the word
```$``` - Move to the end of the line
```^``` - Move to the beginning of the line
```f-<char>``` - Move to the next character
```F-<char>``` - Move to the previous character
```shift-(```,```shift-)``` - Move a sentence up or down
```shift-{```, ```shift-}``` - Move a paragraph up or down
```ctrl-u```, ```ctrl-d``` - Move up and down half page
```ctrl-b```, ```ctrl-f``` - Move up and down full page
```gg```, ```G``` - Move to top or bottom of page

## Editing

```i```, ```a``` - Insert before or after the cursor
```I```, ```A``` - Insert at beginning or end of the line
```o```, ```O``` - Insert before or after current line

```yy``` - Copy entire line
```p``` - Paste clipboard contents
```y-i-<char>``` - Cope text between char
```y-a-<char>``` - Copy text between and including char

```u``` - Undo the last change
```ctrl-r``` - Undo all the changes
```d-i-w``` - Delete a word
```d-i-s``` - Delete a sentence
```d-i-p``` - Delete a paragraph
```dd``` - Delete line
```d-t-<char>``` - Delete up to character
```.``` - Repeat last command

```/``` - Search
```n```, ```N``` - Next and previous
```*```, ```#``` - Search for next word under cursor
