---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  dl {
    margin-bottom: 60px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  img {
    display: block;
    margin: 0px 10px 10px 0px; /* 图片居中 上右下左*/ 
    max-width: 100%; /* 限制图片最大宽度 */
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }


  dl dd {
  margin-top: 5px; 
  margin-bottom: 5px;
}

  dl dd strong {
  font-weight: bold;
  color: black;
  }


  .co-first {
    color: red;
  }

</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 😊 About Me

Greetings! I am Qifan Liang (Simon Leong), a current undergraduate student majoring in Computer Science and Technology at Wuhan University, and also a lab member of the [National Multimedia Software Engineering Technology Research Center at Wuhan University](http://multimedia.whu.edu.cn/). Fortunately, I have conducted computer vision research under Prof. [Jens Rittscher](https://scholar.google.com/citations?user=ED4V7hEAAAAJ) at Oxford University, Prof. [Zhen Han](http://multimedia.whu.edu.cn/index.php?a=show&catid=69&id=135) and Prof. [Kaimin Sun](https://jszy.whu.edu.cn/sunkaimin/en/index/259374/list/index.htm) at Wuhan University. Lastly, welcome to follow my [github account](https://github.com/Simon-leong)!


# 🔬 Research Interest
"Computer vision will open our eyes to a new world of possibilities, where machines not only see but understand the world as we do." - Inspired by Fei-Fei Li

My research interests : 
- **Fundamentals and applications** of deep learning algorithms, and design of training strategies for **few-shot scenarios**. 
- Exploring the recovery of **visually distorted elements** (smoke, haze) in dynamic environments, especially in the medical field. 
- **Human-centered visual perception** and **2D/3D scene understanding**.


# 🔥 News

- 2024.11: I won the DiDi Inc. Outstanding Undergraduate Scholarship (**6/685 in department**) of WHU.
- 2024.10: I ranked **17/227** in the 2024 annual comprehensive assessment.
- 2024.10: I won the Second-Class Scholarship (**Top10%**, school-wide) and was graded as Merit Student (**Top5%**, school-wide) of WHU.
- 2024.09: One **Chinese Software Copyright** "All-weather High-precision Transmission Tower Vibration Monitoring System" has been published.
- 2024.06: My new project has won **2** national awards in 2024.
- 2024.05: One paper is accepted by [ACM Transactions on Multimedia Computing, Communications, and Applications (**TOMM**)](https://dl.acm.org/doi/10.1145/3672400).
- 2024.05: I won the National University Students’Innovation and Entrepreneurship Fund (**Top 3%**, school-wide) of WHU.
- 2024.03: I won the Lei Jun Computer Innovation and Development Fund (**Top 7.2%**, in major) of WHU.
- 2023.11: I won the Samsung Group Outstanding Undergraduate Scholarship (**1/685 in department**) of WHU.
- 2023.10: I ranked **2/227** in the 2023 annual comprehensive assessment.
- 2023.10: I won the First-Class Scholarship (**Top5%**, school-wide) and was graded as Merit Student (**Top5%**, school-wide) of WHU.
- 2023.09: One **Chinese Software Copyright** "Innovative Integrated Platform for Emergency Monitoring of Forest Fires" has been published.
- 2023.07: One **Chinese patent** "Method for Smoke Removal in Fire Images Based on Improved Cycle-Dehaze Neural Network" has been published.
- 2023.07: One paper is accepted by ["2023 30th International Conference on Geoinformatics"](https://ieeexplore.ieee.org/document/10247973).
- 2023.06: [My project](https://github.com/Simon-leong/SenHuo-Forest-Fire-Intelligence-Integration-Software-System-UI) has won **3** national awards in 2023.
- 2022.10: I won the Third-Class Scholarship (**Top15%**, school-wide) and was graded as Outstanding Student (**Top30%**, school-wide) of WHU.

# 📝 Publications

<sup>&dagger;</sup> : equal contribution, <sup>*</sup> : corresponding author

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="images/tomm_new.png">
</dt>
  <dd><a href="https://dl.acm.org/doi/10.1145/3672400"><strong>Few-Shot Face Sketch-to-Photo Synthesis via Global-Local Asymmetric Image-to-Image Translation
</strong></a></dd>
<dd>Yongkang Li, <strong><u>Qifan Liang</u></strong>, Wenjun Mai, Zhen Han*, Zhenhua Wang</dd>
    <dd>ACM Transactions on Multimedia Computing, Communications, and Applications (<strong>TOMM</strong>), 2024 </dd>
<dd><strong> Responsibilities: </strong></dd>
<dd> (1) Problem Analysing (few-shot image-to-image translation); (2) Algorithms Designing (style transfer etc.); (3) Experiments Analysing; (4) Paper Writing </dd>
</dl>


<hr >


<dl>
  <dt><img align="left" width="250"
hspace="10" wspace="20" src="images/CPGIS.png">
</dt>
  <dd><a href="https://ieeexplore.ieee.org/document/10247973"><strong>Study on Forest Fire Diffusion Method Based on Cellular Automata</strong></a></dd>
<dd>Tonghe Zhang&dagger;, Qingxiang Meng*&dagger; , Jinchun Liu, <u><strong>Qifan Liang</strong></u></dd>
<dd>International Conference on Geoinformatics(<strong>CPGIS</strong>), 2023</dd>
<dd><strong> Responsibilities: </strong></dd>
<dd> (1) Problem Analysing (forest fire perdiction); (2) Algorithms Designing; (3) Software Developing </dd>
</dl>

<hr>

##  🖨️In submission & Manuscripts

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="images/iccv_new.png">
</dt>
  <dd><strong>Smokeformer: A Mask-Driven Dynamic Transformer Framework for Endoscopic Video Smoke Removal and a Novel Benchmark Dataset</strong></dd>
<dd><strong><u>Qifan Liang</u></strong>, Zhen Han*, Junlin Li, Yibing Bai, Zhongyuan Wang</dd>
<dd><strong> Responsibilities: </strong></dd>
<dd> (1) Problem Analysing (surgical video de-smoking); (2) Dataset Designing (synthetic smoke videos/paired smoke masks); (3) Algorithms Designing; (4) Experiments Analysing </dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="images/aaai_new_new.png">
</dt>
  <dd><strong>	
Scenario-Aware Meta-Learning: Ensuring Safety and Scalability in Trajectory Prediction
</strong></dd>
<dd><strong><u>Qifan Liang&dagger;</u></strong>, Shengyi Li&dagger;, Haoying Li, Jens Rittscher* </dd>
<dd><strong> Responsibilities: </strong></dd>
<dd> (1) Problem Analysing (long-tail samples); (2) Algorithms Designing (meta-learning); (3) Experiments Analysing </dd>
</dl>

<hr>

**<u>The above 2 papers will be submitted to 2025 Top-tier conferences.</u>**
<hr>

# 🎡 Projects

<dl>
  <dt><img align="left" width="400"
hspace="10" wspace="20" src="images/senhuo_new.gif">
</dt>
  <dd><a href="https://github.com/Simon-leong/SenHuo-Forest-Fire-Intelligence-Integration-Software-System-UI"><strong>Multi-Source Perception and Intelligent Prediction Emergency Monitoring Platform for Forest Fires</strong></a></dd>
  <dd><strong> Responsibilities: </strong></dd>
<dd> (1) Team work organization; (2) Algorithm design; (3) Software implementation </dd>
<dd><strong> Awards: </strong></dd>
<dd> (1) National Second Prize <strong>(Top 0.7%)</strong> in 2023 Chinese Collegiate Computing Competition; (2) National First Prize <strong>(Top 1.7%)</strong> in 2023 China “Dingxin Cup” National Youth Innovation and Entrepreneurship Competition; (3) National Grand Prize <strong>(Top 0.5%)</strong> in 2023 National University Student Surveying and Mapping Discipline Intelligence Competition </dd>
</dl>

<hr>

<dl>
  <dt><img align="left" width="200"
hspace="10" wspace="20" src="images/tower.GIF">
</dt>
  <dd><strong>All-Weather Monitoring System for Power Transmission Towers Using Thermal Infrared Technology</strong></dd>
  <dd><strong> Responsibilities: </strong></dd>
<dd> (1) Algorithm design; (2) Hardware implementation; (3) Software implementation </dd>
<dd><strong> Awards: </strong></dd>
<dd> (1) National Second Prize <strong>(Top 0.7%)</strong> in 2024 Chinese Collegiate Computing Competition; (2) National University Students’Innovation and Entrepreneurship Fund <strong>(Top 3%, school-wide)</strong> of WHU </dd>
</dl>

<hr>

# 🏅 Honors and Awards

- *2024.11* **Outstanding Undergraduate Scholarship** (Award Rate: 10/685, major-wide) *DiDi Inc.*
- *2024.10* **Merit Student** (Award Rate: 5%, school-wide) *Wuhan University*
- *2024.10* **Second-Class Scholarship** (Award Rate: 10%,school-wide) *Wuhan University*
- *2024.08* **National Second Prize** (Award Rate: 0.7%, nation-wide) *2024 Chinese Collegiate Computing Competition*
- *2024.05* **National University Students’Innovation and Entrepreneurship Fund** (Award Rate: 3%, school-wide) *Wuhan University*
- *2024.03* **Lei Jun Computer Innovation and Development Fund** (Award Rate: 7.2%, major-wide) *Xiaomi Corporation*
- *2023.11* **Outstanding Undergraduate Scholarship** (Award Rate: 1/685, major-wide) *Samsung Group*
- *2023.10* **Merit Student** (Award Rate: 5%, school-wide) *Wuhan University*
- *2023.10* **First-Class Scholarship** (Award Rate: 5%, school-wide) *Wuhan University*
- *2023.06* **National Grand Prize** (Award Rate: 0.5%, nation-wide) *2023 National University Student Surveying and Mapping Discipline Intelligence Competition.*
- *2023.06* **National First Prize** (Award Rate: 1.7%, nation-wide) *2023 China “Dingxin Cup” National Youth Innovation and Entrepreneurship Competition*
- *2023.06* **National Second Prize** (Award Rate: 0.7%, nation-wide) *2023 Chinese Collegiate Computing Competition*
- *2022.10* **Outstanding Student** (Award Rate: 30%, school-wide) *Wuhan University*
- *2022.10* **Third-Class Scholarship** (Award Rate: 15%, school-wide) *Wuhan University*


# 📖 Educations

- *2021.09 - 2025.06*, Undergraduate, [School of Computer Science](https://cs.whu.edu.cn/), [Wuhan University](https://www.whu.edu.cn/), China. B.E. in Engineering. **(GPA: 90.92; Ranked Top 1% in the 2022-2023 and Top 7% in the 2023-2024, respectively)**


# 💻 Internships

- *2023.05 - Present*, Student Research Assistant at [the National Engineering Research Center for Multimedia Software lab, WHU](http://multimedia.whu.edu.cn/), Supervised by Prof. [Zhen Han](http://multimedia.whu.edu.cn/index.php?a=show&catid=69&id=135)
- *2024.06 - 2024.10*, Remote Summer Research Internship at [Oxford Big Data Institute](https://www.bdi.ox.ac.uk/) (Oxford University), Supervised by Prof. [Jens Rittscher](https://scholar.google.com/citations?user=ED4V7hEAAAAJ)
- *2022.10 - 2023.5,* Student Research Assistant at [the State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing lab, WHU](https://liesmars.whu.edu.cn/), supervised by Prof. [Kaimin Sun](https://jszy.whu.edu.cn/sunkaimin/en/index/259374/list/index.htm)

# 🎢 Activities

## 🥁 voluntary service

- *2024.02*, Volunteer Program for College Growth and Personal Career Planning, Wuhan, China
- *2023.06*, Computer Vision Knowledge Popularization Education Volunteer Activity, Gaozhou, China
- *2022.06*, Higher Computer Knowledge Science Popularization Volunteer Activity, Maoming, China
- *2022.01*, Chinese New Year Traffic Order Maintenance Volunteer Program, Maoming, China
- *2021.09*, Seminar on Sharing Experiences in Learning Languages for the Higher Education Examination, Shimen Middle School, Foshan, China

## 🎤 Academic Experiences

- Conference Participant, China Computer Federation (CCF) Computer Networking Conference, Wenzhou, China, 2023
- Conference Participant, Intelligent Transportation Networking and Telematics Yongjia Forum, Yongjia, China, 2023

## 🏀 Sports

- I have a deep passion for badminton, showcased through years of competing in local tournaments and organizing community matches to share the sport's excitement. 
- Swimming also holds a special place in my heart. From early morning training sessions to competing in relay races and open-water events, I’ve consistently pushed my limits. 
