---
layout: article
title: 自然语言语义关系研究
key: semantic
tags: [语义关系, 发展心理学, 计算语言学, 自然语言处理, 语言建模]
show_tags: true
show_date: false
sharing: true
lang: zh
---

`(本研究获得了$3500的奖学金)`

从大一下至大三上学期*(02/2019～12/2020)*，我主要的研究项目采用了发展心理学与计算语言学的方法来探索类别关系(taxonomic relations)与主题关系(thematic relations) 这两种不同的语义关系(semantic relations)[^1]。了解儿童是如何习得语义结构的(semantic structure acquisition)、不同语义关系对于语言产出(language production)的不同影响，对语言习得的理论、早期语言发展干预的应用，以及人类语言认知模型的构建都很重要。

<!--more-->

我大一与大二的四个学期(2019春、2020秋、春、暑假)主要是在[认知发展实验室][CDL]的Catarina Vales博士和Anna Fisher教授指导下研究4-6岁儿童的语义结构发展(semantic structure development)与不同语义关系语言输入(linguistic input)的联系。行为实验的数据收集采用了[空间整理方法][SpAM](spatial arrangement method)，而不同的语义关系则是通过利用语料库(包括[Childes]、[Wiki]、[Common Crawl][CC]、[TASA])计算分析逐点互信息([PMI])、潜在语义分析([LSA])，与[GloVE]词向量等自然语言处理的工具来实现的。2020年暑假，我获得了$3500的暑期本科生研究奖学金([SURF])以继续研究此课题，并在实验室与校内本科生研究会议上进行了项目展示。

|![](/assets/images/semantic-gephi-net.png)|
|:--:| 
| *我用[Gephi]对不同词语之间的不同语义联系进行可视化，此图中<span style="color: purple">HGLL </span>代表着相近的类别关系&不同的主题关系(high taxonomic and low thematic similarity)，<span style="color: green">LGHL</span>)则代表了相近的主题关系&不同的类别关系。* |

|![](/assets/images/semantic-word-cloud.png)|
|:--:| 
| *筛选实验素材的过程也用了一些绘图工具，比如R语言的ggplot扩展包。* |

在大三上学期，我加入了Bonnie Nozari教授的[实验室][Bonnie]，在现有图片命名任务(picture naming task)实验架构的基础上设计了打字实验(typing experiment)所需素材、对抗平衡的实验方法(counterbalancing method)、并改写了线上实验的程序。同时，我在David Plaut教授的[并行分布模型课][PDP](parallel distributed processing)的结课论文中，利用[Lens]搭建了一个循环神经网络(fully recurrent neural network)，以对此行为实验进行建模。

在这些研究经历中，我学习并应用了许多技能，包括Python ([NLTK] library), R, [Gephi], [jspsych], javaScript, HTML, CSS, [Lens]等，也对[Qualtrics], [psiTurk]和[MTurk]等心理学线上实验平台有了了解。

|![](/assets/images/semantic-typing-stimulus.png)|
|:--:| 
| *打字图片命名实验的素材选择。* |

<center>
  <img class="image image--xl" src="/assets/images/semantic-rnn-arch.png">
</center>
<div align="center" markdown="1">
  *我为[PDP]学期论文搭建的循环神经网络结构示意图。*
</div>

[CDL]: https://sites.google.com/andrew.cmu.edu/cogdevlab
[SpAM]: https://www.researchgate.net/publication/343145592_Lumping_and_splitting_Developmental_changes_in_the_structure_of_children's_semantic_networks
[PMI]: https://en.wikipedia.org/wiki/Pointwise_mutual_information
[LSA]: https://en.wikipedia.org/wiki/Latent_semantic_analysis
[GloVE]: https://nlp.stanford.edu/projects/glove/
[Childes]: https://childes.talkbank.org/
[Wiki]: https://www.english-corpora.org/wiki/
[CC]: https://commoncrawl.org/
[TASA]: http://lsa.colorado.edu/spaces.html
[SURF]: https://www.cmu.edu/uro/summer%20research%20fellowships/SURF/
[Bonnie]: https://www.nozarilab.com/about
[NLTK]: https://www.nltk.org/
[Gephi]: https://gephi.org/
[jspsych]: https://www.jspsych.org/
[Lens]: https://ni.cmu.edu/~plaut/Lens/Manual/
[Qualtrics]: https://www.qualtrics.com/
[psiTurk]: http://psiturk.org/ee/
[MTurk]: https://www.mturk.com/
[PDP]: https://www.cnbc.cmu.edu/~plaut/Teaching.html

[^1]: 一些专业名词的中文释义可能不准确，以英文原意为准。