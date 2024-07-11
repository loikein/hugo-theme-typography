---
title: "Markdown Test"
weight: -1
# draft: true
date: "2001-01-01T00:00:00Z"
tags: ["Cat", "Mat"]
# categories: ["test-category", "Coding"]
---
## Formatting

#tag

**Bold**, __bold__, **加粗**

*Italic*, _italic_, *斜体*

<u>Underline</u>, <underline>underline</underline>, \([compare: link style](#formatting)\)

<del>Strike</del>, <s>strike</s>, ~~strike~~, ~strike~, --strike--

<mark>Highlight</mark>, =highlight=, ==highlight==, ==consecutive====highlights==

Internal link: [[202005191919]]

<!-- Comments-->

Footnote[^1], footnote[^2]

---


## CriticMarkup


{++addition++} \([compare: link style](#criticmarkup)\)

{>>comment<<}

{--deletion--}

{==highlight==} {>>comment<<}

{~~substution~>substitution~~}


## Lists

- `ul`
- Unordered list

1. `ol`
1. Ordered list

`dl`
:   `dt`
:   Description list

- [x] Task list
- [ ] Task list

## `Code` and highlight

Inline `code`, `` `escape` ``, and <kbd>keystroke</kbd>

```go {hl_lines=["2-5"],linenostart=199}
package main

import "log"

func add(x int, y int) int {
  log.Println("We are going to take the sum of two numbers, and leave a very very very long comment.")
  return x + y
}

func main() {
  y := add(1, 2)
  log.Println(y)
}
```

Here's an example with line numbers. 

```go {linenos=table,hl_lines=["2-5"],linenostart=199}
package main

import "log"

func add(x int, y int) int {
  log.Println("We are going to take the sum of two numbers, and leave a long comment.")
  return x + y
}

func main() {
  y := add(1, 2)
  log.Println(y)
}
```

Here's an example with no language specified.

```
package main

import "log"

func add(x int, y int) int {
  log.Println("We are going to take the sum of two numbers, and leave a long comment.")
  return x + y
}

func main() {
  y := add(1, 2)
  log.Println(y)
}
```

## Font

我能体に傷つけないで吞下 259 ml glass。

> Alas, my love, you do me wrong, To cast me off discourteously. For I have loved you well and long, Delighting in your company. Green&shy;sleeves was all my joy, Green&shy;sleeves was my delight, Green&shy;sleeves was my heart of gold, And who but my lady Green&shy;sleeves.
> 
> 天地玄黄，宇宙洪荒。日月盈昃，辰宿列张。寒来暑往，秋收冬藏。闰余成岁，律吕调阳。云腾致雨，露结为霜。金生丽水，玉出昆冈。剑号巨阙，珠称夜光。果珍李柰，菜重芥姜。海咸河淡，鳞潜羽翔。龙师火帝，鸟官人皇。始制文字，乃服衣裳。推位让国，有虞陶唐。
> 
> 色は匂へど　散りぬるを　我が世誰ぞ　常ならむ　有為の奥山　今日越えて　浅き夢見し　酔ひもせず

0 Oo Ii Ll 1 | 2 Z 5 s 8 Bb 6 #*^~(){}[] . , : ; “ ‘ ’ `

```
0 Oo Ii Ll 1 | 2 Z 5 s 8 Bb 6 #*^~(){}[] . , : ; “ ‘ ’ `
```

## Inline HTML

<code title="#282a36" style="text-align: center; height: 30px; width: 10ch; background-color: #282a36; display: inline-block; border-style: solid; border-color: black; color:white;">#282a36</code>
<code title="#f8f8f2" style="text-align: center; height: 30px; width: 10ch; background-color: #f8f8f2; display: inline-block; border-style: solid; border-color: black; color:black;">#f8f8f2</code>

## LaTeX & Table

$\LaTeX{}$

$$R_1 \begin{cases} >\mu_{2} \\ \leq \mu_{2} \end{cases}$$

| Message to agent 1 | $M_1$          |
| ------------------ | -------------- |
| Agent 1's action   | $a_1$          |
| New finding        | $R_1\begin{cases}>\mu_{2}\\\leq\mu_{2}\end{cases}$ |


## Figure

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob—>Alice: I am good thanks!
```

```mermaid
pie
    title Pie Chart
    “Dogs” : 386
    “Cats” : 85
    “Rats” : 150 
```

```flow
st=>start: Agent
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```

[^1]: The linked footnote appears at the end of the document.

[^2]: New lines
