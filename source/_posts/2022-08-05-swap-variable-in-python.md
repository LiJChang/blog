---
layout: post
title:  "Tuple Swap in Python"
date: 2022-08-15
---

![ny crossing](https://source.unsplash.com/eySzBaaIHAw/w=300)

## How `a,b=b,a` in python works? a.k.a Tuple swap

## 前言
紀錄python `a,b = b,a` 這個語法的意思

## 此篇的前言

## 建立Tuple
在Python中，Tuple是一種immutable的物件(一但被建立就不會被改動)。要理解Tuple swap首先要知道建立Tuple的語法之一
```python
>>> a = 0
>>> b = 1
>>> a,b
(0,1)
```

可以看到`a,b`這行建立了一個Tuple

## Unpack Tuple