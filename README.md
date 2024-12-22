# git-assignment

1. Explain version control.

Version control is like an open source code system which helps for managing and tracking changes to files, documents, and code over time. It enables numerous people to work on the same project at the same time, keeps track of changes, and makes collaboration, error recovery, backup, and branching easier and also classified as either local, centralized, or distributed system.

Version control provides benefits such as history tracking, collaboration, mistake recovery, backup, and branching. Popular versions include Git, which enables users to work offline while pushing changes to a shared repository. Repository, commit, branch, merge, and push/pull are all necessary tools for managing changes in a project.

2. Explain difference between git and github.

Git and GitHub are both version control and collaboration solutions. Git is a local, command-line system that maintains file changes and allows developers to collaborate. GitHub is a web-based platform that hosts Git repositories and provides extra capabilities such as pull requests, code reviews, and problem tracking. Both programs provide unique features for version control and collaboration.

3. List 3 other github alternatives

i.   GitLab
ii.  Bitbucket
iii. SourceForge

4. Explain the difference between git fetch and git pull

The 'git fetch' and 'git pull' commands update a local repository with updates from a remote repository. Git fetches updates from the remote repository without merging them into the local branch. It's perfect for examining modifications before implementing them and checking what's new on the remote without interrupting present work. Git pull, on the other hand, combines 'git fetch' and 'git merge' to obtain updates from a remote repository and merge them into the local branch. It is ideal for transferring modifications from the remote to the local branch. Features, actions, local changes, conflict risk, and use cases are the main distinctions between the two commands. Before choosing whether or how to merge changes into the local branch, use `git fetch` to inspect the changes for safer workflows.

5. Explain in simple terms git rebase and the command for it

Git rebase transfers or reapplies commits from one branch to another. it also rewrites the commit history to make it appear as though the changes were done immediately on top of another branch, onlike merging branches, which produces a new commit to combine changes.
command : git rebase <branch>

6. Explain in simple terms git cherry-pick and the command for it 

Git cherry-pick command is used to apply particular changes (a commit) from one branch to another. You "pick" one or more specific commits and apply them where you need them, onlike merging or rebasing a whole branch.
command : git cherry-pick <commit-hash>

