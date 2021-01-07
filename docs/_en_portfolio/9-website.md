---
layout: article
title: This Website [mqo00.github.io]
key: website 
tags: [programming, web design, Jekyll]
show_tags: true
show_date: false
sharing: true
cover: /assets/images/website-logo.png
lang: en
---

This website itself is my attempt to practice the skills and learn some new tools for web design. 

<!--more-->

Originally I used javaScript / HTML / CSS and node.js to develop a static website, but then I figured there’s a more elegant solution using [Jekyll], so I found a [template] and use my [GitHub] page to host this website. I also host it using my Andrew ID domain that CMU provides[^1], as my parents said somehow they couldn’t access the mqo00.github.io page.

The TeXt Jekyll template doesn't support dynamic language switcher, so after some web searching, I found this [blog][^2] the most useful and wrote one that's compatible with this template without any plugin (to avoid GitHub pages compatibility issues). It's not the most elegant solution, but it works, and I'll probably write more about how I implement the language switcher in the future (Liquid is such a weird language :imp:).

| `The storyboard design of this website` |
| -- |
|![](/assets/images/website.png)|

[Jekyll]: https://jekyllrb.com/
[template]: https://github.com/kitian616/jekyll-TeXt-theme
[GitHub]: https://github.com/mqo00/mqo00.github.io
[blog]: https://matthewlincoln.net/2020/03/01/multilingual-jekyll.html

[^1]: https://www.andrew.cmu.edu/user/qianoum/
[^2]: Lincoln, Matthew D. "Multilingual Jekyll: How The Programming Historian Does That." *Matthew Lincoln, PhD* (blog), 01 Mar 2020, https://matthewlincoln.net/2020/03/01/multilingual-jekyll.html.
