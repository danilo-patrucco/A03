# A03

## Git, Github and Webstorm

### -1 Git installation 

depending on the OS you are using you will have to follow different procedures for the installation of GIT, since I am using Windows 10 i will explain how to install and use GIT in windows.<br/>
Go on the website https://gitforwindows.org/ and download the installer for GIT <br/>
Once the download is completed proceed to install it and click next until the installation is done.<br/>

### -2 Git Setup

Once GIT is installed proceed to set up the global account data, go in the command prompt (cmd.exe or powershell) and type the following <br/>

git config --global user.name "yourusername"<br/>
git config --global user.email "youremail"<br/>

Your GIT is now configured!<br/>

### -3 GitHub 

Go on the github website https://github.com<br/>
Create an account<br/>
On the top right side of the page, next to your profile picture there is a plus, click on it and select the new repository button<br/>
Under repository name put the name of your repository<br/>
Select public (where you are prompted if you want the repo to be public or private)unless you are planning to keep your repo private<br/>
Select Initialize this repository with a README<br/>
Click on Create Repository<br/>
Congratulation, you created your first Repo!<br/>

### Webstorm

In webstorm we will be able to turn on the version control feature.<br/>
Once webstorm is open create a new project<br/>
Once the project is open click on VCS and select Enable version control integration<br/>
From the dropdown menu select Git and press ok, this will enable version control.<br/>
open the terminal and type git init and press enter<br/>
type git add . and press enter<br/>
now you are ready to perform your first commit!<br/>

### First commit 

On the top right section of Webstorm there is a button list next to a tag called Git<br/>
Click on the green tickmark and it will open a window called commit changes<br/>
In the message window write the following : First commit<br/>
Before pushing the commit button make sure that all the files in the top window are selected<br/>
press the button commit<br/>
Your first commit is done, Hurray !<br/>

## Definitions

1 GIT = Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.<br/>
2 GitHub = GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.<br/>
3 Repository = a repository is a central file storage location. It is used by version control systems to store multiple versions of files.<br/>
4 Clone = git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository<br/>
5 Commit = The "commit" command is used to save your changes to the local repository.<br/>
6 Push = The git push command is used to upload local repository content to a remote repository. <br/>
7 Pull = The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.<br/>
8 Branch = Branching is a feature available in most modern version control systems. Instead of copying files from directory to directory, Git stores a branch as a reference to a commit. In this sense, a branch represents the tip of a series of commits—it's not a container for commits.<br/>
9 Merge = Merging is Git's way of putting a forked history back together again. <br/>
10 Merge Conflict = Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge<br/>
11 Fetch = The git fetch command downloads commits, files, and refs from a remote repository into your local repo<br/>
12 Remote = A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server.<br/>


# Resources

for git installation : https://www.atlassian.com/git/tutorials/install-git

For definitions:
1 https://git-scm.com/<br/>
2 https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/<br/>
3 https://techterms.com/definition/repository<br/>
4 https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone<br/>
5 https://www.git-tower.com/learn/git/commands/git-commit<br/>
6 https://www.atlassian.com/git/tutorials/syncing/git-push<br/>
7 https://www.atlassian.com/git/tutorials/syncing/git-pull<br/>
8 https://www.atlassian.com/git/tutorials/using-branches<br/>
9 https://www.atlassian.com/git/tutorials/using-branches<br/>
10 https://help.github.com/en/articles/about-merge-conflicts<br/>
11 https://www.atlassian.com/git/tutorials/using-branches<br/>
12 https://www.atlassian.com/git/tutorials/using-branches<br/>
