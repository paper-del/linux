sed command is a stream editor used to perform basic text transformations on an input stream(a file or input form a pipeline)

basic usage
sed "s/old/new/" filename
example
Hello World
sed 's/world/bash/' text.txt

options
	-i edit files directly without needing to save separately
	-e add the script to the commands to be executed
	-n dont automatically print lines
	-r use extended regular expressions
	-f add script form a file
	-l specify line length for l command
	
