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



# Nano Quick Guide for Bash and CMD

Nano is a text editor for Unix-based systems and cannot be natively run in Windows CMD without a compatibility layer like Cygwin or Windows Subsystem for Linux (WSL). This guide focuses on its use in Bash.

## Opening Nano

- **Bash**: To open or create a file in Nano, type:
  ```bash
  nano filename

## Basic Nano Commands

Commands in Nano are invoked with the `Ctrl` key. Here are some of the most commonly used commands:

- **Ctrl + O**: Save the file. You'll be prompted to confirm the filename.
- **Ctrl + X**: Exit Nano. If you haven't saved your changes, it will ask if you want to save them.
- **Ctrl + K**: Cut the current line and store it in the cut buffer.
- **Ctrl + U**: Paste the contents of the cut buffer into the current line.
- **Ctrl + W**: Search for a string in the text. After typing `Ctrl + W`, enter your search query and press `Enter`.
- **Ctrl + \\_**: Replace a string. Enter the string to search for, then the replacement string.
- **Ctrl + G**: Display the help screen, which lists more commands.

## Navigating in Nano

- **Arrow Keys**: Move the cursor around the text.
- **Alt + Arrow Keys**: Scroll the page without moving the cursor.
- **Ctrl + \\_**: Go to a specific line and column number (useful for large files).

## Configuring Nano (Bash)

Nano's behavior can be customized via the `.nanorc` file in your home directory. Example:

# Quick Guide to Nano, .bash_profile, Aliases, and Environment Variables


## Editing .bash_profile with Nano

- Open your `.bash_profile`: `nano ~/.bash_profile`

## Setting Environment Variables

- Set an environment variable: `export VARIABLE_NAME="value"`
- Example: `export PATH="$PATH:/new/path"`

## Creating Aliases

- Add an alias in `.bash_profile`: `alias ll='ls -la'`

## Saving and Exiting Nano

- Save changes: `Ctrl + O`, then `Enter`
- Exit Nano: `Ctrl + X`

## Applying Changes in .bash_profile

- Reload `.bash_profile`: `source ~/.bash_profile` or `. ~/.bash_profile`

## Using Environment Variables

- Access an environment variable: `echo $VARIABLE_NAME`
- Example: `echo $PATH`

## Common Environment Variables

- `USER`: Current logged in user's name.
- `PS1`: Command prompt appearance.
- `HOME`: User's home directory path.
- `PATH`: List of directories the shell searches for executable files.

## Using `env` to List Environment Variables

- List all environment variables: `env`
- Find a specific variable: `env | grep VARIABLE_NAME`
- Example: `env | grep PATH`

Remember, `.bash_profile` is used by Bash, the default shell on macOS and many Linux distributions. If you're using a different shell (like Zsh, which uses `.zshrc`), or a different operating system's default shell, some details may vary.
