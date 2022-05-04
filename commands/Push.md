# git push

When you have a [remote](./Remote.md) set up you'll need to begin to move [commits](./Commit.md) to the remote. This can be done with the command `git push`.

you can attach a name and branch name to you command to specify where you're pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. this means an commits that are in your local wil be **pushed** to the remote.

### Upstream Tracking

Instead of including the name of the remote an the branch you're on every time, you can set local branches to track an upstream branch. This means you can tell the branch to push its assigned upstream remote branch by using the command `git push`.

Before doing so, you'll need ot use the `-u` or `--set-upstrem` flag. This can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will function the same way.

## Resources

`[Git push Documentation](https://git-scm.com/docs/git-push)

---

[Back to home](../README.md)