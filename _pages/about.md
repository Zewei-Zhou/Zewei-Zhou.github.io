---
permalink: /
title: ""
excerpt: ""
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

👋 I am a PhD student in the [UCLA Mobility Lab](https://mobility-lab.seas.ucla.edu/) of the University of California, Los Angeles (UCLA), advised by [Prof. Jiaqi Ma](https://mobility-lab.seas.ucla.edu/about/). I received my master’s degree from Tongji University with the honor of Shanghai Outstanding Graduate, and conducted research at the Institute of Intelligent Vehicles (TJU-IIV) directed by [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ) and [Prof. Zhuoping Yu](https://ieeexplore.ieee.org/author/37402463600). 

My research focuses on the scene understanding and reasoning of autonomous systems, which enables vehicles/robots to intelligently interact and cooperate with others. 

# 🔥 News
- *2025.01*: &nbsp;🎉 Our team secured the Tier 1 in the [U.S.DOT Intersection Safety Challenge](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge-stage-1b-system-assessment-and) with a $750k award!
- *2024.12*: &nbsp;👏 Our [V2XPnP](https://mobility-lab.seas.ucla.edu/v2xpnp/) paper on cooperative perception and prediction has been released. Enjoy it! 
- *2024.09*: &nbsp;🤞 Our three papers have been submitted to [ICRA 2025](https://2025.ieee-icra.org/). Fingers crossed!
- *2024.08*: &nbsp;🎉 Our survey paper on trajectory prediction has been awarded as [_Best Paper Award for Outstanding Survey_]() of [_IEEE T-IV_](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)! 
- *2024.07*: &nbsp;👏 Our [V2X-Real](https://mobility-lab.seas.ucla.edu/v2x-real/) paper on multi-agents and multi-modal cooperative perception has been accepted by [_ECCV 2024_](https://eccv.ecva.net/virtual/2024/poster/988). 
- *2023.06*: &nbsp;🎉 Shanghai Outstanding Graduate Honor!
- *2022.03*: &nbsp;🎉 Our paper on speed prediction in transportation systems has been accepted by [_iScience (Cell Press)_](https://www.cell.com/iscience/home)！
- *2021.12*: &nbsp;🤖 Our multiple automated guided vehicles (AGVs) passed through field testing and could coordinate movements with each other, [providing a valet experience](/#-project).

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><img src='images/V2XPnP_framework.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction**

**Zewei Zhou**, Hao Xiang, Zhaoliang Zheng, Seth Z Zhao, Mingyue Lei, Yun Zhang, Tianhui Cai, Xinyi Liu, Johnson Liu, Maheswari Bajji, Jacob Pham, Xin Xia, Zhiyu Huang, Bolei Zhou, Jiaqi Ma

_**arXiv**_, 2024 \| [_**Paper**_](https://arxiv.org/abs/2412.01812) \| [_**Project**_](https://mobility-lab.seas.ucla.edu/v2xpnp/) \| [![](https://img.shields.io/github/stars/Zewei-Zhou/V2XPnP?style=social&label=Code%20Stars)](https://github.com/Zewei-Zhou/V2XPnP)

- We proposed V2XPnP, the first open-source V2X spatio-temporal fusion framework for cooperative perception and prediction, and V2XPnP Sequential Dataset, the first large-scale, real-world V2X sequential dataset featuring multiple agents and all V2X collaboration modes (VC, IC, V2V, I2I).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/V2X-Real.png' alt="sym" width="95%"></div>
<div class='paper-box-text' markdown="1">

**V2X-Real: a Large-Scale Dataset for Vehicle-to-Everything Cooperative Perception**

Hao Xiang, Zhaoliang Zheng, Xin Xia, Runsheng Xu, Letian Gao, **Zewei Zhou**, Xu Han, Xinkai Ji, Mingxi Li, Zonglin Meng, Jin Li, Mingyue Lei, Zhaoyang Ma, Zihang He, Haoxuan Ma, Yunshuang Yuan, Yingqian Zhao, Jiaqi Ma

_**ECCV**_, 2024 \| [_**Paper**_](https://arxiv.org/abs/2403.16034) \| [_**Project**_](https://mobility-lab.seas.ucla.edu/v2x-real) \| [![](https://img.shields.io/github/stars/ucla-mobility/V2X-Real?style=social&label=Code%20Stars)](https://github.com/ucla-mobility/V2X-Real)


- We proposed V2X-Real, the first large-scale, real-world, multi-modal dataset for Vehicle-to-Everything (V2X) perception.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/Comprehensive_Study_of_Speed_Prediction.png' alt="sym" width="95%"></div>
<div class='paper-box-text' markdown="1">

**A Comprehensive Study of Speed Prediction in Transportation System: From Vehicle to Traffic**

**Zewei Zhou**, Ziru Yang, Yuanjian Zhang, Yanjun Huang, Hong Chen, Zhuoping Yu

_**iScience (Cell Press)**_, 2022 \| [_**Paper**_](https://www.cell.com/iscience/fulltext/S2589-0042(22)00179-1)

- We aim to draw a complete picture of speed prediction, and comprehensively analyze existing research on speed prediction in transportation system at three levels, i.e. macro traffic, micro vehicles, and meso lane.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/Survey_on_Trajectory_Prediction_Methods.png' alt="sym" width="95%"></div>
<div class='paper-box-text' markdown="1">

**A Survey on Trajectory-Prediction Methods for Autonomous Driving**

Yanjun Huang, Jiatong Du, Ziru Yang, **Zewei Zhou**, Lin Zhang, Hong Chen

_**IEEE Transactions on Intelligent Vehicles**_, 2022 

[_Best Paper Award for Outstanding Survey_]()

- We provide a comparative review of trajectory-prediction methods for autonomous driving and elaborate the popular methods based on physics, classic machine learning, deep learning, and reinforcement learning. 
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🔬 Project

<div class='paper-box'><div class='paper-box-image'><img src='images/gif_parking.gif' alt="sym" width="95%"></div>
<div class='paper-box-text' markdown="1">

[Automated Parking System for Electric Bus with Automated Guided Vehicles (AGV)](), Institute of Intelligent Vehicles, Tongji University, *2020.10 - 2021.12*

_**Student Researcher**_

- We design an A*-based global motion planner for the given park and propose a cooperative planning and control framework for the four AGVs groups to coordinate their movement and guide them to move a bus to its destination.
- The framework is validated and tested in a real bus and AGVs.


</div>
</div>

# 📖 Educations
- *2023.09 - Now*, Ph.D., Transportation Engineering, <img src='images/ucla_seal.jpg' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> University of California, Los Angeles (UCLA), U.S.
- *2020.09 - 2023.06*, M.S., Automotive Engineering, <img src='images/Tongji_logo.png' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> Tongji University (Tongji), Shanghai, China **(Test Waiver Admission)**
- *2016.09 - 2020.06*, B.Eng., Automotive Engineering, <img src='images/CQU_logo.png' style='width: 25px; height: auto; vertical-align:-35%; margin-right:0px;'> Chongqing University (CQU), Chongqing, China **(Outstanding Graduate,Top 1%)**

# 🎖 Honors and Awards
- *2025.01* &nbsp; [Tier 1 Winner of U.S. DOT Intersection Safety Challenge](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge-stage-1b-system-assessment-and) with a $750k award
- *2024.08* &nbsp; [_Best Paper Award for Outstanding Survey_]() of [_IEEE T-IV_](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)
- *2023.06* &nbsp; Shanghai Outstanding Graduate (**Top 1%**)
- *2022.11* &nbsp; Weichai Scholarship (**Top 2%**)
- *2021.09* &nbsp; Tongji Outstanding Master’s Scholarship
- *2019.09* &nbsp; Gratitude to Scientists Scholarship (**Highest scholarship in CQU, Top 0.2%**)
- *2018.09* &nbsp; National Scholarship, China (**Top 1%**)
- *2018-2019* &nbsp; CQU First-class Scholarship (Four times, **Top 2  %**)

<!-- - *2024.01* &nbsp; [Winner of Intersection Safety System Challenge from USDOT Stage 1A with a ](https://www.transportation.gov/briefing-room/us-dot-announces-winners-intersection-safety-challenge) -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📚 Academic Services
**Workshop Organizer**:
- Organizer of [DriveX Workshop on Foundation Models for V2X-Based Cooperative Autonomous Driving](https://drivex-workshop.github.io/) in CVPR 2025.

**Conference Reviewer**: 
- IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR) 2025, IEEE International Conference on Robotics and Automation (ICRA) 2025, IEEE Intelligent Vehicles Symposium (IV) 2024, IEEE Intelligent Transportation Systems Conference (ITSC) 2023 – 2024

**Journal Reviewer**: 
- IEEE Transactions on Intelligent Transportation Systems (T-ITS), IEEE Transactions on Intelligent Vehicles (T-IV), IEEE Open Journal of Intelligent Transportation Systems


# 🏓 Miscellaneous
- I am a big fan of guitar, especially [Fingerstyle](https://en.wikipedia.org/wiki/Fingerstyle_guitar). My favorite acoustic guitarist is [Satoshi Gogo](https://en.gogosatoshi.com/). I also enjoy playing ping pong and badminton.
- I enjoy graphic design, and designed the logo for the Joint Lab [SFVGL](https://csrf.ac.uk/international/) of Tongji University and University of Cambridge.