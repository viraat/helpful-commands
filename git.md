# git

- To show all local and remote branches that (local) git knows about

```bash
git branch -a
```

- [To update the local list of remote branches:](https://stackoverflow.com/questions/36358265/when-does-git-refresh-the-list-of-remote-branches)

```bash
git remote update origin --prune
```

- [Delete a branch both locally and remotely](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-both-locally-and-remotely)

```bash
git push --delete <remote_name> <branch_name>
git branch -d <branch_name>
```