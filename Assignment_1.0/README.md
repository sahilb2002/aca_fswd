# ASSIGNMENT-1

**GIT AND [GITHUB](https://github.com/)**

### Section-1

#### Basic Terminal commands

**cd**: change directory. syntax- *cd dir_name/path*

**mkdir**: make a new empty directory. Syntax- *mkdir dir_name*.
        Note- the directory is made in present working directory.

**pwd**: print working directory. It shows the current working directory. Syntax- *pwd*

**ls**: lists the contents of the directory given as argument(default is working directory). Syntax- *ls dir_name*

**rm**: delete files and/or directories. Syntax- *rm file_name* 
        Note- to delete directories and all of their contents -rf option is used. *rm -rf dir_name*

**mv**: to move(cut+paste) files/directories from one place to another. Syntax- *mv file/dir_name destination_dir_path*
        Note- if moving directories use the -rf option.You can use this command to rename files as well *mv file_name new_file_name*

**cp**: to copy files/directories. Syntax- similar to **mv**.

#### Git commands

**git add**: add edited file to the staging area. Syntax-*git add file(s)_name*.
             Use *git add .* to add all edited files to staging area

**git commit**: commit all the files on staging area. Syntax- *git commit -m "commit message"*

**git clone**: copies a remote repository to local machine. syntax *git clone url_of_remote_repository*

**git pull**: pulls the changes from cloned remote repository to local machine.

**git push**: send the changes in local repository to cloned remote repository.

**git status**: tells you which files are in staging area and which can be added there.

**git log**: prints all the past commits along with date,time,commit id, and commit message.


### Section-2

**client side**: The operations done by a client in client-server connection.

**server side**: The operations done by the server in the connection.

**http**: Stands for hyper text transfer protocol- a set of rules for the connection between a web browser and a web server. The web browser sends a *http* 
request to server and wait for a *http* response from it.

**http vs https**: *https* stand for hyper text transfer protocol secure and is basically more secure than than http. It send the data from browser to server in an encripted format (which http doesnot).

**framework vs libraries**: basiclly framework and libraries are pice of code written by someone else. The difference lies in the fact that while using library the power to control our code is in our hand, which is not true in case of framework.