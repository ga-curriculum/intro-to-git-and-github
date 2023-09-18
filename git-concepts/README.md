# Intro To Git and GitHub - Git Concepts

![Hero image](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to tktk

## What is version control?

A Version Control System (VCS) records changes made to files over time so that you can recall specific versions later. It also makes working in teams easier because it enables developers to submit changes to be merged into the codebase.

## Why use version control?

A VCS allows you to:

Revert files to a previous state
Review changes made over time
Collaborate on a set of files with others
Create separate branches of the codebase to develop new features without impacting the main, or production branch. This process can be done non-linearly

## Git flavored version control

In SEI, we'll be using [Git](https://git-scm.com/) - the world's most popular version control system. [Linus Torvolds](https://en.wikipedia.org/wiki/Linus_Torvalds) created Git in 2005 to help with the development of his main project at the time - Linux.

Git is a version control system designed for tracking changes in source code. It allows developers to collaborate efficiently, manage code history, create and merge branches, and ensure data integrity through cryptographic hashing. Git operates independently but can be integrated with collaboration platforms for additional features.

## Git Vocabulary

### Git Repository

A Git repository (aka Git repo, or just repo) is essentially a copy of your project, but that copy holds information about the who, what, and when of your project. This information helps developers use Git to collaborate, track changes through time, or even revert to previous versions of the code when necessary.

Git repositories can be stored locally on a developer’s machine or hosted on remote servers such as GitHub.

In short - a Git repo allows us to find all past versions of the code, see who made changes as the project evolved, and when those changes were made.

### Git Branch
A Git branch (or just branch) is an independent line of development within a Git repository, allowing developers to work on different features, bug fixes, or experiments without affecting the main codebase.

Each branch represents a separate snapshot of the project's files, diverging from a common point in the repository's history. In short, branches allow developers to contribute to the same set of code and not step on one another's toes. As a result, branches are an essential part of collaboration.

In this course, we will use the `main` branch as our central source of truth, and the default branch name. As of 2020, this is the default naming convention for Git and GitHub. You may see other organizations use the now outdated `master` branch as their default branch name instead - as time goes on, this will be less and less common.

### Remotes
A remote is a reference to a repository hosted on an external server, allowing synchronization and collaboration between a local Git repository and its counterpart located elsewhere.

In this course remotes typically take the form of a URL that will point to a repository on GitHub, but other code-sharing platforms like GitLab and BitBucket exist. When collaborating, these external repositories provide a centralized location for sharing, updating, and accessing a codebase among multiple team members. We’ll discuss remotes in more detail when we cover GitHub itself.