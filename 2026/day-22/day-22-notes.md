
1)What is the difference between git add and git commit?

Ans: git add command move file from untracked to stage area. git commit command will track the file and record the history
permanently in repository history with commit message. 


2)What does the staging area do? Why doesn't Git just commit directly?

Ans:when git add command used it move file to unstaged area where file is ready to commit or tracked. if you wish
to revert the change or do not wish to commit then you can discard it.It sits between your working directory (where you edit files) and the repository (where commits are stored).

3)What information does git log show you?

Ans: git log command show all commit logs with date,time,commit id and done by whom.

4)What is the .git/ folder and what happens if you delete it?

Ans: When "git init" command used it makes a dir as git repository.

Commit history: All snapshots of your project.

Branches and tags: Metadata about different lines of development.

Staging area (index): Tracks what’s ready to be committed.

Configuration: Remote repository addresses, hooks, and settings.

Objects database: The actual content of files stored as blobs.


5)What is the difference between a working directory, staging area, and repository?

Working Directory : The actual file and folder that you will edit

Staging Area:A middle ground between your working directory and repository.

Repository: .git folder. a hidden database that store git history. it contains Commits, branches, tags, and metadata.

