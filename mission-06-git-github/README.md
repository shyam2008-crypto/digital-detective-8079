# Mission 6 - Git and GitHub

# 1. Objective
My task was to practise the basic Git workflow, make a branch, open a Pull Request on GitHub, and explain how branches and Pull Requests help people work together.



# 2. Basic Git workflow
| Git operation | Command | What it does in my own words |
|---|---|---|
| Check repository status | git status | checks the commits and staged files |
| Stage selected changes | git add README.md | it stages with the changes |
| Create a commit | git commit -m "message" | it leaves a msg every time you commit |
| View commit history | git log --oneline | it shows the commits done by me |

Difference between staging a change and committing it:
Staging only gets the change ready. Commit is the one that really saves it in the history.

# 3. Branch update-about
What I added to the root README under My Learning:
I added what I learned, how a computer works with input, process, storage and output, how to use the Terminal, and that computers use binary.

Commands I used to create the branch, commit and publish it:
git checkout -b update-about, then git status, git add README.md, git commit -m "Add My Learning section to README", then git push -u origin update-about

# 4. Pull Request
Status of my Pull Request (open or merged):
Merged. After that I ran git checkout main and git pull origin main.

What a branch is, and what a Pull Request is:
A branch is a separate copy to work on without changing main. A Pull Request asks GitHub to merge my branch into main.

Why they are useful when people work on the same project:
Two people can work on their own branches without breaking each other's work. Someone can also check the changes before they go into main.

# 5. Git command glossary
| Operation | Command | One-line explanation |
|---|---|---|
| Initialise a repository | git init | starts Git in a folder |
| Check status | git status | shows what changed |
| Stage changes | git add | adds files to the next commit |
| Commit changes | git commit | saves the changes with a message |
| View history | git log | shows the past commits |
| Create or list branches | git branch | lists branches or makes a new one |
| Switch branches | git checkout or git switch | moves to another branch |
| Publish changes | git push | sends my commits to GitHub |
| Retrieve remote changes | git pull | gets new changes from GitHub |

# 6. Commands used
- git status, git add, git commit, git log: the basic workflow
- git checkout -b: created and moved to the new branch
- git push -u origin update-about: published the branch to GitHub
- git checkout main and git pull origin main: used after I merged the PR

# 7. My understanding
Version control saves the history of my work so I can go back if something breaks. Git is the tool on my computer and GitHub is the website where the project is stored online. A branch and PR is better than editing main directly because the changes can be checked first.

# 8. Difficulties faced
My push was rejected the first time.

# 9. How I resolved them
I pulled the latest changes and pushed again.

# 10. Evidence
mission-06-git-github/README.md, the update-about branch and the Pull Request on GitHub.
PR link: https://github.com/srivathsa12/digital-detective-8490/pull/1

# 11. Commit details
Commit message: Complete Git and GitHub collaboration mission. Pushed to GitHub. Pull Request status: Merged