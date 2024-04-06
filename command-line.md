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


### Creating and Removing Directories

<!-- Creating and Removing Directories
Bash & PowerShell
Create a Directory
bash
Copy code
mkdir directoryname
Remove a Directory
bash
Copy code
rmdir directoryname  # If empty
rm -r directoryname  # If contains files (Bash)
Remove-Item directoryname -Recurse  # PowerShell
CMD
Create a Directory
cmd
Copy code
mkdir directoryname
Remove a Directory
cmd
Copy code
rmdir /s /q directoryname
File Manipulation
Bash & PowerShell
Copy Files
bash
Copy code
cp source destination
Move/Rename Files
bash
Copy code
mv source destination
CMD
Copy Files
cmd
Copy code
copy source destination
Move/Rename Files
cmd
Copy code
move source destination
Searching and Finding Files
Bash
Find Files
bash
Copy code
find /path/to/search -name "filename"
Search Inside Files
bash
Copy code
grep "search text" /path/to/search
PowerShell
Find Files
powershell
Copy code
Get-ChildItem -Path /path/to/search -Name "filename"
Search Inside Files
powershell
Copy code
Select-String "search text" /path/to/files/*
CMD
Find Files
cmd
Copy code
dir /s /b "filename"
Search Inside Files
CMD lacks a built-in command similar to grep in Bash or Select-String in PowerShell. You might need to use third-party tools or batch scripts for similar functionality. -->


