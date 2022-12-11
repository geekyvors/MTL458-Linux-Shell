# MTL458-Linux-Shell
We will first build a simple shell, much like the bash shell of Linux. A shell takes in user input, forks one or more child processes using the fork system call, calls exec from these children to execute user commands, and reaps the dead children using the wait system call.

The basic functions in the Shell :
* Support simple command execution. 
* Support running commands in background.
* Support piping between commands
* Support environment variables
* _cmd history_: Display the Last 5 executed commands (irrespective of failure or successful run) in FIFO order(latest command on top)
* _ps history_: Display all the child processes started by user along with their current status (RUNNING or STOPPED).
