# Instructons for woring with Git

## How to open a git repository for a folder

**GIT INIT** creates a repository. Enter this command to start working. Entering any other command before GIT INIT will result in an error.

Also, you can ask for a version
**GIT VERSION**

## How to add and commit

*  **GIT ADD** adds a file to be tracked 

* **GIT COMMIT --m 'update msg here'** commits changes to git with your description of what you did

## Viewing a list of all committed changes

* **GIT LOG** shows a list of all committed saves

![What you will see when using git log](logs.png)

* **GIT LOG --GRAPH** this command is used to see a tree of changes, including what's going on on separate branches
![What you will see when using git log graph](loggraph.png)

## Viewing *specific* committed versions and returning to the most up-to-date version

* **GIT CHECKOUT _hash number of a commit_** lets you jump to the version of the file with that specific hash number you typed

* **GIT CHECKOUT MASTER** returns you to the most current version


## Other checks
**GIT STATUS** shows the current branch and tells you if you've got sth to commit

To see the difference between *last saved* and *last committed* versions, type in:
**GIT DIFF**

## How to work with branches

**GIT BRANCH** to see a list of branches

**GIT BRANCH _NEW_BRANCH_NAME_** - to create a new branch

**GIT CHECKOUT _BRANCH_NAME_** - to switch to a branch with this name

**GIT BRANCH -D _BRANCH_NAME_** - to delete a branch

## How to work with remote repositories

1. _Fork_ a project to create a copy of someone's work.

2. Once forked, you can _clone_ it to your local repository using 

**git clone _link_to_remote_repository_**

3. Once cloned, you can switch to appropriate folder using

**cd _folder_name_**

4. Inside the folder create your own additional branch

**git branch _branch_name_**

5. If you would like to suggest changes, make them in this branch, add and commit. 

6. Now we can use 

**git push** to send these changes to remote repository

7. when upload is complete, we will see out additional branch on GitHub. There will also be a Compare&pull request button we can use to send our suggestions to initial folder's owner.
