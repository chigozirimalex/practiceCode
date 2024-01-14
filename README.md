## 1 Explain Version Control

Version Control is a system that records changes to a file or set of files over time so that you can recall specfic versions later. A version control control system (VCS) is a verywise thing to use. It allows you to revert selected files back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when , and more.

## 2 Explain difference between git and github

Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, we can use git without Github, but we cannot use Github without Git.

## 3 List 3 other github alternatives

- GitLab

- Bitbucket

- SourceForge

## 4 Explain the difference between git fetch and git pull

The difference between git fetch and git pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

## 5 Explain in simple terms git rebase and the command for it

Git rebasing is the process of moving or combining a sequence of commits to a new base commits. Rebasing is most useful and easily visualised in the context of a feature branching workflow.

The git rebase command allows you to easily change a series of commits, modifying the history of your repository. you can reorder, edit, or squash commits together.

### Typically, we would use git rebase to:

- Edit previous commit messages
- Combine multiple commits into one
- Delete or revert commits that are no longer necessary

## 6 Explain in simple terms git cherry-pick and the command for it

Git cherry-pick means choosing a commit from one branch and applying it to another branch. This is in constrast with other ways such as merge and rebases which normally apply many commits into another branch.

Git cherry-pick is just like rebasing, an advanced concept and also a powerful command. it is mainly used if you don't want to merge the whole branch and you want some of the commits.

git cherry-pick is a powerful command that enables arbitrary git commits to be picked by reference and appended to the current working head.