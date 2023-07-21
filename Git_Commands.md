# Git Commands
A list of the git commands I've worked with and my rough explainations of how they all work.

### Index
- [Create/Initise Repository](#createinitise-repository)
- [Help](#git-help)
- [Add files to Staging](#add-files-to-staging)
- [Show Staging Status](#show-staging-status)
- [Commit Changes to Local Branch](#commit-changes-to-local-branch)
- [Show Log](#show-log)
- [Push changes to GitHub](#push-changes-to-github)
- [Create Branch](#create-branch)
- [Checkout Branch](#create-branch)
- [Switch Branch](#switch-branch)
- [Merge Branches](#merge-branches)


### Create/Initise Repository 
> `git init $newRepositoryName`
: initilise a directory into a git repository (get it ready for version control)

---

### Git Help

> `git help` 
: list git commands (google if unsure)

---

### Add files to staging

> `git add $fileOrDirectory` 
: start tracking files/directories versions ready for being commited to your branch (copy of main repository)

---

### Show Staging Status

> `git status`
: list files & directories that are tracked or untracked before commiting the changes

---

### Commit Changes to Local Branch

> `git commit`
: commit the changes you have made, to the branch you are in 
- `-m` 
: "Commit message"
- `-a`
: add and commit all

---

### Show log

> `git log`
: list whose commited what and when

---

### Push changes to GitHub

> `git push` 
: publish your local commits to main

---

### Create Branch

> `git branch $nameOfBranch` 
: create a branch of the main repository that you can edit without making changes to the master repository
- `-d` 
: delete named branch (if you're not in it)

---

### Checkout Branch

> `git checkout $nameOfBranch`
: switch to editing the branch

---

### Switch Branch

> `git switch -`
: switches to your previous branch

---

### Merge Branches

> `git merge $nameOfBranch` 
: merges the named branch into the current working branch you are in
    
When trying to resolve merge conflicts go into the listed file in the error message. Try using cat, nano or vim.
    
Then edit, save and commit the changes of the file by simply removing what you dont want in the program. Then executing the command:
        
> `commit -a -m "Commit Message"`

---

