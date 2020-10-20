---
title: "Git_Master"
author: "David Felipe Rubio Méndez"
date: "19/10/2020"
output: 
  html_document: 
    keep_md: yes
---


```r
x <- rexp(50)
y <- rnorm(50)

plot(x,y, col = "red")
```

![](infom_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

let's add some underneath relation 

```r
x_rel = rnorm(50)
y_rel = rexp(50) + x_rel

plot(x_rel,y_rel, col = "blue")
```

![](infom_files/figure-html/unnamed-chunk-2-1.png)<!-- -->
