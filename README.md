## Cheatsheet

[Use the following cheat sheet](/Cheatsheet.md)

### 🍋 1. Create the Development folder

In this challenge, you will be creating the directory that you'll be using to save your work throughout this Bootcamp. Just follow the below steps to guide you:

1. Open the terminal (on Windows you should use [GitBash](https://github.com/git-for-windows/git/releases/download/v2.26.2.windows.1/Git-2.26.2-64-bit.exe))
2. Go into your home directory by running the command `cd`
3. Make sure you see this symbol `~` when you write another terminal command, which means you are at Home.
4. Create a new directory called `Development` inside Home folder using `mkdir`
5. Use `ls` to make sure that the `Development` directory was created.
6. Go into the `Development` directory using `cd Development`
7. Use `pwd` to make sure you're in the right directory

### 🌶 2. The space problem 🛸

1. Create a new directory inside the `Development` folder, call it `Terminal Challenge`.
2. `ls` after that command. Did you create 2 folders? That's because `mkdir` command takes any number of parameters. If you add a space, it will think that you want to create another folder. Delete those 2 folders using the command `rm FOLDER_NAME`
3. Did you get this error `rm: FOLDER_NAME: is a directory`? That's because `rm` only works for files, to remove a folder, you should use the command `rm -r FOLDER_NAME`, this command deletes a folder and its content.
4. `ls` to check that you deleted the 2 folders
5. Now create the folder `Terminal Challenge`, but use another naming convention, which is connecting every word by an underscore. call it `terminal_challenge`. This is a better naming convention that every developer uses, it's going to make your life easier. Although you can name your files and folders with spaces, but that would just require you to wrap your folder/file name with quotation marks like this `mkdir "folder name here"`.

### 🌶🌶 3. Files and text

1. Inside the terminal_challenge folder that you created in the previous task, create 4 `.txt` files by using the command `touch` in a single line. `name.txt` `major.txt` `hobbies.txt` `year_of_birth.txt`
2. Now using the command `nano`, go to every file and type your information. in name.txt file, you will just type your full name, and so on. `nano FILE_NAME`. Always try to type half of the file name, and press tab for auto complete. You might forget the extension if you don't autocomplete.
3. After you complete all the information in all of the files, print their content out to the screen using the command `cat`. Do that for every file.

   ```bash
   cat FILE_NAME
   ```

4. `cat` is short for `concatenate`, which means "link (things) together in a chain or series." And it has a nice feature of concatenating the content of differnet files, and printing them out. Try to concatenate the content of the 4 files you created using the `cat` command as follows

   ```bash
   cat FILE_NAME FILE_NAME FILE_NAME FILE_NAME
   ```

5. You should see all the information now printed in a single command. Try to save the concatenated text in a file using the `>` command after your concatenation as follows:

   ```bash
   cat FILE_NAME FILE_NAME FILE_NAME FILE_NAME > me.txt
   ```

   This command will take the result of the command before the `>` sign, which is printing out the concatenation of the 4 files, and putting them in a new file you called it `me.txt`. Now the result of the concatenation is saved in a file called `me.txt`. Print out the content of the file `me.txt` that you created in the previous command using the `cat` again `cat me.txt`.

6. Now remove all the files `name.txt` `major.txt` `hobbies.txt` `year_of_birth.txt` using the command `rm` in one line. `rm FILE_NAME FILE_NAME FILE_NAME FILE_NAME` and just keep `me.txt`
