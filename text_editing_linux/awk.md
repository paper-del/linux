awk command can search for a pecific word or pattern in a piece of text given or selext a certain column in a file you provide

example
	awk 'action' file.txt
when you want to search for text with a specific pattern or youre looking for a specific word in the text. the command would look something like this
	awk '/regex patter/action' file.txt

awk '{print $0}' information.txt
	work like a cat

awk '{print NR,$0}' information.txt
	use nr and nummers lines

awk '{print $1}' information.txt
	printcertain column

awk '{print $1, $4}' information.txt
	print 1 and 4 collumn

awk '{print $NF}' information.txt
	print last column

awk '{print $1}' information.txt | head -1
	print certified column and line

awk '/^O/' information.txt
	selects any line with text that starts with an O