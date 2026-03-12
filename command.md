# -----------------------------
# Git Configuration
# -----------------------------
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --global --list

# -----------------------------
# Create / Clone Repository
# -----------------------------
git init
git clone <repository-url>

# -----------------------------
# Repository Status
# -----------------------------
git status

# -----------------------------
# Add Files
# -----------------------------
git add filename
git add .
git add *

# -----------------------------
# Commit Changes
# -----------------------------
git commit -m "commit message"
git commit -am "commit message"

# -----------------------------
# View History
# -----------------------------
git log
git log --oneline
git log --graph
git show

# -----------------------------
# Check Changes
# -----------------------------
git diff
git diff --staged

# -----------------------------
# Branch Commands
# -----------------------------
git branch
git branch branch-name
git branch -d branch-name
git branch -D branch-name

# -----------------------------
# Switch Branch
# -----------------------------
git checkout branch-name
git checkout -b branch-name
git switch branch-name
git switch -c branch-name

# -----------------------------
# Merge Branch
# -----------------------------
git merge branch-name

# -----------------------------
# Remote Repository
# -----------------------------
git remote add origin <repo-url>
git remote -v
git remote remove origin

# -----------------------------
# Push Code
# -----------------------------
git push origin main
git push -u origin main
git push origin branch-name

# -----------------------------
# Pull / Fetch
# -----------------------------
git pull
git pull origin main
git fetch
git fetch origin

# -----------------------------
# Remove / Rename Files
# -----------------------------
git rm filename
git mv oldname newname

# -----------------------------
# Undo Changes
# -----------------------------
git restore filename
git checkout -- filename
git reset HEAD filename
git reset --soft HEAD~1
git reset --hard HEAD~1

# -----------------------------
# Stash Commands
# -----------------------------
git stash
git stash list
git stash apply
git stash pop
git stash drop

# -----------------------------
# Tags
# -----------------------------
git tag
git tag v1.0
git push origin v1.0
git push --tags

# -----------------------------
# Rebase
# -----------------------------
git rebase branch-name
git rebase --continue
git rebase --abort

# -----------------------------
# Clean Untracked Files
# -----------------------------
git clean -f
git clean -fd

# -----------------------------
# Git Help
# -----------------------------
git help
git commit --help 
