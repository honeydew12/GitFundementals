# git command

The command `git command` will take all tracked changes (items added with [git add](./Add.md)) and then package them up in what is called a commit.

Commits come with commit messages that are required for each commit. 

You add a message to a commit command using the `-m` flag followed by a message in quotes.

A commit mesage _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we are working on where we just built out the ability to register new accounts,

```
git add .
git commit -m "Added register functionality"
```
Then when viewing the history of a git repository, you can pinpoint where the register functionality was added.

## Resources
- [Git Commit Documentation](http://git-scm-.com/docs/git-commit)

---
[Back to Home](../README.md)
