## Git Workflow

Here's a basic workflow for working with Git:

1.  Create a new local branch for each new feature or bug fix.
2.  Make changes to the code and commit them to the local branch.
3.  Push the local branch to the remote repository.
4.  Create a pull request to merge the local branch into the main branch.
5.  Review the changes and merge the pull request if everything looks good.
6.  Delete the local branch and pull the changes from the main branch to your local repository.

Remember to frequently commit your changes and push them to the remote repository to keep your work backed up and make collaboration with others easier.


## Git Basics


### Create a Repository

Create a new local repository:

 
`git init` 

Clone an existing repository:

 
`git clone <repository_url>` 

### Stage Changes

Stage changes for the next commit:

 
`git add <filename>` 

Stage all changes:

 
`git add .` 

Unstage changes:

 
`git reset <filename>` 

### Commit Changes

Commit changes:

 
`git commit -m "Commit message"` 

Amend the previous commit:

 
`git commit --amend -m "New commit message"` 

### Branches

Create a new branch:

 
`git branch <branch_name>` 

Switch to a branch:

 
`git checkout <branch_name>` 

Create a new branch and switch to it:

 
`git checkout -b <branch_name>` 

Merge a branch into the current branch:

 
`git merge <branch_name>` 

Delete a branch:

 
`git branch -d <branch_name>` 

### Remote Repositories

Show remote repositories:

 
`git remote -v` 

Add a remote repository:

 
`git remote add <remote_name> <repository_url>` 

Remove a remote repository:

 
`git remote remove <remote_name>` 

Push changes to a remote repository:

 
`git push <remote_name> <branch_name>` 

Pull changes from a remote repository:

 
`git pull <remote_name> <branch_name>` 


## Git Advanced Commands

### Git Log

Show the commit history:

 
`git log` 

Show the commit history with a one-line summary of each commit:

 
`git log --oneline` 

Show the commit history for a specific file:

 
`git log <filename>` 

Show the changes made in a specific commit:

 
`git show <commit_id>` 

### Git Cherry-pick

Apply a specific commit to the current branch:

 
`git cherry-pick <commit_id>` 

### Git Rebase

Rebase the current branch onto another branch:

 
`git rebase <branch_name>` 

Interactive rebase to edit, reorder or squash commits:

 
`git rebase -i <branch_name>` 

### Git Reset

Reset the current branch to a previous commit:

 
`git reset <commit_id>` 

Reset the current branch to the last commit and unstage changes:

 
`git reset HEAD~` 

### Git Stash

Stash changes in a temporary area:

 
`git stash save` 

Apply stashed changes:

`git stash apply` 

List all stashed changes:

`git stash list` 

### Git Submodule

Add a submodule:

 
`git submodule add <repository_url> <path>` 

Update submodules to the latest commit:

 
`git submodule update --remote` 

### Git Tag

Create a tag for the current commit:

`git tag <tag_name>` 

Create a tag with a message:

 
`git tag -a <tag_name> -m "Tag message"` 

Push a tag to the remote repository:

 
`git push origin <tag_name>` 

### Git Diff

Show the difference between the working directory and the last commit:

 
`git diff` 

Show the difference between two commits:

 
`git diff <commit_id_1> <commit_id_2>` 

Show the difference between the current branch and another branch:

 
`git diff <branch_name>`
