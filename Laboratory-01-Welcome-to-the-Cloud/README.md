# Laboratory 1: Welcome to the Cloud

## Mission Overview
This laboratory activity served as my onboarding mission as a Junior Cloud Infrastructure Engineer Trainee at CloudNova Technologies. The goal was to get hands-on experience working inside a Linux environment, document my work professionally, and build the foundation of a version-controlled GitHub portfolio that I will continue to update throughout the semester.

## Objectives
- Access a cloud-based Linux environment using KillerCoda
- Explore and navigate the Linux operating system
- Gather basic system information
- Organize files and directories using Linux commands
- Create and maintain a professional GitHub repository
- Document technical work using Markdown
- Demonstrate proper documentation practices used by cloud professionals

## Activities Performed
- Launched an Ubuntu 24.04 Linux Playground using KillerCoda
- Created a new user account (jlaunico) with sudo privileges, a Bash shell, and a home directory
- Logged into the new user account and recorded the current username, working directory, and hostname
- Investigated the Linux environment to gather the distribution, kernel version, CPU information, memory, and disk space
- Recorded the findings inside system-information.md
- Created a folder structure inside the home directory (Notes, Reports, Screenshots)
- Created about-me.md inside the Notes folder
- Set up a public GitHub repository (CCM101-jlaunico) to serve as my ongoing Cloud Computing Portfolio
- Organized the repository with a Laboratory-01-Welcome-to-the-Cloud folder containing this README, system-information.md, about-me.md, reflection.md, and a screenshots folder
- Captured and uploaded screenshots as evidence for each checkpoint

## Linux Commands Used
- `sudo adduser --shell /bin/bash [username]` – create a new user with a Bash shell and home directory
- `sudo usermod -aG sudo [username]` – grant sudo privileges to the new user
- `su - [username]` – switch to the new user account
- `whoami` – display the current logged-in user
- `pwd` – display the current working directory
- `hostname` – display the machine's hostname
- `lsb_release -a` – display the Linux distribution
- `uname -r` – display the kernel version
- `lscpu` – display CPU information
- `free -h` – display memory usage
- `df -h` – display disk space usage
- `mkdir` – create new directories
- `cd` – change directories
- `nano` – create and edit text files
- `cat` – view the contents of a file

## Skills Learned
Through this activity, I learned how to navigate and manage a Linux environment from the command line, including creating users, checking system resources, and organizing files into a clear directory structure. I also learned how to document technical work properly using Markdown, and how to structure a GitHub repository so that it stays organized and professional as more laboratory activities get added throughout the semester. This laid the groundwork for the more advanced cloud computing concepts I'll be exploring in future missions.
