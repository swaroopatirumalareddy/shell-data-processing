# shell-data-processing
## Basic Bash commands
- mkdir creates a new directory
- ls List directory contents
- echo — Prints text to the terminal window
- touch — Creates a file
- man — Print manual or get help for a command
- locate — Locate a specific file or directory
- rmdir deletes the specified empty directory
- rm deletes a specified directory containing files
- pwd shows the current working directory
- cat displays the contents of file
## Command used to fetch data from url:
curl "https://knowindia.gov.in/my-india-my-pride/interesting-facts-about-india.php"
## Command used to count unique words in a sequential order:
tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt

- tr tranforms or deletes characters from strings
- sort sorts the contents of a file in a particular order
- uniq -c returns the number of times a word is repeated
- sort -nr option -n sorts numnerically and option -r sorts in reverse order
## Command used to display top 5 unique words
- head-5 result.txt

