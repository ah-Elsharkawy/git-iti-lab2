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

