# Introduction to Git
This guide has the purpose of learning the basics of Git and practicing different scenarios that will be shown below.

![Picture_01](./git.gif)

## Installation
Available for most operating systems, macOS, Windows, Linux/Unix.

- [Official download](https://git-scm.com/downloads)
    - If you have [Windows](https://phoenixnap.com/kb/how-to-install-git-windows)
    - Otherwise, you have [macOS or Linux](https://github.com/git-guides/install-git)

## Exercises
### Get Started
Check which version of Git (if any) is installed
```bash
 git --version
```

Initialize Git on the current folder
```bash
 git init
```

Set the user name for the current repository to "user-dummy"
```bash
 git config user.name "user-dummy"
```

Set the email for the current repository to "user@dummy.com"
```bash
 git config user.email "user@dummy.com"
```

Review user name and email configured
```bash
 git config --list
```

### Staging environment
Add file.txt to the Staging Environment
```bash
 # Additional command
 # git add .
 git add file.txt
```

### New files 
Check the status of the Git
```bash
 git status
```

Check the compact version of the status for repository
```bash
 git status --short
```

### Commit 
Commit the changes to the current repository with the message "First commit"
```bash
# Additional command
# git commit -am "Add & Commit in one step"
 git commit -m "First commit"
```

View the history of commits for the repository
```bash
 git log
```

Review the history of commits for the repository in one line
```bash
 git log --oneline --graph --decorate
```

### Branch
Create a new branch called "my-new-branch"
```bash
 git branch my-new-branch
```

List the existing branches
```bash
 # The expected branches are "main" / "my-new-branch"
 git branch
```

Move to the "my-new-branch" branch
```bash
 git checkout my-new-branch
```

### Merge
Merge the "my-new-branch" branch with the current branch (main)
```bash
 # Ensure you stay in the main branch 
 git merge my-new-branch
```

Remove the "my-new-branch" branch from the local repository
```bash
 git branch -d my-new-branch
```

### Help
Show the possible options for the status command in command line
```bash
 git status -help
```

Show all git possible commands
```bash
 git help --all
```

[Go to additional Resources](./additional_resources.md)

<!-- It is a secret, send me coffee please. Oswald TC - May 10th 2022 -->