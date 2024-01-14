# Genesis
Coming into Being
## Version Control
-  Version control is a system that tracks and manages changes to files over time. It allows multiple contributors to work on a project simultaneously, keeping a history of modifications. A central repository stores the project files, and users can make edits independently in their local copies. Version control tools, such as Git, record changes in snapshots called commits. 

Difference Between Git and Github

 Features | Git | Github |
----------|-----|--------|
Purpose | Version control system for tracking changes in source code | Web-based platform for hosting Git repositories and collaboration
Usage | Used locally on a developer's machine | Accessed through a web browser, facilitates online collaboration
Functionality |	Tracks changes, manages branches, facilitates collaboration | Provides hosting, web interface, pull requests, issue tracking, and project management tools
Command Line/GUI | Primarily command-line, with optional GUI tools | Primarily accessed through a web interface, also offers a desktop application.


Some Github alternatives are **Gitea**, **GitLab**, **BitBucket**, **SourceForge**


Some Git command like `git fetch` and `git pull` are similar as these are used to update local repositories with changes from remote ones. However they have distinct behaviour:

`Git fetch`, retrieves the latest changes from the remote repository, but it doesn't automatically merge or apply these changes to your local working branch.

`Git Pull`, on the other hand, is a combination of git fetch and git merge. It fetches the changes from the remote repository and automatically merges them into your current working branch.

#### Git Rebase
It is a Git command that helps you tidy up your commit history by integrating the changes from one branch into another. It does this by moving or combining your commits to a new base commit.

command = `git rebase <branch_name>`

#### Git Cherry-pick
It is a Git command that lets you copy specific commits from one branch and apply them onto another branch. It's like picking out specific changes from one branch and adding them to another.

command = `git cherry-pick <commit_hash>`
