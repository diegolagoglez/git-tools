# Git tools #

## Introduction ##

Git tools is a repository that includes tools for Git source code manager.

This tools are commands in the form of `git-*command*` to allow calling with `git` sintax:

```bash
user@box:~:$ git my-tool
```
## Tools included ##

* `git-aliases`: Show git aliases.
* `git-branch-description`: Show the description of the current branch.
* `git-current-branch`: Shows current branch (without any more information).
* `git-last-commit`: Shows the the last repository commit (normal and abbreviated; and its date).
* `git-last-tag`: Show the last tag.
* `git-lg`: Show a limited log.
* `git-merge-request`: Makes merge requests from command line (in heavy development).
* `git-pull-all`: Do a `git pull --rebase` into all subdirectories from the current directory.
* `git-revision`: Shows a revision number like in svn. Please, be aware of the implications.
* `git-sizes`: Shows information about git repo sizes (code size, .git dir size...).
* `git-stats`: Show basic statistics about the current Git repository.
* `git-svn-committers`: Show committers from a Subversion repository in the form of Git users and emails.
* `git-tools`: Not executable script. Source it to use git utilities.

## Installation ##

Copy or link this tools into your binaries directory (maybe `~/bin` or `/usr/local/bin`).
