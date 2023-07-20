# Ironhack final lab git

## What is the purpose of the Feature Branch Workflow in Git?

The purpose of the feature branch is to be able to work on a new development feature.

## How do you set up a new Git repository for your project?

with the command

```sh
$ git init
```

## What is the main branch in the Feature Branch Workflow?

master branch

## How do you create a new branch for a specific feature or task?

```sh
$ git checkout -b "feature/<name-feature>"
```

## How do you switch to a different branch in Git?

```sh
$ git checkout <name-branch>
```

## How do you make changes and track your progress in the feature branch?

```sh
$ git add <files-to-stage>
```

## How do you merge a feature branch into the main branch?

```sh
$ git merge <branch-to-merge>
```

## What should you do if there are merge conflicts during the merge process?

Review where in the code the conflicts are, correct them and continue with the merge

## Why is it important to test the merged codebase after completing the merge?

Because there may be changes that at the time of the merge were left behind at a point in history

## What are some additional challenges you can undertake to enhance your understanding of the Feature Branch Workflow?

Make a good documentation of the respective commits throughout the history of the branch.

Do not clear repository history with HARD RESET or other commands that may alter the flow



## How do you delete a feature branch after merging it into the main branch?

```$
$ git -D <name-branch>
```

## What is the purpose of code reviews in the Feature Branch Workflow?

The purpose is to review the solution from another perspective or to be able to detect possible bugs in the solution before it is merged into the main branch.

## How do you push your feature branch to a remote repository?

```sh
$ git push <remote-repo> <branch-feature>
```

## What is the recommended approach for naming feature branches in the Feature Branch Workflow?

"feature/name-feature"

## How can you keep your feature branch up to date with the latest changes from the main branch?

There are two possible ways depending on the workflow

```sh
$ git pull <remote-repo> <branch>
```

```sh
$ git pull --rebase <remote-repo> <branch>
```

