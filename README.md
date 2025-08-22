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



bundle3
* Exercise 2
git merge branch
git branch ft/service-redesign
git push origin main
git checkout main /ft/service-redesign
git merge ft/service-redesign
 git rebase main




bundle 4
Exercise1
- git remote add git-copy https://github.com/<your-username>/   gym-git-copy.git
- git add home.html
- git commit -m "Updated my home page"
-git push origin main
- git push git-copy main

Exercise2
git checkout -b ft/footer
git add footer.html
git commit -m "ok"
git push -u origin ft/footer
git checkout -b ft/squashing
git merge --squash ft/footer
git commit -m "footer changes squashing"
git push -u origin ft/squashing

bundle 5
Exercise
git add index.html
git commit -m "updated index.html"
git push


bundle 6
Exercise 1
git checkout -b menuFeature

Excersie 2
git checkout -b bug-fix
git add .
git commit -m "updated index-4.html to Contact.html




