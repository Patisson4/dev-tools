### Task 1
```
wsl --install -d Ubuntu-20.04
sudo apt install gitweb
sudo api install lighttpd
git instaweb
```
![img.jpg](img.jpg)
### Task 2
```
git merge --squash master
git branch -D ci
```
![img2.jpg](img2.jpg)
### Task 3
```
git log --graph --decorate $(git rev-list -g --all)
git branch old-master aae7df
```
![img3.jpg](img3.jpg)
![img3_2.jpg](img3_2.jpg)
### Task 4
```
git blame -L 32,32 prisma/seed.ts
```
![img4.jpg](img4.jpg)
![img4_2.jpg](img4_2.jpg)
### Task 5
```
npm install
git bisect start

npm run test
git bisect [bad или good пока работает бинпоиск]
```
![img5.jpg](img5.jpg)
### Task 6
```
git filter-branch --tree-filter "rm -f .env" -- --all
```
![img6.jpg](img6.jpg)
![img6_2.jpg](img6_2.jpg)
![img6_3.jpg](img6_3.jpg)
### Task 7
```
git rebase -i HEAD~3 --exec "git commit --amend --reset-author --no-edit"
```
![img7.jpg](img7.jpg)
![img7_2.jpg](img7_2.jpg)
![img7_3.jpg](img7_3.jpg)
### Task 8
```
git config rerere.enabled true
git merge feature
```
### Task 9
```
npm start
```
### Task 10
```
git gc
```
![img8.jpg](img8.jpg)
![img8_2.jpg](img8_2.jpg)
### Task 11
```
git checkout -b report
git add docs/REPORT.md
git add -p docs/REPORT.md
```