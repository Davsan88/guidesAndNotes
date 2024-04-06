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
  ```bash
  dir

- **Change Directory**
  ```bash
  cd \path\to\directory

- **Print Working Directory**
  ```bash
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
 ```bash echo.> filename

- **Remove a File**
  ```bash 
  del filename