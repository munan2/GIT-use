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

