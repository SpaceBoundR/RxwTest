### git账户配置
```
git config --global user.name "Your Name"
git config --global user.email "email@examle.com"
```
> **--global** 全局配置

### 创建版本库
```
git init
```

### 把文件添加到版本库
```
git add readme.txt
git commit -m "wrote a readme file"
```
> **-m** 本次提交的说明
可以add多个文件，一次性commit

### 查看当前版本库状态
```
git status
```

### 查看文件修改内容
```
git diff readme.txt 
```

### 查看文件工作区和版本库中区别
```
git diff HEAD -- readme.txt
```


### 查看提交历史
```
git log
git log --pretty=oneline
```

> **--pretty=oneline** 精简历史信息

### 退回到以前的版本
```
git reset --hard HEAD~1
```
> **HEAD~1** 退回到上1个版本

### 退回到指定的版本
```
git reset --hard 1094adb
```
> **1094adb** 指定的版本号

### 查看命令历史
```
git relog
```