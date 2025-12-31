# 📘 Git & GitHub Commands Documentation: -

:- This document provides a quick reference to commonly used Git and GitHub commands, their purpose, and workflow explanations.

📌 What is Git?

:- Git is a distributed version control system that helps developers track changes, collaborate, and manage source code efficiently.

🔧 Initial Git Setup :- <br>
Configure Username:- <br>
:->  git config --global user.name "Rikin Patel" <br>

Configure Email:- <br>
:->  git config --global user.email "rikinpatel@gmail.com"<br>

Verify Configuration:- <br>
 :-> git config --list <br> <br>

📥 Working with Repositories:- <br>
Clone a Repository: <br> 
:-> git clone <repository_url> <br> <br>


👉 Creates a local copy of a remote repository. <br>

Initialize a New Repository: <br>
:-> git init <br> <br>

📊 Checking Repository Status: <br> 
Check File Status: <br>
:-> git status <br> <br>

 See File Differences:- <br>
  :-> git diff <br> <br>

📂 Git File States:- <br> <br>
Untracked:->	New files not tracked by Git <br>
Modified:-> 	Files that have been changed <br>
Staged:->    	Files ready to be committed <br>
Unmodified:->	No changes<br> <br>

➕ Adding & Committing Changes:-  <br> <br>
Add Files to Staging Area:- <br>
:-> git add <file_name> 


or

git add .   <br> <br>

Commit Changes:- <br>
:->  git commit -m "Your commit message" <br> <br>

🚀 Pushing & Pulling Code:- <br> <br>
: Push Code to Remote Repository:- <br>
:-> git push origin main <br> <br>

Pull Latest Changes: <br>
  :-> git pull <br> 

Push with Upstream Tracking:- <br>
  :-> git push -u origin <branch_name> <br>

Get Help for Push Command:- <br>
  :-> git push --help <br> <br>

🌿 Branch Management:- <br>
List All Branches: <br>
  :-> git branch <br>

Create a New Branch:- <br>
  :-> git checkout -b <branch_name> <br>

Switch Branch:- <br>
  :-> git checkout <branch_name> <br>

Rename Branch to Main <br>
  :-> git branch -m main <br>

Delete a Branch <br>
  :-> git branch -d <branch_name> <br>

View Remote Branches <br>
  :-> git branch -r <br> <br>

🧾 Commit History:- <br> <br>
View Commit Logs <br>
  :-> git log <br> <br>

Graph View (Tree Structure):- <br>
  :-> git log --graph --oneline --decorate --all <br> <br>

🔗 Pushing an Existing Local Repository to GitHub:- <br>
:-> git remote add origin <repository_url> <br>
:-> git branch -m main <br>
:-> git push -u origin main <br> <br>

🔄 Rebase Pull (Advanced):- <br>
  :-> git pull --rebase origin main <br>

🚀 Push All Branches at One Time:- <br> 
      :-> git push --all origin <br> <br>

🏷️ Push All Tags (Optional) <br>
      :-> git push --tags <br>



