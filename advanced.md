### Advanced Linux Commands ###

## grep
Searches text in files

Example:
grep "error" logfile.txt


## find
Searches files in directories

Example:
find / -name file.txt


## awk
Processes text column-wise

Example:
awk '{print $1}' file.txt


## sed
Edits text in files

Example:
sed 's/old/new/g' file.txt


## tar
Archives files

Examples:
tar -cvf backup.tar folder
tar -xvf backup.tar
