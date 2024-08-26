**1.** Link my repo
```
git remote add origin <link repo>
```
**2.** To see what your branch is (Ex: Master or Main)
```
git branch
```
**3.** Change branch to main
```
git branch -M main
```
**4.** Add all files which need to push on github
```
git add .
```
**5.** Add commit (description) for your changes
```
git commit -m "your comment here"
```
**6.** For the first time you push on github
```
git push -u origin main
```
**7.** If you want to overwrite what you push on github
```
git push -f origin main
```
**8.** See folders, files inside your project after using `git add`:
```
ls
```
---
For the first time create a repo on github and use git to push: 1 -> 3 -> 4 -> 5 -> 6 <br/>
After pushing for the first time and want to overwrite it: 1 -> 3 -> 4 -> 5 -> 7

---
[Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
