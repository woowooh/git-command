# git-command  
git remote add origin git@github.com:woowooh/git-command.git  
添加远程主机 origin [url]   
git push -u origin master  
本地 master 推送至远程 origin，同时 -u 设置默认主机为 origin  
git push origin master:dev  
本地 master 推到 origin 主机 dev 远程分支上  
  
git reset --hard   
重置 stage 区与工作目录  
  
git reset (mixed)  
保留工作目录，清空暂存区  
  
git checkout .   
使用暂存区文件覆盖工作区(修改后，未add的话)   
  
git reset --hard  
add 后，还未 commit 的话  
  
git reset --hard origin/master  
已commit 还未 push 的情况 或者 git reset --hard last_commit_id
   
git reset <commit_id> <file_path>  
回退单个文件  
   
git stash save "save message"  
储存并备注信息  

git stash list git stash show   
查看暂存信息  

git stash apply stash@{n}   
应用第 n 个暂存信息


