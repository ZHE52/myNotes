## 下载

git clone 目标链接既可以了



## 上传

### 第一次上传

第一步，初始化项目

在项目文件根目录中右键gitbash

```
git init
```

第二步，没懂

```
git add .   （注意这里有个点）
```

说明：

```
 git commit -m '本次提交的说明'（说明信息为必填项，最好是信息有意义，便于后期理解）
```

第三步：复制仓库链接

https://gitee.com/kakaluotede/notebook.git

https://gitee.com/kakaluotede/note-book.git

https://gitee.com/kakaluotede/note-test4.git

第四步，将本地和仓库绑定

```
git remote add origin https://gitee.com/kakaluotede/note-test4.git
```

如果有问题

git remote rm origin

第五步，将本地上传到远程仓库

```
git push -u origin master
```

git push origin master

git push https://gitee.com/kakaluotede/notebook.git master



$ git branch -r



### 第二次或者第三次上传

git add .

git commit -m "随便写点东西，表示本次上传了什么，做了什么更新之类的"

git push origin master

### 帖子

1、git status 查看当前有变更的代码文件
2、git add . 你本地所有修改了的文件添加到暂存区。
3、git commit -m “xxxxx” 引号里面是你的介绍，就是你的这次的提交是什么内容，便于你以后查看，这个是将索引的当前内容与描述更改的用户和日志消息一起存储在新的提交中。
4、git pull origin master(不知道干啥的，不用也可以) 这是同步代码，将远程最新的代码先跟你本地的代码合并一下，如果确定远程没有更新，可以不用这个，最好是每次都执行以下，完成之后打开代码查看有没有冲突，并解决，如果有冲突解决完成以后再次执行2跟3的操作。这里master可以是其他分支名字。 注：如果解决冲突后，需再次执行步骤2和3。
5、git push origin master 将代码推至远程就可以了。这里master可以是其他分支名字。
————————————————

                            本文是秋枫 ~原创文章，转载请附上博文链接！

原文链接：https://blog.csdn.net/weixin_43472938/article/details/129206402

