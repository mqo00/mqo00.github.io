---
layout: article
title: 机械荷花 [05833 期末项目]
key: lotus
tags: [物理计算, Arduino, 传感器]
show_tags: true
show_date: false
sharing: true
cover: /assets/images/lotus-cover.jpg
lang: zh
lightbox: true
---

*2022年秋季*，我上了 *Applied Gadgets, Sensors and Activity Recognition in HCI*（05-833）这门课。期末项目我花了两周做了一朵**机械荷花**：对着它吹气，它会亮灯并绽放；摸一摸荷叶，它会播放音乐。

<!--more-->

<div>{%- include extensions/youtube.html id='OvxlnOO45rE' -%}</div>

灵感来自 [Ever-Blooming Mechanical Tulip][tulip]。我的版本加入了传感器，让花能和人互动：
- **对花吹气**（气流传感器）→ 亮灯（SMD LED 与 NeoPixel RGB）并绽放（舵机）；
- **触摸荷叶**（TTP223 触摸传感器）→ 播放音乐（扬声器）并变换颜色（NeoPixel）；
- 用协程库（coroutine）让灯光、音乐和舵机同时运行。

制作过程从画花瓣草图开始，到搭花的骨架和机械结构（*大量*黄铜焊接），再到LED布线、舵机机构、写代码整合一切（以及更多的测试），最后把所有东西装进花盆、加上电池，让它脱离电脑也能运行。也就是在这时，东西开始坏了 :(

| `设计草图` | `焊接骨架` |
| :--: | :--: |
| ![](/assets/images/lotus-sketch.jpg) | ![](/assets/images/lotus-skeleton.jpg) |
{: .photo-grid}

| `LED布线与测试` | `装进花盆` |
| :--: | :--: |
| ![](/assets/images/lotus-wiring.jpg) | ![](/assets/images/lotus-pot.jpg) |
{: .photo-grid}

| `成品（夜晚）` | `成品（白天）` |
| :--: | :--: |
| ![](/assets/images/lotus-final.jpg) | ![](/assets/images/lotus-day.jpg) |
{: .photo-grid}

gadgets这课真是挑战自我：两周做了一朵机械荷花，烧了两个breadboard、三个Arduino，以及无数次掉了要重新solder的花瓣💔 机械工程的朋友们请收下我最诚挚的敬意🫡 hardware debugging 真的太难了！有这功夫我宁愿写代码🥲🥲

[tulip]: https://www.instructables.com/Ever-Blooming-Mechanical-Tulip/
