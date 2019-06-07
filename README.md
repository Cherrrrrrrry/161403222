# 161403222陈皓月
161403222陈皓月实验报告
一、实验目的
  1、了解Linux编程环境；
  2、掌握在Linux环境下编程的常用工具，例如：shell,vim,make,gedit,git及各种语言的集成开发环境；
  3、了解Linux系统的内存、进程、线程、同步、通信的基本原理和其在实际程序中的应用；
  4、掌握Linux环境下的应用程序设计、开发和项目管理；
  5、通过16学时的实验，在Linux环境下设计并实现一个代码量不小于2000的项目。
二、实验环境
  Linux编程环境。
三、实验步骤
  1、确定项目方案及编程语言。项目方案：开发一个“沈阳大学生家教平台”微信小程序。编程语言：JavaScript语言。
  2、搭建环境。安装Linux系统，并在Linux系统下安装微信开发者程序，安装wine。
  3、模块设计。主要分为“首页”、“我要找老师”、“我要当家教”三个大模块。其中，“首页”又包括“科目选择”、“名师在校”、“家教头条”三个小模块；在“我要找老师”模块可以显示几位老师的家教信息；在“我要当家教”模块可以看到学生信息。
  4、编程实现。写入代码并导入相应的图片以实现该微信小程序。
  5、调试运行。
四、实验内容
  1、搭建环境。
  （1）安装Linux系统。
  （2）安装wine。
      在终端输入命令：sudo apt-get install wine 或者在“Ubuntu软件”中搜索“wine”以安装wine。
  （3）安装nwjs-sdk。
      下载linux版nwjs-sdk：wget https://dl.nwjs.io/v0.25.4/nwjs-sdk-v0.25.4-linux-x64.tar.gz 或在页面中直接下载。
  （4）解压nwjs-sdk。
      安装好nwjs-sdk压缩包后选择文件夹提取或输入命令tar xvf  nwjs-sdk-v0.25.4-linux-x64.tar.gz以解压。
  （5）进入nwjs-sdk对应的目录。
      cd nwjs-sdk-v0.25.4-linux-x64。
  （6）启动nwjs-sdk，若能够正常运行则关闭，不能的话检查上述步骤。
      ./nw。
  （7）基于nwjs-sdk安装微信开发工具包。
      获取微信开发工具包：输入命令git clone https://github.com/cytle/wechat_web_devtools.git 或直接在页面中下载。
      进入wechat_web_devtools目录：cd wechat_web_devtools。
      复制微信开发工具包（package.nw在wechat_web_devtools目录下）到nwjs-sdk目录下:输入命令cp package.nw ~/development/nwjs-sdk-v0.25.4-linux-x64/ -rf  或者直接拷贝粘贴过去。
  （8）启动。
      ./nw。
  附部分截图：
  
  
