# Intro To Git and GitHub - Git Fundamentals

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to tktk

## Check local repository status

Command: `git status`

#### What it does:
It tells us what is happening in a local repository at any given moment - Is the branch up to date? Are there changes we can commit to it? What is the state of those files?

#### When and why we use it:
Use this command to help understand the current status of our Git repo.

If you’re ever having trouble with git commands, `git status` is usually a good way to start troubleshooting!

## View Remotes

Command: `git remote -v`

#### What it does:

This command lists all of the remotes that have been configured for a local repository.

#### When and why we use it:

When you push/pull code to/from GitHub, you can select which remote you'd like to use. This command helps you identify which remotes are available.

#### Common Usage:

If you're following a class code-along, you might have an `upstream` remote with a link to the class repository that the instructor is pushing code to regularly so that you're able to pull changes to your local machine.

You might also have an `origin` remote with a link to your personal repository so that you can push your code to your own GitHub account as well.

Use the `git remote -v` command when you want to see all the remotes for a given repository.