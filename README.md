# SE-Group13
This is the repo for Software Engineering course 2022, group13
# Git Cheat Sheet
- 取得 repo: `git clone https://github.com/YenTinaNTHU/SE-Group13.git`
- 新增 branch: `git branch <new branch name>`
- 切換 branch: `git checkout <branch name>`
- 新增＋切換 branch: `git checkout -b <new branch name>`
- 檢視有哪些 branch： `git branch`
- Add -> Commit
    `git add -A`
    `git commit -m '<commit message>'`
- Push 到 GitHub: `git push`
- 新的 branch 第一次 push: `git push --set-upstream origin <branch name>`
- merge branch:
    1. 先切回主分支：`git checkout main`
    2. `git merge <branch name>`
    3. `git push`