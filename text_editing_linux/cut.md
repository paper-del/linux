cut is a command line utility that allows you to cut parts of a line from specified files or piped data and print result 
cut option file
flags
	-f selected by specifying a field set of fields or a range of fields
	-b by bytes
	-c by characters
	-d specifies delimeter that will be use instead of tab
	--complement Complement the selection. When using this option, `cut` displays all bytes, characters, or fields except the selected ones
	-s doesnt print linesnot containing delimeters
examples
cut -f 1,3 test.txt
shows only 1 and 3 line
cut -f -4 test.txt
from 1 to 4