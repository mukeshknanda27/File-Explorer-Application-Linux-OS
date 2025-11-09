 # File-Explorer-Application-Linux-OS

A console-based file explorer application written in C++ that interfaces with the Linux operating system to manage files and directories.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Building](#building)  
  - [Running](#running)  
- [Usage](#usage)  
- [License](#license)  
- [Contributing](#contributing)  
- [Contact](#contact)

---

## About

The File-Explorer-Application-Linux-OS project provides a simple command-line interface to explore, navigate, and manage files and directories on a Linux system. It is implemented in C++ and uses standard Linux system calls and library functions to perform file operations.

---

## Features

- Navigate through directories (change directory, list directory contents).  
- Inspect file attributes (e.g., file size, last modification time).  
- Create and delete directories.  
- Create, rename, delete files.  
- Copy and move files/directories.  
- Handle errors gracefully (e.g., invalid paths, permission denied).  
- Cross-Linux compatibility (requires standard C++ development tools).

---

## Getting Started

### Prerequisites

- A Linux system (Ubuntu, Fedora, Debian, etc.).  
- A C++ compiler supporting C++11 or higher (e.g., `g++`).  
- Basic familiarity with terminal/command-line usage.

### Building

1. Clone the repository:

   ```bash
   git clone https://github.com/mukeshknanda27/File-Explorer-Application-Linux-OS.git
   cd File-Explorer-Application-Linux-OS


## compile the source code 
g++ -std=c++11 -o file_explorer_app File_explorer_app.cpp


## running
./file_explorer_app

## Usage
> ./file_explorer_app
Welcome to File Explorer
Current directory: /home/user
Commands:
  ls         – list contents
  cd <path>  – change directory
  info <file> – show file info
  mkdir <dir> – create directory
  rm <path>   – remove file or directory
  mv <src> <dst> – move/rename
  cp <src> <dst> – copy
  exit        – quit
> ls
Documents  Downloads  file1.txt  testDir/
> cd Documents
> info report.pdf
Filename: report.pdf
Size: 125345 bytes
Last modified: 2025-11-09 14:30:22
Permissions: rw-r---r--
> mkdir NewFolder
> exit
Goodbye!

