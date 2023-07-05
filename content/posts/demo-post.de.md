---
title: "Demo Post"
date: 2023-05-29T16:18:21+02:00
draft: false
---

## Table

| asdf | asdf | adsf | asdf | asdf | asdf | asdf |
|------|------|------|------|------|------|------|
| asdf | asdf | asdf    | asdf | asdf | asdf | asdf |
| asdf | asdf | asdf    | asdf | asdf | asdf | asdf |
| asdf | asdf | asdf    | asdf | asdf | asdf | asdf |
| asdf | asdf | asdf    | asdf | asdf | asdf | asdf |
| asdf | asdf | asdf    | asdf | asdf | asdf | asdf |

## Image

![](/images/avatar.png)

## Tabs

{{< tabs tabTotal="2" >}}

{{% tab tabName="First Tab" %}}
This is markdown content.
{{% /tab %}}

{{< tab tabName="Second Tab" >}}
{{< highlight text >}}
This is a code block.
{{< /highlight >}}
{{< /tab >}}

{{< /tabs >}}

## Mermaid

{{< mermaid >}}
sequenceDiagram
participant Alice
participant Bob
Alice->>John: Hello John, how are you?
loop Healthcheck
John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts <br>prevail!
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
{{< /mermaid >}}

## PlantUML

{{< plantuml >}}
PC -> Phone: Connect to Phone

{{< /plantuml >}}

## Katex

$$
f(a,b,c) = (a^2+b^2+c^2)^3
$$


