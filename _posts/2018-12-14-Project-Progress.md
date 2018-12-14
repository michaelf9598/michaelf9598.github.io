---
layout: post
title: "Michael Figueroa, Progress in my Project"
date: 2018-12-14
---

In this 



![Malaysia](/image/Malaysia.png)


```
wsize = 600 
lsize = 300 
#BASE
RS = radial-star(14,40,120,"solid","yellow")

RR = rectangle(wsize,lsize,"solid","red")

WS = rectangle(wsize,lsize / 14,"solid","white")

BR = rectangle(wsize / 2, 250,"solid","blue")

YC = circle(300 / 4.7, "solid","yellow")


#COMP

RRWS = place-image(WS,300,290,RR)

RRWS2 = place-image(WS,300,290 - 42 ,RRWS)

RRWS3 = place-image(WS,300,290 - 84 ,RRWS2)

RRWS4 = place-image(WS,300,290 - 126 ,RRWS3)

RRWS5 = place-image(WS,300,290 - 168 ,RRWS4)

RRWS6 = place-image(WS,300,290 - 210 ,RRWS5)

RRWS7 = place-image(WS,300,290 - 252 ,RRWS6)

RRWS8 = place-image(BR,150,50,RRWS7)

Circ = place-image(YC,100 / 2.75,93,RRWS8)
```
