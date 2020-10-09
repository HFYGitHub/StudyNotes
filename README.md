# 学习笔记
## 这里会记录再学习过程中的各种问题
## 随缘更新~~~


## 一，GitHub文件上传命令
### 1.git init初始化仓库
### 2.git add ./文件路径 添加文件或添加指定文件
### 3.git commit -m “提交信息” 对每一次提交进行记录 （可选，修改tag版本号）
### 4.git remote add origin XXX.git关联GitHub仓库
### 5.git push -u origin mastert 确认上传提交 
### 错误解决
#### 1.git remote rm origin
#### 偶尔会遇到报错src refspec master does not match any  更换一个名字即可

## 二，GitHub文件更新
### 1.git status 查看更新状态
### 2.git add . 添加文件
### 3.git commit -m "更新信息" 记录更新信息
### 4.git remote add origin XXX.git 关联GitHub仓库
### 5.git push origin HEAD:master 上传
