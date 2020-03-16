# VIM 
## Normal mode
```
: > %s/old/new/g = replace string
/ > word = search for word
/ > esc > n = find next

h = left
l = right
j = down
k = up

i = INSERT mode inbetween
a = INSERT mode append   
shift + O = INSERT mode blank ABOVE selected line
shift + o = INSERT mode blank BELOW selected line
v = VISUAL mode
d > d = delete line
d > l = delete 1 character right
d > h = delete 1 character left
d > a > w = delete selected word
cmd + k = move current line up
cmd + j = move current line down
```
## Motion
- enable sneak plugin (within vscode vim settings) 
```
s > {char}{char} = search for character
S > {char}{char} = search backwards
; = search next
```
## Visual mode
```
viw = select word
shift + S = surround mode
viw > shift + S > ' = surround with '
viw > y > esc >p = copy word and paste
```

# Editor control
## Quick search
```
space = quick search
space > delete = search file
cmd + 1 = find in files
cmd + 2 = view explorer
```
## Tab control
```
cmd + d = close selected tab
cmd + w = toggle to other split window
cmd + e = toggle right tab
cmd + q = toggle left tab
```
## Window Splitting
```
cmd + m = split vertical
cmd + n = split horizontal
```

# Terminal
## Tmux + Oh-my-zsh
```
ctrl + tab = toggle terminal
ctrl + ` = select tab
shift + right-arrow = move to right tab
shift + left-arrow = move to left tab
ctrl + b > c = create new tab
ctrl + b > , > enter = rename tab
ctrl + b > x > y > enter = close window
```