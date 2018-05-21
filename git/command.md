# GIT Command

## git remote 
```
git remote //列出所有仓库的名字
git remote -v //列出远程仓库对应的克隆地址
git remote add new_name git://github.com/xxxx/xxxx.git //新增一个远程仓库，制定一个简单的名字 
git remote show origin //查看远程仓库详细信息
git remote rm new_name // 删除仓库
git remote rename old_name new_name //仓库改名字
```
## git fetch
```
git fetch new_name //抓取仓库有的本地没有的内容
```

## git下的origin 


## git push origin master
```
git push origin master //推送远程仓库
git push -u origin master //设置为默认推送远程仓库分支，后续直接使用git push 
```
