## 标题
```markdown
# A First-level heading
## A second-level heading
```
以此类推最多有*6*级标题

## 文本样式
- `** **` 或者 `__ __` **加粗**
- `* *` 或者 `_ _`  *斜体*
- `~~ ~~` ~~删除线~~
- `<sub> </sub>` <sub>下标</sub>
- `<sup> </sup>` <sup> </sup>上标
- `<ins> </ins>` <ins>下划线 </ins>

## 引用文本
>I use a quote

## 代码
`  `` `  包裹一小段代码
` ``` ` 包裹一大段代码

## 链接
`[]` 包裹链接文本 `()` 包裹链接URL
[Github Markdown](https://docs.github.com/zh/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#line-breaks)

### 标题链接
依然是`[]()`样式 , 但是`()`内放入`#title` 
>   title有如下格式
    字母转换成小写形式。
    空格由连字符 (`-`) 代替。 任何其他空格或标点符号都将被删除。
    前导和尾随空格被删除。
    标记格式被删除，只保留内容（例如，`_italics_` 变为 `italics`）。
    如果标题的自动生成的定位点与同一文档中的早期定位点相同，那么通过追加连字符和自动递增整数来生成唯一标识符。
### 图片
`![]()`
## 换行符
- 行的最后留两个空格
- 行的末尾包含反斜杠
## 列表
### 无序列表
```markdown
- first pattern
* second pattern
+ third pattern
```
### 有序列表
```markdown
1. first
2. second
3. third
```
### 任务列表
```markdown
- [ ] task1
- [x] task2
```
- [ ] task1
- [x] task2  
## 脚注
`[^num]`

Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].
[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## 警报
```markdown
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## 表格
```markdown
| | |
| | |
|-|-|
| | |
| | |
```

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
表格末尾的竖线可选。  
单元格的宽度可以不同，无需在列内准确对齐。 标题行的第一列中必须至少有三个横线。

## 折叠部分
```markdown
<detail>
<summary> </summary>
<\detail>
```

## Mermaid
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
