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
  cp source destination
- **Move/Rename Files**
  mv source destination

### CMD
- **Copy Files**
  copy source destination
- **Move/Rename Files**
  move source destination

## Searching and Finding Files

### Bash
- **Find Files**
  Find /path/to/search -name "filename"
- **Search Inside Files**
  grep "search text" /path/to/search

### PowerShell
- **Find Files**
  Get-ChildItem -Path /path/to/search -Name "filename"
- **Search Inside Files**
  Select-String "search text" /path/to/files/*

### CMD
- **Find Files**
  dir /s /b "filename"
- **Search Inside Files**
  MD lacks a built-in command similar to `grep` in Bash or `Select-String` in PowerShell. You might need to use third-party tools or batch scripts for similar functionality.


