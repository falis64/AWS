# LINUX COMMANDS
```cd``` - changes directory

```ls``` - provides a list of the files and folders in the current directory

```ls -a``` - same as ```ls``` but also shows all hiden files/folders

```ls -l``` - lisrs the contents of current directory in a long format

```pwd``` - shows your current location

```touch``` - creates new folder

```nano 'name'``` - opens 'name'file with ```nano``` editor

```cat 'name' ``` - shows content of 'name' folder

```mkdir``` - creates new directory

```mkdir 'directory'``` - creates a new directory with a specified name

```uname``` - states details of operating system

```nano``` - opens the specified file in the nano text editor

```cp``` - copy

```cp'source''destination'``` - copyies a file from the source path to the destination

```rm 'file'```- deletes specified file

```cd ..``` - go back one step

```ll``` - lists the details of all the files inside the folder

```mv``` - used to move or rename files

```chmod 700 'filename'``` - changes permission of the file

```top`` - shows all the running processes(opens task manager)

```head -1 filename``` - this would show only the first lines of a files

```tail -2``` = shows the last 2 lines of a file

```nl filename``` - numbers content of file

```cat filename | grep word``` - finds a particular word in file

```ps aux | grep bash``` - finds running processes that are using bash

```sudo su``` - goes into admin mode

```sudo touh 'filename'``` - creates a script file

```sudo nano 'filename'``` - opens file with nano

```sudo systemctl stop/start nginx``` - used to stop/start process

```sudo apt install``` - installs nginx

```sudo apt update/upgrade nginx``` - updates/upgrades services

```service nginx status``` - checks the status of nginx service

```sudo chmod +x filename``` - makes file executable

```sudo ./filename``` - executes file


# Creating variables in Linux

```printenv``` - Prints all the environmental variables

```env`` - Shows all current variables and their values

```Printenv variable_name``` - Prints the value of the variable

```echo $variable_name``` Prints the value of specified variable

```export VARIABLE=value``` - creates a new environmental variable with a specified value

```source .bashrc``` - refreshes the .bashrc to show any updated changes

In order to store variables in the environement so you can access it next time, you have to add them to the ```.bashrc``` script. The steps to do this are below:

- Open the script with a nano command which is ```nano .bashrc```

- Scroll to the bottom and add your new code there. Make sure to not touch any of the codes already there

- Now type in ```export Variable=value``` - this is to create an environmental variable which will be added to this script

- Now use ```printenv Variable``` to see if there was a change. You'll see that it has not and that's because it needs to be refreshed

- Use ```source .bashrc``` - this will show the updated .bashrc with your new added variable
