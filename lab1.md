## Introduction
This lab report explores three fundamental commands: cd, ls, and cat, which are crucial for anyone aiming to master the macOS terminal. Through practical examples, we'll demonstrate how these commands are used to change directories, list contents, and display file contents, respectively. Each command will be showcased under three different scenarios to provide a comprehensive understanding of their functionality and output. 

## Command Examples
**'cd' command**

*No Arguments

![Image](cd No Arguments.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu

Why that output: The 'cd' command without arguments takes you to your home directory by default. 

Error or not: No error is produced.


*Directory Path Argument

![Image](cd DPA.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1/messages

Why that output: Using 'cd' with a directory path changes the current directory to the specified one. 

Error or not: No error is produced as messages is a valid directory.


*File Path Argument

![Image](cd FPA.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output:  'cd' expects a directory, not a file. 

Error or not: Trying to cd into a file results in an error.



**'ls' command**

*No Arguments

![Image](ls1.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' without arguments lists all items in the current directory.

Error or not:  No error is produced.


*Directory Path Argument

![Image](ls2.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a directory path lists the contents of that directory. 

Error or not: No error is produced since messages contains files.


*File Path Argument

![Image](ls3.jpg)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a file path confirms the file's existence by listing it. 

Error or not: No error is produced.


**cat command**
