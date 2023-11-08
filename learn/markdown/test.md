[TOC]

# 总览

Markdown 速查表提供了所有 Markdown 语法元素的基本解释。如果你想了解某些语法元素的更多信息，请参阅更详细的 [基本语法](https://markdown.com.cn/basic-syntax) 和 [扩展语法](https://markdown.com.cn/extended-syntax).


---

## 基本语法

这些是 John Gruber 的原始设计文档中列出的元素。所有 Markdown 应用程序都支持这些元素。

| 元素                                                         | Markdown 语法 |
| :----------------------------------------------------------: | ------------- |
| [标题（Heading）](https://markdown.com.cn/basic-syntax/headings.html) | `#H1 ##H2` |
| [粗体（Bold）](https://markdown.com.cn/basic-syntax/bold.html) | **bold text** |
| [斜体（Italic）](https://markdown.com.cn/basic-syntax/italic.html) | *italicized text* |
| [引用块（Blockquote）](https://markdown.com.cn/basic-syntax/blockquotes.html) | `> blockquote ` |
| [无序列表（Unordered List）](https://markdown.com.cn/basic-syntax/unordered-lists.html) | `- First item  <br/>- Second item<br/>- Third item` |
| [代码（Code）](https://markdown.com.cn/basic-syntax/code.html) | ``code`` |
| [分隔线（Horizontal Rule）](https://markdown.com.cn/basic-syntax/horizontal-rules.html) | `---` |
| [链接（Link）](https://markdown.com.cn/basic-syntax/links.html) | `[title](https://www.example.com)` |
| [图片（Image）](https://markdown.com.cn/basic-syntax/images.html) | `![alt text](image.jpg)` |
| **单引号 `'` 的作用是将文本标记为普通文本，而不是 Markdown 语法元素。** | **bold text** |
|  | `**bold text**` |

### 1. 举例

* `> blockquote `


> 这是引用块
>
> 问题或建议，请**留言**。

* `---`

---

* `[title](https://www.example.com)`

  [**markdown**](https://markdown.com.cn/editor/)

* `![alt text](image.jpg)`

![GMAIL](logo_gmail_lockup_default_2x_r5.png "Magic Gardens")[![GMAIL](logo_gmail_lockup_default_2x_r5.png "Magic Gardens")](https://markdown.com.cn/assets/img/shiprock.c3b9a023.jpg)













##  扩展语法

| 元素                                                         | Markdown 语法                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [表格（Table）](https://markdown.com.cn/extended-syntax/tables.html) | `| Syntax   | Description || ----------- | ----------- || Header   | Title    || Paragraph  | Text    |` |
| [代码块（Fenced Code Block）](https://markdown.com.cn/extended-syntax/fenced-code-blocks.html) | ````{ "firstName": "John", "lastName": "Smith", "age": 25}```` |
| [脚注（Footnote）](https://markdown.com.cn/extended-syntax/footnotes.html) | Here's a sentence with a footnote. `[^1]` `[^1]`: This is the footnote. |
| [标题编号（Heading ID）](https://markdown.com.cn/extended-syntax/heading-ids.html) | `### My Great Heading {#custom-id}`                          |
| [定义列表（Definition List）](https://markdown.com.cn/extended-syntax/definition-lists.html) | `term: definition`                                           |
| [删除线（Strikethrough）](https://markdown.com.cn/extended-syntax/strikethrough.html) | `~~The world is flat.~~`                                     |
| [任务列表（Task List）](https://markdown.com.cn/extended-syntax/task-lists.html) | `- [x] Write the press release- [ ] Update the website- [ ] Contact the media` |

### 1. 举例

* `表格`

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

* `代码块`

  ```json
  {
   "firstName": "John",
   "lastName": "Smith",
   "age": 25
  }
  ```

* `脚注`

  
  Here's a simple footnote,[^1] and here's a longer one.[^你好]
  
  [^1]: This is the first footnote.
  
  [^你好]: Here's one with multiple paragraphs and code.
```Java
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}  

```
* `任务列表语法`


- [x] Write the press release

- [ ] Update the website

- [ ] Contact the media

  ##  其他

* `Markdown 换行语法`

  支持两个或多个空格进行换行，为了兼容性，请在行尾添加“结尾空格”或 HTML 的 `<br>` 标签来实现换行。

  

* `Markdown 链接语法`
  这是一个链接 [Markdown语法](https://markdown.com.cn "这是一个链接")。

  
  
*  `Markdown 图片语法`

[![这是图片](philly-magic-garden.9c0b4415.jpg "Magic Gardens")](https://markdown.com.cn/basic-syntax/images.html)





* `Markdown 内嵌 HTML 标签`
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>
This is another regular paragraph.



