## SHARING GIT AWARENESS

A sandbox repo to make sure as many people as possible use Git in their development tasks

#### List of Git CLI commands I've learned
- git init
- git config
- git commit
- git add
- git push 
- git remote add [branch_name]

#### Commit hashes
Every commit is identified by a unique hash ID	

#### HEAD pointer
HEAD is a special pointer indicating the current commit in the history

#### File statuses
Untracked - the file is present in the directory but not being tracked by Git
New - file is new in the directory and added to the staged area for the first time
Modified - file modified in compasion to the last commit or staging action AND not added to the current's commit staging area
Staged - file staged for commit

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged -- "git commit" --> tracked/commited;
```
