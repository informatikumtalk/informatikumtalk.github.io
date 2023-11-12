---
title: "[003] Accelerating Reinforcement Learning of Robotic Manipulations via Feedback from Large Language Models"
weight: -3
readingtime: 60
date: 2023-11-12
tags: ["robotics", "manipulation", "large language models", "reinforcement learning"]
author: "储焜"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "3rd Informatikum Talk by 储焜."
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
schedule:  2023-11-12 17:00-18:00
pass: false
cover:
    image: "https://xf-zhao.github.io/assets/img/publication_preview/Lafite2-1400.webp" # image path/url
    alt: "003 Talk" # alt text
    caption: "储焜 will share with us this paper" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: false # only hide on current single page
---

#### Abstract
Reinforcement Learning (RL) plays an important role in the robotic manipulation domain since it allows self-learning from trial-and-error interactions with the environment. Still, sample efficiency and reward specification seriously limit its potential. One possible solution involves learning from expert guidance. However, obtaining a human expert is impractical due to the high cost of supervising an RL agent, and developing an automatic supervisor is a challenging endeavor. Large Language Models (LLMs) demonstrate remarkable abilities to provide human-like feedback on user inputs in natural language. Nevertheless, they are not designed to directly control low-level robotic motions, as their pretraining is based on vast internet data rather than specific robotics data. In this paper, we introduce the Lafite-RL (Language agent feedback interactive Reinforcement Learning) framework, which enables RL agents to learn robotic tasks efficiently by taking advantage of LLMs' timely feedback. Our experiments conducted on RLBench tasks illustrate that, with simple prompt design in natural language, the Lafite-RL agent exhibits improved learning capabilities when guided by an LLM. It outperforms the baseline in terms of both learning efficiency and success rate, underscoring the efficacy of the rewards provided by an LLM.


#### Time, Location

- (UTC +01:00) Europe/Berlin, 12 Nov 2023, 17:00-18:00
- Informatikum WTM group, F-231; and online
<a href="https://calndr.link/event/LQJQQJ8mhI"><img src="/addtocalendar.png" alt="HTML tutorial" style="width:42px;height:auto;float:center;">Add to calendar</a>


#### Speaker: 储焜

#### See also:
- [arXiv preprint](https://arxiv.org/abs/2311.02379)
