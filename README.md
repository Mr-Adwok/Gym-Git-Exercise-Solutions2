# Gym-Git-Exercise-Solutions2

* Exercise 1
1.  git init
Reinitialized existing Git repository in /home/tupac/Documents/Gym-Git-Exercise-Solutions/.git/

2. git branch -m main master(git branch -m main master)
 git branch
* master

3. git status and git add .
4. git commit and git push
5. git branch Branch-name "git branch dev";
6. git branch -d branch-name


* Exercise 2
git add home.html
git stash push -m "home.html changes"

git add about.html
git stash push -m "about.html changes"
git stash list


git add team.html
git stash push -m "team.html changes"

git add home.html about.html
git commit -m "Add home and about page changes"
git push origin main

 git stash
 git stash pop stash@{1}
 git push origin dev


* Bundle 2
* Exercise 1
git add .
git commit -m ""
git push
git merge ft/bundle-2


* Exercise 2
git add .
git commit -m ""
git push origin main/ft/bundle2
git checkout main/ft/bundle-2
git merge ft/bundle-2
