# Cyber Security 

Basic Cyber security Sutff

## Linux Basic Commands

|Command|Use|
|---|---|
|`\|`|Pipe is used to redirect the output of one command/program to input of another command/program|
|`ls`|lists the contents of the current directory|
|`ls dir`|lists the contents of directory `dir`|
|`ls -a dir`|lists the contents including the hidden files/folders|
|`ls -l file`|gives information about owner, creation date and time, permissions for file|
|`mkdir dir`|will make a new directory `dir`|
|`mkdir -p dir1/dir2`|creates the required parent directories if it dosent't already exist|
|`cd dir`|changes the directory to `dir`|
|`cd ..`|moves to parent directory of current directory|
|`cd`|moves to the home directory|
|`touch file`|creates a new empty file with filename `file`|
|`cat file`|displays contents of `file`|
|`cat file1 file2 > file3`|create a new file `file3` with contents of both `file1` and `file2`|
|`cat file1 >> file2`|adds contents of `file1` to end of `file2`|
|`cp file1 file2`|copies contents of `file1` to a new file `file2`|
|`cp -r dir1 dir2`|copies the directory `dir1` to a new directory `dir2` with the contents of `dir1`|
|`mv file1 file2`|changes the name of file from `file1` to `file2`|
|`mv dir1 dir2`|changes the name of directory from `dir1` to `dir2`|
|`mv file1 file2 dir1`|moves both file1 and file2 to the directory dir1 given that the directory exists.|
|`rm file1` | removes the file `file1`|
|`rmdir dir1` |removes the directory `dir1` only if the directory is empty|
|`rm -rf dir1` | removes the directory `dir1` even if it has contents|
|`echo argument`| writes `argument` to standard output|
|`grep "hello" file`| gives the lines that contain `hello`|
|`grep -i "hello" file` | search for the string case insensitively|
|`grep -c "hello" file`| prints the number of lines which has the string|
|`grep -v "hello" file` | displays the line that are not matched|
|`grep "^hello" file`| matches the lines that start with the string|
|`grep "hello$" file`| matched the lines that end with the string|
|`tr -d 'w' file`|removes all w from the `file`|
|`tr -s file` | replaces multiple spaces in a string with single space |
|`tr -cd 'w' file` | complement of what other option does. So here removes everything except w|
|`cut -b 1,2,3 file.txt` |prints the first 3 bytes of each line in the file|
|`cut -b 2-5 file.txt` | prints the 2nd to 5th bytes of each line|
|`cut -d " " -f 1 file.txt` | d spefifies the delimiter and f specifies the field|
|`sort file.txt` |  sorts the contents of the file|
|`sort -o out.txt in.txt`| puts the output to out.txt|
|`sort -r file.txt` | sorts in reverse order|
|`sort -n file.txt` | sorts the files in numeric order|
|`sort -u file.txt` | removes duplicate elements|
|`man command`|displays a manual page about the command|
|`ssh sample.ssh.com` |connects to a remote computer called sample.ssh.com|
|`ssh user@sample.ssh.com` |can be used to log in as a different user|
|`ssh user@sample.ssh.com -p port`| can be used to specify the `port` to connect to|
|`xxd file.txt` |Prints out the hex dump of the given `file`|
|`$var`|used to output the value of the variable `var`|

Sort command sorts the contents of a text file, line by line.

- Lines starting with a number will appear before lines starting with a letter.
- Lines starting with a letter that appears earlier in the alphabet will appear before lines starting with a letter that appears later in the alphabet.
- Lines starting with a lowercase letter will appear before lines starting with the same letter in uppercase.

### Looping in Bash

- **if statement**: `if [ exp1 condition exp2 ]; then statements; fi` : `statement` gets executed if condition satisfies for `exp1` and `exp2`. `conditions` can be

  - `-eq` equal to
  - `-ne` not equal to
  - `-gt` greater than
  - `-lt` less than
  - `-a` and
  - `-o` or

- **if else statement** : `if [ exp1 condition exp2 ]; then statements; else statements; fi`

- **if else if statement** : `if [ exp1 condition exp2 ]; then statements; elif [ exp1 condition exp2 ] then statements; else statements; fi`

- **for statement** : `for i in {1..n}; do command; done` or `for((i=1;i<=n;i+=1)); do command; done`

- **while statement** : `while condition; do command; done`

## Reversing

The Roadmap 

![alt text](https://github.com/Amik-Sen-Fun/InCTF-Bro/blob/main/images/re.png?raw=true)
