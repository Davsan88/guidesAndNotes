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


## Using Wildcards

Wildcards are characters that enable you to select multiple files or directories based on pattern matching. The most common wildcard is `*`, which matches any number of characters.

### Delete all `.txt` files in a directory:

- **Bash/PowerShell**: `rm *.txt`
- **CMD**: `del *.txt`

### List Detailed Contents Including Hidden Files, Sorted by Time

  - **Bash/PowerShell**: `ls -alt`
  - **CMD**: `dir /a /o-d`

### Copy Files Using Wildcards

  - **Bash/PowerShell**: `cp *.txt /path/to/destination/`
  - **CMD**: `copy *.txt C:\path\to\destination\`

### Move and Rename a File

  - **Bash/PowerShell**: `mv oldname.txt newname.txt`
  - **CMD**: `rename oldname.txt newname.txt`

### Remove All .log Files in the Current Directory

  - **Bash/PowerShell**: `rm *.log`
  - **CMD**: `del *.log`



## Options and Modifiers

Options, typically prefixed with a dash (`-`), modify the behavior of commands to make them more versatile. As shown with the `ls` command, multiple options can be used together to refine the output.

### Listing Contents

- **List All Contents** including hidden files (`-a`), in long format (`-l`), and ordered by modification time (`-t`):
  ```bash
  ls -a  # Include hidden files
  ls -l  # Long format
  ls -t  # Order by modification time
  ls -alt # Combined options


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



# Command Reference Guide for Bash and CMD

## Basic Commands

### cat (Bash)
- Concatenates and displays files.
- Usage: `cat file.txt`

### echo 
- **Bash/CMD**: Outputs the given text to the terminal.
- Usage: `echo "Hello World"`

## Standard Streams

- **stdin (standard input)**: The default input stream, providing input to commands.
- **stdout (standard output)**: The default output stream for commands.
- **stderr (standard error)**: The default error stream for commands.

## Redirection in Bash and CMD

- `>`: Redirects standard output to a file, overwriting existing content.
  - Bash/CMD: `echo "Hello" > file.txt`
- `>>`: Redirects standard output to a file, appending to existing content.
  - Bash/CMD: `echo "World" >> file.txt`
- `<`: Redirects standard input from a file to a command.
  - Bash: `grep "search" < file.txt`
  - CMD: Similar concept, but used differently.
- `|`: Pipes standard output of one command to another command.
  - Bash/CMD: `cat file.txt | grep "search"`

## Commands with Redirection

### sort 
- **Bash**: Sorts lines of text alphabetically.
  - Options:
    - `-r`: Reverses the result of comparisons.
    - `-n`: Compares according to string numerical value.
  - Usage: `sort file.txt`

### uniq (Bash)
- Filters duplicate, adjacent lines of text.
  - Options:
    - `-c`: Prefix lines by the number of occurrences.
    - `-d`: Only print duplicate lines.
  - Usage: `sort file.txt | uniq`

### grep (Bash)
- Searches for a text pattern and outputs it.
  - Options:
    - `-i`: Ignore case distinctions.
    - `-v`: Invert the sense of matching, to select non-matching lines.
  - Usage: `grep "pattern" file.txt`

### sed (Bash)
- Searches for a text pattern, modifies it, and outputs it.
  - Options:
    - `-e script`: Add the script to the commands to be executed.
    - `-n`: Suppress automatic printing of pattern space.
  - Usage: `sed 's/original/replacement/' file.txt`

### find (Bash/CMD)
- **Bash**: Searches for files in a directory hierarchy.
  - `-name "pattern"`: Search for files that match the pattern.
  - Usage: `find . -name "file.txt"`
- **CMD**: Searches for a file or files in a directory.
  - `/R`: Recursive search.
  - Usage: `dir /R file.txt`
  
**Note**: Some options and commands are specific to Bash (Linux, macOS) and may not have direct equivalents in CMD (Windows), but similar functionality can often be achieved with different syntax or by using additional tools like PowerShell for Windows users.
