# git commands starting a project 
1. git init 
2. git clone "foldername"

# git staging 
cahnge waiting to be commited(waiting room)
git add file_name -> stage a file
git add . , git add -A , git add --all -> stage akll changes

# checkpoint /savpoint 
git commit -m "msg"
git commit -a -m "msg"
git log
# tagging (bookmark for commits)
git tag  tagname
git tag -a tagname -m "msg"
git show tagname
git tag
git push origin tagname

# stash


# braching 
creating new branch for new features liek a seperate workspace

git branch -> list all branches
1. creating branch 
git branch branch-name --> create new branch
git chechout branch-name --> switch to new branch

git checkout -b branch-name --> both create and switch
git switch -c branch-name  --> also for both create and switch


# git checkout nad git switch -> navigation btw branches
# switch branches
git switch branch-name
git checkout branch-name

git switch - => switch to prev branch

# deleting a branch
git branch -d branch-name (merged)
git branch -D branch-name (not merged)

# renaming a branch
git branch -m old-name new-name

# merging 
merge completed feature to main 

1. first switch to main branch
git switch main

2. then merge branch
git merge branch-name

# merge conflict
same file same line diifreent changes diffrent branches