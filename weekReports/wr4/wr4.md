---
name: Alexandra Rivera Rodriguez
semester: Fall 23
course: CIS 106 Linux Fundamentals
---

# Week Report 4

## Practice From the Presentation The Linux File System:

### Practice 1
![Practice 1](wr4-p1.png)

### Practice 2
![Practice 2.1](wr4-p2.1.png)
![Practice 2.2](wr4-p2.2.png)
![Practice 2.3](wr4-p2.3.png)
![Practice 2.4](wr4-p2.4.png)
![Practice 2.5](wr4-p2.5.png)
![Practice 2.6](wr4-p2.6.png)
![Practice 2.7](wr4-p2.7.png)
![Practice 2.8](wr4-p2.8.png)

### Practice 3 (Challenge Practice)
![Practice 3.1](wr4-p3.1.png)
![Practice 3.2](wr4-p3.2.png)
![Practice 3.3](wr4-p3.3.png)
![Practice 3.4](wr4-p3.4.png)

## The Linux File System Directories And Their Purpose:

![Filesystem 1](fs1.1.png)
![Filesystem 2](fs1.2.png)
![Filesystem 3](fs1.3.png)

## All The Commands For Navigating The Filesystem:

| Command | What it does                                                                   | Syntax                                | Example                                               |
| ------- | ------------------------------------------------------------------------------ | ------------------------------------- | ----------------------------------------------------- |
| pwd     | Prints current working directory                                               | `pwd`                                 | `pwd`                                                 |
| cd      | Changes the current working directory to Home                                  | `cd` + `destination`                  | `cd` or `cd ~` or `cd $HOME` or `cd ariverarodriguez` |
|         | Changes the current working directory - Prev working directory                 | `cd` + `destination`                  | `cd -`                                                |
|         | Change from current working directory to a different directory                 | `cd` + `destination`                  | `cd Downloads` or `cd ~/Downloads`                    |
|         | Go back one or more directories                                                | `cd` + `..`                           | Go back 1: `cd ../` Go back 2: `cd ../../`            |
| ls      | Displays all the files inside a given directory                                | `ls` + `option` + `directory to list` | `ls`                                                  |
|         | List all the files inside the current working directory including hidden files | `ls` + `option` + `directory to list` | `ls -a`                                               |
|         | List all the files inside the current working directory                        | `ls` + `option` + `directory to list` | `ls -a ~/Pictures`                                    |
|         | "" sorted by last modified                                                     | `ls` + `option` + `directory to list` | `ls -t ~/Documents`                                   |
|         | "" sorted by file size                                                         | `ls` + `option` + `directory to list` | `ls -s ~/Documents`                                   |
|         | "" sorted by extension                                                         | `ls` + `option` + `directory to list` | `ls -x ~/Documents`                                   |
|         | "" sorted by name descending                                                   | `ls` + `option` + `directory to list` | `ls -r ~/Documents`                                   |
|         | "" recursively                                                                 | `ls` + `option` + `directory to list` | `ls -R ~/Documents`                                   |
|         | Lists all the options of ls command                                            | `ls` + `--help`                       | `ls --help`                                           |


## Basic Terminology

* **File system** The way files are stored and organized.
* **Current directory** The directory where you are at the moment
* **Parent directory** A directory that contains subfolders
* **The difference between your home directory and the home directory** Current working directory is home directory. The home directory is the root where you need administrator privileges.
* **pathname** indicates the location of the file in the filesystem (like an address)
* **relative path** The location of a file starting from the current working directory or a directory that is located inside the current working directory
  * Ex. Downloads/song.mp3
* **absolute path** the location of a file starting at the root of the file system
  * Ex. /home/john/Downloads/song.mp3
