## Welcome to TEDxSoftdev Shell Scripting by Sadid Ethun and Theo Fahey

### What is a Shell Script?

- A shell script is a program to be run by a shell.  
- A shell is a command line interpreter. 
- Steve Bourne created the first shell for Unix.

### Hsitory of Unix Shells

- First shell was made by Ken Thompson in 1971.
- Steve Bourne made the Bourne Shell in 1977.
- Goals to interactively execute commands and writing reusable scripts.

### Bash

- Bourne-Again Shell made to replace the Bourne Shell.
- Improvements such as command history, command-line editing, and job control (pausing and resuming processes).

### Running a Shell Script

- To run a .sh file, you must make the file executable using chmod +x  
- No need to compile separately as the language is written for the shell to understand

### Hello World

Code:
```
#!/bin/bash
echo "Hello, world!"
```

Output:
```
Hello, World!
```

### Variables 
- The shell treats the “=” sign as a variable assignment.
- There cannot be spaces around the “=” sign.
- The shell does not care about types of variables.
- Some special variables are already set.

Code:
```
message="Hello World"
echo $message
```

Output:
```
Hello World
```

### Arrays
-

### Conditionals
-

### Loops
- For loops iterate through a set of values until the list is exhausted.

Code:
```
for i in 1 2 3 4 5
do
  echo "Looping ... number $i"
done
```

Output:
```
Looping ... number 1
Looping ... number 2
Looping ... number 3
Looping ... number 4
Looping ... number 5
```   
      
- While loops will run indefinitely until a specific case is reached.

Code:
```
a=0
while [ $a -lt 5 ]
do
   echo $a
   a=`expr $a + 1`
done
```

Output:
```
1
2
3
4
5
```
