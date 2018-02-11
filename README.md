---
iOS代码自动化工具
---
一直以来都想写个自动化的工具，简化iOS开发，自动化脚本主要有以下几种方式：
``` bash
commandline
Xcode插件，苹果屏蔽了好多很好用的插件
图形化界面，做个图形化的界面点击生成代码
workflow，目前可以支持Python，Ruby，shell等，
```

## 项目地址
https://github.com/ZWXAllen/automation.git

## 安装方式
``` bash
git clone https://github.com/ZWXAllen/automation.git
cd automation/project && sudo python setup.py develop
点击安装Services下的workflow
```


## 本文主要教workflow这种方式，一图胜千言， Let's start!
``` bash
新建一个workflow，选择命令行，然后选你喜欢的语言，这里我选的是Python，
位于选项选Xcode,表示可以在Xcode右键执行代码
输出内容替换文本选项则是选的文字会被脚本输出代替，
服务收到选项 选文本表示可以获取文字内容，选文件夹，文件则可以获取文件路径
保存后系统会在 ~/Library/Services 路径下生成workflow
```



