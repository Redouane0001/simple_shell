 0x16. C - Simple Shell team project
0.
Write a beautiful code that passes the Betty checks
1.
Write a UNIX command line interpreter.
Usage: simple_shell
Your Shell should:
Display a prompt and wait for the user to type a command. A command line always ends with a new line.
The prompt is displayed again each time a command has been executed.
The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
You don’t have to:
execve will be the core part of your Shell, don’t forget to pass the environ to it…
2.
Simple shell 0.1 +
Handle command lines with arguments
3.
Simple shell 0.2 +
Handle the PATH
fork must not be called if the command doesn’t exist
4.
Simple shell 0.3 +
Implement the exit built-in, that exits the shell
Usage: exit
You don’t have to handle any argument to the built-in exit
5. 
Simple shell 0.4 +
Implement the env built-in, that prints the current environment
6.
Simple shell 0.1 +
Write your own getline function


You will need to use static variables
You are not allowed to use getline
7.
Simple shell 0.2 +
You are not allowed to use strtok
8.
Simple shell 0.4 +
9.
Simple shell 0.4 +
handle arguments for the built-in exit
Usage: exit status, where status is an integer used to exit the shell


10.
Simple shell 1.0 +
Implement the builtin command cd:
11.
Simple shell 1.0 +
Handle the commands separator ;


12.
Simple shell 1.0 +
Handle the && and || shell logical operators
13.
Simple shell 1.0 +
Implement the alias builtin command
14.
Simple shell 1.0 +
Handle variables replacement
15.
Simple shell 1.0 +
Handle comments (#)
16.
Simple shell 1.0 +
Usage: simple_shell [filename]
Your shell can take a file as a command line argument

