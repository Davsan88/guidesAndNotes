# Command Line Reference Guide



## Navigating the File System


### Bash (Linux/macOS) & PowerShell

- **List Files and Directories**
  ```bash
  ls  # Bash
  Get-ChildItem  # PowerShell, alias: ls

- **Change Directory**
  ```bash
  cd /path/to/directory

- **Print Working Directory**
  ```bash
  pwd  # Bash
  Get-Location  # PowerShell, alias: pwd


### Windows Command Prompt (CMD)

- **List Files and Directories**
  ```cmd
  dir

- **Change Directory**
  ```cmd
  cd \path\to\directory

- **Print Working Directory**
  ```cmd
  cd



## Creating and Removing Files


### Bash & PowerShell

- **Create a File**
  ```bash
  touch filename  # Bash
  New-Item filename -Type file  # PowerShell
  
- **Remove a File**
  ```bash
  rm filename
  

### CMD

- **Create a File**  
  ```cmd 
  echo.> filename

- **Remove a File**
  ```cmd
  del filename



## Creating and Removing Directories


### Bash & PowerShell

- **Create a Directory**
  ```bash
  mkdir directoryname

- **Remove a Directory***
  ```bash
  rmdir directoryname  # If empty
  rm -r directoryname  # If contains files (Bash)
  Remove-Item directoryname -Recurse  # PowerShell


### CMD

- **Create a Directory**
  ```cmd
  mkdir directoryname

- **Remove a Directory**
  ```cmd
  rmdir /s /q directoryname



## File Manipulation


### Bash & PowerShell

- **Copy Files**
  ```bash
  cp source destination

- **Move/Rename Files**
  ```bash
  mv source destination


### CMD

- **Copy Files**
  ```cmd
  copy source destination

- **Move/Rename Files**
  ```cmd
  move source destination



## Searching and Finding Files


### Bash

- **Find Files**
  ```bash
  Find /path/to/search -name "filename"

- **Search Inside Files**
  ```bash
  grep "search text" /path/to/search


### PowerShell

- **Find Files**
  ```bash
  Get-ChildItem -Path /path/to/search -Name "filename"

- **Search Inside Files**
  ```bash
  Select-String "search text" /path/to/files/*


### CMD

- **Find Files**
  ```cmd
  dir /s /b "filename"

- **Search Inside Files**
  ```cmd
  MD lacks a built-in command similar to `grep` in Bash or `Select-String` in PowerShell. You might need to use third-party tools or batch scripts for similar functionality.



# Enhanced Command Line Reference Guide


## General CLI Operations

- **Clear the Terminal**
  - Bash/PowerShell: `clear` (On some systems, `Ctrl` + `L` also works)
  - CMD: `cls`
- **Autocomplete File or Directory Names**
  - Press `Tab` to autocomplete the name of a file or directory.
- **Cycling Through Previous Commands**
  - Use the `↑` (up arrow) and `↓` (down arrow) keys to cycle through previously entered commands.



## File and Directory Management


### Listing Contents

- **List All Contents** including hidden files (`-a`), in long format (`-l`), and ordered by modification time (`-t`):
  ```bash
  ls -a  # Include hidden files
  ls -l  # Long format
  ls -t  # Order by modification time
  ls -alt # Combined options


## Creating and Removing Files

### Bash & PowerShell
- Create a File
  ```bash
  touch filename`  # Bash
  New-Item filename -Type file`  # PowerShell

- Remove a File
  ```bash
  rm filename`

### CMD
- Create a File
  
  echo.> filename`

- Remove a File
  
  del filename`

## Creating and Removing Directories

### Bash & PowerShell

- Create a Directory
  ```bash
  mkdir directoryname

- Remove a Directory
  ```bash
  rmdir directoryname  # If empty
  rm -r directoryname  # If contains files (Bash)
  Remove-Item directoryname -Recurse  # PowerShell

### CMD

- Create a Directory
  ```cmd
  mkdir directoryname

- Remove a Directory
  ```cmd
  rmdir /s /q directoryname


## File Manipulation

### Bash & PowerShell

- Copy Files
  ```bash
  cp source destination

- Move/Rename Files
  ```bash
  mv source destination

### CMD

- Copy Files
  ```cmd
  copy source destination

- Move/Rename Files
  ```cmd
  move source destination

## Searching and Finding Files

### Bash

- Find Files
  ```bash
  find /path/to/search -name "filename"

- Search Inside Files
  ```bash
  grep "search text" /path/to/search

### PowerShell

- Find Files
  ```bash
  Get-ChildItem -Path /path/to/search -Name "filename"

- Search Inside Files
  ```bash
  Select-String "search text" /path/to/files/*

### CMD

- Find Files
  ```cmd
  dir /s /b "filename"

- Search Inside Files
  CMD lacks a built-in command similar to `grep` in Bash or `Select-String` in PowerShell. You might need to use third-party tools or batch scripts for similar functionality.
