# Test_github
This repository will  be used study github
这是一个学习github的日志仓库，在这里可以看到学习的整个过程。
这只是开始，接下来还会有别的仓库记录别的语言的学习。

第一步：建立仓库并建立新的分支，并提交创建的内容
===============================================
  1，在仓库页面的右上角点击New即可进入创建新的仓库的页面，如下图
  --------------------------------------------------------------
![image](https://github.com/feiyun112/Test_github/blob/main/images/%E4%BB%93%E5%BA%93.jpg)
  
  2，创建分支：
  --------
  分支是某一时刻对同一个仓库（我感觉说是项目更加适合）在不同版本上进入工作的方法。在默认情况下，你的仓库有一个名为**master**的分支，它被公认为主分支。我们使用分支进行工作，然后再将其提交到**master**上。

当你从**master**中创建一个分支时，也可以说，你正在制作一个副本，或者快照，就像在那个时间点的**master**一样。当你在你的分支上工作的时候，如果其他人对你的**master**分支进行了修改，你可以**Pull**这些更新。
下面展示了：
![image](https://github.com/feiyun112/Test_github/blob/main/images/feature.jpg)

进入仓库，点击顶部名为master，在find/create feature中创建一个新的分支，点击下面的create branch.....

![image](https://github.com/feiyun112/Test_github/blob/main/images/%E5%88%86%E6%94%AF.jpg)

3，编辑并提交创建的内容（此次是在分支上创建并提交）
--------------------------------------------------
现在，你的代码视图中已经有funs分支了，她是master分支的一个副本。下面，我们对她做一些编辑。

在 GitHub 上，保存修改被称之为commit，即提交。每次提交都有一个相关的提交消息，用来说明为什么进行特定的修改。提交消息保存了你修改的历史，因此其他贡献者能够通过“提交信息”了解你做了什么修改和为什么这么做。

***编辑和提交修改内容：***

点击`readme.md`文件；
单击文件视图右上角的铅笔图标进行编辑；
在编辑器中，写一点关于你自己的东西；
写一个提交消息，描述你的修改；
单击`Commit changes`按钮。
**这里修改的仅仅是分支上的readme.md，和master中的不一样了。**

4，提出pull请求
---------------
编辑的很好！现在你已经有了一个与master内容不同的分支了，接下来，可以提出 Pull 请求啦！

Pull 请求是 GitHub 协同工作的核心。当你提出一个 Pull 请求的时候，你就已经默认允许其他人审查和合并你贡献的代码到他们的分支啦！Pull 请求展示了两个分支内容上的差异。这些修改，添加和删除的内容将分别用绿色和红色标记出来。

只要你提交过修改的内容，你就可以提出 Pull 请求，同时开启一个讨论，甚至在你的代码完成之前你就可以提出 Pull 请求。

在你 Pull 请求的“请求信息”中，通过使用 GitHub 的@mention system，你可以向特定的人或团队反馈问题，无论他们在你身边还是在 10 个时区之外。

你也可以在自己的仓库中提出 Pull 请求，并将其合并。在开发大型项目之前，这是学习 GitHub Flow 非常好的方法。

当你完成你的信息之后，点击Create pull request！（即点击顶部的pull requests)

5，合并你的pull请求
-------------------
在这最后一步中，是时候将你在funs分支中的修改一起合并到master分支即主分支中啦！

单击绿色Merge pull request按钮将修改的内容合并到master分支；
单击Confirm merge按钮；
删除该分支，因为它修改的内容已经合并了，在“紫色”框中点击Delete branch按钮。

![image](https://github.com/feiyun112/Test_github/blob/main/images/pull%E2%80%94%E2%80%94requests.jpg)

![image](https://github.com/feiyun112/Test_github/blob/main/images/compare.jpg)

![image](https://github.com/feiyun112/Test_github/blob/main/images/merge.jpg)

## github常用的专业术语
**Repository**：简称Repo，可以理解为“仓库”，我们的项目就存放在仓库之中。也就是说，如果我们想要建立项目，就得先建立仓库；有多个项目，就建立多个仓库。

**Issues**：可以理解为“问题”，举一个简单的例子，如果我们开源一个项目，如果别人看了我们的项目，并且发现了bug，或者感觉那个地方有待改进，他就可以给我们提出Issue，等我们把Issues解决之后，就可以把这些Issues关闭；反之，我们也可以给他人提出Issue。

**Star**：可以理解为“点赞”，当我们感觉某一个项目做的比较好之后，就可以为这个项目点赞，而且我们点赞过的项目，都会保存到我们的Star之中，方便我们随时查看。在 GitHub 之中，如果一个项目的点星数能够超百，那么说明这个项目已经很不错了。

**Fork**：可以理解为“拉分支”，如果我们对某一个项目比较感兴趣，并且想在此基础之上开发新的功能，这时我们就可以Fork这个项目，这表示复制一个完成相同的项目到我们的 GitHub 账号之中，而且独立于原项目。之后，我们就可以在自己复制的项目中进行开发了。

**Pull Request**：可以理解为“提交请求”，此功能是建立在Fork之上的，如果我们Fork了一个项目，对其进行了修改，而且感觉修改的还不错，我们就可以对原项目的拥有者提出一个Pull请求，等其对我们的请求审核，并且通过审核之后，就可以把我们修改过的内容合并到原项目之中，这时我们就成了该项目的贡献者。

**Merge**：可以理解为“合并”，如果别人Fork了我们的项目，对其进行了修改，并且提出了Pull请求，这时我们就可以对这个Pull请求进行审核。如果这个Pull请求的内容满足我们的要求，并且跟我们原有的项目没有冲突的话，就可以将其合并到我们的项目之中。当然，是否进行合并，由我们决定。

**Watch**：可以理解为“观察”，如果我们Watch了一个项目，之后，如果这个项目有了任何更新，我们都会在第一时候收到该项目的更新通知。

**Gist**：如果我们没有项目可以开源或者只是单纯的想分享一些代码片段的话，我们就可以选择Gist。不过说心里话，如果不翻墙的话，Gist并不好用


# 第二步：Git与Github之间的交互

## 1，Git与Github之间进行绑定

**生成ssh key** 

命令：***ssh-keygen -t rsa***

将公钥填写到github中的ssh and GPG keys中：公钥id_rsa.pub

**验证是否绑定**

命令：***ssh -T git@github.com****

## 2,通过Git将代码提交到Github
有两种方式：
**第一种**：本地没有 Git 仓库，这时我们就可以直接将远程仓库clone到本地。通过clone命令创建的本地仓库，其本身就是一个 Git 仓库了，不用我们再进行init初始化操作啦，而且自动关联远程仓库。我们只需要在这个仓库进行修改或者添加等操作，然后git add *** &git commit -m"****" 即可。然后git push origin master(main)即可。

**第二种**：本地有 Git 仓库，并且我们已经进行了多次commit操作。先建立一个仓库，然后git init 初始化，再git remote add origin https://github.com/guobinhit/springmvc-tutorial.git命令,关联远程仓库（在此，默认大家都知道如何获取远程仓库的地址），其中origin为远程仓库的名字,
输入git pull origin master命令，同步远程仓库和本地仓库,再在本地仓库中进行增加，删除等的操作，然后git add ***,git commit -m"****",再输入git push origin master命令，将本地仓库修改（或者添加）的内容提交到远程仓库：

注：本地仓库和远程仓库的名字可以随意取。

