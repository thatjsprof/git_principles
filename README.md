## Git helper methods

Starting a new project
> git init <br>
> git add .<br>
> git commit -m "\<your-commit-message\>"<br>
> git branch -M main<br>
> git remote add origin https://github.com/<your-github-username\>/<repository-name.git><br>


Joining an existing repository: There are 2 ways to do this
1. Forking the repo from your github dashboard
2. Cloning the repo from your github dashboard or running the command below from the folder:
> git clone <repository-path\>


To add a single file use
> git add <file-name\>
To add files recursively use
> git add .


To make a new commit use:
> git commit

The above command would open an editor in your terminal. Type in your commit message and ctrl + save to save your changes then ctrl + w to quit the editor.

To add all changed files and commit automatically use:
> git commit -am <your-commit-message\>

To update changes on github to your local machine use:
> git pull origin <branch-name\>

To push changes on your local machine to github use
> git push origin <branch-name\>

To view your present status use
> git status

To view a list of all your tracked files use
> git ls-files

To back out after creating a commit use
> git reset HEAD <file-name\>

To discard all changes to a file use
> git checkout -- <file-name\>

To change the name of a file use
> git mv <old-file-name\> <new-file-name\>

You can also rename a file using above command but without git. Github would interpret this as you deleted a file and then created a new one. To add the new file then use the command below for git to update changes and interpret action as renamed file

> git add -A

You can also use the command below to update git's index
> git add -u

To move a file into a different directory use
> git mv <file-name\> <folder-name\>

You can also use the command below to move a file
> mv <file-name\> ..

To remove a file use
> git rm <file-name\>