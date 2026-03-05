command substitution allows you to use the output of a command as an argument to antother commadn 
example
command = $(ls -l file1.jpg)
echo $command