---
name: Alexandra Rivera Rodriguez
semester: Fall 23
course: CIS 106 Linux Fundamentals
---

# Week Report 8

## What is VIM?
* VIM is a vi command-line text editor that is included in all POSIX (Portable Operating System Interface) compliant operating systems
* Crucial for system administration

## What is nano?
Nano is a built-in linux text editor in the terminal 

## Describe in your own words how to:
## Start and quit vim
* Start VIM
    * type `vim`
  * Quit VIM
    * press esc and type `:qa!`
## What are the different vim modes:
* Insert Mode
  * used for writing text
* Normal Mode
  * used for manipulating text
* Command Mode
  * used for entering vim commands
* Visual Mode
  * used for navigation and manipulation of text selections
* Select Mode
  * similar to visual mode
* Ex-Mode
  * Similar to the command-like mode but optimized for batch processing


## Insert text in vim
1. Start vim
2. Enter insert mode
   1. press letter i
3. Type text
   1. I like linux
   Pizza is great
   I go to school
4. exit vim
   1. :q!


## Save a file in vim
* enter normal mode in vim
  * `:w` saves the file
  * `:w new.txt` will save the file as new.txt
  * `:wq` will save the file and quit
  * `:wqa!`will save the file and close all files open in the buffer


## Search for a word inside vim
* syntax:
  * `/search-term`
* Example:
  * `/hello`
* `?` will search backwards
  * `?hello`
* `*` searches for the next occurrence of the word under the cursor
* `#` will search backward for the previous occurrence of the word under the cursor

## Delete text in vim
* `dw` deletes a current word
* `dd` deletes line under the cursor
* `d + /word` delete until the word is given



