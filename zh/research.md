---
layout: article
title: 研究
show_title: true
lang: zh
key: research
lightbox: true
---

<div class="research-overview">
  <div class="research-overview__text">
    <p>我研究的核心问题是：<b>我们应如何让人类为AI时代做好准备？</b>为此，我<i>设计、构建并评估</i>大模型应用，以培养<b>AI素养</b>、优化<b>人机任务分工</b>，并支持高效的<b>人机协作流程</b>，尤其是在<i>编程与计算机教育</i>领域。我采用<i>混合研究方法</i>探究人们如何与AI系统协作和学习，并设计系统与框架来支持高效人机团队的训练与评估。</p>
    <p>快速跳转：<a href="about#projects">精选项目</a> · <a href="#publications">论文列表</a> · <a href="#talks">受邀报告</a> · <a href="https://scholar.google.com/citations?user=3EAMFQIAAAAJ&hl=en">Google Scholar</a></p>
  </div>
</div>

## 论文列表 {#publications}

<p class="theme-desc">* 同等贡献　† 指导 · 另见 <a href="https://scholar.google.com/citations?user=3EAMFQIAAAAJ&hl=en">Google Scholar</a>。</p>

<div>
{% include publications.html %}
</div>

## 受邀报告 {#talks}

<ul class="talks">
{%- for t in site.data.talks -%}
  <li><span class="talks__when">{{ t.when }}</span><span><b>{{ t.title }}</b><br><span class="talks__where">{{ t.where }}</span></span></li>
{%- endfor -%}
</ul>
