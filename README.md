GIT HUB COMMANDS: -

git CLONE <link from github> (Cloning a repo on our Local machine) <br>
git config --global user.name "Rikin patel" <br>
git config --global user.email "rikinpatel@gmail.com" <br>
git config --list (To verify) <br>
git push --HELP (to know in detail about this push command -- { (--HELP)= to know in detail about commands }) <br>

git init <br>
git status (ti check for any changes in the repo) <br>
git diff (to see the difference of current version with last committed version) <br>
git ADD (adds new or changed files in your working directory to the git staging area) <br>
git COMMIT -M "Some msg" (to add changes in git repo or it is the record of changes) <br>
git PUSH origin MAIN (upload local repo content to remote repo) <br>
git PULL (to fetch the latest files from remote repo) <br>
git LOG (to see the old commits history) <br> <br>

Untracked = new files that git doesn't yet track <br> Modified = changed <br> Staged = file is ready to be committed <br> Unmodified = Unchanged <br>

git BRANCH (to check branch) <br>
git CHECKOUT -b {new branch name} (to create new branch) <br>
git BRANCH -m MAIN (to rename branch) <br>
git CHECKOUT {branch name} (to Navigate or move to another branch) <br>
git BRANCH -d {branch name} (to delete branch) <br>

* Push an existing repository from the command line: -  <br>
  git REMOTE ADD ORIGIN <LINK FORM GITHUB> <br>
  git BRANCH -m MAIN <br>
  git PUSH -U origin MAIN <br>

* git push -u origin {BRANCH NAME--(EX:-feature-login)} (Push the local branch to remote) <br>
  git branch -r (Verify remote branches) <br>
  git LOG --GRAPH --ONELINE --DECORATE --ALL (for SHOW in TREE-VIEW) <br>
  git PULL --RABASE origin MAIN 
  




    
