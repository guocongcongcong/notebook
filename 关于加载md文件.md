# 关于VsCode上加载.md

## 目录

<!-- TOC -->

- [关于VsCode上加载.md](#%E5%85%B3%E4%BA%8Evscode%E4%B8%8A%E5%8A%A0%E8%BD%BDmd)
    - [目录](#%E7%9B%AE%E5%BD%95)
    - [笔记本](#%E7%AC%94%E8%AE%B0%E6%9C%AC)
    - [Markdown Preview Enhanced](#markdown-preview-enhanced)
        - [加载](#%E5%8A%A0%E8%BD%BD)
        - [使用](#%E4%BD%BF%E7%94%A8)
        - [效果展示](#%E6%95%88%E6%9E%9C%E5%B1%95%E7%A4%BA)
    - [Markdown TOC](#markdown-toc)
        - [加载](#%E5%8A%A0%E8%BD%BD-1)
        - [使用](#%E4%BD%BF%E7%94%A8-1)
        - [效果展示](#%E6%95%88%E6%9E%9C%E5%B1%95%E7%A4%BA-1)
        - [bug：VSCode中Markdown目录显示异常](#bugvscode%E4%B8%ADmarkdown%E7%9B%AE%E5%BD%95%E6%98%BE%E7%A4%BA%E5%BC%82%E5%B8%B8)
    - [VSCode上md文件语法](#vscode%E4%B8%8Amd%E6%96%87%E4%BB%B6%E8%AF%AD%E6%B3%95)

<!-- /TOC -->


## 笔记本

这是我在github上写的一个小脚本，如果你用的是windows系统，并且和我一样喜欢记录东西的话，类似于写日记那样，那么你可以尝试一下[笔记本](https://github.com/guocongcongcong/notebook/tree/master)，我个人觉得挺好用的。具体说明：

>https://github.com/guocongcongcong/notebook/tree/master

## Markdown Preview Enhanced

这个插件是用来组织显示md文件的显示的，使用过的pdf的排版，使用起来比vscode自带的看起来更舒服。

### 加载
加载方法，在右侧扩展中输入即可。
![加载](https://img-blog.csdnimg.cn/2018112917105517.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)

### 使用
在.md页面点击右上角的这个图标
![在这里插入图片描述](https://img-blog.csdnimg.cn/201811291713356.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
### 效果展示
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129171301588.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)

## Markdown TOC

这个是做目录的，我想在文件中添加目录，手动也可以做，但是自己做就太麻烦了，这个插件可以很好的完成这个功能。

### 加载
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129171634109.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)

### 使用
重启加载完成后，在.md文件上右键单击，点击：Markdown TOC：insert/update 就可以了。该插件会在点击的地方生成一个目录。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129171716881.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
### 效果展示
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129171945638.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)

> 每次你修改目录并保存后都会更新目录
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129172100626.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)

### bug：VSCode中Markdown目录显示异常
有的时候用着用着你就会发现，生成的目录出现问题了。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129172208542.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
这个显示就不是很美了，所以我们可以修改vscode的配置来完成修复
![在这里插入图片描述](https://img-blog.csdnimg.cn/2018112917233243.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
点击左下角的小齿轮，设置，输入Eol，默认行位字符为：/n
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129172435583.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
完成后关闭setting，重建加载目录，完美解决
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181129172630452.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2RvdWJsZV9kZWJ1Zw==,size_16,color_FFFFFF,t_70)
## VSCode上md文件语法

- 一级无序列表
  - 两个空格 后是二级列表
  >引用块的使用
  - 单行代码的使用时使用反引号包裹比如：`jscode`
- 表格
1. 有序列表
2. 有序列别

|表头1 |表头2
--------|------
列1     |  列2

| name | age | sex |
|:----:|:----:|:----:|
|tony |20|男|
|lucy|21|女|

学号|姓名|分数
-|-|-|
12|小明|78
14|小红|79
13|小绿|80

- 强调 _字体倾斜_ *字体倾斜* **加粗** __加粗__
- 转义 \\ \` \~ \_ \- \+ \. \!
- ~~删除线~~
```md
- 一级无序列表
  - 两个空格 后是二级列表
  >引用块的使用
  - 单行代码的使用时使用反引号包裹比如：`jscode`
- 表格
1. 有序列表
2. 有序列别

|表头1 |表头2
--------|------
列1     |  列2

| name | age | sex |
|:----:|:----:|:----:|
|tony |20|男|
|lucy|21|女|

学号|姓名|分数
-|-|-|
12|小明|78
14|小红|79
13|小绿|80

- 强调 _字体倾斜_ *字体倾斜* **加粗** __加粗__
- 转义 \\ \` \~ \_ \- \+ \. \!
- ~~删除线~~
```

空格的使用：&nbsp; &nbsp;

内部链接:[内部链接]

外部链接:[外部链接]

[另一种方法](https://i.csdn.net/#/uc/profile)

---
[内部链接]:##md的使用
[外部链接]:./2018·8·2.md/###Date

```md
空格的使用：&nbsp; &nbsp;

内部链接:[内部链接]

外部链接:[外部链接]

---
[内部链接]:##md的使用
[外部链接]:./2018·8·2.md/###Date
```
Email 链接
【语法】直接<邮箱号地址>即可
【示例】作者的 email 链接.

qq邮箱:<double_debug@qq.com>

    double_debug

```md
[地址](https://www.jianshu.com/p/86e7fa33de8e)

Email 链接
【语法】直接<邮箱号地址>即可
【示例】作者的 email 链接.

qq邮箱:<double_debug@qq.com>

    double_debug
```


