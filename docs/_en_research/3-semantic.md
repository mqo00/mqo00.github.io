---
layout: article
title: Semantics Relations Research
key: semantic
tags: [semantic relations, development, computational linguistics, NLP, modeling]
show_tags: true
show_date: false
sharing: true
lang: en
---

`$1750 (summer '19) & $3500 (summer '20) fellowship`

From the start of my freshman Spring *(02/2019)* to the end of my junior Fall *(12/2020)*, the main focus of my research projects have been on **semantic relations**. I’ve studied the **taxonomic** and **thematic** (or associative relations in some literature) word relations from both **developmental** and **computational** aspects. 

<!--more-->

Understanding **how children acquire structured semantic networks** is critical both for theoretical accounts of knowledge acquisition and for applied endeavors such as reducing inequalities in the knowledge of school-relevant domains, and **studying the differential effects of different semantic relations on word production** help fine-tune the models and hypotheses on cognitive architecture of language.

During my freshman and sophomore years, I primarily worked with Dr. [Catarina Vales] and Dr. [Anna Fisher] in the [Cognitive Development Lab][CDL] to study the correlation between different patterns of linguistic inputs and children’s semantic structure. The behavioral data was collected from children of 4-6 years old using the Spatial Arrangement Method ([SpAM]). The statistical measures we’ve used to capture the thematic and taxonomic relations include [PMI], [LSA], and [GloVe], and the corpora we’ve tried to calculate or analyze these measures include [Childes], [Wiki], [Common Crawl][CC], and [TASA]. 

|![](/assets/images/semantic-gephi-net.png)|
|:--:| 
| *I used [Gephi] to visualize the word net of different word relations (<span style="color: purple">HGLL </span> here denotes high taxonomic and low thematic similarity, and vice versa for <span style="color: green">LGHL</span>).* |

In 2020 summer, I received a **$3500** Summer Undergraduate Research Fellowship ([SURF]) to work on the proposal “The contribution of thematic and taxonomic language statistics to the development of structured semantic networks” and presented at lab meetings and Undergraduate Research Meet-Up.

|![](/assets/images/semantic-word-cloud.png)|
|:--:| 
| *R library ggplot was also used to aid the stimulus selection process.* |


During my junior Fall, I worked in Dr. Bonnie Nozari's [lab][Bonnie] on a similar project to study the differential effects of taxonomic and thematic word relations in picture naming task and the typing modality. Meanwhile, in my Parallel Distributed Processing class ([85-419/719][PDP]) taught by Dr. David Plaut, I implemented (using [Lens]), presented, and wrote a short paper on a simulation model on this task using a fully recurrent network.

 I’ve practiced and gained a lot of skills during these research experiences, including Python ([NLTK] library), R, [Gephi], [jspsych] javaScript, HTML, CSS, [Lens], and I also had some exposures to those tools that host online psychology experiment like [Qualtrics], [psiTurk] and Amazon Mechanical Turk ([MTurk]).

|![](/assets/images/semantic-typing-stimulus.png)|
|:--:| 
| *Some selected stimulus of the typing picture-naming experiment.* |

<center>
  <img class="image image--xl" src="/assets/images/semantic-rnn-arch.png">
</center>
<div align="center" markdown="1">
  *This is the fully recurrent network model architecture I used for [PDP]'s final paper.*
</div>

[Catarina Vales]: https://cvales.weebly.com/
[Anna Fisher]: https://www.cmu.edu/dietrich/psychology/people/core-training-faculty/fisher-anna.html

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
<!--http://www.cnbc.cmu.edu/~plaut/IntroPDP/index.html -->