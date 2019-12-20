# 常用git命令

1. git init
2. git add
3. git commit -m "xxxx"
4. git status
5. git diff
6. git log  (--pretty=oneline) 显示从最近到最远的提交日志 HEAD:当前版本  
7. git reset --hard  +  HEAD:当前版本  HEAD^上个版本    HEAD^^上上个版本   HEAD~100  版本号（前几位即可）
8. git reflog 记录你的每一次命令
9. git checkout -- file 让这个文件回到最近一次git commit或git add时的状态。
10. git reset HEAD file 把暂存区的修改撤销掉（unstage），重新放回工作区  
11. git rm
12. git remote add origin git@github.com:ezez666/repo-name.git
13. git push    第一次加-u       git push origin master
14. git clone

