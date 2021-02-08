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