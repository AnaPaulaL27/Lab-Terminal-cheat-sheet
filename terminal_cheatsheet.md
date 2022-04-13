# Ana Paula's Terminal Commands-     📝Cheat Sheet 📝


## <i>This is list of commands that you will find useful during the course!</i>

__________________________


______
### 🔹<u> Command 1 </u>: <b>ls</b>


*  <u> ls </u> <p>A list of files and folders will appear </p>

* <u> ls -l </u><p>A list of files and folders along with permissions, owner and date last modified </p>

* <u> ls -al</u> <p> A list of files and folders including hidden files </p>




__________________________
### 🔸<u> Command 2 </u>: <b> mv </b>

To move a file we use the <b>mv</b> command.

This one needs 2 pieces of information: 

1. The thing we're moving 
2. The place we're moving it to. 

<u>E.g 1</u>

If we wanted to move our image file back up a level and into our Documents folder we'd do it like this:

>mv my_picture.png ..

 ".." = The directory above the one that we are in

<u> E.g 2:</u>

mv intro_to_terminal.md ./day_01

<u> E.g 3:</u>

mv intro_to_terminal.md ../week_01

Note that we can also use "mv" to <b> rename files</b>

<u> E.g 1</u>

> mv my_file.md intro_to_terminal.md

<u> E.g 2</u>

mv week_01 week_1

__________________________

### 🔹<u> Command 3 </u>: <b> cd </b>


* <u> cd </u> 

 If we ever get lost we can get back to our home directory by typing either cd ~ or just cd on its own.

 cd command can be used to enter through a series of different folders within one command. 

<u> E.g </u>

 if we had a Coding folder within our Documents folder above, then we could use: 

>cd Documents/Coding

* <u> cd  .</u>  

This means to change to this directory- not useful

* <u> cd  ..</u>

<p> This means to change directory above the one that we are in 
</p>

__________________________

### 🔸<u> Command 4 </u>: <b> pwd </b>

<p> If you get lost, use pwd to help you figure out where you are! It shows you what you can see as if you were navigating through the finder</p>

__________________________
### 🔹<u> Command 5 </u>: <b> mkdir </b>

The <b>mkdir</b> command creates directories

<u> E.g: </u>

>mkdir my_directory

<u>Note</u> -

* File names are case-sensitive

* Spaces are allowed, but difficult to work with. It's better to use an underscore to write the directories

* Almost any character is allowed in a file or directory name. 

<i><b> Except</b> </i> forward slash / which is used as the separator in file paths and the dot . which indicates a file extension. The backslash \ is best avoided as well

* A directory needs to have a unique name within its parent directory

* When we create a file using the command line we need to include the file extension.

__________________________
### 🔸<u> Command 6 </u>: <b> Touch </b>

<p> Once we have created our directory we can move into it and create some files. We'll use the touch command to create a new file. But first navigate into that directory </p>

<u>E.g:</u>

>cd my_directory

>touch my_file.txt

Note that we need a file extension, telling us what type of file it is. It can be a file of any type such as ".pdf" or ".png"

<u> Related commands:</u> You can use "open" command in the command line to open files

<u>E.g:</u>

>open my_file.txt

Also you can open this text file using VSCode editor using the "code" command

<u>E.g:</u>

> code my_file.txt.
__________________________
### 🔹<u> Command 7 </u>: <b> rm </b>

<p>

* <u>rm </u>
<p> The command we use to delete a file is "rm".</p>

<u>E.g</u>

>rm profile_picture.png

* <u> rm -r </u>

<p>Deleting a directory is similar to above, but again we need the -r flag</p>

<u>E.g</u>

>rm -r my_directory

* <u> rm -rf </u>

Deletes forcefully- permanent removal  without any prompts 

</p>

__________________________
### 🔸<u> Command 8 </u>:  <b> ~ </b>

The tilde  ~  takes you back to your home directory 
__________________________
### 🔹<u> Command 9 </u>:  <b> .</b>


 "." = This directory

__________________________
### 🔸<u> Command 10 </u>: <b> . </b>

 ".." = The directory above the one that we are in
__________________________
### 🔹<u> Command 11 </u>:  <b> cp </b>

* <u>cp</u>

Copying a file is very similar to moving a file only using the "cp" command.

<u> You need 2 things: </u>

1.  Provide the path to the thing we want to copy
2.  Provide location we want to copy it to

<u> E.g </u>

If we want to make a copy of a picture file to the my_directory location:


1. profile_picture.png
2. my_directory

<u> Result:</u>

> cp profile_picture.png my_directory

If we provide a filename in the second path we can rename the copy as we move it.
<p>

* <u>cp -r</u>

<p> If we want to copy an entire directory we need to add the -r flag (for recursive) to the cp command.</p>


__________________________
### 🔸<u> Command 12 </u>: <b> Pressing command + K </b>

This will clear your whole screen

__________________________
### 🔹<u> Command 13 </u>: <b> Typing clear
 
 This will clean your screen but your information will still be available for viewing if you scroll up 

__________________________
### 🔸<u> Command 13 </u>: <b>Pressing the tab button </b>

Tab key allows us to auto-complete many different commands. 

E.g:

pressing tab when we had written cd Doc will complete the line to 

> cd Documents.


_____
<u> WARNING!</u>

 If we delete something from the command line it's gone, there's no restoring it without taking your laptop to a data recovery specialist.

___

## 🌐 <u><b> GIT HUB COMMANDS/NOTES </b></u>🌐

___
📝 <u><b>STEP 1</b></u>: git init
___

•Git can be initialised on any directory

•The git init command creates a new Git repository

___
✅ <u><b>STEP 2</b></u>: git add
____
• The git add command adds a change in the working directory to the staging area. 

•It tells Git that you want to include updates to a particular file in the next commit.
___
📸 <u><b>STEP 3</b></u>: git commit
___
• The git commit command captures a snapshot of the project's currently staged changes. 

• Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to.

___
🌍 <u><b>STEP 4</b> </u>: git push 
____
 • Use the “git push” command to push the commits on the local repository to a remote repository. 
 
 • The “push” command updates new local commits on a remote server. 
 
 •The push takes two arguments: the remote name (origin) and the branch name (master).

___

<u> Commands: </u>


> git status

Check if tracking
___
>git log

check log
_____
<u> Extra info:</u>

 * yellow cross - ✗
 
  means something in there hasnt been commited


 * To quit log: [command ] + q





 
