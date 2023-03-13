0. echo "Hello World" => Prints Hello World to the screen
1. echo '"(Ôo)'\' => Displays a confused smiley
2. cat /etc/passwd => Displays a file
3. cat /etc/passwd /etc/hosts => Displays two files content
4. tail /etc/passwd => Displays the last 10 lines of /etc/passwd
5. head /etc/passwd => Displays the first 10 lines of /etc/passwd
6. head -3 iacta | tail -1 => Displs the third line of the file iacta
7. echo "Best School" > \\\*\\\\"'\"Best School"\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) => Creates the file with the test Best School
8. ls -la > ls_cwd_content => Writes the result of ls -la into the file ls_cwd_content
9. tail -n 1 < iacta >> iacta => Duplicates the last line of the file iacta
10. find . -type f -name "*.js" -delete => deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. find . -type d -not -name '.' | wc -l =>  a script that counts the number of directories and sub-directories in the current directory.
12. ls -t1 | head => a script that displays the 10 newest files in the current directory.
13. sort | uniq -u =>  a script that takes a list of words as input and prints only words that appear exactly once.
14. grep -i "root" /etc/passwd => Display lines containing the pattern “root” from the file /etc/passwd
15. grep -i "bin" /etc/passwd => Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16. grep -iA 3 "root" /etc/passwd => Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
17.  
