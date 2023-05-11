# Exercises you can do using Git Bash

## 1. Check the status of your working directory

Before you use `git stash`, it's a good idea to check the status of your working directory using the `git status` command:

```bash
git status
```

This command will show you the current status of your working directory, including any modified or untracked files.

## 2. Stash your changes

If you have changes that you don't want to commit yet, you can stash them using the `git stash` command:

```bash
git stash
```

This command will save your changes to a temporary area so you can work on them later.

## 3. Check the stash list

To see a list of your stashed changes, use the `git stash list` command:

```bash
git stash list
```

This command will show you the stash list, which includes the stash number, the branch name, and a description of the stash.

## 4. Apply a stash

If you want to apply a stash, you can use the `git stash apply` command followed by the stash number:

```bash
git stash apply stash@{0}
```

This command will apply the stash with the stash number `0`. You can replace `0` with the number of the stash you want to apply.

## 5. Remove a stash

If you want to remove a stash from the stash list, you can use the `git stash drop` command followed by the stash number:

```bash
git stash drop stash@{0}
```

This command will remove the stash with the stash number `0`. You can replace `0` with the number of the stash you want to remove.

## 6. Apply and remove a stash

If you want to apply a stash and remove it from the stash list at the same time, you can use the `git stash pop` command followed by the stash number:

```bash
git stash pop stash@{0}
```

This command will apply the stash with the stash number `0` and remove it from the stash list. You can replace `0` with the number of the stash you want to apply and remove.

## 7. Create a stash with a message

You can create a stash with a message to make it easier to identify later using the `git stash save` command followed by a message:

```bash
git stash save "message"
```

This command will create a stash with the message `message`.

### 8. Apply a stash without removing it

If you want to apply a stash without removing it from the stash list, you can use the `git stash apply` command followed by the stash number:

```bash
git stash apply --index stash@{0}
```

This command will apply the stash with the stash number `0` without removing it from the stash list. You can replace `0` with the number of the stash you want to apply.

## 9. Show the changes in a stash

To see the changes in a stash, use the `git stash show` command followed by the stash number:

```bash
git stash show -p stash@{0}
```

This command will show the changes in the stash with the stash number `0`. You can replace `0` with the number of the stash you want to show.

## 10. Create a branch from a stash

If you want to create a new branch from a stash, you can use the `git stash branch` command followed by a branch name and the stash number:

```bash
git stash branch new-branch-name stash@{0}
```

This command will create a new branch named `new-branch-name` from the stash with the stash number `0`. You can replace `0` with the number of the stash you want to use.

## 11. Drop a stash

If you want to remove a stash from the stash list, you can use the `git stash drop` command followed by the stash number:

```bash
git stash drop stash@{0}
```

This command will remove the stash with the stash number `0` from the stash list. You can replace `0` with the number of the stash you want to drop.

## 12. List all stashes

To list all the stashes in the stash list, you can use the `git stash list` command:

```bash
git stash list
```

This command will display a list of all the stashes in the stash list, along with their stash numbers and messages.

## 13. Clear all stashes

To remove all the stashes from the stash list, you can use the `git stash clear` command:

```bash
git stash clear
```

This command will remove all the stashes from the stash list.

## 14. Apply a stash and delete it

If you want to apply a stash and remove it from the stash list, you can use the `git stash pop` command followed by the stash number:

```bash
git stash pop stash@{0}
```

This command will apply the stash with the stash number `0` and remove it from the stash list. You can replace `0` with the number of the stash you want to apply.

## 15. Apply a stash to a specific branch

If you want to apply a stash to a specific branch, you can use the `git stash apply` command followed by the stash number and the branch name:

```bash
git stash apply stash@{0} --index && git checkout branch-name
```

This command will apply the stash with the stash number `0` to the branch named `branch-name` and switch to that branch. You can replace `0` with the number of the stash you want to apply.

These are just a few more examples of the commands you can use with `git stash` in Git Bash. With these commands, you can manage your stashes effectively and keep your Git repository organized.

- [Return to Home](../README.md)

<!-- It is a secret line. Oswald TC - May 11nd 2023 -->
