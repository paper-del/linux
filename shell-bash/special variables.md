$0
	the filename of the current script
$n 
	these variables correspond to the arguments with which s script was invoked here n is
	a positive decimal number corresponding to the position of an argument(the first argument is $1 the second argument is $2 and so on)
$#
	the number of arguments supplied to a script
$*
	all the arguments are double quoted if a script receives two arguments $* is equivalent to $1 $2
$@
	all the arguments are individually double quoted if a script receives two arguments $@ is equivalent to $1 $2 
$?
	the exit status of the last command executed 
$$
	the process number of the current shell fore shell scripts this is the process id under which they are executing
$!
	the process number of the last background command

you can add them by writing after opening script
./script.sh parameter parameter paremeter