---
Name: Brian Hernandez Delgado
Semester: Fall 2022
Course: CIS-106
---




## Week Report 4/ Homework 4


# Practices
![P1](P1.png)




| Directory | Data Stored in Directory                                                                                                                      |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Bin       | Essential Commands                                                                                                                            |
| dev       | Device Files                                                                                                                                  |
| etc       | System Configuration Files                                                                                                                    |
| Home      | User Home Directories                                                                                                                         |
| Media     | Mount point for removable media, such as DVDs and floppy disks                                                                                |
| opt       | Add on software packages                                                                                                                      |
| proc      | Kernel information, process control, system hardware information                                                                              |
| srv       | Information relating to services that run on the system                                                                                       |
| usr       | Software not essential for system operation, such as applications                                                                             |
| var       | Dedicated to variable data, such as logs, databases, websites, and temporary spool (email etc.) files that persist from one boot to the next. |

# Commands
| Command | What it does                                                                                  | Syntax                       | Example                  |
| ------- | --------------------------------------------------------------------------------------------- | ---------------------------- | ------------------------ |
| pwd     | used for displaying the current working directory                                             | pwd                          | /home/brian              |
| cd      | used for changing the current working directory to either desired directory or home directory | cd+destination               | cd /home/brian/Downloads |
| ls      | used for displaying all files inside given directory                                          | ls+option+intended directory | ls -a ~/Pictures         |

**Definitions**
1. File Systems: files are stored and organized to simplify access to data
2. Current Directory: directory where you currently are
3. Parent Directory:Previous working directory
4. Your Home Directory: directory under root
5. The Home Directory: it is root
6. Pathname: indicates the location of the file in the filesystem
7. Relative Path: the location of a file starting from the current working directory or a directory that is located inside the current working directory 
8. Absolute Path: the location of a file starting at the root of the file system

***Commands used to navigate the filesystem***
1. Tab Completion: autocompletes a command by pressing the tab key
2. Arrow keys: allows you to move, edit, and repeat commands
3. Ctrl+a: go to the start of the command line
4. Ctrl+e: go to the end of the command line
5. Ctrl+k: delete from cursor to the end of the command line
6. Ctrl+u: delete from cursor to the start of the command line
7. Ctrl+w: delete from cursor to start of word