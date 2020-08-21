**Git 全局设置:**  
git config --global user.name "Trigger"  
git config --global user.email "275750245@qq.com"
---
**创建一个新仓库**  
git clone http://47.103.97.77/Trigger/bhp-project.git  
cd bhp-project  
touch README.md  
git add README.md  
git commit -m "add README"  
git push -u origin master  
---
**推送现有文件夹**  
cd existing_folder  
git init  
git remote add origin http://47.103.97.77/Trigger/bhp-project.git  
git add .  
git commit -m "Initial commit"  
git push -u origin master  
---
**推送现有的 Git 仓库**  
cd existing_repo  
git remote rename origin old-origin  
git remote add origin http://47.103.97.77/Trigger/bhp-project.git  
git push -u origin --all  
git push -u origin --tags  
---
