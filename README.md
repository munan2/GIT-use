# GIT-use
## 使用GIT公钥

```
ssh-keygen -t rsa -C "18845724607@163.com"
cd ~/.ssh
ls --> id_rsa		id_rsa.pub
cat id_rsa.pub //将这个结果粘贴过去
```

## GIT使用
### 新建分支 
git branch zhangyan
### 切换到某一分支
git checkout zhangyan
### 新建分支并且切换到该分支上
git checkout -b zhangyan
### 查看本地所有分支
git branch
### 查看本地以及远程分支
git branch -a
### 将自己的分支和mater合并
git checkout master   //切到master分支上  
git merge zhangyan    //将zhangyan分支和master合并
### 删除自己的分支
git branch -d zhangyan  //删除自己的分支
git branch //删除完可以查看一下是否自己的分支已被删除
### 新建远程分支
假设本地有分支master  
git push origin master:zy //这样就是建立了一个远程分支 zy
### 删除远程分支
git push origin :zy  
或者 git push origin -delete zy
### 将本分支与远程分支关联
git checkout zhangyan //首先切换到本地自己的分支上   
git pull origin zy // zy是远程的分支
### 查看分支修改状态  提交
git status  
git commit -m 'xxx'
## VIM使用
### 打开单个文件
vim ReadMe.md 
### 修改
输入 i
### 修改完保存并退出
按下 esc 键  + ZZ（大写的Z）
### 不修改直接退出
按下esc键 :q!

