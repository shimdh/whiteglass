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

```python
previous = 0
current = 1
i = 1

while i <= 10:
  print(current)
  temp = previous
  previous = current
  current = current + temp
  
  i += 1
```