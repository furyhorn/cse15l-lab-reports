## Introduction
This lab report explores three fundamental commands: cd, ls, and cat, which are crucial for anyone aiming to master the macOS terminal. Through practical examples, we'll demonstrate how these commands are used to change directories, list contents, and display file contents, respectively. Each command will be showcased under three different scenarios to provide a comprehensive understanding of their functionality and output. 

## Command Examples
**'cd' command**

*No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/a42780ec-f8f7-4f45-8222-4f3ad4cb2927)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu

Why that output: The 'cd' command without arguments takes you to your home directory by default. 

Error or not: No error is produced.


*Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/703cbc15-60a2-4569-87f6-701a25b18721)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1/messages

Why that output: Using 'cd' with a directory path changes the current directory to the specified one. 

Error or not: No error is produced as messages is a valid directory.


*File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/b6aad1a3-46bd-4b3b-8224-d30df91d9fcb)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output:  'cd' expects a directory, not a file. 

Error or not: Trying to cd into a file results in an error.



**'ls' command**

*No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/08a9fc97-1997-4433-adb8-6fb768d1d88e)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' without arguments lists all items in the current directory.

Error or not:  No error is produced.


*Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/b185d995-a714-4399-8936-395b9288a968)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a directory path lists the contents of that directory. 

Error or not: No error is produced since messages contains files.


*File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/3c60e189-9707-45a2-af37-bd30a138167c)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a file path confirms the file's existence by listing it. 

Error or not: No error is produced.


**cat command**

*No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/db5d0df0-a522-4384-b371-3f9ecb67d935)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' without arguments reads from standard input. 

Error or not: It's not an error, but not typical usage for viewing files.


*Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/d8aea548-b9a3-4756-97fc-f608be4ec297)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' cannot be used on directories.

Error or not: No error is produced.


*File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/8e99df1a-ed6a-4d48-979e-c8c98767b302)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

absolute path after: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' displays the contents of the specified file. 

Error or not: No error is produced.
