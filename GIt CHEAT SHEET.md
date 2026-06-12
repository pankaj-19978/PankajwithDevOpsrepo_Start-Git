# GIT CHEAT SHEET (Begginer Friendly)
# 🔹 1. Setup Git (only once)
  git config --global user.name "Your Name" 
  git config --global user.email "Your@email.com"
# 🔹 2. CHECK CONFIG: 
  git config --list
# 🔹 3. Start a New Project/Make a Directory (Initialize Git)
  mkdir "Directory name"
  git init
  touch "file name"
# 🔹 4. Check Status of Files
  git status
# 🔹 5. Add files to Staging area
# add one file:  
  git add "file name"
# Add All files:
  git add .
# 🔹 6. Commit Files
  git commit -m "Your Commit Message"
# 🔹 7. Connect Local Repo to Github
  git remote add origin (RepoURL)
# 🔹 8.Check Remote:
  git remote -v
# 🔹 9. Push Code to Github
# First Push:
  git push -u origin main
# Next Pushes
  git push
# 🔹 10. Pull Latest changes From Github
  git pull
# 🔹 Clone a REpository
  git clone (URL)
# 🔹 11.View Commit History
  git log
# 🔹 12.Simple Views
  git log --online
# 🔹 13. Create a Switch Branch
  git branch (BranchName For Example Feature1)
# 🔹 14. Switch to Branch
  git checkout (Branch Name)
# 🔹 15. Create + Switch (Shortcut)
  git checkout -b (Branch Name)
# 🔹 16. Merge a Branch
# Switch to main:
  git checkout main
# Merge:
  git merge (Branch Name)
# 🔹 17. Delete a Branch
  git branch -d (Branch Name)
# 🔹 18. Undo Mistake
# Undo Staged file:
  git reset filename
# Undo Commit (Keep Change)
  git reset --soft HEAD~1
# 🔹 19. Undo Commit (Discard changes):
  git reset --hard HEAD~1
# 🔹 20. Remove a file Repo
# delete file from repo and local:
  git rm filename
  git commit -m "Removed file"
  git push
# 🔹 21. Just Remove from Git But Keep Locally
  git rm --cached filename
# 🔹 22. Quick Daily Workflow (most used)
  git add .
  git commit -m "updated day files"
  git push


















  
