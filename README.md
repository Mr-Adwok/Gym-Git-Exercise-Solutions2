
````markdown
# Gym-Git-Exercise-Solutions2

---

# Bundle 1

## Exercise 1
1. Initialize repository
   ```bash
   git init
   # Reinitialized existing Git repository in /home/tupac/Documents/Gym-Git-Exercise-Solutions/.git/
````

2. Rename branch `main` → `master`

   ```bash
   git branch -m main master
   git branch
   # * master
   ```
3. Check status, stage & commit

   ```bash
   git status
   git add .
   git commit -m "initial commit"
   git push
   ```
4. Create and delete branches

   ```bash
   git branch dev
   git branch -d branch-name
   ```

---

## Exercise 2

1. Stash file changes

   ```bash
   git add home.html
   git stash push -m "home.html changes"

   git add about.html
   git stash push -m "about.html changes"
   git stash list

   git add team.html
   git stash push -m "team.html changes"
   ```
2. Commit staged files

   ```bash
   git add home.html about.html
   git commit -m "Add home and about page changes"
   git push origin main
   ```
3. Restore from stash and push

   ```bash
   git stash
   git stash pop stash@{1}
   git push origin dev
   ```

---

# Bundle 2

## Exercise 1

```bash
git add .
git commit -m "bundle 2 changes"
git push
git merge ft/bundle-2
```

---

# Bundle 3

## Exercise 2

```bash
git merge branch
git branch ft/service-redesign
git push origin main
git checkout main /ft/service-redesign
git merge ft/service-redesign
git rebase main
```

---

# Bundle 4

## Exercise 1

1. Add second remote

   ```bash
   git remote add git-copy https://github.com/<your-username>/gym-git-copy.git
   ```
2. Update home page & commit

   ```bash
   git add home.html
   git commit -m "Updated my home page"
   git push origin main
   git push git-copy main
   ```

## Exercise 2

1. Create `ft/footer` branch

   ```bash
   git checkout -b ft/footer
   git add footer.html
   git commit -m "ok"
   git push -u origin ft/footer
   ```
2. Squash merge into `ft/squashing`

   ```bash
   git checkout -b ft/squashing
   git merge --squash ft/footer
   git commit -m "footer changes squashing"
   git push -u origin ft/squashing
   ```

---

# Bundle 5

## Exercise

```bash
git add index.html
git commit -m "updated index.html"
git push
```

---

# Bundle 6

## Exercise 1

```bash
git checkout -b menuFeature
```

## Exercise 2

```bash
git checkout -b bug-fix
git add .
git commit -m "updated index-4.html to Contact.html"
```

```


