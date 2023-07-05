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

![image[(https://github.com/feiyun112/Test_github/blob/main/images/compare.jpg)

![image](https://github.com/feiyun112/Test_github/blob/main/images/merge.jpg)
