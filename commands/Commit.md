# git commit

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes.

A commit message_can_ be anything, but best practice dictates that you should use that massage to indicate the changes included in the commit.

for example, if you have an application we're working on wherewe just built out the ability to register new accounts, then you might habe some variation of the following"

```
git add .
git commit -m "Added register functionality"
```

Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources 

-[Git Commit Documenation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)