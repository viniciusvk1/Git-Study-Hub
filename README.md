<h1><b>Git Study</b></h1>

<h3>Git is a widely used distributed version control system in the software development community. It allows developers to work together on projects, managing changes to the code efficiently and recording the history of these changes. In this tutorial, we will learn how to use Git to manage a project in the Git Study Hub Repository.</h3><br>


<h2><b>Git Installation and Configuration</b></h2>
Before we get started, you need to install Git on your machine. You can find installation instructions on the official Git website: https://git-scm.com/downloads. Once installed, open the terminal and configure your user information using the following commands:
<br>

~~~bash
git config --global user.name "Your name here"
git config --global user.email "your-email@example.com"
~~~
<br>

<h2><b>Creating a Git Repository</b></h2>

To create a new Git repository, simply create a folder on your local machine and use the git init command in the terminal inside the folder to initiate version control. For example:

~~~bash
mkdir my-project
cd my-project
git init
~~~
<br>

<h2><b>Adding Files to the Repository</b></h2>
Now that the repository has been created, you can add files to it. To add all files in a folder to the repository, use the git add . command in the terminal. To add only a specific file, use git add file-name. After adding the files, you need to commit them so that the changes are recorded:
<br><br>


~~~bash
git commit -m "First commit"
~~~

<h2><b>Branches</b></h2>
Branches are branches of your project that allow you to work on changes without affecting the main version of the code. To create a new branch, use the git branch branch-name command. To switch to the new branch, use the git checkout branch-name command. To merge changes from the current branch with another branch, use the git merge branch-name command.
<br><br>


<h2><b>Remote Repository</b></h2>
GitHub is a Git repository hosting service that allows you to work together on projects. To send your local repository to GitHub, create an empty repository on the site and use the git remote add origin repository-url command. Then, send the files using git push origin branch-name. To download changes from the remote repository to the local one, use the git pull origin branch-name command.
<br><br>


<h2><b>Learn more</b></h2>
To learn more, consult the official Git documentation at https://git-scm.com/docs.
