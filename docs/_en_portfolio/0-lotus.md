---
layout: article
title: Mechanical Lotus [05833 Final Project]
key: lotus
tags: [physical computing, Arduino, sensors]
show_tags: true
show_date: false
sharing: true
cover: /assets/images/lotus-cover.jpg
lang: en
lightbox: true
---

In *2022 Fall*, I took *Applied Gadgets, Sensors and Activity Recognition in HCI* (05-833). For the final project, I spent two weeks building a **mechanical lotus** that lights up and blooms when you blow on it, and plays music when you touch its leaf.

<!--more-->

<div>{%- include extensions/youtube.html id='OvxlnOO45rE' -%}</div>

The idea came from the [Ever-Blooming Mechanical Tulip][tulip]. My version adds sensors so the flower responds to people:
- **Blow on the flower** (airflow sensor) → it lights up (SMD LEDs & NeoPixel RGB) and opens (servo motor);
- **Touch the leaf** (TTP223 touch sensor) → it plays music (speaker) and changes colors (NeoPixel);
- A coroutine library keeps the lights, music, and motor running at the same time.

The build went from sketching the petals, to the flower skeleton and mechanics (with *a lot* of brass soldering), to LED wiring, servo mechanics, putting everything together in code (and even more testing), and finally packing it all into a pot with a battery so it works without a laptop. That's also when things started to break :(

| `Design sketch` | `Soldering the skeleton` |
| :--: | :--: |
| ![](/assets/images/lotus-sketch.jpg) | ![](/assets/images/lotus-skeleton.jpg) |
{: .photo-grid}

| `LED wiring & testing` | `Packing into a pot` |
| :--: | :--: |
| ![](/assets/images/lotus-wiring.jpg) | ![](/assets/images/lotus-pot.jpg) |
{: .photo-grid}

| `Final product (night)` | `Final product (day)` |
| :--: | :--: |
| ![](/assets/images/lotus-final.jpg) | ![](/assets/images/lotus-day.jpg) |
{: .photo-grid}

This class really pushed me: in two weeks I burned through two breadboards and three Arduinos, and re-soldered countless petals that fell off 💔. My deepest respect to all mechanical engineers 🫡 Hardware debugging is *hard*! I'd rather write code any day 🥲

[tulip]: https://www.instructables.com/Ever-Blooming-Mechanical-Tulip/
