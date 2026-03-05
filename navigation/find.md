its command that helps find files in your system
finding a single file in the whole system
	find / -name "plik.txt"
finding everything
	fing ~/documents -ls
find by content
	find ~/Documents/ -name "*txt" -exec grep -Hi penguin {} \;
find by type
	fing ~ -type f
