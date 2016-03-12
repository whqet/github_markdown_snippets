# GitHub Markdown Snippets
非常实用的、利用**原生html标签方式**书写Markdown的Sublime Text代码段(Sublime Text Snippets)，本版本增加了*中文输入提示*，并且使用*md*前缀避免与原生html标签的*冲突*。

![](https://img.shields.io/badge/Version-2.0.1-brightgreen.svg)

## 安装

### 通过Package Control安装（英文版）
最简单的方式是通过[Package Control](https://packagecontrol.io/)安装。

- 打开**命令面板-Command Palette** <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> or <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
- 选择 **Package Control : Install Package**
- 搜索 **Github Markdown Snippets**

### 手动安装

- 克隆本库或者下载[ZIP](https://github.com/whqet/github_markdown_snippets/archive/2.0.1.zip)
- 解压缩到**包文件夹-Packages**( `Preferences > Browse Packages...` )  

## 使用
这里有个简单教程 [here](http://praveenpuglia.github.io/github_markdown_snippets). 

输入md+标签名，然后tab键即可，简单吧。:relaxed:

:snowflake: 类似于`blockquote`的长标签可以使用简写。

## 简写列表

```
mdh1     // Heading 1
mdh2     // Heading 2
mdh3     // Heading 3
mdh4     // Heading 4
mdh5     // Heading 5
mdh6     // Heading 6
```
# 一号标题  
## 二号标题  
### 三号标题  
#### 四号标题  
##### 五号标题
###### 六号标题
```
mdb         // Bold
mdi         // Italic
mdbq        // Blockquote
mdstrike    // Strikeout
mdhr        // Horizontal Rule, Divider
```
**粗体文字** 

*斜体文字* 

> 引用文字
> 继续...

~~删除线文字~~ 

---

```
mdcode    // Inline Code
mdpre     // Code Block with language based highlighting.
```
`单行代码`

```javascript
var message = "Code Block";
alert( message );
```

```
mda      // Anchor
mdimg    // Image
```
[链接文字](链接地址) 

![Github Logo](https://wasin.io/wp-content/uploads/2015/05/showimage.png) 

```
mdol       // Ordered List
mdul       // Unordered List
mdtable    // Table
```

1. 第一项
2. 第二项
3. 第三项


- 我
- 爱
- Markdown

| 表头 | 表头 |
| ------------- | ------------- |
| 单元格 | 单元格 |
| 单元格 | 单元格 |







  

