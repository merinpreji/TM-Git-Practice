# intro to git
Git is a tool or a version controller. It allows multiple people to collaborate on the same project.
### key concepts
- **Repository** A folder where your project is **stored**. (stored/shared)
- **Commit** A snapshot of your project at a particular point in time. (save) It will save the code at a specific point of time. (Aautomated First TC)
- **Branch** A separate line of development, allowing you to work on features or fixes. (different version) Master Branch/Main Branch, Personal/Sub Branch
- **Clone** Creating a local copy of a remote repository
- **Push** Send your changes to a remote repository. (upload)
- **Pull** Get the latest changes from a remote repository. (download)

### commands
# ✅ 1. Clone a Repository
git clone https://github.com/username/repository-name.git

# ✅ 2. Navigate to the Project Folder
cd TMDemo

# ✅ 3. Check the Current Branch
git branch

# ✅ 4. Create a New Branch
git checkout -b feature_one

# ✅ 5. Switch Between Branches
git checkout feature_one

# ✅ 6. Add Files to Staging
git add .
git add filename

# ✅ 7. Commit Changes
git commit -m "Your commit message here"

# ✅ 8. Push Code to GitHub (First Time)
git push -u origin feature_one

# ✅ 9. Push Code After Making Changes
git add .
git commit -m "Updated login form"
git push

# ✅ 10. Pull Latest Changes from GitHub
git pull
git pull origin main

# ✅ 11. Merge Two Branches
git checkout main
git merge feature_one
git push

# ✅ 12. Check the Git Status
git status

# ✅ 13. View Commit History
git log
git log --oneline

# ✅ 14. Delete a Branch
git branch -d feature_one
git push origin --delete feature_one

# ✅ 15. Set Remote URL (if wrong account)
git remote set-url origin https://github.com/merinponvayal/TMDemo.git
git remote -v

# ✅ 16. Clone a Specific Branch
git clone -b branch-name https://github.com/username/repository-name.git

# ✅ 17. Undo Last Commit (Optional)
git reset --soft HEAD~1
git reset --hard HEAD~1

# ✅ 18. Fork a Repository (if it's public)
git clone https://github.com/your-username/repository-name.git
git push

# ✅ 19. Stash Changes (if you need to switch branches)
git stash
git stash pop

# ✅ 20. Remove a File from GitHub
git rm --cached filename
git commit -m "Removed file"
git push

# ✅ 21. Configure Git Credentials
git config --global user.name "merinponvayal"
git config --global user.email "your-email@gmail.com"

# ✅ 22. Force Push (if needed)
git push -f

# ✅ 23. Discard Uncommitted Changes
git restore .
git reset HEAD

# ✅ 24. Check Remote URL
git remote -v

# ✅ 25. Add Remote URL (if missing)
git remote add origin https://github.com/merinponvayal/TMDemo.git

# ✅ 26. Save Git Credentials Forever (no password prompt)
git config --global credential.helper store

git log
git revert code
