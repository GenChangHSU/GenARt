---
title: Post1
author: Gen-Chang Hsu
date: '2026-07-06'
slug: []
categories: ["R Packages"]
tags: ["flametree"]
image: /img/post/Post1.png
weight: 100
---

This is the start of the post.


``` r
library(tidyverse)
library(flametree)

# pick some colors
shades <- c("#1b2e3c", "#0c0c1e", "#74112f", "#f3e3e2")

# data structure defining the trees
dat <- flametree_grow(time = 10, trees = 10)

# draw the plot
dat %>% 
  flametree_plot(
    background = "antiquewhite",
    palette = shades, 
    style = "nativeflora"
  )
```

<img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-1.png" alt="" width="100%" style="display: block; margin: auto;" />


This is the end of the post!

<br>


