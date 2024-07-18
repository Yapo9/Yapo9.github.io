---
layout: page
permalink: /research/index.html
title: Publications
---

> Lastest Update: 14th May 2024&nbsp;  [中文版本 (Chinese Version)](https://caihanlin.com/file/publications-zh/)

# 我的论文列表

欢迎查看我的论文列表。你可以点击“摘要”按钮来查看每篇论文的摘要。
## 已发表论文
- “Sadly, this space is still empty, but I hope to fill it with some content soon. Stay tuned!”
<ul>
  <li>
    <span>论文标题1</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1')">摘要</button>
    <div id="abstract1" class="abstract-content">
      <p>这是论文1的摘要内容。</p>
    </div>
  </li>
  <li>
    <span>论文标题2</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract2')">摘要</button>
    <div id="abstract2" class="abstract-content">
      <p>这是论文2的摘要内容。</p>
    </div>
  </li>
  <!-- 添加更多论文条目 -->
</ul>

<script>
  function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none" || abstract.style.display === "") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }
</script>

<style>
  .abstract-content {
    display: none;
    margin-top: 10px;
    font-size: 0.9em; /* 调整摘要内容的字体大小 */
  }
  .toggle-abstract {
    cursor: pointer;
    color: blue;
    background: none;
    border: none;
    padding: 0;
    text-decoration: underline;
    margin-left: 10px;
    font-size: 0.9em; /* 调整“摘要”按钮的字体大小 */
  }
  li {
    margin-bottom: 20px;
  }
</style>