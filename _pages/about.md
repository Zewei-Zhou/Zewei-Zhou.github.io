---
permalink: /
title: "Zewei Zhou - Homepage"
excerpt: "Zewei Zhou is a PhD student in the UCLA Mobility Lab, and research focuses on the scene understanding and reasoning of autonomous systems which enables vehicles/robots to intelligently interact and cooperate with others."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

👋 I am a PhD candidate at the [UCLA Mobility Lab](https://mobility-lab.seas.ucla.edu/) of the University of California, Los Angeles (UCLA), advised by [Prof. Jiaqi Ma](https://mobility-lab.seas.ucla.edu/about/). I am also a research intern at [Motional](https://motional.com/). I received my master’s degree from Tongji University with the honor of Shanghai Outstanding Graduate, advised by [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Zhuoping Yu](https://ieeexplore.ieee.org/author/37402463600). 

My research focuses on the scene understanding and reasoning of autonomous systems, which enables vehicles/robots to intelligently interact and cooperate with others. Currently, I am exploring the Vision-Language-Action (VLA) models and closed-loop simulation in this domain. My research is supported by [Amazon AI PhD Fellowship](https://www.sciencehub.ucla.edu/2025-amazon-ai-phd-fellows/#main-footer).


# 🔥 News
- *2026.04*: &nbsp;👏 Our [SpanVLA](https://spanvla.github.io/) paper on eficient action bridging and learning from negative-recovery samples for VLA Model has been released!
- *2025.10*: &nbsp;🎉 Our [V2XPnP](https://mobility-lab.seas.ucla.edu/v2xpnp/) paper won the [Best Paper Award (1st)]() at the [ICCV 2025 DriveX Workshop](https://drivex-workshop.github.io/)!
- *2025.09*: &nbsp;🎉 I am honored to be selected as an [Amazon AI PhD Fellow](https://www.sciencehub.ucla.edu/2025-amazon-ai-phd-fellows/#main-footer) for 2025, and received the [Amazon AI PhD Fellowship](https://www.amazon.science/news/amazon-launches-68-million-ai-phd-fellowship-program).
- *2025.09*: &nbsp;👏 Our [AutoVLA](https://arxiv.org/pdf/2506.13757) paper on the Vision-language-action model for end-to-end autonomous driving has been accepted by [NeurIPS 2025](https://neurips.cc/)!
- *2025.06*: &nbsp;👏 Our [V2XPnP](https://mobility-lab.seas.ucla.edu/v2xpnp/) and [TurboTrain](https://arxiv.org/pdf/2508.04682) paper on the end-to-end multi-task framework for multi-agent multi-frame system and the efficient & balanced multi-task learning strategies for the system have been accepted by [ICCV 2025](https://iccv.thecvf.com/)!
- *2025.06*: &nbsp;👏 Our [CooperRisk](https://arxiv.org/pdf/2506.15868v1) paper on the cooperative multi-agent prediction and risk quantification has been accepted by [IROS 2025 (Oral)](https://www.iros25.org/).
- *2025.01*: &nbsp;👏 Our [Co-MTP](https://xiaomiaozhang.github.io/Co-MTP/) paper on cooperative prediction framework with multi-temporal fusion has been accepted by [ICRA 2025](https://2025.ieee-icra.org/). 
<!-- - *2025.01*: &nbsp;🎉 Our team secured the Tier 1 in the [U.S.DOT Intersection Safety Challenge](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge-stage-1b-system-assessment-and) with a $750k award! -->
- *2024.08*: &nbsp;🎉 Our survey paper on trajectory prediction has been awarded as [Best Paper Award for Outstanding Survey]() of [IEEE T-IV](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)! 
- *2024.07*: &nbsp;👏 Our [V2X-Real](https://mobility-lab.seas.ucla.edu/v2x-real/) paper on multi-agents and multi-modal cooperative perception has been accepted by [ECCV 2024](https://eccv.ecva.net/virtual/2024/poster/988). 
- *2023.06*: &nbsp;🎉 Shanghai Outstanding Graduate Honor!

<!-- - *2022.03*: &nbsp;🎉 Our paper on speed prediction in transportation systems has been accepted by [iScience (Cell Press)](https://www.cell.com/iscience/home)！
- *2021.12*: &nbsp;🤖 Our multiple automated guided vehicles (AGVs) passed through field testing and could coordinate movements with each other, [providing a valet experience](/#-project). -->

# 📝 Selected Publications <span style="font-size: 1rem; font-weight: normal;">( [See All Publications >](https://scholar.google.com/citations?user=TzhyHbYAAAAJ) )</span>

<div class='paper-box'><div class='paper-box-image'><img src='images/SpanVLA_demo.gif' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**SpanVLA: Efficient Action Bridging and Learning from Negative-Recovery Samples for Vision-Language-Action Model**

**Zewei Zhou***, <span style="color:#7a8288;">Ruining Yang*, Tony Qi, Yiluan Guo, Sherry X. Chen, Tao Feng, Kateryna Pistunova, Yishan Shen, Lili Su, Jiaqi Ma</span>

SpanVLA introduce a efficient action bridging with sparse KV-Cache and history initialization and learn from negative-recovery samples to improve the robustness.

[Arxiv, 2026](https://arxiv.org/abs/2604.19710) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2604.19710) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://spanvla.github.io/)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/AutoVLA_framework.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning**

**Zewei Zhou***, <span style="color:#7a8288;">Tianhui Cai*, Seth Z. Zhao, Yun Zhang, Zhiyu Huang, Bolei Zhou, Jiaqi Ma</span>

 AutoVLA is a novel VLA model that unifies reasoning and action generation within a single autoregressive generation model for end-to-end autonomous driving.

[NeurIPS, 2025](https://neurips.cc/) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2506.13757) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://autovla.github.io/) \| [![](https://img.shields.io/github/stars/ucla-mobility/AutoVLA?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/ucla-mobility/AutoVLA)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/V2XPnP.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction**

**Zewei Zhou**, <span style="color:#7a8288;">Hao Xiang, Zhaoliang Zheng, Seth Z Zhao, Mingyue Lei, Yun Zhang, Tianhui Cai, Xinyi Liu, Johnson Liu, Maheswari Bajji, Xin Xia, Zhiyu Huang, Bolei Zhou, Jiaqi Ma</span>

V2XPnP includes the first open-source V2X spatio-temporal fusion framework for cooperative perception and prediction and the first real-world V2X sequential dataset featuring all V2X collaboration modes (VC, IC, V2V, I2I).

<span style="color:#68349a;"> **Best Paper Award, ICCV 2025 DriveX Workshop** </span>

[ICCV, 2025](https://iccv.thecvf.com/) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2412.01812) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://mobility-lab.seas.ucla.edu/v2xpnp/) \| [![](https://img.shields.io/github/stars/Zewei-Zhou/V2XPnP?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/Zewei-Zhou/V2XPnP)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/TurboTrain.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**TurboTrain: Towards Efficient and Balanced Multi-Task Learning for Multi-Agent Perception and Prediction**

**Zewei Zhou***, <span style="color:#7a8288;"> Seth Z. Zhao*, Tianhui Cai, Zhiyu Huang, Bolei Zhou, Jiaqi Ma </span>

TurboTrain is an efficient training framework for multi-agent perception and prediction, eliminating the need for manually designing and tuning complex multi-stage training pipelines, reducing training time and improving performance.

[ICCV, 2025](https://iccv.thecvf.com/) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2508.04682) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://github.com/ucla-mobility/TurboTrain) \| [![](https://img.shields.io/github/stars/ucla-mobility/TurboTrain?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/ucla-mobility/TurboTrain)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/RiskMM.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Risk Map As Middleware: Towards Interpretable Cooperative End-to-end Autonomous Driving for Risk-Aware Planning**

**Zewei Zhou***, <span style="color:#7a8288;">Mingyue Lei*, Hongchen Li, Jiaqi Ma, Jia Hu</span>

RiskMM is an interpretable end-to-end cooperative driving framework by incorporating the Risk Map as Middleware, which explicitly captures the spatiotemporal risk distribution and facilitates planning with learning-based MPC.

[RA-L, 2025](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7083369) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2508.07686) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>]() 


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/Co-MTP.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Co-MTP: A Cooperative Trajectory Prediction Framework with Multi-Temporal Fusion for Autonomous Driving**

**Zewei Zhou***, <span style="color:#7a8288;">Xinyu Zhang*, Zhaoyi Wang, Yangjie Ji, Yanjun Huang, Hong Chen</span>

Co-MTP is a general cooperative trajectory prediction framework with multi-temporal fusion, which leverages the V2X system to fully capture the interaction among agents in both history and future domains to benefit the planning.

[ICRA, 2025](https://2025.ieee-icra.org/) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2502.16589) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://xiaomiaozhang.github.io/Co-MTP/) \| [![](https://img.shields.io/github/stars/xiaomiaozhang/Co-MTP?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/xiaomiaozhang/Co-MTP)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/V2X-Real.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**V2X-Real: a Large-Scale Dataset for Vehicle-to-Everything Cooperative Perception**

<span style="color:#7a8288;">Hao Xiang, Zhaoliang Zheng, Xin Xia, Runsheng Xu, Letian Gao,</span> **Zewei Zhou**<span style="color:#7a8288;">, Xu Han, Xinkai Ji, Mingxi Li, Zonglin Meng, Jin Li, Mingyue Lei, Zhaoyang Ma, Zihang He, Haoxuan Ma, Yunshuang Yuan, Yingqian Zhao, Jiaqi Ma</span>

V2X-Real is the first large-scale, real-world, multi-modal dataset for Vehicle-to-Everything (V2X) perception.

[ECCV, 2024](https://eccv.ecva.net/Conferences/2024)  \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/pdf/2403.16034) \| [<img src='images/project.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://mobility-lab.seas.ucla.edu/v2x-real) \| [![](https://img.shields.io/github/stars/ucla-mobility/V2X-Real?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/ucla-mobility/V2X-Real)

</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><img src='images/Comprehensive_Study_of_Speed_Prediction.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**A Comprehensive Study of Speed Prediction in Transportation System: From Vehicle to Traffic**

**Zewei Zhou**, <span style="color:#7a8288;"> Ziru Yang, Yuanjian Zhang, Yanjun Huang, Hong Chen, Zhuoping Yu

A complete picture of speed prediction and comprehensive analysis on speed prediction in transportation system at three levels, i.e. macro traffic, micro vehicles, and meso lane.

[iScience (Cell Press), 2022](https://www.cell.com/iscience/home) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://www.cell.com/iscience/fulltext/S2589-0042(22)00179-1)
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><img src='images/Survey_on_Trajectory_Prediction_Methods.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**A Survey on Trajectory-Prediction Methods for Autonomous Driving**

<span style="color:#7a8288;"> Yanjun Huang, Jiatong Du, Ziru Yang,</span> **Zewei Zhou**<span style="color:#7a8288;">, Lin Zhang, Hong Chen</span>

A comparative review and analysis of trajectory-prediction methods for autonomous driving and elaborate the popular methods based on physics, classic machine learning, deep learning, and reinforcement learning. 

<span style="color:#68349a;"> **Best Paper Award for Outstanding Survey, IEEE T-IV** </span>

[IEEE Transactions on Intelligent Vehicles (T-IV), 2022](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857) \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://ieeexplore.ieee.org/document/9756903)


</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🔬 Project

<div class='paper-box'><div class='paper-box-image'><img src='images/gif_parking.gif' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Automated Parking System with Automated Guided Vehicles (AGV)**

<span style="color:#7a8288;"> Institute of Intelligent Vehicles, Tongji University, *2020.10 - 2021.12*</span>

**Student Researcher**

Design an A*-based global motion planner for the given park and propose a cooperative planning and control framework for the four AGVs groups to coordinate their movement and guide them to move a bus to its destination. 

The system is tested in a real AGVs platform and can provide a valet experience.


</div>
</div>

# 📖 Educations
- *2023.09 - Now*, Ph.D., Transportation Engineering, <img src='images/ucla_seal.jpg' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> University of California, Los Angeles (UCLA), U.S.
- *2020.09 - 2023.06*, M.S., Automotive Engineering, <img src='images/Tongji_logo.png' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> Tongji University (Tongji), Shanghai, China **(Test Waiver Admission)**
- *2016.09 - 2020.06*, B.Eng., Automotive Engineering, <img src='images/CQU_logo.png' style='width: 25px; height: auto; vertical-align:-35%; margin-right:0px;'> Chongqing University (CQU), Chongqing, China **(Outstanding Graduate,Top 1%)**

# 🎖 Honors and Awards
- *2025.10* &nbsp; [Best Paper Award, ICCV 2025 DriveX Workshop](https://drivex-workshop.github.io/)
- *2025.10* &nbsp; [NeurIPS 2025 Scholar Award](https://neurips.cc/)
- *2025.09* &nbsp; [Amazon AI PhD Fellowship](https://www.sciencehub.ucla.edu/2025-amazon-ai-phd-fellows/#main-footer)
- *2025.01* &nbsp; [Tier 1 Winner of U.S. DOT Intersection Safety Challenge](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge-stage-1b-system-assessment-and) with a $750k award
- *2024.08* &nbsp; [Best Paper Award for Outstanding Survey](), [IEEE T-IV](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)
- *2023.06* &nbsp; Shanghai Outstanding Graduate (**Top 1%**)
- *2022.11* &nbsp; Weichai Scholarship (**Top 2%**)
- *2021.09* &nbsp; Tongji Outstanding Master’s Scholarship
- *2019.09* &nbsp; Gratitude to Scientists Scholarship (**Highest scholarship in CQU, Top 0.2%**)
- *2018.09* &nbsp; National Scholarship, China (**Top 1%**)
<!-- - *2018-2019* &nbsp; CQU First-class Scholarship (Four times, **Top 2  %**) -->

<!-- - *2024.01* &nbsp; [Winner of Intersection Safety System Challenge from USDOT Stage 1A with a ](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge) -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📚 Academic Services
**Organizer**:
- Organizer of [DriveX Workshop on Foundation Models for V2X-Based Cooperative Autonomous Driving](https://drivex-workshop.github.io/iccv2025/) in [CVPR 2026](https://drivex-workshop.github.io/cvpr2026/), [CVPR 2025](https://drivex-workshop.github.io/cvpr2025/) and [ICCV 2025](https://drivex-workshop.github.io/iccv2025/).
- Organizer of Tutorial on [Beyond Self-Driving: Exploring Three Levels of Driving Automation](https://drivex-tutorial.github.io/) at [ICCV 2025](https://iccv.thecvf.com/).

**Conference Reviewer**: 
- IEEE / CVF Computer Vision and Pattern Recognition ([CVPR](https://cvpr.thecvf.com/))
- Annual Conference on Neural Information Processing Systems ([NeurIPS](https://neurips.cc/))
- Annual AAAI Conference on Artificial Intelligence ([AAAI](https://aaai.org/conference/aaai/aaai-26/))
- IEEE International Conference on Robotics and Automation ([ICRA](https://www.ieee-ras.org/conferences-workshops/fully-sponsored/icra))
- IEEE/RSJ International Conference on Intelligent Robots and Systems ([IROS](https://www.ieee-ras.org/conferences-workshops/financially-co-sponsored/iros))
- IEEE Intelligent Vehicles Symposium ([IV](https://ieee-iv.org/))
- IEEE Intelligent Transportation Systems Conference ([ITSC](https://ieee-itsc.org/))

**Journal Reviewer**: 
- International Journal of Computer Vision ([IJCV](https://link.springer.com/journal/11263))
- IEEE Robotics and Automation Letters ([RA-L](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7083369))
- IEEE Transactions on Intelligent Transportation Systems ([T-ITS](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979))
- IEEE Transactions on Intelligent Vehicles ([T-IV](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857))


# 🏓 Miscellaneous
- I am a big fan of guitar, especially [Fingerstyle](https://en.wikipedia.org/wiki/Fingerstyle_guitar). My favorite acoustic guitarist is [Satoshi Gogo](https://en.gogosatoshi.com/). I also enjoy playing ping pong and badminton.
- I enjoy graphic design, and designed the logo for the Joint Lab [SFVGL](https://csrf.ac.uk/international/) of Tongji University and University of Cambridge.