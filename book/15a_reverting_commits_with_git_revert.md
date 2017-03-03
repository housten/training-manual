### Reverting Commits

To get your game working, you will need to reverse the commit that incorrectly renames `index.html`.

> **Warning**: Before you reverse the commit, it is a good idea to make sure you will not be inadvertently reversing other changes that were lumped into the same commit. To see what was changed in the commit, use `git show SHA`.


1. Initialize the revert: `git revert <SHA>`
- Type a commit message.
- Push your changes to GitHub.