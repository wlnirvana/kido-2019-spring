# 第十五周作业

- [第十五周作业](#%E7%AC%AC%E5%8D%81%E4%BA%94%E5%91%A8%E4%BD%9C%E4%B8%9A)
  - [Github和单元测试](#github%E5%92%8C%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95)
  - [搜索题](#%E6%90%9C%E7%B4%A2%E9%A2%98)
  - [在线编程挑战](#%E5%9C%A8%E7%BA%BF%E7%BC%96%E7%A8%8B%E6%8C%91%E6%88%98)

## Github和单元测试

上周为大家演示了公司内部常见的测试流程。本周的作业，你需要转变身份，成为测试工程师。

想象在一个公司里面，经过反复讨论，你们已经商量好了要做哪些功能。现在功能的开发交由另外的团队完成，你则需要对这些功能进行测试——同样是以代码的形式。

（事实上，在现实当中，一些公司甚至会要求先写出测试，然后才开始进行功能的开发。）

在本练习中，你需要fork一份原始代码，下载下来，做出改动，并申请将自己的改动合并进原始代码。

1. 从学堂账户fork本周作业的代码仓库，网址是https://github.com/practischool/git-unittest
2. 将自己账户的代码仓库clone到本地
3. 在IntelliJ里面打开这个项目
4. 在IntelliJ窗口的右上角，找到三个绿色的符号：锤子、运行、Debug
5. 在锤子和播放键中间的下拉菜单里面，选择`App`
6. 点击运行键，可以看到程序运行了`App.java`里面的`main`函数，输出了`Hello World!`
7. 在锤子和播放键中间的下拉菜单里面，选择`unittest(单元测试)`
8. 点击运行键，可以看到程序运行了单元测试，并打印了大量错误信息Error。
9. （可选）在命令行（即终端terminal）里面，用`cd`命令进入项目的文件夹。
10. （可选）如果你的电脑安装了`maven`（所有Linux电脑应该都装了），现在执行`mvn test`，即可看到跟第8步一样的错误信息，但是是彩色的。
11. 浏览`src/main/java/org/practischool/App.java`文件，可看到相关功能已经由另一个团队完成。
12. 注意！！！第13步需要大家合作完成，每人只修改其中的2-3个函数即可。
13. 修改测试文件`src/test/java/org/practischool/AppTest.java`，使得第8或第10步（你所负责的函数）的错误信息不再产生。
14. commit
15. push
16. 通过pull request申请合并

## 搜索题

上周艺文提了一个好问题：Java代码能不能像HTML、CSS那样，跑在Github上？

简单地说，不能。

那么，在互联网公司里面，Java代码到底跑在哪里呢？请你自己查资料，搞清楚这个问题。

## 在线编程挑战

[五子棋][1]

[1]:https://vijos.org/d/kidolab_2019_Spring/homework/5cff9a49f4136234c8c28bcc