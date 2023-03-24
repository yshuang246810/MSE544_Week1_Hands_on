# MSE544_Week1_Hands_on

## Hands-on 1: Sign up for Hyak and Use some basic Command line

Authors: Ting Cao & [Ziyu Zhang](https://github.com/Ilxxll)

### Table of Content

- [Task 1: Sign up for membership in the STF group.](#task1)
- [Task 2: Locate a terminal or SSH client on your computer.](#task2)
- [Task 3: Familiarize yourself with the command line.](#task3)
- [Task 4: Use Vi to create a file with 2-3 sentences about what the term ‘Big Data’ means to you.](#task4)
- [Task 5: Familiarize yourself with file transfers.](#task5)

## Task 1 Sign up for membership in the STF group.<a name="task1"></a>

#### Step 1:
Go to the Hyak Research Computing Club(RCC) getting-start Webpage: [https://depts.washington.edu/uwrcc/getting-started-2/getting-started/](https://depts.washington.edu/uwrcc/getting-started-2/getting-started/) and follow the instruction to finish the sign-up.

#### Step 2:

Read the `wiki page for Hyak` and get familiar with Hyak setup.The wiki provides detailed information on how to access and use Hyak, including instructions on how to log in, set up software, run jobs, and manage data storage. It also includes troubleshooting tips and answers to common questions. Reading the wiki will help you gain a better understanding of how to effectively use Hyak for their research needs.

[`Wiki page for Hyak`](https://wiki.cac.washington.edu/display/hyakusers/)

[`Wiki page for lotin to Hyak`](https://wiki.cac.washington.edu/display/hyakusers/Logging+In)


## Task 2 Locate a terminal or SSH client on your computer.<a name="task2"></a>

### Step 1: Set up your terminal

#### For Mac user: you can use `Terminal`.

- Click on the Finder icon in the Dock to open a Finder window.
- Press `Command + F` to bring up the Finder search bar.
- Type `Terminal` in the search bar and wait for the search results to appear.
- Once the search results appear, locate the Terminal application and click on it to open it.

#### For windows user: You can use `Windows Terminal`

For windows user, you can read the webpage that help you use it:
[https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

Or you can use Xshell, GitBash or PuTTY.

### Step 2: Start becoming comfortable using these command line interfaces if you are not already.

Like with any new skill, using command line interfaces (CLIs) takes practice and persistence to become proficient. It can be daunting to start using the command line, but with practice and patience, you can become more comfortable and confident with this powerful tool. Here is a webpage that can help you get familiar with Command line. 

[https://www.git-tower.com/blog/command-line-cheat-sheet/](https://www.git-tower.com/blog/command-line-cheat-sheet/)

### Step 3: Test connection with Hyak:

Input `ping klone.hyak.uw.edu` to test 

And then use `control + C` to stop the ping

<img src="./image/ping.png" style="height: 75%; width: 60%;"/>

### Step 4: Connect to Hyak!

Input `ssh uwid@klone.hyak.uw.edu` to connect to Hyak

your UW user id should replace USERID.

<img src="./image/Hyak.png" style="height: 75%; width: 60%;"/>

## The rest instructions can be either worked on hyak or local
## Task 3 Familiarize yourself with the command line.<a name="task3"></a>

#### Shells:
- The terminal lets you enter commands that do things. It gives you a `command line`. For our purposes we can also call it a `shell`.
- Those commands are actually little programs that get run. When you run "ls", that's a program called "ls" in the folder "/bin"
- You can list a bunch of commands in a text file and tell the terminal to run it from top to bottom. This is called a `shell script`. A typical shell script starts with the header line #!/bin/bash

#### Directories
- At any given point, there is one folder on your computer the shell is "sitting inside of". This is the shell's `present working directory (pwd)`. You change the working directory with the `cd` command.

- Relative paths name a directory or file relative to the current working directory. They start with "." (the working directory), ".." (the parent of the working directory), or a file/folder name.

  Can keep using ../../../ to relocate to your parent directory.
  
- Absolute paths start from the root of the drive. They're the same no matter what your working directory is. On windows they start with a drive letter (like "C:\"), and on Linux they start with a "/".
  If you are on hyak: use your directory under gscratch instead of home directory. 
  See difference: https://wiki.cac.washington.edu/display/hyakusers/Managing+your+Files#ManagingyourFiles-HomeDirectories

#### Try to use some common commands:

cd (change directory), ls (list), pwd (print working directory), mkdir (create new directory), rm (remove), vi (open file with the vim editor)

<img src="./image/Common_command_line.png" style="height: 75%; width: 60%;"/>

#### Additional resources:

https://www.youtube.com/watch?v=5RTSlby-l9w&ab_channel=PercyGrunwaldfromTopTechSkills (video for WSL installation and access)
https://www.git-tower.com/blog/command-line-cheat-sheet/ (cheat sheet)
https://ubuntu.com/tutorials/command-line-for-beginners#1-overview (pedagogical overview)


## Task 4 Use `Vi` to create a file with 2-3 sentences about what the term ‘Big Data’ means to you.<a name="task4"></a>

- 1. Open a terminal window / Connect to Hyak.
- 2. Navigate to the directory where you want to create the file. For example, if you want to create the file in your home directory, type `cd ~` and press Enter.
- 3. Type `vi big_data.txt` and press Enter to create a new file called `big_data.txt` using the Vi text editor.
- 4. Press `i` to enter insert mode and start typing your 2-3 sentences about what Big Data means to you.
- 5. Once you've finished writing, press the `Esc` key to exit insert mode.
- 6. Type `:wq` (including the colon) and press Enter to save the file and exit the Vi editor.

#### Additional resources:

https://www.guru99.com/the-vi-editor.html

cheatsheet of vim command: https://vimsheet.com/


## Task 5 Familiarize yourself with file transfers.<a name="task5"></a>

Once you are approved by STF, practice moving some files from your local computer to your scratch
directory.

For Mac user, here is the wiki page for you to know how to transfer the file: https://wiki.cac.washington.edu/display/hyakusers/Hyak+Mac+file+transfer 

For Windows user, here is the wiki page for you to know how to transfer the file:https://wiki.cac.washington.edu/display/hyakusers/Hyak+Windows+file+transfer 

Here is the wiki page to guide you how to manage your file in Hyak: https://wiki.cac.washington.edu/display/hyakusers/Managing+your+Files

Also, you can use some third-party software to transfer files like XShell, Putty, Filezilla, or any other client.

## Assignment

Upload the `big_data.txt` file created in the fourth task to canvas.
