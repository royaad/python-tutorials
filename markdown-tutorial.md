# This is a h1 header

## This is a h2 header

### This is a h3 header

#### This is a h4 header

##### This is a h5 header

###### This is a h6 header

This is a normal text

This is a [hyperlink](https://www.markdownguide.org/basic-syntax/)

This is a [section link](#this-is-a-h1-header)

This is an image ![title](/images/logging-error-vs-exception.png)

This is a **bold text**

This is also __bold__

This is *italic text*

This is also _italic_

This is ***bold and italic***

This is also ___bold and italic___

This is a ~~scratched text~~

This is a numbered list

This is a `code`

```bash
ls -h / | sort
```

```python
def function(*args, **kwargs):
    return
```

This is an inline lateX formula $f(x)=\alpha .e^{-\beta x}$

While this is a display equation
$$\dfrac{n!}{k!(n-k)!} = \binom{n}{k}$$

Check [link](https://ashki23.github.io/markdown-latex.html) for more lateX.

> This is an single indentation
>> This is a double indentation
>>> This is a triple indentation

1. item 1
   1. indented item 1
   2. indented item 2
2. item 2
3. item 3

This is a bullet point list

* item 1
  * indented item 1
  * indented item 2
* item 2
* item 3

We can use `+`, and `-` equally instead of `*`.

This is a check list

* [ ] to do 1
* [ ] to do 2
* [x] to do 3

This is a horizontal rule
***

we can equally use ___ or --- istead of ***.

To build a table

1st Header|2nd Header|3rd Header
---|:---:|---:
col 1 is|left-aligned|1
col 2 is|center-aligned|2
col 3 is|right-aligned|3

The alignment is define by --- (left), :---: (center), and ---: (right).

Previewing mermaid charts on VSCode requires an additional extension

```Mermaid
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
```

For more info on mermaid charts refer to [link1](https://jojozhuang.github.io/tutorial/mermaid-cheat-sheet/) and [link2](https://mermaid.js.org/syntax/flowchart.html).

With `Markdown All In One` extension installed to VSCode, links can be simply created by selecting the text and pasting the link onto it.
