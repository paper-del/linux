the nl command numerate files
examle
	nl text.txt
		1
		2
		3
	nl -s ". " text.txt
		1.
		add a dot and space after number
	nl -w 1 -s ". " distros.txt
	removes space 
	
	nl -b a distros.txt
		this counts blank lines too
	nl -v 100  distros.txt
		100
		101
		102
	nl -n rz distros.txt
		include leadning zeros for each line
		000001
		000002
		