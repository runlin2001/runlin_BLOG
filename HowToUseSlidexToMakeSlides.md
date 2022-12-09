# 使用slidex来制作演示文稿

- [使用slidex来制作演示文稿](#使用slidex来制作演示文稿)
  - [使用方法](#使用方法)
  - [编辑方法](#编辑方法)
    - [方法一](#方法一)
    - [方法二](#方法二)
  - [导出pdf](#导出pdf)


## 使用方法
在slidex安装的目录（slidex）下用命令提示符窗口使用命令。
```
$ slidex
```
按照上面的指示，**open**即可打开默认浏览器，此时展示的是文件夹目录下的slides.md文件。

## 编辑方法
### 方法一
在slidex安装的目录（slidex）下使用命令提示符打开。输入：
```
$ slidex
```
按照上面的指示，**edit**即可打开编译器，找到文件夹目录下的slides.md文件进行编辑。  
使用的语法是Markdown。
### 方法二
直接打开slides.md进行编辑。
- 注意，如果是VScode + slidex插件的情况下，还需要在新建终端在里面使用```$ slidex```命令。否则无法实现preview窗口的功能。

## 导出pdf
与使用和导入的方法相同，在slidex安装的目录（slidex）下用命令提示符窗口使用命令。
```
$ slidex export
```
此外，还有dark mode可以选择。另外还有其他的mode详细可以在slidex在github的网站去了解
```
$ slidex export --dark
```
