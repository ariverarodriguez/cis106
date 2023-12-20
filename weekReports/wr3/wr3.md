---
name: Alexandra Rivera Rodriguez
semester: Fall 23
course: CIS 106 Linux Fundamentals
---

# Week Report 3

## Summary of Presentations

### Introduction to Linux
**What is an operating system?**
An operating system provides all fundamental software features of a computer. An OS enables you to use the computer's hardware providing you the basic tools that make the computer useful

**Aside from a kernel, what other parts make an operating system?**
* Command-Line Shells
* Graphical User Interfaces
* Utility and Productivity Programs
* Libraries

**What is a Linux distribution?**
A linux distribution is any operating system that runs the Linux kernel. A complete Linux System package.

**What is Ubuntu?**
Ubuntu is a Linux Distribution, freely available with both community and professional support.

**Define the following terms: Open Source, Closed source, free software**
1. Open Source - Software that is distributed for a fee or free. Source code is distributed with the software.
2. Closed Source - Software is not distributed with source code. User is restricted from modifying the code.
3. Free Software - Software is distributed with the source code. Software can be free of charge or obtained by a fee.

**What are the 4 freedoms defined by the free software foundation?**
* Freedom 0: Use the software for any Purpose
* Freedom 1: Examine the source code and modify it as you see fit
* Freedom 2: Redistribute the software
* Freedom 3: Redistribute your modified software

### The Basics of Virtualization

**What is virtualization?**
Defined as creating virtual versions of something. Often used to let multiple OSs run on one physical machine at the same time.

**List 3 benefits of virtualization**
* Reduces costs by decreasing the physical hardware that must be purchased for a network
* Offers the ability to save the state of a machine at a given time and roll it back or forward
* Allows for programs coded for one type of hardware or operating system to work on another that it's not designed to work on

**What is a hypervisor?**
There are two types:
- Type 1 (bare-metal) This type of hypervisor runs directly on the hardware. The hypervisor is basically the operating system for the physical machine. Type 1 has better performance because there is no host OS involved and the system is dedicated to supporting virtualization.
- Type 2 is an application that runs on top of an operating system. This is most commonly used in client-side virtualization.

**What is virtualbox**
Virtualbox is a powerful virtualization product for enterprise as well as home use. It is the only professional solution that is freely available as Open Source Software under GNU General Public License (GPL) version 3

### Exploring Desktop Environments

**What is a desktop environment? (Provide 3 examples)**
A desktop environment is an implementation of the desktop metaphor made of a bundle of programs running on top of a computer operating system, which shares a common GUI, sometimes described as a graphical shell
1. GNOME
2. Cinnamon
3. Openbox

**List 4 common elements of desktop environments**
1. File Manager - Allows you to perform file maintenance activities graphically
2. Icons - A picture representation of a file or program
3. System Tray - A special menu, commonly attached to a panel. It provides access to programs that allow a user to log out, lock their screen, manage audio settings, view notifications, shut down or reboot the system, and so on.
4. Window Manager - Determine how windows (also called frames) are presented on the desktop. Control the size and appearance of windows and manage how additional windows can be placed (next to each other or overlapping).

**What is Ubuntu’s default desktop environments?**
GNOME 3 (GNU Network Object Model Environment)

**What are the official flavors of Ubuntu?**
* KDE Desktop Environment
* XFCE DE
* Mate DE
* Cinnamon DE
* LXQT DE
* Deepin DE
* Pantheon DE
* Raspberry Pi DE

### What is a Shell

**What is Bash?**
Bash Shell is what makes large-scale IT possible. It automates sequences of repetitive, complex commands.

**How do you access the Linux CLI?**
Two ways to access Linux CLI:
1. Terminal Emulator
2. Linux Console

**What is a console terminal?**
A console terminal is a text input and output environment.

**What is a terminal emulator?**
A terminal emulator is a program that allows you to access the Linux CLI.

**Provide 3 examples of Linux commands**
* `date` - displays the current time and date
* `df` - displays the current amount of free space on our disk drives
* `uname` - displays information about yur system

### Managing Software

**Which command is used for updating ubuntu**
`apt update` and `apt upgrade`
Example: `sudo apt update; sudo apt upgrade -y`

**Which command is used for installing software. Provide an example.**
`apt install`
Example: `sudo apt install firefox flameshot caffine -y`

**Which command is used for removing software. Provide an example.**
`apt remove`
Example: `sudo apt remove firefox flameshot caffine -y`

**Which command is used for searching for software. Provide an example.**
`apt search "youtube.com"`
Example: 

**Definition of the following terms:**
* Package - Archives that contain binaries of software, configuration files, and information about dependencies
* Library - Reusable code that can be used by more than one function or program
* Repository - A large collection of software available for download
