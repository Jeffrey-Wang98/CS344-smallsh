# CS344-smallsh

Written for Operating Systems CS344

This program was created for Unix systems.

This project recreates some Bash shell commands, such as cd, exit, and non-built-in commands using exec() functions.
This shell can parse file redirection, function calls and their parameters, and running programs in the background.
This is done by forking processes each time a new process is created. 

To run the shell, download all files and run `make` in root directory to create smallsh.exe. Then, run `./testscript` to run the script
that grades smallsh. This should output all tests and the score for the program. This should output a score of 180/180.
