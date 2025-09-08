# Git Notes

+ Git Command
    + git init
        + create .git
    + git status
        + show tracked/untracked files
    + git add
        + add files to tracked
    + git commit -m "text"
        + save version
    + git log
        + saved history
    + git remote add origin URL
        + add URL to remote
        + remote name = origin
    + git remote
        + show all remote
    + git push -u origin master
        + remote = origin
        + branch = master
        + -u = defalt remote and branch
    + git branch -M main
        + change branch to main
        + -m 是一般的 rename，如果新名稱已存在會失敗。
        + -M 是強制 rename，即使已經有同名分支也會覆蓋掉。
