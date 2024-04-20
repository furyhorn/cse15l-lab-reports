## Introduction
This lab report explores three fundamental commands: ```cd```, ls, and cat, which are crucial for anyone aiming to master the macOS terminal. Through practical examples, we'll demonstrate how these commands are used to change directories, list contents, and display file contents, respectively. Each command will be showcased under three different scenarios to provide a comprehensive understanding of their functionality and output. 

## Command Examples

**'cd' command**
---
>No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/5493e2c5-0027-42e1-9072-4083f7a37ba8)

absolute path before: 
```
/Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1
```

Why that output: The 'cd' command without arguments takes you to your home directory by default. 

Error or not: No error is produced.



>Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/ec47c357-0cee-4586-9749-bcbc7b534bc7)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: Using 'cd' with a directory path changes the current directory to the specified one. 

Error or not: No error is produced as messages is a valid directory.



>File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/6fc0be3b-ad32-4c0d-96f3-72a7e199f305)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output:  'cd' expects a directory, not a file. 

Error or not: Trying to cd into a file results in an error.




**'ls' command**
---
>No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/1b39e91d-ff9a-4790-bd0f-69beb3180a89)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' without arguments lists all items in the current directory.

Error or not:  No error is produced.



>Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/7e0e24e6-b8c1-4697-84e2-b048d0de5dc6)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a directory path lists the contents of that directory. 

Error or not: No error is produced since messages contains files.



>File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/948990be-5606-4c02-95d8-20fcf6b5901a)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'ls' with a file path confirms the file's existence by listing it. 

Error or not: No error is produced.



**cat command**
---
>No Arguments

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/8dda8baf-f35a-42ec-ba31-27cd324e6598)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' without arguments reads from standard input. 

Error or not: It's not an error, but not typical usage for viewing files.



>Directory Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/c0e3f470-7021-48c5-8c11-1ae4acbd2e42)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' cannot be used on directories.

Error or not: Trying to 'cat' a direcory results in an error.



>File Path Argument

![image](https://github.com/furyhorn/cse15l-lab-reports/assets/165836763/e02b44b7-0760-4610-a54e-3890ce9c8fbe)

absolute path before: /Users/shirleyxu/Desktop/UCSD/CSE 15L/lecture1

Why that output: 'cat' displays the contents of the specified file. 

Error or not: No error is produced.
