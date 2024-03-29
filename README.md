# Git ITI Lab 2

Ahmed Alaa Elsharkawy.

## Branches Overview

### Creating Two Branches: `dev` and `test`

![Dev and Test Branches](dev_and_test_branches.png)

### Merging `dev` with `main`

![Merging Dev with Main](merge_dev_with_main.png)

## Removing Branches Locally

To remove a branch locally, use the following command:

```bash
git branch -d branch_name
```

If the branch has unmerged changes, you can force delete it with:

```bash
git branch -D branch_name
```

## Removing Branches Remotly

To remove a branch remotly, use the following command:

```bash
git push origin -d branch_name
```

## Creating Annotated Tags

![Annotated Tags](annotated_tags.png)

## How to List Tags Locally

```bash
git tag
```

## How to Delete Tags Locally and Remotely

Locally

```bash
git tag -d tag_name
```

Remotely

```bash
git push --delete origin tag_name
```

## What is Git Rebase? Give Me an Example.

Git rebase is a command used to modify the commit history by moving or combining commits. It's often used to maintain a clean and linear commit history.

### Example

Suppose you have a feature branch with three commits, and you want to incorporate the latest changes from the main branch. Instead of merging, you can rebase

```bash
git checkout feature_branch

git rebase main
```
