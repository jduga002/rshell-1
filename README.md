#rshell
**rshell** is a budding executable file that has functionality like a shell on UNIX-operating systems, like the GNOME terminal.
This project is currently in development, and as is only a very simplistic base of a terminal. Additional functions will be added in the near future.

#How to Use
The rshell executable currently supports these capabilities of a shell.
```
Printing via command prompt.
Performing executables with argumentList functionality.
Connectors(&&, ||, ;) can be used freely within the code to execute multiple commands.
Displays various error messages of executables that fail to execute.
Exit the shell by typing 'exit'.
```

#Installation Guide
Follow these steps on a shell of your own:
```
$ git clone  http://github.com/yourusername/rshell.git
$ cd rshell
$ git checkout hw0
$ make
$ bin/rshell
```

#Bugs/Limitations/Issues
As this is still a project in development, this list will be updated with bugs, issues, and concerns that plague this project from completion.
```
*Unable to parse more than 2 connectors in a single command prompt.
*Unable to comprehend a combination of && and || connectors in a single command prompt.
*The code suffers from an extensive algorithm that, at best, only works for 1 occurence of connectors per line or ; connector parse.
```
