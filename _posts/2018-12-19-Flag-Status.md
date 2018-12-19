---
layout: post
title: "Flag Status"
date: 2018-12-19
---
# Program Code
```
include image

size = 100

width = size * 8

height = size * 5

RR = rectangle(500, 300, "solid","red")

WR = rectangle(500, 70, "solid","white")

WR2 = rectangle(500, 70, "solid","white")

RT = triangle(300, "solid", "blue")
RT30 = rotate(30,RT)

WS = star(height / 8,"solid","white")

Flag-Stripes = overlay-xy(WR, 0, -50, RR)
Flag-Stripes2 = overlay-xy(WR2, 0, -180, Flag-Stripes)
Flag-Triangle = overlay-xy(RT30, 0, 0, Flag-Stripes2)
Flag-Star = overlay-xy(WS, -45, -100, Flag-Triangle)

```
# Program Output
![ImageTitle](/images/Imag.png)
This is my project, I'm somewhat proud of all the progress I have done. I spent lot of time on this and thanks to some support from my classmate, It's completel. Diffuclties were doing this on my own and the good was that I had people helping me oout
