# Chapter 1: The Big Picture
## 1.1: Levels and Layers of Abstraction in a Linux System
  <details> 
    <summary>How many levels do you have in the Linux system?
</summary>
      A Linux system has three main levels. Hardware, Kernel and User Processes.
    </details>

## 1.2: Hardware: Understanding Main Memory
 <details> 
    <summary>What is a CPU?
</summary>
      A CPU is an operator on memory, it reads data from the memory and writes data back out to the memory.
    </details>
    
## 1.3: The kernel
<details> 
    <summary>What is the Kernel?
</summary>
      The kernel is software residing in memory, acting as a mediator, manages the hardware and is the primary interface between hardware and any running program.
    </details>

## 1.4: User Space


## 1.5: Users


# Chapter 2: Basic Commands And Directory Hierarchy
## 2.1: The Bourne Shell: /bin/sh
<details> 
    <summary>What is the Shell?
</summary>
      The shell is one of the most important parts of the Unix/Linux system. It is a program used to run commands that the user enters into the terminal.
    </details>
    
## 2.2: Using The Shell

<details>
  <summary>A shell window as a terminal.</summary>

  Dấu nhắc lệnh (prompt) thường kết thúc bằng `$`. Nếu bạn thấy `#` thay vì `$`, có nghĩa là bạn đang chạy terminal với quyền root.
</details>

  <details>
  <summary>Cat</summary>
  Output the contents of one or more files or another source of input.
</details>

<details>
  <summary>(stdin and stdout)</summary>
  Unix processes use I/O streams to read and write data.Processes read data from input streams and write data to output streams.
</details>

## 2.3: Basic Commands
<details>
  <summary>ls</summary>
The ls command lists the contents of a directory.
</details>

<details>
  <summary>cp</summary>
cp copies files.  $cp file1 file2 (copy file1 to file2).
</details>

<details>
  <summary>mv</summary>
 use mv to move files to other directories or renames a file($ mv file1 file2). 
</details>

<details>
  <summary>touch</summary>
The touch command create a file.
</details>

<details>
  <summary>rm</summary>
deletes (removes) a file.
</details>

<details>
  <summary>echo</summary>
The echo command prints its arguments to the standard output.
</details>


## 2.4: Navigating Directories
<details>
  <summary>What is a absolute path?</summary>
 A path starts with /.
</details>

<details>
  <summary>What is a relative path?</summary>
 A path starts with not /.
</details>

<details>
  <summary>What is cd command?</summary>
  Changes the current working directory.
</details>

<details>
  <summary>What is a mkdir or rmdir command?</summary>
 The mkdir command creates a new directory. The rmdir command removes the directory.  $rm -r dir (to delete a directory and its contents).
</details>

<details>
  <summary>What is a Shell Globbing? (“Wildcards”)?</summary>
 Shell Globbing (also known as Wildcards) is a technique in Linux that allows the use of special characters (wildcards) to search, filter, or manipulate multiple files and directories simultaneously. $ls *.txt (List all .txt files in current directory).
</details>

## 2.5: Intermediate Commands
<details>
  <summary>What is a grep?</summary>
 The grep command prints the lines from a file or input stream that match an expression. For example, to print the lines in the /etc/passwd file that contain the text root, enter this:
 $ grep root /etc/passwd
</details>

<details>
  <summary>There are three important things regular expressions:</summary>
 •	.* matches any number of characters, including none (like the * in globs and wildcards).
 •	.+ matches any one or more characters.
 •	. matches exactly one arbitrary character
</details>

<details>
  <summary>What is a grep?</summary>
 The grep command prints the lines from a file or input stream that match an expression. For example, to print the lines in the /etc/passwd file that contain the text root, enter this:
 $ grep root /etc/passwd
</details>

<details>
  <summary>There are three important things about regular expressions:</summary>

  •  `.*`  
     Matches any number of characters, including none (like the `*` in globs and wildcards).  

  •  `.+`  
     Matches any one or more characters.  

  •  `.`  
     Matches exactly one arbitrary character.  

</details>



## 2.6: Changing Your Password and Shell
## 2.7: Dot Files
## 2.8: Environment and Shell Variables
## 2.9: The Command Path
## 2.10: Special Characters
## 2.11: Command-Line Editing
## 2.12: Text Editors
## 2.13: Getting Online Help
## 2.14: Shell Input and Output
## 2.15: Understanding Error Messages
## 2.16: Listing and Manipulating Processes
## 2.17: File Modes and Permissions
## 2.18: Archiving and Compressing Files
## 2.19: Linux Directory Hierarchy Essentials
## 2.20: Running Commands as the Superuser












