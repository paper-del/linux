first method is to use bash command like
bash file.sh

next method is to put bash location on the begining of shell file
#!/bin/bash
and use
./file.sh 
	in terminal
but we need to add execution permission to this file using
chmod u+x file.sh

and last you can use source command
using this command ands variables to main process
source file.sh



