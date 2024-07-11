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
