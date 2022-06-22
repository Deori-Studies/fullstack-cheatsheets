# Unix & Bash
## Creating and navigating

| Command           | Meaning                                               |
|-------------------|-------------------------------------------------------|
| ls                | list files and directories                            |
| ls -a             | lists all files and directories including hidden ones |
| mkdir directory   | create a directory                                    |
| cd directory      | change to named directory                             |
| cd                | change to home directory                              |
| cd ~              | change to home directory                              |
| cd ..             | change to parent directory                            |
| pwd               | show the path of the current directory                |


## Search and Manipulation

| Command           | Meaning                                               |
|-------------------|-------------------------------------------------------|
| cp file_1 file_2  | copy file_1 and call new file file_2                  |
| mv file_1 file_2  | move file_1 to file_2                                 |
| rm file           | remove a file                                         |
| rm -rf directory  | force remove a file or directory                      |
| cat file          | display a file                                        |
| less file         | display a file one page at a time                     |
| head file         | display the first lines of a file                     |
| tail file         | display the last lines of a file                      |
| grep keyword file | keyword search                                        |
| wc file           | counts the number of lines/words/characters in a file |
| man command       | show the online manual page for the given command     |
| whatis            | brief description of the given command                |
| apropos keyword   | proposes commands similar to the keyword              |


## Input and Output

| Command           | Meaning                                                                                            |
|-------------------|----------------------------------------------------------------------------------------------------|
| command > file              | redirect standard output to a file                                                       |
| command >> file             | append standard output to a file                                                         |
| command < file              | redirects the standard input of a file, lets you manipulate the file without changing it |
| commandone \| commandtwo    | pipes the output of commandone to the input of commandtwo                                |
| cat file_1 file_2 > file_12 | concatenates file_1 and file_2 into one file_12                                          |
| sort                        | sort data                                                                                |


## Permissions

| Command           | Meaning                                                                                            |
|-------------------|----------------------------------------------------------------------------------------------------|
| command > file              | redirect standard output to a file                                                       |
| who                         | list currently logged in users                                                           |
| ls -lag                     | list access rights for all files                                                         |
| chmod[options] file         | change access rights for the named file                                                  |


## Jobs and Processes

| Command           | Meaning                                                                                            |
|-------------------|----------------------------------------------------------------------------------------------------|
| command > file              | redirect standard output to a file                                                       |
| command &                   | run command in background                                                                |
| ctrl+c                      | eliminates work running in the foreground                                                |
| ctrl+z                      | suspend the job running in the foreground                                                |
| bg                          | returns suspended background processes                                                   |
| jobs                        | list suspended and background processes                                                  |
| fg %1                       | restarts the first suspended process                                                     |
| kill %1                     | terminates the first suspended process                                                   |
| ps                          | list current processes                                                                   |
| kill [PID]                  | kill the process with the informed PID                                                   |
| kill -9 [PID]               | force kill the process with the given PID                                                |
