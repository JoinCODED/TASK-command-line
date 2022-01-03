## Terminal Cheat Sheet

> **Tip before you use the cheat sheet:**
> Anytime you see `FILE_NAME` or `FOLDER_NAME` that means you should write a file name, or a folder name, don't literally write `FILE_NAME` because that's not part of the command.

## Commands

`cd FOLDER_NAME`: is used to navigate to the folder

`cd ..`: is used to go up in a directory level

`cd -`: is used to go back in history

`cd` or `cd ~` are used to go to home directory `~`

`cd /`: is used to go to root directory `/`

`ls`: is used to list all items in a folder

`ls -la`: is used to list all items in a folder with details and hidden folder

`pwd`: is used to print the current working directory to know where we are in the folder structure

`touch FILE_NAME` is used to create a new file

`mkdir FOLDER_NAME` is used to create a new directory

`nano FILE_NAME` is used to open a text editor to edit a file

`code .` to open Vs code for the current working directory. By default this command is available on Windows when installing VSCode, but for mac users, you will have to install it by going to VSCode then open he command pallete (command + shift + p) and write `shell`. Choose `Shell Command: install 'code' command in PATH`

`rm FILE_NAME` to remove a single file

`rm -rf` to force remove a whole folder with its whole content

`cat FILE_NAME` to print out the content of the file

`echo "ANY_TEXT"` to print out the text after the word `echo`

`COMMAND > FILE_NAME` is used after a command to save the content of the output of the command in an existing file, or a new file. If the file has content, it will override it.

`COMMAND >> FILE_NAME` is used after a command to save the content of the output of the command after the end of an existing file, or a new file. If the file has content, it will just append to it.

---

## Important Notations

`.`: the current working directory (where you are standing now in terminal)

`..`: the parent working directory

`/`: the root folder. You shouldn't mess around there

`~`: the home folder, if you have more than one user in your computer, the home folder is going to be the home of the user that you are currently sig ned in though.

`$`, `$` or `#`, the one that shows at the beginning of every prompt in the command line
In short, if the screen shows a dollar sign ($) or hash (#) on the left of the blinking cursor, you are in a command-line environment.

$, #, % symbols indicate the user account type you are logged in to.

- Dollar sign `$` means you are a normal user.
- hash `#` means you are the system administrator (root).
- In the C shell, the prompt ends with a percentage sign `%`.

There are differences on prompts in different Unix or GNU/Linux distributions because of their default settings.

For example, the prompt of Debian/Ubuntu is

```
guest@linux:~$
```

The one of Fedora/CentOS/RedHat is

```
[guest@linux ~]$
```

And the one of SuSE Linux/OpenSUSE is

```
guest@linux:~>
```

In general, the prompt usually show the login user name, machine hostname, and current working directory and ended with a dollar `$`, percentage `%`, or hash `#` sign.

```
guest@linux:~$
```

- `guest` - username: the user account you are logged in to.
- `linux` - machine hostname: the machine you are operating.
- `~` - current working directory: the directory you are in.
- Tilde `(~)` means home directory, i.e. the default directory when first logging in.

[Reference](wiki.debian.org.hk/w/Basic_Command_Line)
