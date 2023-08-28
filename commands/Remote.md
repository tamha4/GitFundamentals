# git remote

When working with git, a **remote** is any git repository thatis not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote respositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they have different statesif changes not shared between the two.

### Adding a remote

A remote can added with the `git remote add` command, followed by the name and location of the remote.

the name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

-[Git Remote Documenation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)