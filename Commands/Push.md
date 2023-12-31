# Git Push

When you have a [remote](./Remote.md) set up you'll need to beging to move [commits](./Commit.md) to the remote. This can be done with command `git push`.

You can attach a name and branch name to you command to specify where you're pushing to. 

```
git push orgin main
```

This command will push the **main** branch to the remote called **orgin**. This means any commits that are in your local will be **pushed** to the remote. 

### Upstream Tracking

Instead of including the name of the remote and the branch you're on every time, you can set local branches to track and upstream branch. This means you can tell the branch to push to its assigned upstream remote branch by using the command `git push`.

Before doing so, you'll need to use the `-u-` or `--set-upstream` flag. This can be done on any `git push`.

```
git push -u orgin main
```

After this command is used, you can just use `git push` and it will funcion the same way.

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to Home](../README.md)

