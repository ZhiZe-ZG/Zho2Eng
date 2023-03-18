# Zho2Eng
Personal conventions regarding bilingual documentation.

该项目原名“中英双语文档”。

## 语言数量和顺序

一般默认中英双语，中文在前，英文在后。如有改变需要特殊说明。

## 标题

在标题中，不同语言的标题用 `|` 隔开。按语言顺序书写。`|` 前后需要至少一个空格。例如：

```markdown
## 多语言 | Multilanguage
```

## 纯文字段落

纯文字段落以段落为单位，默认按语言顺序书写。默认一段按所有语言翻译后才是下一段。例如：

```markdown
这个项目是中文书写的，如果有兴趣翻译此项目可以提交 pull request。

This project is written in Chinese. If you are interested in translating this project, feel free to submit a pull request.

在标题中，不同语言的标题用 `|` 隔开。先是中文，然后英文。正文中，同一段落的不同语言版本也按同样顺序排列。

The titles in different languages are separated by `|`. First Chinese, then English. In the body text, the different language versions of the same paragraph of text are also arranged in the same order.

如果标题或段落不需翻译或无法翻译，则只有一项。

If a heading or paragraph does not need to be translated or cannot be translated, there is only one edition.

列表、表格、插图等内容如有必要翻译且可以翻译，则也翻译。翻译后的内容列于原内容下方。如有必要，翻译后的内容和原内容之间使用分割线分隔。

Lists, tables, illustrations, etc. are translated if necessary and available. The translated content is listed below the original content. If necessary, separate the translated content from the original content with a dividing line.

受精力和能力限制，目前知则所能提供的英文翻译非常有限。

Due to energy and capacity constraints, ZhiZe currently provides very limited English translations.
```

如果两种语言中某个段落完全一致，允许完全相同的段落重复。例如：

```markdown
他说的那句话是：

What he said was:

Good Morning!

Good Morning!
```

其中文版其实就是（中文为主体的文章中夹杂了英文单词或语句）：

```markdown
他说的那句话是：

Good Morning!
```

Markdown 中的引用块视作纯文本段落例如：

```markdown
> 你好，世界！

> Hello, world!
```

### 非纯文字内容

图片、表格、列表等默认为不需要翻译的。也就是所有语言格式一致，如果需要翻译，则使用 `---` 隔开。例如：

```markdown
* Visual Studio Code
* 纸质词典
* 知则厨房

---

* Visual Studio Code
* Printed Dictionaries
* ZhiZe's Kitchen
```

## 多语言和其他语言

理论上这种语法可以支持多语言和其他语言顺序。例如：

```markdown
## Paragraph 1 | Absatz 1 | 段落 1

Das Instrument, welches die Vermittlung bewirkt zwischen Theorie und Praxis, zwischen Denken und Beobachten, ist die Mathematik; sie baut die verbindende Brücke und gestaltet sie immer tragfähiger.

The instrument that mediates between theory and practice, between thought and observation, is mathematics; it builds the connecting bridge and makes it stronger and stronger.

数学是协调理论与实践、思维与观察的工具；它建造了连接的桥梁并使其不断巩固。

Daher kommt es, dass unsere ganze gegenwärtige Kultur, soweit sie auf der geistigen Durchdringung und Dienstbarmachung der Natur beruht, ihre Grundlage in der Mathematik findet.

Thus it happens that our entire present-day culture, insofar as it rests on intellectual insight into and harnessing of nature, is founded on mathematics.

因此可以说，只要我们现今的文明依靠对自然的理性洞察和驾驭，它就建立在数学的基础上。
```

