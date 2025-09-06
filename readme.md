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
  Shows details of a specific commit.[2]

## Branching

- **git branch**  
  Lists local branches.[3][1][2]

- **git branch <name>**  
  Creates a new branch.[1][2]

- **git branch -d <name>**  
  Deletes a branch.[3][1][2]

- **git checkout <branch>**  
  Switches to the specified branch.[3][1][2]

- **git checkout -b <name>**  
  Creates and checks out a new branch.[3][1][2]

- **git merge <branch>**  
  Merges another branch into current branch.[1][2]

## Remote Repositories

- **git remote add origin <url>**  
  Adds a new remote repository.[4][1]

- **git remote -v**  
  Lists remote repositories.[4][1]

- **git push**  
  Pushes committed changes to remote repository.[2][3][1]

- **git push origin <branch>**  
  Pushes branch to remote.[4][1]

- **git pull**  
  Fetches updates from remote and merges.[3][1][2]

- **git fetch**  
  Fetches updates from remote, but does not merge.[1][2]

## Staging and Undo

- **git stash**  
  Temporarily stashes local changes.[2][1]

- **git stash pop**  
  Applies latest stashed changes.[4]

- **git checkout -- <file>**  
  Discards changes in a file.[3][1]

- **git reset <file>**  
  Unstages a file from the staging area.[2]

## Configuration

- **git config --global user.name "name"**  
  Sets global username for commits.[1][2]

- **git config --global user.email "email"**  
  Sets global email for commits.[1][2]

## Comparison and Inspection

- **git diff**  
  Shows differences between files and branches.[2][1]

- **git diff <source branch> <target branch>**  
  Preview changes before merging.[4][1]

## Tagging

- **git tag <tagname>**  
  Give a tag to a specific commit.

***

### Table: Command and Use

| Command                          | Use                                        |
|-----------------------------------|--------------------------------------------|
| git init                         | Initialize repository [1]              |
| git clone <url>                   | Clone remote repo [1]                  |
| git add <file>                    | Stage file [1]                         |
| git commit -m "msg"               | Commit changes [1][2]              |
| git status                        | View file changes [1]                  |
| git branch <name>                 | Create a branch [1][2]             |
| git checkout <branch>             | Switch branches [1][3]            |
| git merge <branch>                | Merge branch [1][2]                |
| git push                          | Push changes [1][4]               |
| git pull                          | Pull updates [1][3]               |
| git log                           | View history [1][2]                |
| git diff                          | Show changes [1][2]                |
| git stash                         | Stash changes [1][2]               |
| git config --global user.name     | Set username [1][2]                |
| git config --global user.email    | Set email [1][2]                   |

This covers all essential **Git commands** and their uses for everyday version control and collaboration tasks.[3][1][2]

