---
title: Git-ting Started
datePublished: Fri Jan 20 2023 16:38:18 GMT+0000 (Coordinated Universal Time)
cuid: cld4qx6d0000109l8eig4dh2s
slug: git-ting-started
tags: git, technical-articles

---

Git is one of those tools that we take for granted when writing software. Here are some basic commands to get you started on your journey as a programmer.

## Setting up

```bash
git init ...
```

## Making Your Changes

### Git Status

```bash
git status
```

### Git Add

```bash
git add .
```

The Git Add command adds in files with changes that need to be committed into a staging area. At this point, the changes are not yet saved, although they are recorded down.

### Git Commit

```bash
git commit -m "<insert commit message here>"
```

Git commit, as the name suggests, saves your changes as a commit. It is customary to add a commit message using the `-m` flag, which serves as a descriptive reminder of the changes that you have made. This might not seem so useful when you are making changes to code that you alone work on.

## Syncing Up

## Fixing a Mess