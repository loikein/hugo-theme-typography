---
title: "Shortcodes Test"
weight: -1
# draft: true
date: "2001-01-02T00:00:00Z"
tags: ["Cat"]
categories: ["test-category"]
---
## Details

{{< details title="Summary goes here" open=true >}}
<u>Raw HTML</u>

Can use Markdown syntax like *italic* **bold** and even

lists
: like this
: and this
{{< /details >}}

## Ruby

Because I {{< ruby "can" "want" >}}.

## Spoiler

{{< spoiler >}}Inline spoiler{{< /spoiler >}}

{{< spoiler title="Block spoiler" block=true >}}
Like, really similar to Details. Almost look exactly the same.

Can use Markdown syntax like *italic* **bold** and even

lists
: like this
: and this
{{< /spoiler >}}

## Sticky

Available colors: yellow (default){{< sticky "yellow [sticky](#sticky)" >}}, green, blue, pink, purple

Marginalia (or apostils) are marks made in the margins{{< sticky "words goes here" "green" >}} of a book or other document. They may be scribbles, comments, glosses (annotations), critiques, doodles, drolleries, or illuminations.{{< sticky "more words goes here" "blue" >}}

Some famous marginalia were serious works heart of gold, or drafts thereof, written in margins{{< sticky "你好世界" "pink" >}} due to scarcity of paper{{< sticky "consecutive consecutive consecutive consecutive consecutive notes" "purple" >}}. Voltaire composed in book margins while in prison, and Sir Walter Raleigh wrote a personal statement in margins just before his execution.

Bug:

Do not{{< sticky "Uh-oh" "green" >}}
: Use in `<dt>`

`<dd>`
: Is fine (kinda) {{< sticky "Meh…" "blue" >}}

## Poem

Not really a shortcode, but I actually made the [sticky](#sticky) shortcode for it, so here we go:

```poem {lang="en"}
The neighbours gossiped idly at the door.
Copernicus lay dying overhead.
His little throng of friends{{< sticky "I am a serious comment I am a serious comment I am a serious comment" "blue" >}}, with startled eyes,
Whispered together, in that dark house of dreams,
From which by one dim crevice in the wall
He used to watch the stars.
        "His book has come
From Nuremberg at last; but who would dare
To let him see it now?"--
                            "They have altered it!
```

```poem
天地玄黄，宇宙洪荒。
日月盈昃，辰宿列张。
寒来暑往，秋收冬藏。
闰余成岁，律吕调阳。
```

```poem {lang="ja"}
色は匂へど　散りぬるを
我が世誰ぞ　常ならむ
有為の奥山　今日越えて
浅き夢見し　酔ひもせず
```

### Lyrics

```lyrics {lang="en"}
Alas my loue, ye do me wrong{{< sticky "words goes here" "green" >}},  
to cast me off discurteously:
And I haue{{< sticky "more words goes more words goes more words goes more words goes more words goes here" "blue" >}} loued you so long,
Delighting in your companie.

Greensleeues was all my ioy,
Greensleeues was my delight:
Greensleeues was my{{< sticky "你好世界" "pink" >}} heart of gold{{< sticky "consecutive notes" "purple" >}},
And who but Ladie Greensleeues.
```
