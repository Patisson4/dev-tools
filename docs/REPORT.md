### Task 1
```
wsl --install -d Ubuntu-20.04
sudo apt install gitweb
sudo api install lighttpd
git instaweb
```
![img.png](img.png)
2.
```
git merge --squash master
git branch -D ci
```
3.
```
git log --graph --decorate $(git rev-list -g --all)
git branch old-master aae7df
```
4.
```
git blame -L 32,32 prisma/seed.ts
```
5.
```
npm install
git bisect start

npm run test
git bisect [bad или good пока работает бинпоиск]
```
6.
```
git filter-branch --tree-filter "rm -f .env" -- --all
```
7.
```
git rebase -i HEAD~3 --exec "git commit --amend --reset-author --no-edit"
```
8.
```
git config rerere.enabled true
git merge feature
```
9.
```
npm start
```
10.
```
git gc
```
11.
```
git checkout -b report
git add docs/REPORT.md
git add -p docs/REPORT.md
```