---
layout: default
title: user@home:~$
---

<img src="https://via.placeholder.com/150" class="profile-img" alt="My Photo">

### 关于我 (About Me)

你好。我是一名社会学博士（毕业于浙江大学），目前专注于**组织社会学**以及**计算语言学**的交叉研究。

我对语言背后的结构着迷，无论是社会结构还是句法结构。

### 研究兴趣
* **社会学**: 组织社会学
* **语言学**: 变异主义社会语言学 (Variationist Sociolinguistics), 形式语义学 (Type-Logical Semantics), 语音学
* **技术**: OpenSUSE, Python, 语音数据挖掘

---

### 最新博客
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <span style="color: #666;">{{ post.date | date: "%Y-%m-%d" }}</span>
      » <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
