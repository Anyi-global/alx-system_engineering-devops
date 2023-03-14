0. alias ls="rm *" => a script that creates an alias.
1. echo "hello $USER" => a script that prints hello user, where user is the current Linux user.
2. export PATH=$PATH:/action => Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
3. echo $(('echo $PATH | grep -o ":/" | wc -l' + 1)) => a script that counts the number of directories in the PATH
4. printenv => a script that lists environment variables.
5. set =>  a script that lists all local variables and environment variables, and functions.
6. BEST="School" =>  a script that creates a new local variable
7. export BEST="School" => a script that creates a new global variable.
8. echo $(($TRUEKNOWLEDGE + 128)) => a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
9.  
