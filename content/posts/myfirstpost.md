---
title: 'Myfirstpost'
date: 2024-02-12T14:56:59+03:00
draft: false

tags: ["html", "css", "hugo"]
categories: ["технологии"]
---

## Всем привет!

Это мой **новый** пост с моем новом *блоге*, 
созданном с использованием [Hugo](https://gohugo.io)
генератора статических сайтов!

[Markdown Syntax](https://www.markdownguide.org/basic-syntax/)

### Первые шаги при работе с Hugo

Создание нового сайта:
    
    hugo new site MyFreshWebsite --format yaml

Устанавливаем тему (в данном случае PaperMod):
    
    git clone https://github.com/adityatelange/hugo-PaperMod themes/PaperMod --depth=1

В `config.yml` добавляем строку:
    
    theme: ["PaperMod"]