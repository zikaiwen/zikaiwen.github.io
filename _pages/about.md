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

Hi there! I am a **human-computer interaction (HCI)** researcher specializing in **usable privacy and security**. As privacy and security technologies advance, they often prioritize automation. This leaves users passively accepting protection measures they neither fully understand nor can verify. I believe that **user autonomy** should be fundamental to privacy and security management in today's complex cyberspace, with technology as a supporting tool. My research advances user autonomy principles through three core pillars: 1) designing evidence-based digital safety educational games, 2) developing human-centered defenses against AI-enabled threats, and 3) enabling informed decisions with appropriate AI support. My research has been published in leading venues including ACM CHI, IEEE S&P, and Information Sciences.

I am a postdoc in the Computer Science Department at [Virginia Tech](https://website.cs.vt.edu/), working with [Prof. Yaxing Yao](https://yaxingyao.cs.vt.edu/). I am fortunate to have worked as a postdoc at [HKUST VIS Lab](http://vis.cse.ust.hk/vislab_homepage/people.html), following my Ph.D. in computer science from [Cornell University](https://www.cs.cornell.edu/) (2021). Before that, I recieved my joint first-class honours bachelor degrees in computer science from [University of Strathclyde, Glasgow, U.K.](https://www.strath.ac.uk/) and [BUCT, Beijing, China](https://www.buct.edu.cn/main.htm).

# 🔥 News
<div class="responsive-scroll-container">
<ul> 
    <li><em><strong>2024.10:</strong></em> 🎉 <a href="https://website.cs.vt.edu/research/Seminars/zikaialex_wen.html">Join my Oct 25 Virginia Tech talk on interactive gaming & intelligent agent systems for privacy & security!</a></li> 
    <li><em><strong>2024.08:</strong></em> 🎉 <a href="https://www.aminer.cn/ai2000/search_rank?id=562cf8b845cedb3398d18ca9&searchValue=Zikai%20Wen%20(Alex)&yearLeft=2014&yearRight=2024">I am honored to receive the AI 2000 Most Influential Scholar Award Honorable Mention in security and privacy!</a></li>
    <li><em><strong>2024.07:</strong></em> 🎉 <a href="https://chi2025.acm.org/subcommittees/selecting-a-subcommittee/#user_experience">I am serving as an Associate Chair of ACM CHI 2025. Please submit your amazing work here!</a></li>
    <li><em><strong>2024.05:</strong></em> 🎉 <a href="https://spei2024.github.io/">I'm co-organizing a SOUPS workshop on revolutionizing privacy & security EdTech. Join us on Aug 11!</a></li>
    <li><em><strong>2024.02:</strong></em> 🎉 <a href="https://hcil.umd.edu/events/event/bbl-speaker-series-decoding-teenagers-implicit-struggles-with-accessibility-and-safety-in-computing-technologies/">Join my April 18 UMD BBL talk on teenagers' implicit struggles with info tech safety & accessibility!</a></li>
    <li><em><strong>2023.07:</strong></em> 🎉 <a href="https://chi2024.acm.org/subcommittees/selecting-a-subcommittee/">I am serving as an Associate Chair of ACM CHI 2024. Please submit your amazing work here!</a></li>
    <li><em><strong>2022.11:</strong></em> 🎉 <a href="https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/">I have been awarded the Fellowship of China Postdoctoral Science Foundation! A big thank you to my research team!</a></li>
</ul>  
</div>

<style>
.responsive-scroll-container {
  max-height: 14vh; /* Adjust as needed */
  overflow-y: auto;
  padding: 10px;
  border: 1px solid #ccc;
}

/* Smooth scrolling on mobile */
@media (hover: none) {
  .responsive-scroll-container {
    -webkit-overflow-scrolling: touch;
  }
}
</style>

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCI Journal</div><img src='images/dpposter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-Sharing Decision](https://www.sciencedirect.com/science/article/pii/S0020025523003201) in Information Sciences, Sep. 2023.

**Authors:** **Zikai Alex Wen**, Jingyu Jia, Hongyang Yan, Yaxing Yao, Zheli Liu, Changyu Dong

**Highlights:** Our explanatory illustration design simplifies the understanding of differential privacy protection of numerical data. A survey of 228 people shows visual illustration outperformed text-based explanation in understanding differential privacy. Learning about privacy-enhancing technology does not necessarily increase the willingness to share data.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI'19</div><img src='images/whathackpaper.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What.Hack: Engaging Anti-Phishing Training Through a Role-Playing Phishing Simulation Game](https://dl.acm.org/doi/10.1145/3290605.3300338) in the proceedings of the SIGCHI Conference on Human Factors in Computing Systems (CHI), 2019.

**Authors:** **Zikai Alex Wen**, Zhiqiu Lin, Rowena Chen, Erik Andersen

**Highlights:** People being phished is due in part to insufficient and tiresome user training in cybersecurity. we designed the game What.Hack, which not only teaches phishing concepts but also simulates actual phishing attacks in a role-playing game to encourage the player to practice defending themselves.

**Pointer:** [Game](https://research.zkwen.site/whatdothack/)

</div>
</div>

# 📖 Full Publications

Symbol \* indicates that I am the (co-)corresponding author. My current citation status is: <a href='https://scholar.google.com/citations?user=apCH14IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

| Venue   | Title  | Author(s) | Theme(s) | 
| :-----: | ------ | --------- | -------- |
| **ISCI Journal** | [DPGazeSynth: Enhancing Eye-Tracking Virtual Reality Privacy With Differentially Private Data Synthesis](articles/rendpgazesynth24.pdf) | Xiaojun Ren, Jiluan Fan, Ning Xu, Shaowei Wang, [Changyu Dong](https://changyudong.site/), **Zikai Wen\*** | Privacy |
| **VLDB'24** | [Privacy Amplification via Shuffling: Unified, Simplified, and Tightened](articles/wangprivacy24.pdf) | Shaowei Wang, Yun Peng, Jin Li, **Zikai Wen**, Zhipeng Li, Shiyu Yu, [Di Wang](https://shao3wangdi.github.io/), Wei Yang | Privacy | 
| **AIS&P'23** | [Email Reading Behavior-Informed Machine Learning Model to Predict Phishing Susceptibility](articles/xuemail23.pdf) | Ning Xu, Jiluan Fan, **Zikai Wen\*** | Security |
| **ISCI Journal** | [The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-Sharing Decision](articles/weninfluence23.pdf) | **Zikai Alex Wen**, Jingyu Jia, Hongyang Yan, [Yaxing Yao](https://yaxingyao.cs.vt.edu/), Zheli Liu, [Changyu Dong](https://changyudong.site/) | Privacy |
| **CHI Play EA'22** | [CollectiAR: Computer Vision-Based Word Hunt for Children with Dyslexia](articles/feicollectiar22.pdf) | Danlu Fei, Ze Gao, [Linping Yuan](http://yuanlinping.top/), **Zikai Alex Wen\*** | EdTech, Gaming |
| **IEEE GEM'22** | [What Features Influence Impact Feel? A Study of Impact Feedback in Action Games](articles/linfeatures22.pdf)  | Zhonghao Lin, Haihan Duan, **Zikai Alex Wen**, [Wei Cai](https://faculty.washington.edu/weicaics/index.html) | Gaming |
| **IEEE GEM'22** | [Understanding the Challenges of Team-Based Live Streaming for First-Person Shooter Games](articles/liunderstanding22.pdf)  | Jiaye Li, Minghao Li, **Zikai Alex Wen**, [Wei Cai](https://faculty.washington.edu/weicaics/index.html) | Gaming |
| **ASSETS EA'21** | [An Intelligent Math E-Tutoring System for Students with Specific Learning Disabilities](articles/wenmath21.pdf) | **Zikai Alex Wen**, [Yuhang Zhao](https://www.yuhangz.com/), Erica Silverstein, Shiri Azenkot | EdTech, Gaming |
| **ASSETS'20** | [Teacher Views of Math E-Learning Tools for Students with Specific Learning Disabilities](articles/wenteacher20.pdf) | **Zikai Alex Wen**, Erica O Silverstein, [Yuhang Zhao](https://www.yuhangz.com/), Anjelika Lynne S Amog, [Katherine Garnett](https://education.hunter.cuny.edu/about/faculty-staff/kate-garnett/), Shiri Azenkot | EdTech |
| **ASSETS EA'19** | [Teacher Perspectives on Math E-Learning Tools for Students with Specific Learning Disabilities](articles/wenteacher20.pdf) | **Zikai Alex Wen**, Anjelika Lynne S Amog, Shiri Azenkot, [Katherine Garnett](https://education.hunter.cuny.edu/about/faculty-staff/kate-garnett/) | EdTech |
| **CHI'19** | [What.Hack: Engaging Anti-Phishing Training Through a Role-Playing Cyber Defense Simulation Game](articles/wenwhatdothack19.pdf) | **Zikai Alex Wen**, [Zhiqiu Lin](https://linzhiqiu.github.io/), Rowena Chen, [Erik Andersen](http://www.cs.cornell.edu/~eland/) | Security, EdTech, Gaming |
| **CHI EA'17** | [What.Hack: Learn Phishing Email Defence the Fun Way](articles/wenwhatdothack19.pdf) | **Zikai Alex Wen\***, Yiming Li, Reid Wade, Jeffrey Huang, Amy Wang | Security, EdTech, Gaming | 
| **S&P'16** | [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](articles/kosbahawk16.pdf) | [Ahmed Kosba](https://akosba.github.io/), [Andrew Miller](https://soc1024.ece.illinois.edu/), [Elaine Shi](http://elaineshi.com/), **Zikai Wen**, [Charalampos Papamanthou](https://www.cs.yale.edu/homes/cpap/) | Privacy |
| **SAC'14** | [Efficient Protocols for Private Record Linkage](articles/wenprl14.pdf) | **Zikai Wen**, [Changyu Dong](https://changyudong.site/) | Privacy |
| **CCS'13** | [When Private Set Intersection Meets Big Data: an Efficient and Scalable Protocol](articles/dongpsi13.pdf) | [Changyu Dong](https://changyudong.site/), Liqun Chen, **Zikai Wen** | Privacy |

# 🎖 Awards and Grants
- *2024* [**AI 2000 Most Influential Scholar Award Honorable Mention in Security and Privacy**](awards/aminer.png) from AMiner
- *2022* [**The Fellowship of China Postdoctoral Science Foundation ($80K RMB)**](https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/) from CPSF
- *2022* [**Outstanding Service Award**](awards/mmsp-service22.pdf) from IEEE MMSP
- *2017* **The Student Game Design Competition Runner-Up** at ACM CHI 
- *2014* **The Andrew McGettrick Prize** from University of Strathclyde, Glasgow
- *2014* **The Outstanding Graduate of Beijing** from Beijing Municipal Education Commission
