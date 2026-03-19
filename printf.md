its like echo but better use [[conversion specifier]]
syntax
	printf [-v var] format [arguments...]
-v option tells printf to assign it to the variable var
the formati is a string that may contain three diferent types of objects:d
	- Regular characters are printed to the output as-is.
	- Backslash-escaped characters are interpreted and then printed.
	- Conversion specifiers that describe the format and are replaced by the values of respective arguments that follow the format string.
arguments are values that teplace the specifiers in the format string
the command accpets any number of arguments
printf "Open issues: %s\nClosed issues: %s\n" "34" "65"
Open issues: 34
Closed issues: 65

easier way
	prinf 'a\n' b c d 
		print a
	printf '%s\n' b c d 
		pritn b c d 
	printf 'hello %s\n ' b c d
		hello b
		hello c
		hello d
	print 'hello %s\n world %s\n' b c d e 
		hello b
		world c
		hello d
		world e

