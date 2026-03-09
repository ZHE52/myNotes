### 如果是github的话，建议走ssh，以及第一次使用github需要弄秘钥，在设置中创建秘钥



### 第一次

git init

git branch -M main    //github专属

git config --global init.defaultBranch main     //一步到位的，上面一条不适用的话，我就用这条

git add 你要上传的文件
git commit -m "[项目描述](https://so.csdn.net/so/search?q=项目描述&spm=1001.2101.3001.7020)"(必做)
git remote add origin 你的仓库地址
git pull --rebase origin master（同步用的，第一次上传不需要）
git push -u origin master

### 第二次OR第N次

git add .

git commit -m "描述"

git push origin master 推送远程仓库

### 问题：

如果远程仓库（多人协作）冲突，现拉最新代码合并后再推送

```git pull origin master   # 拉取并合并远程修改 ```

```git push origin master    # 重新推送```

**强制推送**（谨慎使用）：仅在确认需覆盖远程历史时使用：

``` git push --force origin master         # 强制覆盖（高风险） git push --force-with-lease origin master  # 更安全的强制推送（推荐）```





### 强制上传

**适用场景**：远程仓库的旧代码不再需要，希望用本地重构后的代码完全覆盖远程仓库。

``` \# 1. 添加所有修改到暂存区 git add . ``` 

```# 2. 提交本地修改（建议添加清晰的重构描述） git commit -m "refactor: 项目架构重构，调整模块结构和依赖关系" ```

```# 3. 强制推送到远程仓库（覆盖原有提交） git push -f origin master```

git push -u origin master -f

### 查看上传历史

