$ ./main


xsh# pwd
/home/user


xsh# cd /tmp
xsh# pwd
/tmp


xsh# set FOO banana
xsh# echo My favorite fruit is a $FOO.
My favorite fruit is a banana.


xsh# unset FOO
xsh# echo I'd love to eat a $FOO colored slug.
I'd love to eat a  colored slug.


xsh# ls
file1.txt file2.txt


xsh# cat < file1.txt //pipe contents of file to input of cmd
This is file 1


ls > output.txt //pip cmd output to file


xsh# sleep 5 &
running in background: process ‘ID’


xsh# echo "Hello World" | tr 'a-z' 'A-Z'
"HELLO WORLD"


xsh# ls | wc -w
6


xsh# ls -l 
total 56
-rw-r--r-- 1 user user    90 Dec 12 22:35 file1.txt
-rw-r--r-- 1 user user  6128 Dec 12 22:50 cmd_shell.c


xsh# quit
