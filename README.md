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
```console
 # Extra 
 # If you use Windows (OS) 
 # git update-git-for-windows
 git --version
```

Initialize Git on the current folder
```console
 git init
```

Set the user name for the current repository to "user-dummy"
```console
 git config user.name "user-dummy"
```

Set the email for the current repository to "user@dummy.com"
```console
 git config user.email "user@dummy.com"
```

Review user name and email configured
```console
 git config --list
```

### Staging environment
Add file.txt to the Staging Environment
```console
 # Additional command
 # git add .
 git add file.txt
```

### New files 
Check the status of the Git
```console
 git status
```

Check the compact version of the status for repository
```console
 git status --short
```

### Commit 
Commit the changes to the current repository with the message "First commit"
```console
# Additional command
# git commit -am "Add & Commit in one step"
 git commit -m "First commit"
```

View the history of commits for the repository
```console
 git log
```

Review the history of commits for the repository in one line
```console
 git log --oneline --graph --decorate
```

### Branch
Create a new branch called "my-new-branch"
```console
 git branch my-new-branch
```

List the existing branches
```console
 # The expected branches are "main" / "my-new-branch"
 git branch
```

Move to the "my-new-branch" branch
```console
 git checkout my-new-branch
```

### Merge
Merge the "my-new-branch" branch with the current branch (main)
```console
 # Ensure you stay in the main branch 
 git merge my-new-branch
```

Remove the "my-new-branch" branch from the local repository
```console
 git branch -d my-new-branch
```

### Help
Show the possible options for the status command in command line
```console
 git status -help
```

Show all git possible commands
```console
 git help --all
```

[Go to additional Resources](./additional_resources.md)

[My friends, click here](./Pool%20Folder%20(Pull%20Requests)/README.md)

<!-- It is a secret, send me coffee please. Oswald TC - Feb 26th 2023 -->