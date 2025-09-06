#Learning Github

Learning github and git

```javascript
console.log("Hello world!");
```

Here is a concise list of all major **Git commands** and their typical usage, covering what developers use most frequently in day-to-day work.

## Repository Setup

- **git init**  
  Initializes a new Git repository in the current folder.

- **git clone <url>**  
  Clones a remote repository to local system.

## File Management

- **git status**  
  Shows current status of files (modified, staged, untracked).
- **git add <file>**  
  Stages changes done to a file.

- **git add . / git add -A**  
  Stages all changes (new, modified, deleted files) in folder.
- **git rm <file>**  
  Removes a file from the working directory and staging area.

## Commit and History

- **git commit -m "message"**  
  Commits staged changes with a message.

- **git log**  
  Displays commit history.

- **git log --oneline**  
  Shows brief commit history.

- **git show <commit>**  
  Shows details of a specific commit.

## Branching

- **git branch**  
  Lists local branches.

- **git branch <name>**  
  Creates a new branch.

- **git branch -d <name>**  
  Deletes a branch.

- **git checkout <branch>**  
  Switches to the specified branch.

- **git checkout -b <name>**  
  Creates and checks out a new branch.

- **git merge <branch>**  
  Merges another branch into current branch.

## Remote Repositories

- **git remote add origin <url>**  
  Adds a new remote repository.

- **git remote -v**  
  Lists remote repositories.

- **git push**  
  Pushes committed changes to remote repository.

- **git push origin <branch>**  
  Pushes branch to remote.

- **git pull**  
  Fetches updates from remote and merges.

- **git fetch**  
  Fetches updates from remote, but does not merge.

## Staging and Undo

- **git stash**  
  Temporarily stashes local changes.

- **git stash pop**  
  Applies latest stashed changes.

- **git checkout -- <file>**  
  Discards changes in a file.

- **git reset <file>**  
  Unstages a file from the staging area.

## Configuration

- **git config --global user.name "name"**  
  Sets global username for commits.

- **git config --global user.email "email"**  
  Sets global email for commits.

## Comparison and Inspection

- **git diff**  
  Shows differences between files and branches.

- **git diff <source branch> <target branch>**  
  Preview changes before merging.

## Tagging

- **git tag <tagname>**  
  Give a tag to a specific commit.

***

### Table: Command and Use

| Command                          | Use                                        |
|-----------------------------------|--------------------------------------------|
| git init                         | Initialize repository                 |
| git clone <url>                   | Clone remote repo                     |
| git add <file>                    | Stage file                            |
| git commit -m "msg"               | Commit changes                    |
| git status                        | View file changes                     |
| git branch <name>                 | Create a branch                   |
| git checkout <branch>             | Switch branches                  |
| git merge <branch>                | Merge branch                      |
| git push                          | Push changes                     |
| git pull                          | Pull updates                     |
| git log                           | View history                      |
| git diff                          | Show changes                      |
| git stash                         | Stash changes                     |
| git config --global user.name     | Set username                      |
| git config --global user.email    | Set email                         |

This covers all essential **Git commands** and their uses for everyday version control and collaboration tasks.

