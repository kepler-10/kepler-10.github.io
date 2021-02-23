## this is news notebook for February

**Happy Lunar New Year**

### git 命令

#### 1.how to change git remote url ?

使用命令：git remote set-url origin https://github.com/kepler-10/kepler-10.github.io

#### 2.本地创建新分支并push到远程

```xml
查看分支：git branch -a

1.本地创建新分支
git branch -c `branch-name`
2.将本地分支push到远程，并建立远程分支
git push -u origin `branch-name` 
3.远程更新文件
先 git checkout `branch-name` 
再进行push 操作
```

