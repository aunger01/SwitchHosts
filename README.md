# SwitchHosts!

 - Author: oldj
 - Email: oldj.wu@gmail.com
 - Blog: http://oldj.net/
 - Source: https://github.com/oldj/SwitchHosts
 - Homepage: https://oldj.github.io/SwitchHosts/


这是一个用于快速切换 hosts 文件的小程序，基于 [MacGap](http://macgapproject.github.io) 开发，同时使用了 [Vue.js](http://vuejs.org/) 以及 [CodeMirror](http://codemirror.net/) 等框架/库。


## 功能特性：

 - 快速切换 hosts
 - hosts 文件语法高亮


## 下载地址：

你可以直接下载源码到本地运行或编辑，或者在下面下载可执行版本：

 - [SwitchHosts! 下载地址1](https://github.com/oldj/SwitchHosts/releases)
 - [SwitchHosts! 下载地址2](http://pan.baidu.com/share/link?shareid=150951&uk=3607385901)



## 更新历史：

### v3.1

 - 2015-12-20 从 Electron 切换至 MacGap 。

### v3.0
    
 - 2015-11-30 完成 3.0 版基本功能。
 
### v2.0
 
 - 2013-02-06 解决 Linux/Mac 下没有修改系统 hosts 文件权限的问题。
 - 2012-12-27 启动时检查是否为单一实例，禁止同时运行多个实例。
 - 2012-11-16 接受 @charlestang 网友的 pull request，同时参考了 @allenm 的修改，实现了 Common Hosts 功能。
 - 2012-11-09 简单优化：Common Hosts 不允许删除，不允许“切换到”，将右键菜单相关条目禁用，允许更换图标颜色。修复新增在线方案时，url 框默认禁用的小 bug。
 - 2012-10-09 增加 hosts 方案拖拽排序功能。
 - 2012-10-05 修复在中文目录下程序无法正常启动的问题。
 - 2012-09-30 初步完成 0.2.0 版。
 
### v1.0

 - 2011-12-14 允许输入超长的 hosts 方案。
 - 2011-10-09 发布 0.1.6 版，修复若干 bug，增加自动检查最新版本的功能。
 - 2011-09-29 发布 0.1.5 版，新增 hosts 内容语法高亮。
 - 2011-09-28 发布 0.1.4 版，新增“添加”、“删除”按钮；hosts 内容修改后自动保存；修复若干 bug。
 - 2011-09-19 发布 0.1.3 版，修复若干 bug。
 - 2011-09-15 发布 0.1.2 版，添加主面板，可以在主面板上对 hosts 进行增加、删除、编辑、重命名等操作。
 - 2011-09-02 发布 0.1.0 版，完成基本功能。



## 打包方法

请参考 [MacGap 文档](http://docs.macgap.com/)。


## 版权

本程序完全免费，并基于 MIT 协议开源。