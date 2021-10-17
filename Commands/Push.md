# git push
When you have a [remote](./REMOTE.md) set up you'll need to begin to move [commits](./COMMIT.md) to the remote.
You can attach a name and branch name to your command to specify where you're pushin to.
```
git push orgin main
```
This command will push the **main** branch to the remote called **orgin** this means any commits that are in your local will be **Pushed** to the remote.
### Upstream Tracking 
Instead of including the name of the remote and the branch you're on everytime, you can set local branches to the track an upstream branch.
This means you can tell the breanch to push to its assigned upstream remote branch by using the command `git push`
```
git push - u orgin main
```
After this command is used, you can just use `git push` and it will function the same way.
## Resources 
- [Git Push Documentation](https://git-scm.com/docs/git-push)
---
[Back to home](../README.md)