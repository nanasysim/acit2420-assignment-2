# Assignment 2: 
This repository contains the bash scripts for the second assignment of the course `ACIT 2420`. The assignment consists of two projects, each of which is described in a separate section below.

## Table of contents
1. [Project 1](#project-1)
2. [Project 2](#project-2)

## Project 1
Project once consists of three scripts:
1. `setup`
2. `config-files`
3. `install-packages`

### setup
The `setup` script will set up the project environment. It will install the necessary packages, clone the starting files, and create symbolic links to configuration files.

**How to run this script:**
```bash
chmod +x setup
```
then
```bash
sudo ./setup
```
### config-files
The `config-files` script will clone the starting files repository and create symbolic links to the configuration files.
When you run `setup`, it will automatically run this script with the correct options.

**How to run this script:**
```bash
chmod +x config-files
```
then
```bash
sudo ./config-files
```

### install-packages
This script will install pacakges from a file. If the package file does not exist in the current directory, it will create one. When you run `setup`, it will automatically run this script with the correct options.

**How to run this script:**
```bash
chmod +x install-packages
```
then
```bash
sudo ./install-packages
```

## Project 2
Project two only consists of one script:
1. `create-user`

### create-user
This script will create a new user with the specified shell, a home directory, contents of the /etc/skel directory copied into the new user's home directory, additional groups that they could be added to, and a password created using the passwd utility
**How to run this script:**
```bash
chmod +x create-user
```
then
```bash
sudo ./create-user
```