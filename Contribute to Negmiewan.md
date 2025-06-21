# Git-Github 入门级使用教程 \[Negmiewan适用版\]
by Elainex
## 1. 编写初衷
本教程主要用于Negmiewan项目的后续完善（这个项目名其实有点草率...），共同完善手册以供入门小白查阅快速上手CFD。

对刚接触新领域、新软件的小白而言，学习通常需要很大的沉没成本，而且缺乏**一份可以快速解答常见问题的材料**。本项目的编写初衷，正是编写一份较为完善的入门资料（以供组内查阅）。

对于刚刚接触命令行操作和服务器任务提交的小白来说，**基础的命令会相对琐碎**，而且相当一部分不太能用到，学习效率就会差很多。而对于软件来讲，**for beginners，掌握一些基础功能便足以应对日常科研工作中的应用需求**，进阶功能完全可以在熟练使用基础功能后进一步拓展和掌握而非系统性学习；另一方面，**大部头的user-guide（尤其是全英文的）对于初学者来说并不够友好**，即便自学也需要一定的门槛，尤其是程序的运行流程、组成成分有一定掌握。这就使得这样一份资料的编写势在必行。

鉴于每人的研究方向、使用的语言软件都各有差异，本项目希望尽可能将不同内容涵盖进来；即便是对Linux系统、各类软件、服务器都刚刚接触的小白，也能够利用这样一份指导性的手册快速上手，正是我们所希望的。

当然，也欢迎组内的兄弟姐妹以及业内同行朋友们参与到本项目的编纂中，万分感谢！

---
## 2. 贡献内容
Git-Github使用的保姆级教程可以参考：[![BiliBili](https://img.shields.io/badge/BiliBili-f0f8ff?style=flat&logo=bilibili&logoColor=007af9)](https://www.bilibili.com/video/BV1s3411g7PS/?spm_id_from=333.337.search-card.all.click&vd_source=60e0926731e3d7d6f750b7e07be7b721)

以下简要介绍下参与到本项目的基本流程：（本地编写提交建议使用VSCode完成）
- 1. 在Github的Negmiewan项目的Repository中点击右上角的 [fork](https://github.com/Elainex0930/Negmiewan/fork)
- 2. 在打开的界面创建自己的branch，名称可以为Negmiewan-xxxx（自定义即可）
- 3. 在VSCode中打开一个用于该项目的文件夹，执行以下命令将自己账号下的branch克隆到本地：
~~~
git clone https://github.com/xxxxx/Negmiewan-xxxx.git
~~~
命令中的项目地址为自身账号内的branch地址，可以在自己对应repo页面下右上角的`<> code` 标识下进行复制。
克隆失败可能是网络原因，可以将梯子的终端代理命令复制到VSCode的Http: Proxy Kerberos Service Principal配置。
- 4. 利用以下命令检查是否添加了Negmiewan的原项目作为上游项目。
~~~
git remote -v
~~~
如果结果并未显示upstream来源，运行以下命令：
~~~
git remote add upstream https://github.com/Elainex0930/Negmiewan.git
~~~
- 5. 运行以下命令创建自己的分支
~~~
git checkout -b XDorz
~~~
`XDorz`是自己的分支名，可以自定义，也可以是自己的用户名。
- 6. 本地完成编写等操作。
- 7. 利用以下命令在命令行上传推送(提交内容根据实际修改情况自定义)。
~~~
git add .
git commit -m "modify(Chpt 8): an error of xxx corrected."
git push -u origin XDorz
~~~
- 8. 从本人项目的[Pull requests](https://github.com/Elainex0930/Negmiewan/pulls)选择本人项目主分支与你自己创建的`XDorz`分支比对合并（Create PR）。
---
## 3. 内容反馈
由于各种原因，项目中难免会有错误，还望批评指正！

本项目的交流群见本人主页！！再次感谢！！
