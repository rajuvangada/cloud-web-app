# Cloud Web App

## Overview

Cloud Web App is a Linux-based project workspace created to demonstrate essential Linux, shell scripting, Git, and GitHub skills. The project includes a structured directory layout, a simple HTML application, project documentation, screenshots, and an executable shell script for project status reporting.

## Project Objectives

* Create a well-organized Linux project structure.
* Develop a basic HTML web application.
* Implement a shell script to display project information.
* Practice Linux file permissions using chmod.
* Initialize and manage a Git repository.
* Create and work with a dedicated Git branch.
* Push the project to GitHub for version control and collaboration.


## Project Structure

cloud-web-app/
│
├── app/
│   └── index.html
│
├── scripts/
│   └── project-status.sh
│
├── docs/
│
├── screenshots/
│
├── README.md
└── .gitignore
```

### Directory Description

| Directory/File | Purpose                                    |
| -------------- | ------------------------------------------ |
| app            | Contains the web application files         |
| scripts        | Stores shell scripts used in the project   |
| docs           | Project documentation and supporting files |
| screenshots    | Assignment evidence screenshots            |
| README.md      | Project documentation                      |
| .gitignore     | Defines files and folders ignored by Git   |


## Technologies Used

* Linux (Ubuntu/WSL)
* Bash Shell Scripting
* Git
* GitHub
* HTML5


## Commands Used

## Linux Commands Used and Their Purpose

### Navigation Commands

| Command  | Purpose                                                          |
| -------- | ---------------------------------------------------------------- |
| `pwd`    | Displays the current working directory path                      |
| `cd`     | Changes the current directory                                    |
| `ls`     | Lists files and directories                                      |
| `ls -la` | Lists all files including hidden files with detailed information |

### Directory Management

| Command    | Purpose                              |
| ---------- | ------------------------------------ |
| `mkdir`    | Creates a new directory              |
| `mkdir -p` | Creates multiple directories at once |

### File Management

| Command | Purpose                                |
| ------- | -------------------------------------- |
| `touch` | Creates a new empty file               |
| `cp`    | Copies files or directories            |
| `mv`    | Moves or renames files and directories |
| `rm`    | Removes files                          |
| `rm -r` | Removes directories and their contents |

### File Viewing and Editing

| Command | Purpose                              |
| ------- | ------------------------------------ |
| `nano`  | Opens a text editor in the terminal  |
| `cat`   | Displays the contents of a file      |
| `more`  | Displays file contents page by page  |
| `less`  | Allows scrolling through large files |
| `head`  | Displays the first lines of a file   |
| `tail`  | Displays the last lines of a file    |

### Permission Management

| Command              | Purpose                                                |
| -------------------- | ------------------------------------------------------ |
| `chmod`              | Changes file permissions                               |
| `chmod 755 filename` | Gives owner full access and others read/execute access |

### Shell Script Commands

| Command       | Purpose                                     |
| ------------- | ------------------------------------------- |
| `#!/bin/bash` | Specifies Bash as the script interpreter    |
| `echo`        | Prints text to the terminal                 |
| `pwd`         | Shows current directory inside a script     |
| `ls`          | Lists files and directories inside a script |

### Git Commands
| Command                                  | Purpose                                                 |
| ---------------------------------------- | ------------------------------------------------------- |
| `git init`                               | Initializes a new Git repository                        |
| `git status`                             | Shows the current state of the repository               |
| `git add .`                              | Stages all files for the next commit                    |
| `git commit -m "message"`                | Saves staged changes with a descriptive message         |
| `git log --oneline`                      | Displays commit history in a compact format             |
| `git branch`                             | Lists all branches in the repository                    |
| `git checkout -b linux-setup`            | Creates and switches to a new branch                    |
| `git remote add origin <repository-url>` | Connects the local repository to GitHub                 |
| `git remote -v`                          | Displays configured remote repositories                 |
| `git push -u origin linux-setup`         | Pushes the branch to GitHub and sets upstream tracking  |
| `git pull`                               | Downloads and merges changes from the remote repository |
| `git clone <repository-url>`             | Creates a local copy of a GitHub repository             |


### GitHub Workflow Summary

1. Create project structure in Linux.
2. Create files and shell scripts.
3. Initialize Git repository.
4. Stage and commit project files.
5. Create the `linux-setup` branch.
6. Connect the repository to GitHub.
7. Push the branch to the remote repository.
8. Verify files and commit history on GitHub.


## Shell Script Functionality

The project-status.sh script performs the following tasks:

1. Displays a project status message.
2. Prints the current working directory.
3. Lists project files and folders.
4. Confirms successful execution.


## Git Workflow

1. Initialize a local Git repository.
2. Stage project files.
3. Commit changes with descriptive messages.
4. Create the linux-setup branch.
5. Connect the local repository to GitHub.
6. Push the branch to the remote repository.


## Learning Outcomes

Through this project, the following skills were practiced:

* Linux navigation and file management
* Directory and file creation
* Shell scripting fundamentals
* Linux file permissions
* Git version control
* Branch management
* GitHub repository management
* Project documentation


## Author

Raju Vangada

B.Tech Student

Cloud Computing and Linux Fundamentals Assignment
