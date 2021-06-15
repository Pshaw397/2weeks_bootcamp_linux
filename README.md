# DevOps Bootcamp

## Introduction to DevOps and why DevOps/benefits

- DevOps is the intergration of Development and Operations
- Incorporates Continous Intergration/Delivery/Deployment into the life cylce
- Allows for the silos of Development and Operations to be broken down for happier, more collaborative teams
- Ensures good processes across the different teams, including automating the development process.
- Increased automation means the developed code will contain less defects when it is deployed

### Linux commands that also work on Bash
- Create a Dir `mkdir name_of_the_dr`
- Go inside the Dir `d name of the dir`
- Come out of the Dir `cd ..` or `cd`
- Who am I `pwd`
- Create a file `touch name_of_the_fil` or `nano file_name` you land inside the file
- Exit from nano `ctrl x` then `y` then `enter`
- List all `ls -a` or `ls`
- To see the contents of the file on the terminal `cat file_name`
- Clear your screen `clear`
- Delete a folder `rm -rf name_of_the_folder`
- Delete an individual file `rm name_of_the_file`
- Find out machine name `uname` or `uname -a` for full machine name

## More Linux commands
- To see hidden files `ls -a`
- The wildcards are `*` for zero or more, `?` for a single character and `[]` to represent a range of characters.
- To list processes use ps `-ef`.
- To kill a specific process use kill `-9 PID`.
- To resume suspended jobs whilst keep them in the background `bg`.
- To continue a stopped job by running it in the foreground `fg`.
- To print the final few lines of a file `tail`.
- To print the first few lines of a file `head`.
- To sort using a variety of different options `sort (option) <filename>`.
- To count a certain type of data `wc`. Some examples include `-l` for lines or `-w` for words.
- `r` makes a file readable.
- `w` makes a file writable.
- `x` makes a file executable.
- 777 allows all control over a file.
- 400 allows the owner to read a file.
- 600 allows the owner to read and write a file.
- `chmod +rwx filename` to add permissions.
- `chmod -rwx directoryname` to remove permissions.
- `chmod +x filename` to allow executable permissions.
- `chmod -wx filename` to take out write and executable permissions.
- `ls -l [path]` to view permissions of a selected file

- Piping and redirection is the how we connect the streams between programs and files to direct data in a variety of useful ways.
- `STDIN (0)` is a standard input (data fed into the program)
- `STDOUT (1)` is a standard output (data printed by the program, defaults to the terminal)
- `STDERR (2)` is a standard error (for error messages, also defaults to the terminal)
