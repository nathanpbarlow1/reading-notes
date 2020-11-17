###Git Intro

##Prerequisites 

You need to have an understanding of Terminal (for Mac users) or Command Line (for Windows and Linux Users)

##Version Control

Version Control allows you to view previous versions of a file. You can also revert back to any of the previously saved versionm while also providing you the ability to track and compare changes. This allows for mistakes to be fixed with ease.

- **Local Version Control**: Version control that is saved in a database on your local machines hard disk. 
- **Centralized Version Control**Version control that allows collaboration with others on a single server that can be accessed by multiple clients. This provides visibility into other team members work and provided administrators control over the distribution of revision priviledges. 
- **Distributed Version Control** Instead of relying on a single server, a DVCS allows clients to create mirrored repositories which provides a backup in case of failure. This type of version control also allows collaboration across a team. 

##So, what is Git?
- Git is a type of DVCS that stores data in a file sytem made up of snapshots (moments in time, called a 'commit')
- Other notes: Git mostly works at the local level, allows you to track changes, makes it difficult to lose data, and provides 3 different 'states' of your work: committed, modified and staged. 

##History of Git
- Git can be traced back to an open source software project call ed Linux Kernel
- The intention was to create a DVCS with a workflow design similar to BitKeeper (previously used DVCS)and to allow non-linear development via multiple branches.
- Other goals included supporting large projects, possessed strong mechanisms preventing corruption, and had a simple design. 

##Getting Started
- **Download Git** [Depending on Your OS] (https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)
- **Graphical Clients** Git provides some GUI (Graphical User Interface) tools, however there's also 3rd party GUI Clients available for all OS types. [Check the followng link for more info](https://git-scm.com/downloads/guis)
- **Initial Customization** When you first setup GIT, take a look at these available settings to customize the tool: configuration of variables (via git config) and setting your identity, which will be used as a unique 'signature' whenever something is committed. 
- **Default Text Editor** FYI, if you don't set a default text editor, Git will use the system's default editor. 
- **Check Settings** Use the git `config --list command.`


- **Getting Help**

If you need help, the 3 following commands will allow you to access the manual:
`git help command`
`git command --help`
`man git-command`

##Setting Up a Git Repository
- **Importing**
Command Line can be used to be import projects, take a look at the commands below: 

Switch to the target project’s directory
Example:

`$ cd test (cd = change directory)`
Use the git init command
`$ git init`
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

To start tracking these repository files, perform an initial commit by typing the following:
`$ git add *.c`
`$ git add LICENSE`
`$ git commit -m “any message here”`

- **Cloning**

Copying Git repositories are also available, use the following command: 
`$ git clone https://github.com/test`

##Workflow
- **Local Repository Structure**

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

- **Saving Changes**

Tracked vs. Untracked State:

Tracked: can be modified, unmodified, or staged; they were part of the most recent file snapshot.

Untracked: these files are not in the last snapshot and do not currently reside in the staging area.

- **The lifecycle of File Status**

1. After you edit a file, Git flags it as modified because of changes made after the previous commit.
2. You stage the modified file.
3. Then, you commit staged changes.

![File Status Life Cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

###Other Commands
- **CheckFile Status**
`git add filename`
`$ git add*`

- **Committing All Changes**
`$ git commit -a`

- **Pushing Changes**
`$ git push origin master`

- **Stashing Changes**

When you are not ready to commit changes but do not want to lose them either, `git stash is a great option.` This command temporarily removes changes and hides them, giving you a clean working directory. When you are ready to continue working on the changes, simply use the `git stash apply` command to retrieve the hidden changes.

##Remote Repositories

Versions of a project that's online or on a network. Allows multiple repositories with read/write or read-only privileges. 

- **Cloned Repositories**

As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

[site sourced for this outline](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)
