---
layout: default
title: welcome to my first markdown blog
---
<h2>{{ page.title }}</h2>

## 欢迎使用Markdown

### 欢迎使用Markdown

*斜体*

**正文加粗**

| 日期        | 安排   |    
| --------   | -----:  |  
| 6.10 | 无安排 |


<p>{{ page.date | date_to_string }}</p>