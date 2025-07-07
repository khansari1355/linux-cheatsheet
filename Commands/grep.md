## grep
- grep -i "pattern" file  : case-insensitive search
- grep -r "pattern" folder/ : recursive search

samples
grep "system" /etc/passwd
small or capital find
grep -i "system" /etc/passwd
or input redirection
grep -i "system" < /etc/passwd
Search system to all file in /etc folder
grep -i "system" /etc/*
Search system to all file in all directory and subdirectory
grep -iR "system" /etc/*
Reverse Search 
grep -v "system" /etc/passwd
show line number and result Search
grep -n "system" /etc/passwd 
