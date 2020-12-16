---
layout: post
title: "피보나치 수열 구현"
date: 2020-12-16 20:00:00 +0900
---

# 피보나치 수열 구하기

## python(while)

```python
prev = 1
curr = 1

count = 0

while count < 50:
  print(prev)

  tmp_no = prev

  prev = curr
  curr = tmp_no + curr

  count += 1
```
