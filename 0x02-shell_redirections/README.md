* echo "Hello, World" is a script that prints "Hello, World", followed by a new line to the standard output
* echo \"\(Ôo\)\' is a script that displays a confused smiley "(Ôo)'
* cat /etc/passwd is a script that displays the content of the /etc/passwd file
* cat /etc/passwd /etc/hosts is a script that displays the content of /etc/passwd and /etc/hosts
* tail -n 10 /etc/passwd is a script that displays the last 10 lines of /etc/passwd
* head -n 10 /etc/passwd is a script that displays the first 10 lines of /etc/passwd
* head -n 3 iacta | tail -n 1 is a script that displays the third line of the file iacta in the working directory
* echo "Best School" | cat > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)' is a script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
* ls -la > ls_cwd_content is a script that  writes into the file "ls_cwd_content" the result of the command "ls -la"
* tail -n 1 iacta | cat >> iacta is a script that duplicates the last line of the file in the working directory
* find . -type f -name "*.js"  -delete is a script that finds all regular files with .js extension and delete them
* find . -mindepth 1 -type d | wc -l is a script that searches and counts the number of directories and subdirectories (current and parent directories not included) beginning from the current directory
* ls -t1 | head -n 10 is a script that lists the files and directories in the current directory, sorted by modification time (newest first) and then displays the 10 newest files in the current directory
* sort | uniq -u is a script that takes input lines, sorts and filters them to ensure that only lines without duplicates are displayed
* grep "root" /etc/passwd is a script that searches for lines in the /etc/passwd file which contain the pattern "root" and then displays those lines as output
* grep -c "bin" /etc/passwd is a script that searches for lines in the /etc/passwd file which contain the pattern "bin" and then displays the total count of the lines as the output
* grep -A 3 "root" /etc/passwd is a script that searches for lines in the /etc/passwd file which contain the pattern "root" and displays each matching line alongside the three lines that come after it
