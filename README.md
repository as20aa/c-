# c++ & visual studio 2017
c++ IDE：visual  studio 2017的使用
## visual studio 2017的安装
* [安装链接](https://www.visualstudio.com/zh-hans/?rr=https%3A%2F%2Fwww.bing.com%2F)
* [在visual studio 2017上编写c++代码并调试](https://docs.microsoft.com/zh-cn/cpp/build/vscpp-step-1-create)
## c++编程调试tips
* 在调试中可能会遇到没有插入断点就进入调试，程序界面一闪而过的情况，可以加入语句
```c++
system("pasuse");
```
  作为替代品，也可以在发布时让人看到运行结果并确认
# visual studio 2017中使用github进行版本控制和发布
[安装visual studio 2017的github工具包](https://visualstudio.github.com/)    
[友情链接](https://github.com/github/VisualStudio)    
[如何使用](https://services.github.com/on-demand/windows/visual-studio)
# 如何将已经完成的项目上传到github
* 打开visual studio 2017，打开相应的项目文件
* 点击右侧的团队资源管理
* 点击github的publish按钮
* 按照提示填写介绍，点击pull按钮
* 等待上传同步完成
## 如何用现有的代码进行调试
* 首先新建一个空文件夹用于测试
* 将现有的cpp文件复制进去
* 在visual studio 中新建一个空项目在新建的文件夹
* 项目->添加现有项，加入刚才复制的cpp文件
* 点击生成->生成解决方案
* 点击调试->开始调试，即可开始调试刚才的cpp程序
