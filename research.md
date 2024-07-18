---
layout: page
permalink: /research/index.html
title: research
---

> Lastest Update: 14th May 2024&nbsp;  [中文版本 (Chinese Version)](https://yapengf.com/research-zh/)

You can click on the “abstract” button to view the abstract of each paper and click on “abstract” again to retrieve it.

## Publications

- “Sadly, this space is still empty, but I hope to fill it with some content soon. Stay tuned!”

## Working Papers

<ul>
  <li>
    <span>论文标题1</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1')">abstract</button>
    <div id="abstract1" class="abstract-content">
      <p>这是论文1的摘要内容。</p>
    </div>
  </li>
  <li>
    <span>论文标题2</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract2')">abstract</button>
    <div id="abstract2" class="abstract-content">
      <p>这是论文2的摘要内容。</p>
    </div>
  </li>
</ul>

## Other Projects

<ul>
  <li>
    <span>医保支付改革、道德风险与医疗控费——来自Bunching-DID的证据（2024，合作者：丛正龙、倪晨旭、王震）</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1')">abstract</button>
    <div id="abstract1" class="abstract-content">
      <p>本文旨在评估医保支付方式改革特别是DRG/DIP支付模式对于医疗费用控制和医疗质量提升的影响，通过前沿的Bunching-DID方法识别医保“起付线”对患者就诊行为的扭曲效应（道德风险），发现“起付线”的设置使得大约8%的就诊费用被调整至起付线以上，人均年度医疗费用平均提高28.8%。在考虑“起付线”诱导患者道德风险的情况下，DRG/DIP改革在降低医疗费用和提高医疗质量方面的效果有限，“起付线”附近的患者自付费用不降反升，而医院存在“推诿”重症病人的倾向，政策效应在地区、医院特点、患者特征等方面存在异质性。此外，DIP相比DRG能有效降低患者道德风险、缓解医院控费预期。本文在针对评估医疗提质控费的政策工具方面具有一定启示作用，如何精准识别或者避免道德风险问题，或将成为之后政策评估尤其是健康经济学中的重点与难点。</p>
    </div>
  </li>
  <li>
    <span>论文标题2</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract2')">abstract</button>
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