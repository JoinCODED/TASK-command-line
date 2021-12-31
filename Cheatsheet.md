## Terminal Cheat Sheet

> **Tip before you use the cheat sheet:**
> Anytime you see `FILE_NAME` or `FOLDER_NAME` that means you should write a file name, or a folder name, don't literally write `FILE_NAME` because that's not part of the command.

`cd FOLDER_NAME`: is used to navigate to the folder

`cd ..`: is used to go up in a directory level

`cd -`: is used to go back in history

`cd `: is used to go to home directory `~`

`cd ~`: is used to go to home directory `~`

`cd /`: is used to go to root directory `/`

`ls`: is used to list all items in a folder

`ls -la`: is used to list all items in a folder with details and hidden folder

`pwd`: is used to print the current working directory to know where we are in the folder structure

`touch` is used to create a new file

`mkdir` is used to create a new directory

`nano FILE_NAME` is used to open a text editor to edit a file

`code .` to open Vs code for the current working directory. By default this command is available on Windows when installing VSCode, but for mac users, you will have to install it by going to VSCode then open he command pallete (command + shift + p) and write `shell`. Choose `Shell Command: install 'code' command in PATH`

`rm FILE_NAME` to remove a single file

`rm -rf` to force remove a whole folder with its whole content

`cat FILE_NAME` to print out the content of the file

`echo "ANY_TEXT"` to print out the text after the word `echo`

`COMMAND > FILE_NAME` is used after a command to save the content of the output of the command in an existing file, or a new file. If the file has content, it will override it.

`COMMAND >> FILE_NAME` is used after a command to save the content of the output of the command after the end of an existing file, or a new file. If the file has content, it will just append to it.
