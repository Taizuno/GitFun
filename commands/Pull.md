# git pull

Similar to [gitpush](./Push.md), a `git pull` will interact with a remote repository. only this time it will **pull** the changes it does not have from the remote down to the local repository.

this means any commits made that are on the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use `git pull` without specifying a remote or branch.

## Resources

- [git pull documentation](https://git-scm.com/docs/git-pull)

---

[back to home](../README.md)