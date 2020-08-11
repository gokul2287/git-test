## git test repository 

This repository tells us about how to setup basic development environment using Git and Node 

- Set up a Git repository and perform basic Git operations
- Set up and use online Git repositories
- Use Node-based modules to perform basic operations.

**Setting up Git** 

Downloading and Installing Git
To install Git, go to https://git-scm.com/downloads to download the Git installer for specific computing platform. Then, follow the installation steps to install Git using the installer.

**Global Configuration for Git**

Open a cmd window or terminal on computer.
make sure that Git is installed and available on the command line, by typing the following at the command prompt:
*git --version*

To configure user name to be used by Git, type the following at the prompt:
*git config --global user.name "Your Name"*

To configure email to be used by Git, type the following at the prompt:
*git config --global user.email <your email address>*

check default Git global configuration, using below command:
*git config --list*

**Basic Git Commands**

To initialize the folder as a Git repository:  *git init *

check Git repository's status: *git status*

Adding files to the staging area, To add files to the staging area in Git repository : *git add .*

Commiting to the Git repository: *git commit -m "message"*

Checking the log of Git commits: *git log / git log --oneline *

Checking out a file from an earlier commit: *git checkout <commit's number> <file name>*

Resetting the Git repository: 
*git reset HEAD <file name>* 
*git checkout -- <file name>* 


**Setting up an Online Git repository** 
Sign up or Sign in to GitHub (https://github.com)

Set the local Git repository to set its remote origin: *git remote add origin <repository URL>*

Pushing your commits to the online repository: *git push -u origin master*

Cloning an online repository: *git clone <repository URL>*


**Setting up Node.js and NPM **

Installing Node : go to https://nodejs.org and download. 
verify the node installations using command *node -v and npm -v *

**Basics of Node.js and NPM**

Initializing package.json in project folder: *npm init* 
Follow the prompts and answer the simple questions. Accept the default values for most of the entries. 
set the entry point to *index.html* 
This should create a package.json file in project folder.

Installing an NPM Module: *npm install <package name> --save-dev*


**Setting up .gitignore** 

Create a file in project directory named .gitignore (Note: the name starts with a period) Then, add the following to the .gitignore file

*node_modules* 

this excludes the above folder to get in online repository (github). 
