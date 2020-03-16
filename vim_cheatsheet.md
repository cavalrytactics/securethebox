# VIM. 
- protip. replace esc with capslock
- practice touch-typing/motion everyday
- read: http://tnerual.eriogerg.free.fr/vimqrc.html daily
## Normal mode
```
+──────────────────────────────────────+──────────────────────────────────────+
tab                                    = escape to enter NORMAL mode
cmd > click                            = multi cursor select

/ > word                               = search for word
/ > esc > n                            = find next
```
## Insert and Replace
```
: > %s/old/new/g                       = replace string
x                                      = delete character in cursor position
shift + r                              = REPLACE mode
i                                      = INSERT mode inbetween
a                                      = INSERT mode append   
shift + o                              = INSERT mode blank ABOVE selected line
o                                      = INSERT mode blank BELOW selected line
v                                      = VISUAL mode
d > d                                  = delete line
c > c                                  = delete line and INSERT mode
shift + c                              = delete everything after cursor
u                                      = undo
U                                      = redo
d > l                                  = delete 1 character right
d > h                                  = delete 1 character left
d > a > w                              = delete selected word
cmd + k                                = move current line up
cmd + j                                = move current line down
y > y                                  = copy line
p > p                                  = paste line
```
## Motion
- enable sneak plugin (within vscode vim settings) 
```
h                                      = left
l                                      = right
j                                      = down
k                                      = up
s > {char}{char}                       = search for character
S > {char}{char} > ;                   = search for character next
S > {char}{char}                       = search backwards
S > {char}{char} > ;                   = search backwards next
f > {char} > ,                         = move back to char
f > {char} > ;                         = move forward to char
shift + m                              = move cursor to middle line of window
g > g                                  = top of file
```
## Visual mode
```
highlight > o                          = swap highlight position
viw                                    = select word
shift + S                              = surround mode
viw > shift + S > "                    = surround with "
viw > y > esc > p                      = copy word and paste after cursor
viw > y > esc > P                      = copy word and paste before cursor
```

# Editor control
## Quick search
```
space                                  = quick search                   *remap*
space > delete                         = search file                    *remap*
cmd + 1                                = find in files                  *remap*
cmd + 2                                = view explorer                  *remap*
```
## Tab control
```
cmd + d                                = close selected tab             *remap*
cmd + w                                = toggle to other split window   *remap*
cmd + e                                = toggle right tab               *remap*
cmd + q                                = toggle left tab                *remap*
```
## Window Splitting
```
cmd + m                                = split vertical                 *remap*
cmd + n                                = split horizontal               *remap*
```

# Terminal
## Tmux + Oh-my-zsh
```
ctrl + tab                             = toggle terminal
ctrl + `                               = select tab
shift + right-arrow                    = move to right tab
shift + left-arrow                     = move to left tab
ctrl + b > c                           = create new tab
ctrl + b > , > enter                   = rename tab
ctrl + b > x > y > enter               = close window
```