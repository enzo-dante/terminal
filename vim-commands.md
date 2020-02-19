# file management 

- :q! 
    - force quit w/o saving

- :wq
    - save file & quit

- :w [file] / :w 
    - save specific file / save current

- :e [file]
    - open specific file 

- u = undo change

- control + r = redo

- i = enter insert mode 

:set nu! = show/hide line number

# movement

- (normal mode) j = down / h = left / l = right / k = up
- gg = top of file
- shift + g = bottom of file 
- w = start at next word
- e = end of next word
- b = start of previous word   
- o = insert on line below
- shift + o = insert on line above
- a = insert at cursor positin 
- 0 = insert a beginning of the line
- shift + $ = insert at end of line

- shift + {} = jump up/down between paragraphs 

- ctrl + u = up half page
- ctrl + d = down half page
- ctrl + c = normal mode 

- ctrl + o = move backword in command chain
- ctrl + i = move forward in command chain 

- [line_number] + shift + g = jump to specific line 

- cw = delete highlight and enter insert 

# editing

- yy = copy text
- shift + v = copies highlighted section
- p = paste copied highlighted section 
- dd = delete line
- d = delete highlighted 
- c = remove and insert mode 
- . = repeat last command 

- cc = remove line and enter insert mode 

- dt{character} = delete from current to character

- ct{character} = change from current to character

- f/F{character} = jump to character/previous character

# search and replace text

- /[keyword]
    - searches for keyword in file 

- n
    - move to next keyword instance 

- :%s/[original]/[target_value]/g
    - find instance of original text and replace target value

- :%s/[original]/[target_value]/gc
    - replace all occurances of original value to target value 

# vimium: vim in the browser
- chrome: https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb?hl=en
- firefox: https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/?src=search

# vim map
- https://external-preview.redd.it/YR2lVxHjzKwIIoRqFeusj3182IxUILqM2zjMSI0g654.png?auto=webp&s=f4202aed992ff7223a513e67047ca33b9f41bbc8

# vim games 
- vim adventures: https://vim-adventures.com/
