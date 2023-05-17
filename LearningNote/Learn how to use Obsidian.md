[教程视频](https://www.bilibili.com/video/BV1V34y1k7St/?spm_id_from=pageDriver&vd_source=ce8faff6947bfef0aa5b02e9f84edf43)

## What is Obsidian？
* 双链笔记，可以在知识点之间建立连接
* 免费
* 支持markdown
* 丰富的插件系统
* 核心插件与第三方插件
* 可引用模板
* 纯文本的优势，资料库可以完全本地化，为同步带来方便
* 方便对接一些支持markdown的网站

## The position of Obsidian
* 不是word
* 不是信息收集工具
* 是码字的工具
* 知识管理
	* 内容
	* 链接

## Application of Obsidian
* 写作
* 建立深度知识库
	* 关联知识点
	* 发现新知识

## Operation of Obsidian
* 实时预览是默认开启的
* 所有的资料基于资料库
* 切换资料库后设置的主题和插件就没了
* 插入本地图片直接复制黏贴插入

## 文件配置
* .obsidian里装的是设置配置文件
* plugins插件文件
* theme主题文件

## 界面
* 最左边的是功能面板
	* 第一个是快速切换，输入要查找的文章标题，可以设置快捷键
	* 第二个是关系图谱
	* 命令面板快速让ob执行命令，如改变深色浅色主题，设置的快捷键是`Crtl + ,`
	* 切换资料库.
* 然后是管理文件的区域
* 中间是工作区
* 最右边是链接面板

## Markdown in Obsidian[^注释]

**加粗**
*斜体*
~~删除线~~

编号
1. 数字加句点空格
	1. 缩进
2. 自动编号

* 星号
* tab缩进控制下一级

>引用

代码块，可以加上语言让语法高亮
```python
import pandas as pd
import numpy as np

df = pd.DateFrame()
```

- [ ] 任务列表
- [ ] 
- [x] 方框中间在加上x就是完成事项



[^注释]: [Cmd Markdown 编辑阅读器](https://www.zybuluo.com/mdeditor)

## 链接
* 入链
* 出链

通过链接可以复习一些名词解释。
比如这里我链接了一篇文章，是latex的公式表
[[Latex]]。
在编辑模式下将鼠标悬停按下Ctrl键就可以看到这篇文章，如果是阅读模式，只需要将鼠标悬停就能看到文章内容。
接下来我在这里展示的是这篇文章的一个标题下的内容[[Latex#根号[ ](https://www.cnblogs.com/1024th/p/11623258.html 648600159)]]。同样的这样就可以使得文章中这一部分被展示出来。也可以表示一个段落块[[Latex#^2c6cc2]]。这个块会由obsidian自动生成一个代码以便于链接。这个代码是不能被修改的。可以为这个链接取个别名，比如[[Latex#投射[ ](https://www.cnblogs.com/1024th/p/11623258.html 1152632293)|Latex投射]]。可以在括号前再加一个感叹号这样连接的内容就会被直接展示出来![[Latex#投射[ ](https://www.cnblogs.com/1024th/p/11623258.html 1152632293)|Latex投射]]设置里需要开启预览。

## 模板
设置模板文件夹，装进去模板的文件，每次直接插入模板就可以了。

## Plugins
Community Plugins

## 查询和搜索
* 对于当前文档的搜索`Ctrl + F`
* 对于整个资料库的搜索`Ctrl/Cmd + Shift + F`
* 指定搜索范围
	* 搜索文件按名file: word
	* 搜索文本内容 content: word，或者什么都不加
	* 搜索标签tag: #tage: word
	* 搜索同一行中的多个关键字 line: word1, word2
	* 搜索同章节的多个关键词 section: word1, word2
* 保存查询结果
	* 代码query```

```query
导数
```

