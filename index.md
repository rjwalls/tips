---
layout: default_minimal
title: Random Tips 
---

This page is just a collection of random commands and such that myself (or
collaborators) have found useful.

### R

Write delimited file without quotes, row, and column labels:

```r
write.table('gtlds.txt', row.names=FALSE, col.names=FALSE, quote=FALSE)
```



