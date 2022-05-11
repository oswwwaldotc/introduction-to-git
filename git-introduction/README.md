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
 git --version
```

Initialize Git on the current folder
```console
 git init
```

Set the user name for the current repository to "user-test"
```console
 git config user.name "user-test"
```

Set the email for the current repository to "user@test.com"
```console
 git config user.email "user@test.com"
```

Review user name and email configured
```console
 git config --list
```

### Staging environment
Add file.txt to the Staging Environment
```console
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
 git branch
```

Move to the "my-new-branch" branch
```console
 git checkout my-new-branch
```

### Merge
Merge the "my-new-branch" branch with the current branch
```console
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

## Tips and Tricks
The cheat sheet features the most important and commonly used Git commands for easy reference.

![Picture_02](./cheat_sheet.png)

- [GitHub](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitLab](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
- [Bitbucket](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

Also, great content and self-study:

- [What is Git? A Beginner's Guide to Git Version Control](https://www.freecodecamp.org/news/what-is-git-learn-git-version-control/)
- [Learning git branching](https://learngitbranching.js.org/)
- [Playlist on YouTube](https://youtube.com/playlist?list=PLTd5ehIj0goMCnj6V5NdzSIHBgrIXckGU)

<!-- It is a secret, send me coffee please. Oswald TC - May 10th 2022 -->