# My git notes

**git init** - turn folder into repository

**git status**

**git commit -m "Add test"**
| Command | Functionality |
|--------------------|-------------------------|
|'git switch -c <branchname>' |'create a new branch and switch to it'|
|'git switch <branchname>' |'switch to it'|
|'git branch' |'list your branches' |
|'git branch -a' |'list all branches (local and remote) |
|'git branch -d <branchname>' |'delete a branch' |

##Git Branches and PRs##

1. Open last main version **git pull origin main**
2. Create a new branch and switch to it **git switch -c <branchname>**
3. List what you have in branch **ls**
4. Find and run necessary file **code <filename>**
5. Change file in VS
6. Save it **command+S**
7. Check changes **git status**
8. Stage all changes in the current directory for the next commit **git add .**
9. Make commit **git commit -m"your message"**
10. Push to repositary **git push -u origin <branchname>**
11. On GitHub, a yellow action box should appear, suggesting you **create a pull request** for the named branch.
12. Wait for respons from Sn-s or merge the pull request
