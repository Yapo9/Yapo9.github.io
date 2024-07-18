---
layout: page
permalink: /research-zh/index.html
title: research
---

> Lastest Update: 14th May 2024&nbsp;  [English Version (英文)](https://yapengf.com/research/)



您可以点击“摘要”按钮来查看每篇论文的摘要，再次点击“摘要”以收回。

## 已发表论文

- “我会努力让这里不是空白的”
  
## 工作论文

<ul>
  <li>
    <span>医保支付改革、道德风险与医疗控费——来自Bunching-DID的证据（2024，合作者：丛正龙、倪晨旭、王震）</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1')">摘要</button>
    <div id="abstract1" class="abstract-content">
      <p>本文旨在评估医保支付方式改革特别是DRG/DIP支付模式对于医疗费用控制和医疗质量提升的影响，通过前沿的Bunching-DID方法识别医保“起付线”对患者就诊行为的扭曲效应（道德风险），发现“起付线”的设置使得大约8%的就诊费用被调整至起付线以上，人均年度医疗费用平均提高28.8%。在考虑“起付线”诱导患者道德风险的情况下，DRG/DIP改革在降低医疗费用和提高医疗质量方面的效果有限，“起付线”附近的患者自付费用不降反升，而医院存在“推诿”重症病人的倾向，政策效应在地区、医院特点、患者特征等方面存在异质性。此外，DIP相比DRG能有效降低患者道德风险、缓解医院控费预期。本文在针对评估医疗提质控费的政策工具方面具有一定启示作用，如何精准识别或者避免道德风险问题，或将成为之后政策评估尤其是健康经济学中的重点与难点。</p>
    </div>
  </li>
  <li>
    <span>土地财政与政府隐性债务：来自聚束估计的证据（2023，合作者：丛正龙）</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract2')">摘要</button>
    <div id="abstract2" class="abstract-content">
      <p>稳妥处置地方政府隐性债务问题是未来政府工作的重点和难点，文章基于聚束估计方法，利用工业用地出让最低价标准政策对土地交易市场的冲击，识别地方土地出让行为对政府隐性债务的影响。研究发现，《全国工业用地出让最低价标准》的实施使得土地成交单价出现了显著的聚束效应，平均有11.09%的地块成交单价受《标准》影响而调整至最低价标准右侧；地方政府工业用地出让总价款受政策影响，相较于反事实分布平均增加了7.96%，地方政府综合土地出让总收入受政策影响，相较于反事实分布平均降低了1.5%，地方政府隐性债务受政策影响，相较于反事实分布平均增加了14.1%。Wald估计结果显示，地方工业用地出让价款每增加1%，地方政府隐性债务规模将增加1.768%，综合土地出让价款每增加1%，地方政府隐性债务规模将减少9.502%，意味着地方政府工业用地收入对于政府隐性债务具有正向效应，而地方政府综合土地出让收入对于政府隐性债务具有负向的挤出效应。研究结果为防范化解地方政府债务风险、实现高质量发展提供了创新路径和理论证据。</p>
    </div>
  </li>
</ul>

## 其他项目
<ul>
  <li>
    <span>医保支付改革、道德风险与医疗控费——来自Bunching-DID的证据（2024，合作者：丛正龙、倪晨旭、王震）</span>
    <button class="toggle-abstract" onclick="toggleAbstract('abstract1')">摘要</button>
    <div id="abstract1" class="abstract-content">
      <p>本文旨在评估医保支付方式改革特别是DRG/DIP支付模式对于医疗费用控制和医疗质量提升的影响，通过前沿的Bunching-DID方法识别医保“起付线”对患者就诊行为的扭曲效应（道德风险），发现“起付线”的设置使得大约8%的就诊费用被调整至起付线以上，人均年度医疗费用平均提高28.8%。在考虑“起付线”诱导患者道德风险的情况下，DRG/DIP改革在降低医疗费用和提高医疗质量方面的效果有限，“起付线”附近的患者自付费用不降反升，而医院存在“推诿”重症病人的倾向，政策效应在地区、医院特点、患者特征等方面存在异质性。此外，DIP相比DRG能有效降低患者道德风险、缓解医院控费预期。本文在针对评估医疗提质控费的政策工具方面具有一定启示作用，如何精准识别或者避免道德风险问题，或将成为之后政策评估尤其是健康经济学中的重点与难点。</p>
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