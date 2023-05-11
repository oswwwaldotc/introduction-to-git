# Exercises you can do using Git Bash

## 1. Fork the Repository

First, you need to fork the repository that you want to contribute to. This will create a copy of the repository under your GitHub account, where you can make changes without affecting the original repository.

To fork a repository, go to the repository's page on GitHub, and click on the "Fork" button on the top right corner of the page.

## 2. Clone the Forked Repository

Next, you need to clone the forked repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/forked-repo.git
```

Replace "your-username" with your GitHub username, and "forked-repo" with the name of the repository that you forked.

## 3. Create a New Branch

Before making any changes, create a new branch in the forked repository to work on the changes. You can create a new branch using the following command:

```bash
git checkout -b new-branch-name
```

Replace "new-branch-name" with a descriptive name for the branch.

## 4. Make Changes

Now, you can make the desired changes to the files in the local repository. You can use any text editor or IDE to modify the files.

## 5. Commit Changes

After making the changes, you need to commit them to the local repository using the following commands:

```bash
git add .
git commit -m "Descriptive message about the changes made"
```

## 6. Push Changes to GitHub

Next, you need to push the changes to your forked repository on GitHub using the following command:

```bash
git push origin new-branch-name
```

## 7. Create a Pull Request

Once you have pushed the changes to your forked repository, you can create a pull request to merge the changes into the original repository. 

To do this, go to the repository's page on GitHub and click on the "New pull request" button. Select the branch that contains the changes you want to merge, and write a descriptive message about the changes you made. Then, click on the "Create pull request" button to submit the pull request.

After submitting the pull request, the original repository's owner can review your changes and either approve or reject the pull request. If they approve the changes, they can merge them into the original repository using the GitHub interface.

## 8. Sync Forked Repository with Original Repository

If the original repository has been updated since you forked it, you can sync your forked repository with the changes using the following steps:

1. Add the original repository as a remote to your local repository using the following command:

   ```bash
   git remote add upstream https://github.com/original-owner/original-repo.git
   ```

   Replace "original-owner" with the GitHub username of the original repository's owner, and "original-repo" with the name of the original repository.

2. Fetch the changes from the original repository using the following command:

   ```bash
   git fetch upstream
   ```

3. Merge the changes into your local branch using the following command:

   ```bash
   git merge upstream/main
   ```

   Replace "main" with the name of the branch in the original repository that you want to merge.

4. Push the changes to your forked repository on GitHub using the following command:

   ```bash
   git push origin new-branch-name
   ```

   Replace "new-branch-name" with the name of the branch that you created earlier.

By syncing your forked repository with the original repository, you can keep your changes up to date with any changes made by the original repository's owner.

- [Return to Home](../README.md)

<!-- It is a secret line. Oswald TC - May 11nd 2023 -->
