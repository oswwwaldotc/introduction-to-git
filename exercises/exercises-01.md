# Exercises you can do using Git Bash

## Exercise 1: Create a Git Repository

1. Open Git Bash and navigate to the directory where you want to create your Git repository using the `cd` command. For example, if you want to create a repository in the "Documents" folder, you can use the following command:

```bash
cd Documents
```

2. Once you're in the directory where you want to create your repository, use the following command to create a new Git repository:

```bash
git init
```

This will initialize a new Git repository in the current directory.

### Key Commands:

* `cd`: Changes the current directory to the specified directory.
* `git init`: Initializes a new Git repository in the current directory.

## Exercise 2: Add and Commit Changes

1. Create a new file in your repository using your favorite text editor. For example, you can use the following command to create a new file called "README.md":

```bash
touch README.md
```

2. Add the file to the Git staging area using the following command:

```bash
git add README.md
```

This tells Git to track changes to the "README.md" file.

3. Commit the changes to the repository using the following command:

```bash
git commit -m "Initial commit"
```

This creates a new commit with the changes you just made to the "README.md" file.

### Key Commands:

* `touch`: Creates a new file with the specified name.
* `git add`: Adds the specified file(s) to the Git staging area.
* `git commit`: Commits the changes in the staging area to the Git repository.

## Exercise 3: View Repository Status

1. Use the following command to view the current status of your repository:

```bash
git status
```

This will display the current state of your repository, including any changes that have been made since the last commit.

2. Use the following command to view the commit history of your repository:

```bash
git log
```

This will display a list of all the commits that have been made to the repository, including the commit message and the author.

### Key Commands:

* `git status`: Displays the current status of the Git repository.
* `git log`: Displays the commit history of the Git repository.

## Exercise 4: Create and Switch Branches

1. Use the following command to create a new branch:

```bash
git branch new-branch
```

This will create a new branch called "new-branch".

2. Use the following command to switch to the new branch:

```bash
git checkout new-branch
```

This will switch to the "new-branch" branch.

### Key Commands:

* `git branch`: Creates a new branch in the Git repository.
* `git checkout`: Switches to the specified branch in the Git repository.

## Exercise 5: Merge Branches

1. Switch back to the master branch using the following command:

```bash
git checkout master
```

This will switch back to the master branch.

2. Use the following command to merge the "new-branch" branch into the master branch:

```bash
git merge new-branch
```

This will merge the changes from the "new-branch" branch into the master branch.

### Key Commands:

* `git merge`: Merges the specified branch into the current branch.

## Exercise 6: Clone a Repository

1. Find a Git repository you want to clone. For example, you can use the following command to clone the Git repository for the Git website:

```bash
git clone https://github.com/dev-oswld/introduction-to-git
```

This will clone the Git repository for the Git website to your local machine.

2. Once the repository has been cloned, navigate to the directory using the `cd` command. For example, if the repository was cloned to your "Documents" folder, you can use the following command to navigate to the repository:

```bash
cd Documents/introduction-to-git
```

### Key Commands:

* `git clone`: Clones the specified Git repository to your local machine.
* `cd`: Changes the current directory to the specified directory.

## Exercise 7: Push Changes to a Remote Repository

1. Make some changes to a file in your local repository.

2. Use the following command to add the changes to the staging area:

```bash
git add .
```

This will add all the changes you made to the staging area.

3. Use the following command to commit the changes:

```bash
git commit -m "Made some changes"
```

This will create a new commit with the changes you made.

4. Use the following command to push the changes to the remote repository:

```bash
git push
```

This will push the changes to the remote repository.

### Key Commands:

* `git add`: Adds the specified file(s) to the Git staging area.
* `git commit`: Commits the changes in the staging area to the Git repository.
* `git push`: Pushes the changes in the local repository to the remote repository.

## Exercise 8: Pull Changes from a Remote Repository

1. Use the following command to pull changes from the remote repository:

```bash
git pull
```

This will pull any changes from the remote repository to your local repository.

### Key Commands:

* `git pull`: Pulls changes from the remote repository to the local repository.

- [Return to Home](../README.md)

<!-- It is a secret line. Oswald TC - May 11nd 2023 -->
