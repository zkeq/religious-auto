## 河南省宗教自动答题脚本，可自定义时间
#### (未填正确选项,需自行修改!!)
生成题库的项目 : [python提取题库信息自动化脚本](https://github.com/zkeq/religious-auto_data-py)
(自己写的  [题库不大正确,大概90分到95分差不多][没得过80多分,也没超过多95分)

![GIF](https://edu-image.nosdn.127.net/D97468EE8EBE2D04A09C4B76A3F55FE6.gif)

## 本仓库使用方法:

1.下载并解压本仓库到本地

2.本仓库的题库未填正确选项,需要自行修改

3.将题目的答案填入 [extension/js/data.js](/extension/js/data.js) 中的 **answer**中,
  -  (大写字母ABCD) , 
  -  判断题则为正确为A,错误为B. 
  -  多选题不同字母之间**不用**隔任何字符

3.安装脚本,开始使用
  - (在chrome扩展窗口选择安装已经解压的插件,选择**extension**目录即可)

-------------
-------------
原作者概述:

> 作者：tanyiqu，也就是本人自己
>
> 软件是一个浏览器扩展，安装后点击图标即可使用
> 
> 
> 
> 项目地址：https://github.com/tanyiqu/religious-auto
> 
> 下载：https://github.com/tanyiqu/religious-auto/releases
> 
> 太慢了的话，用网盘链接：https://tanyiqu.lanzoui.com/b0cqofvfe
> 
> **一定对你有用的，请给我的项目点个star**
>
> **仅做学习用途**
> 
> 思路：
> 
> - 使用浏览器扩展方式
> - 注入jquery.js
> - 注入script.js脚本
> - 在script.js中，遍历已有的题库，使用jquery在页面中获取这道题。如果有这道题就把答案选中，没有这道题就跳过
> - 最后点击交卷的时候，系统会自动查找哪道题没有做，最后再做了就行
