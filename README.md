# 欢迎使用 Markdown在线编辑器 MdEditor

**Markdown是一种轻量级的 「标记语言」**

![markdown](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png "Pandao editor.md")


Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。它允许人们使用易读易写的纯文本格式编写文档，然后转换成格式丰富的HTML页面，Markdown文件的后缀名便是".md"


## MdEditor是一个在线编辑Markdown文档的编辑器

*MdEditor扩展了Markdown的功能（如表格、脚注、内嵌HTML等等），以使让Markdown转换成更多的格式，和更丰富的展示效果，这些功能原始的Markdown尚不具备。*

> Markdown增强版中比较有名的有Markdown Extra、 MultiMarkdown、 Maruku等。这些衍生版本要么基于工具，如<s>Pandoc</s>, Pandao; 要么基于网站，如Github和Wikipedia，在语法上兼容，但在一些语法和渲染效果上有改动。

MdEditor源于Pandao的JavaScript开源项目，开源地址[Editor.md](https://github.com/pandao/editor.md "Editor.md")，并在MIT开源协议的许可范围内进行了优化，以适应广大用户群体的需求。向优秀的markdown开源编辑器原作者Pandao致敬。


![Pandao editor.md](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png "Pandao editor.md")



## MdEditor的功能列表展示

# 标题H1

## 标题H2

### 标题H3

#### 标题H4

##### 标题H5

###### 标题H6

### 字符效果和横线等
---

~~删除线~~  <s>删除线(开启识别HTML标签时)</s>

*斜体字*  _斜体字_

**粗体**  __粗体__

***粗斜体***  ___粗斜体___

下标 : X<sub>2</sub> ,  上标 : O<sup>2</sup>

**缩写(同HTML的abbr标签)**
> 即更长的单词或短语的缩写形式，前提是开启识别HTML标签时，已默认开启

The <abbr title="Hyper Text Markup Language">HTML</abbr> specification is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.
### 引用 Blockquotes

> 引用文本 Blockquotes

引用的行内混合 Blockquotes

> 引用：如果想要插入空白行`即<br />标签`，在插入处先键入两个以上的空格然后回车即可，[普通链接](https://www.mdeditor.com/)。

### 锚点与链接 Links
[普通链接](https://www.mdeditor.com/)

[普通链接带标题](https://www.mdeditor.com/ "普通链接带标题")

直接链接：<https://www.mdeditor.com>

[锚点链接][anchor-id]
[anchor-id]: https://www.mdeditor.com/

[mailto:test.test@gmail.com](mailto:test.test@gmail.com)

GFM a-tail link @panda

邮箱地址自动链接 test.test@gmail.com  www@vip.qq.com

> @pandao

### 多语言代码高亮 Codes

#### 行内代码 Inline code


执行命令：`npm install marked`

#### 缩进风格

即缩进四个空格，也做为实现类似`<pre>`预格式化文本(Preformatted Text)的功能。

     <?php
        echo "Hello world!";
     ?>
预格式化文本：

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

#### JS代码
```javascript
function test() {
    console.log("Hello world!");
}
```

#### HTML 代码 HTML codes
```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <meta name="keywords" content="Editor.md, Markdown, Editor" />
        <title>Hello world!</title>
        <style type="text/css">
            body{font-size:14px;color:#444;font-family: "Microsoft Yahei", Tahoma, "Hiragino Sans GB", Arial;background:#fff;}
            ul{list-style: none;}
            img{border:none;vertical-align: middle;}
        </style>
    </head>
    <body>
        <h1 class="text-xxl">Hello world!</h1>
        <p class="text-green">Plain text</p>
    </body>
</html>
```
### 图片 Images

图片加链接（Image + Link）

[![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png)](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png "markdown")

> Follow your heart.

---
### 列表 Lists

#### 无序列表 (减号) Unordered Lists (-)
 - 列表一
 - 列表二
 - 列表三
 
 #### 无序列表 (星号) Unordered Lists (+)
 
 * 列表一
 * 列表二
 * 列表三
 
 #### 无序列表 (加号和嵌套) Unordered Lists (+)
 + 列表一
 + 列表二
     + 列表二-1
     + 列表二-2
     + 列表二-3
 + 列表三
     * 列表一
     * 列表二
     * 列表三
     
 #### 有序列表 Ordered Lists (-)
 
 1. 第一行
 2. 第二行
 3. 第三行
 
 #### GFM task list
 
 - [x] GFM task list 1
 - [x] GFM task list 2
 - [ ] GFM task list 3
     - [ ] GFM task list 3-1
     - [ ] GFM task list 3-2
     - [ ] GFM task list 3-3
 - [ ] GFM taks list 4
     - [ ] GFM task list 4-1
     - [ ] GFM task list 4-2
     
 ----
 
 ### 绘制表格 Tables
 
 | 项目 | 价格 | 数量 |
 | :---: | :---: | :---: |
 | 计算机 | $1600 | 5 |
 | 手机 | $12 | 12 |
 | 管线 | $1 | 234 |
 
 First Header | Second Header 
 ------------ | -------------
 Content Cell | Content Cell
 Content Cell | Content Cell
 
| First Header | Second Header |
| ------------ | ------------- |
| Content Cell |  Content Cell |
| Content Cell |  Content Cell |

| Function name | Description                |
| ------------- | -------------------------- |
| `help()`      | Display the help window.   |
| `destroy()`   | **Destroy your computer!** |

| Left-Aligned | Center Aligned | Right Aligned |
| :----------- | :------------: | ------------: |
| col 3 is     | some wordy text | $1600        |
| col 2 is     | centered        | $12          |
| zebra stripes | are neat       | $1           |

| Item     | Value |
| -------- | ----: |
| Computer | $1600 |
| Phone    | $12   |
| Pipe     | $1    |




 
 
 
 
 
 
 
 
 
 
 

















