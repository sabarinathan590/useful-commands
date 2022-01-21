# Useful terminal commands (Linux::Ubuntu)

## Commands

* `ps -ef | grep <KEY_TO_SEARCH>` To find a process by it's name or jar name

* `kill -9 <PROCESS_ID>` To kill a process using it's id. Note: to get the process id use above command (refer screenshot 1 for reference) 

* `kill -9 <PROCESS_ID1> <PROCESS_ID2>` To kill multiple process, provide multiple process id's with space

* `touch <FILE_NAME>` to create file

* `mkdir <FOLDER_NAME>` to create folder (directory)

* `rm <FILE_NAME>` to delete file. To delete multiple files in a single shot provide the file names with space

* `rmdir <FOLDER_NAME>` to delete a folder. To delete multiple folders in a single shot provide the folder names with space
  - `rm -rf <path>` recursively deletes dir and suppresses warning (**can be dangerious. `rm -rf /` would delete _everything_. use with caution**)

* `pwd` print current working directory

* `cd` go to root folder

* `cd <PATH>` go the specified path

* `cd <FOLDER_NAME>` go the folder from the current directory

* `cat <FILE_NAME>` to print the content of the file in the console

* `nohup java -jar test.jar &` to start a process in back ground and the output will written to nohup.out filr

* `head -n <FILE_NAME>` to display the first **n** lines of a file

* `tail -n <FILE_NAME>` to display the last **n** lines of a file

* `tail -f <FILE_NAME>` to follow the file content continously

* `wc -l <FILE_NAME>` to count the number of lines in a file

* `printenv | less` print all environment variables

* `history` show history of other commands entered into terminal
  - `history -<num>` only show last `num` commands

* `netstat -an | grep <PORT_NUMBER>` to check whether a port is being listened

* `netstat -an | grep <LISTEN>` to list all the ports which are being listned

* `zip <TARGER_FILE_NAME>.zip <SOURCE_FILES in space de-limitted>` to create a zip files with the mentioned files eg: zip newfile.zip name.txt

* `unzip <FILE_NAME>` to unzip a file

* `clear` clear console

* `mv <SOURCE FOLDER OR FILE> <TARGET FOLDER> ` to move a folder or file to a folder
  - At times mv command is used to rename a file like mv /home/1.txt /home/2.txt


#### Sample outputs
* screenshot 1

![image](https://user-images.githubusercontent.com/22836306/150583491-83de7027-31ea-4869-b357-9b52c02578c7.png)
