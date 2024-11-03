# guvi-zenclass-task6-7
Bash Scripting

Create a shell script to print the HTTP error code of guvi.in & print, the success/failure message based on the error code response

![shell script](https://github.com/ranju386/guvi-zenclass-task6-7/blob/main/oct-devops-24-task6.jpg)

Explanation

1.	curl -o /dev/null -s -w "%{http_code}\n": This command uses curl to request the URL, suppresses the output (-o /dev/null), hides progress (-s), and only prints the HTTP status code.
2.	The script checks if the status code is in the range of 200 (success), 400 (client error), or 500 (server error), printing a specific message based on the category.

sed command

Given a file, replace all occurrence of the word "give" with "learning" from 5th line till the end in only those lines that contain the word "welcome"

![sed command](https://github.com/ranju386/guvi-zenclass-task6-7/blob/main/oct-devops-24-task7-a.jpg)

Explanation:
1. sed -i edits the file in place.
2. 5,$ specifies the range from the 5th line to the end of the file.
3. /welcome/ checks for lines containing "welcome."
4. s/give/learning/g replaces all occurrences of "give" with "learning" in matched lines.
