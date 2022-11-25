# Git Worktree

This repository explains the usefulness of worktree :D

## Clone
```bash
git clone --bare https://github.com/BruceChanJianLe/git-worktree.git
```

## Setup

Paste this line in your config file.
```
fetch = +refs/heads/*:refs/remotes/origin/*
```

## Fetch
```bash
git fetch
```

## Add Tress

Add your favourite folder and branch!
```bash
git worktree add master master
```

## Reference

- [link]()
