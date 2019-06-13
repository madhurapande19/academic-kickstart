---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Performance evaluation of Q-learning and SARSA on Taxi ride problem"
subtitle: ""
summary: ""
authors: [Madhura Pande, Monika Ahirwar]
tags: []
categories: []
date: 2019-06-13T17:13:01+05:30
lastmod: 2019-06-13T17:13:01+05:30
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

 This project explores a Taxi environment where there is a requirement to pick and drop passengers to specific locations, maneuvering through open roads with the aim of efficiently scheduling trips. There is a mega-reward for successfully picking and dropping passengers and penalties for bumping into walls or wrong drops. We use prinicples of Reinforcement Learning to train an agent with different algorithms and meaure the performance at this task. We implement a random agent, a SARSA agent, a Q-learning agent and a smart Q-learning agent for this problem and present a performance comparison analysis. The smart Q-learning agent has few improvements(over the standard version) to better handle the exploration-exploitation trade off and help achieve good performance within less iterations. Moreover, experiments are done to choose the best set of hyper parameters for this problem using Grid search technique.

{{% staticref "files/RL_ppt1.pdf" %}}Slides{{% /staticref %}}