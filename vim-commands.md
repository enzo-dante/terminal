# file management
cmd + /
- find cursor

:q!
- force quit w/o saving

:wq
- save file & quit

:w [file] / :w
-  save specific file / save current

:e [file]
-  open specific file

u = undo change

control + r = redo

i = enter insert mode

:set nu! = show/hide line number

# movement

ctrl + o = move backword in command chain

ctrl + i = move forward in command chain

(normal mode) j = down / h = left / l = right / k = up

I = insert at start of line

A = insert at end of line

gg = top of file

shift + g = bottom of file

w = start at next word

e = end of next word

b = start of previous word

o = insert on line below

shift + o = insert on line above

a = insert at cursor positin

0 = insert a beginning of the line

shift + $ = go to end of line

shift + { / shift + } = jump up/down between paragraphs

ctrl + u = up half page

ctrl + d = down half page

ctrl + c = normal mode

[line_number] + shift + g = jump to specific line

cw = delete current word and enter insert

# editing

delete all the target characters vertically
- put your cursor on the target character, 
- press ctrl + v
- go down until the last commented line
- press x

commenting a block of text
- press Esc (to leave editing or other mode)
- hit ctrl+v (visual block mode)
- use the ↑/↓ arrow keys to select lines you want
- Shift+i (capital I)
- insert the text you want
- press Esc

f/F{character} = jump to character/previous character
- ; = jump to next instance of character
- , = jump to previous instance of character

ct{character} = change from current to character

y$ = copy only line text/ cursor to end of line

yy = copy entire line and with enter space

shift + v = copies highlighted section

p = paste copied highlighted section

dd = delete line

d = delete highlighted

c = remove and insert mode

. = repeat last command

cc = remove line and enter insert mode

dt{character} = delete from current to character

# search and replace text

/[keyword]
    - searches for keyword in file

n
    - move to next keyword instance

:%s/[original]/[target_value]/g
    - find instance of original text and replace target value

:%s/[original]/[target_value]/gc
    - replace all occurances of original value to target value

# vimium: vim in the browser
chrome: https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en
firefox: https://addons.mozilla.org/enS/firefox/addon/vimiumf/?src=search

# vim map
https://externalreview.redd.it/YR2lVxHjzKwIIoRqFeusj3182IxUILqM2zjMSI0g654.png?auto=webp&s=f4202aed992ff7223a513e67047ca33b9f41bbc8

# vim games
vim adventures: https://vimdventures.com/

# vs_code vimium

cmd+shift+L
	- multiursor edit on all instances of selected text
