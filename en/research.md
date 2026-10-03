---
layout: article
title: Research
show_title: true
lang: en
key: research
lightbox: true
---

<div class="research-overview">
  <div class="research-overview__text">
    <p>The big question for my research is: <b>how should we best prepare humans for the AI era?</b> To this end, I <i>design, build, and evaluate</i> LLM applications to foster <b>AI literacy</b>, optimize <b>human–AI task delegation</b>, and support effective <b>human–AI workflows</b>, especially in <i>programming and computing education</i>. I conduct <i>mixed-methods research</i> to investigate how people collaborate and learn with AI systems, and design systems and frameworks to support training and evaluation of effective human–AI teams. I frame my work around the key research questions of <b><i>what to teach</i></b>, <b><i>how to teach</i></b>, and <b><i>how to evaluate</i></b>.</p>
    <p>Jump to: <a href="about#projects">Selected Projects</a> · <a href="#publications">Publications</a> · <a href="#talks">Invited Talks</a> </p>
  </div>
  <div class="research-overview__fig">
    <img class="lightbox-ignore" src="/assets/images/research-overview.png" alt="Overview of my research: what to teach (pAIr, DSPM), how to teach (HypoCompass, ROPE, ImaginAItion), and how to evaluate (SPHERE, RECAP)">
  </div>
</div>

## Publications {#publications}

<p class="theme-desc">* equal contribution　† mentoring　· See also <a href="https://scholar.google.com/citations?user=3EAMFQIAAAAJ&hl=en">Google Scholar</a>.</p>

<div>
{% include publications.html %}
</div>

## Invited Talks {#talks}

<ul class="talks">
{%- for t in site.data.talks -%}
  <li><span class="talks__when">{{ t.when }}</span><span><b>{{ t.title }}</b><br><span class="talks__where">{{ t.where }}</span></span></li>
{%- endfor -%}
</ul>
