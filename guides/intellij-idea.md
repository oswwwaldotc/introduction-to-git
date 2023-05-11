# How to enable Git as a version control system with IntelliJ IDEA

Sure, here is a guide on how to enable Git as a version control system with IntelliJ IDEA IDE:

## 1. Install Git

First, you need to install Git on your system. You can download the latest version of Git from the official website [https://git-scm.com/downloads].

## 2. Configure Git

After installing Git, you need to configure it with your name and email address. Open the Git Bash terminal and enter the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Make sure to replace `Your Name` and `your-email@example.com` with your actual name and email address.

## 3. Install IntelliJ IDEA IDE

If you haven't already, download and install the latest version of IntelliJ IDEA from the official website [https://www.jetbrains.com/idea/download/].

## 4. Create a new project

Open IntelliJ IDEA and create a new project by selecting "New Project" from the welcome screen or by clicking on "File" > "New" > "Project...". Select your desired project type and configure the project settings.

## 5. Enable Git in IntelliJ IDEA

Once you have created the project, you need to enable Git in IntelliJ IDEA. Open the "Settings" window by clicking on "File" > "Settings" or by pressing "Ctrl + Alt + S" on Windows or "Cmd + , " on Mac. In the "Settings" window, go to "Version Control" > "Git". Make sure that the "Path to Git executable" field is set to the path where Git is installed on your system. You can click on the "Test" button to verify that IntelliJ IDEA can locate Git.

## 6. Initialize Git repository

Now, you can initialize a Git repository in your project by clicking on "VCS" > "Import into Version Control" > "Create Git Repository" or by right-clicking on the project root folder and selecting "Git" > "Initialize Repository". IntelliJ IDEA will create a `.git` folder in your project root directory, which contains all the Git-related files and folders.

## 7. Create a new Git branch

To create a new Git branch, you can click on "Git" > "Branches" > "New Branch" or by pressing "Ctrl + Alt + Shift + N" on Windows or "Cmd + Alt + Shift + N" on Mac. Enter a name for the new branch and click "OK". You can now switch to the new branch by clicking on "Git" > "Branches" > "your-branch-name" or by clicking on the branch name in the bottom right corner of the IntelliJ IDEA window.

## 8. Commit changes

After making changes to your project, you can commit the changes to your Git repository by clicking on "VCS" > "Commit Changes" or by pressing "Ctrl + K" on Windows or "Cmd + K" on Mac. Enter a commit message and click "Commit". Your changes will now be stored in the Git repository.

## 9. Push changes

If you want to push your changes to a remote Git repository, you can click on "VCS" > "Git" > "Push" or by pressing "Ctrl + Shift + K" on Windows or "Cmd + Shift + K" on Mac. Enter your Git credentials and click "OK". Your changes will now be uploaded to the remote Git repository.

These are the basic steps to enable Git as a version control system with IntelliJ IDEA IDE. With Git, you can easily manage your project versions, collaborate with other developers, and keep track of changes.

- [Official docs](https://www.jetbrains.com/help/idea/using-git-integration.html)
- [Return to Home](../README.md)

<!-- It is a secret line. Oswald TC - May 11nd 2023 -->
