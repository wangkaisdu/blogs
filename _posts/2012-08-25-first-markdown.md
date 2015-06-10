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

<table>
<thead>
<tr class="header">
<th align="left">2</th>
<th align="left">2</th>
<th align="left">2</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">1</td>
<td align="left">1</td>
<td align="left">2</td>
</tr>
</tbody>
</table>