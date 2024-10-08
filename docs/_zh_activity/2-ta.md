---
layout: article
title: 计算机入门课15-150/110｜ 助教
key: TA
tags:  [助教, 教学, 高等教育, 编程, 计算机科学]
show_tags: true
show_date: false
sharing: true
cover: /assets/images/15150-logo.png
lang: zh
---

在大三下学期*(2021春季)*、升大四的暑假*(2021暑期)*，与大四上学期*(2021秋季)*，我分别在我们学校的编程入门大课[15-150: 函数式编程入门][15150](150)、高中生计算机学者项目([CSS])、与[15-110: 编程原理][15110](110)里当助教(TA)。

<!--more-->

150使用SML/NJ编译器教授函数式编程语言ML、程序的数学证明、抽象数据类型、Work & Span分析、线性与并行算法等等。2021年春季的150有2位教授、39名TA、1只鹦鹉(150吉祥物@[Polly the polymorphic parrot][polly])，以及335名注册学生，基本都是在线通过Zoom上课，但也有小部分的线下讲座以及lab[^1]的席位。

|![](/assets/images/15150-ins.png)|
|:--:| 
| *15150吉祥物 Polly的ins账号 @pollythepolymorphicparrot* |

观察这种规模的课程在幕后的运营着实是很有意思，我们运用了一系列的教育科技工具，如：
- **GitHub**：课程基础架构，TA们可以在这里编写作业/lab的新问题、生成问题/答案文档/lab签到密码、raise issues、实现测试反馈等；
- **Slack**：教学人员交流渠道，用各种功能的大群小群来布置任务、收集反馈、社交、发表情包、庆祝TA生日等等；
- **Google Drive**：分享幻灯片、OH[^2]笔记、lab准备文档等；以及**Google Form**：各种表单，主要是收集150学生课程反馈；
- **Gradescope**：TA用来判学生作业/考试的平台，编程作业有Autograder；
- **Canvas**：发布讲座的录像、作业的问题、以及lab的问题和答案等；
- **OHQ**[^2]：线上OH排队工具，TA从OHQ上“领取”学生(FIFO)并到学生的Zoom房间里回答问题；
- **Piazza**：线上问答平台，学生可以实名/匿名/公开/私人发表提问帖，也会被TA用来发布一些作业常见问题；
- **Zoom**：线上视频会议平台。

作为TA，我们每周差不多要花20个小时用来
1. 参加教学人员会议，讨论教学计划、作业以及lab制作的情况，
2. 和其他TA一起教lab (差不多20名学生)，
3. 判作业，
4. 举办OH，
5. 回Piazza的问题帖子，
6. 制作并测试新的作业、lab问题，等等。

|![](/assets/images/15150-ohq.png)|![](/assets/images/15110-ohq.png)|
| -- | -- |
| *在2021年春季，我回答了67个学生提出的110个问题* | *在2021年秋季，我回答了50个学生提出的88个问题* |

因为我个人对于学习科学的兴趣，观察教育理论在实际应用中遇到的种种限制着实是很有意思，而且面对同一个事件，不同背景的教学人员也会有非常不一样的看法。150在学期中曾有学生在Piazza上发布了一个关于Gradescope Autograder评分标准的反馈长帖，引起了150学生与教学人员的热议。我关于此事件以及提高教学质量的一些思考可以看[这里][post]。这个对话实际上产生了很多有意思的问题，比如
* 学生需要失败才能学习吗？
* 假设学生不能成熟地面对自己的失败是否是个居高临下的姿态？
* 不论我们做什么，是否总是会有学生抱怨他们的失分不符合预想？

从教育实践与设计的角度出发，我个人认为以上问题的答案都是“否”，但150的一些教学人员与我的看法是相反的。这些问题大概都需要具体情况具体分析，但从学期中的那场讨论里 ，我切实体会到了在现实情境下提升教育质量的难度。于是我决定要在不同的课里积累更多的助教经验，体验不同的CS课程制度、学生经历、以及教学中会遇到的相同或不同的挑战。

|![](/assets/images/15150-parrot.png)|![](/assets/images/15110-ta-feedback.png)|
| -- | -- |
| *Credit to Mia Tang, 前150TA* | *我作为110助教收到的期中学生反馈* |

因此，在我升大四的暑假，我在CMU给难以接触CS资源的高中生们开办的计算机学者([CSS])项目中当助教；而在大四的上学期(2021秋季)，我决定去[15-110: 编程原理][15110]当助教。2021秋季的110有26位TA与300+名注册学生，基本上是线下教学，让我体验、积累了更多线下教学的经验。

比起150，110有更多样的学生来源，因为150是CS专业的必修课，但110是在CMU最基础的一节编程入门课。我大学前完全没有接触过编程，大一上的第一节编程课就是110 (我的课程体验详见[此推送])，现在返回去当110的助教，有种传承的感觉 :-)

在CSS与110里，我还练习了给不同学科背景的、第一次接触编程的人解释计算机科学重要概念，并像我当年上110遇到的[教授们][instructors]一样，分享我们对CS的兴趣与热爱。大四上学期我同时在上一门*个性化在线学习*的研究生课，趁机就把期末项目的[智能教学助手][cognitive tutor]做成了给110学生的递归练习。

[^1]: lab 翻译成实验课/小课什么的感觉都不太准确，CS课的lab或者recitation基本上就是TA带着复习总结一些课上的概念再做做题。
[^2]: OH即为Office Hour，TA每周固定的帮助学生答疑解惑的时间；OHQ即为Office Hour Queue，是CMU很多CS课用来排OH队的一个工具，根据问题难度以及Queue的拥挤情况，每个学生大致需要5-25分钟。

[15150]: http://www.cs.cmu.edu/~15150/
[15110]: https://www.cs.cmu.edu/~15110/
[polly]: https://www.instagram.com/pollythepolymorphicparrot/
[post]: https://qianouma.medium.com/ta-experience-reflection-a-conversation-about-course-improvement-suggestions-7045373cbfe9
[instructors]: /zh_activity/6-cs-academy.html
[cognitive tutor]: /zh_portfolio/0-pol.html

[此推送]: https://mp.weixin.qq.com/s/p8RFIPIM3TDh2CrS0QMwNA
[CSS]: https://www.cmu.edu/pre-college/academic-programs/computer-science-scholars.html