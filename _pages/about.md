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

Hi there! I am a **human-computer interaction (HCI)** researcher specializing in **usable privacy and security**. I aim to help users enhance their anti-deception capabilities and digital resilience, enabling more empowering and enjoyable online communication. My research focuses on two main areas: (1) designing video games and interactive media to make cybersecurity education more engaging and (2) optimizing and developing privacy-enhancing technologies to improve the usability of digital privacy measures. My research has been published in leading computer and information science venues including ACM CHI, Information Sciences, ACM CCS, and IEEE S&P.

I am a postdoc in the Computer Science Department at [Virginia Tech](https://website.cs.vt.edu/), working with [Prof. Yaxing Yao](http://yaxingyao.com/). I am fortunate to have worked as a postdoc at [the HKUST Visualization Lab](http://vis.cse.ust.hk/vislab_homepage/people.html). I received my Ph.D. degree in computer science from [Cornell University](https://www.cs.cornell.edu/). Before that, I recieved my joint First-class Honours bachelor degree in computer science from [University of Strathclyde, Glasgow, U.K.](https://www.strath.ac.uk/) and [BUCT, Beijing, China](https://www.buct.edu.cn/main.htm).

# 🔥 News
- *2024.10*: &nbsp;🎉🎉 **I am seeking a tenure-track position in cybersecurity, computer science, information science, or a related field!**
- *2024.10*: &nbsp;🎉🎉 [Join my seminar talk at Virginia Tech, Oct 25, on transforming cybersecurity education with games and visual tech!](https://website.cs.vt.edu/research/Seminars/zikaialex_wen.html)
- *2024.08*: &nbsp;🎉🎉 [I am honored to receive the AI 2000 Most Influential Scholar Award Honorable Mention in Security and Privacy!](https://www.aminer.cn/ai2000/search_rank?id=562cf8b845cedb3398d18ca9&searchValue=Zikai%20Wen%20(Alex)&yearLeft=2014&yearRight=2024)
- *2024.07*: &nbsp;🎉🎉 [I am serving as an Associate Chair of ACM CHI 2025. Please submit your amazing work here!](https://chi2025.acm.org/for-authors/)
- *2024.04*: &nbsp;🎉🎉 [I'm co-organizing a SOUPS workshop on revolutionizing privacy & security EdTech. Join us on Aug 11!](https://spei2024.github.io/)
- *2023.07*: &nbsp;🎉🎉 [The e-Learning Ancillary Facilities Program in which I act as a co-investigator secures 30 Million HKD funding from QEF!](https://elafp.edb.edcity.hk/projects.php?lang=en)

<!-- - *2023.03*: &nbsp;🎉🎉 ["The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-sharing Decision" was published in Information Sciences Journal (JCR Q1, IF 8.1)!](https://www.sciencedirect.com/science/article/abs/pii/S0020025523003201) -->
<!-- - *2022.11*: &nbsp;🎉🎉 [I have been awarded the Fellowship of China Postdoctoral Science Foundation! A big thank you to my research team!](https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/) -->
<!-- - *2022.11*: &nbsp;🎉🎉 ["CollectiAR: Computer Vision-Based Word Hunt for Children with Dyslexia" poster was accepted by CHI Play'22.](https://cma.hkust-gz.edu.cn/zikai-ai-games/) -->
 <!-- - *2022.10*: &nbsp;🎉🎉 "New Differential Privacy Communication Pipeline and Design Framework" poster was accepted by SOUPS'22. -->

# 📝 Selected Publications 

Symbol \* indicates the corresponding authorship; Symbol ^ indicates a student I mentor.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCI Journal</div><img src='images/dpposter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-sharing Decision](https://www.sciencedirect.com/science/article/pii/S0020025523003201) in Information Sciences, Sep. 2023.

**Authors:** **Zikai Alex Wen**, Jingyu Jia, Hongyang Yan, Yaxing Yao, Zheli Liu, Changyu Dong

**Highlights:** Our explanatory illustration design simplifies the understanding of differential privacy protection of numerical data. A survey of 228 people shows visual illustration outperformed text-based explanation in understanding differential privacy. Learning about privacy-enhancing technology does not necessarily increase the willingness to share data.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AIS&P'23</div><img src='images/phishing-detect-flowchart.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Email Reading Behavior-Informed Machine Learning Model to Predict Phishing Susceptibility](https://link.springer.com/chapter/10.1007/978-981-99-9785-5_40) in the proceedings of the International Conference on Artificial Intelligence Security and Privacy (AIS&P), 2023.

**Authors:** Ning Xu^, Jiluan Fan^, **Zikai Wen\***

**Abstract:** As phishing threats intensify, our research develops innovative anti-phishing solutions using machine learning and eye-tracking, specifically the TransMLP Hybrid model that achieves an 88.75% accuracy rate. This model not only proactively alerts users to potential scams in real-time but also ensures consistent interpretation of eye-tracking data across various email interfaces and displays.

**Pointer:** [Github](https://github.com/zikaiwen/EmailEye-PhishPredict)

</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI Play EA'22</div><img src='images/collectiar.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CollectiAR: Computer Vision-Based Word Hunt for Children with Dyslexia](https://dl.acm.org/doi/abs/10.1145/3505270.3558318) in the EA of the Annual Symposium on Computer-Human Interaction in Play (CHI Play), 2022.

**Authors:** Danlu Fei, Ze Gao, Linping Yuan, **Zikai Alex Wen\***

**Abstract:** The existing word recognition and spelling training games for children with dyslexia were not able to leverage children's immediate vicinity. Therefore, we designed an augmented reality mobile game, CollectiAR, that uses computer vision to identify objects in the player's immediate vicinity.

**Pointers:** [Presentation](https://youtu.be/5kLCCoV4r1I)

</div>
</div>
-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI'19</div><img src='images/whathackpaper.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[What.Hack: Engaging Anti-Phishing Training Through a Role-Playing Phishing Simulation Game](https://dl.acm.org/doi/10.1145/3290605.3300338) in the proceedings of the SIGCHI Conference on Human Factors in Computing Systems (CHI), 2019.

**Authors:** **Zikai Alex Wen**, Zhiqiu Lin, Rowena Chen, Erik Andersen

**Abstract:** People being phished is due in part to insufficient and tiresome user training in cybersecurity. we designed the game What.Hack, which not only teaches phishing concepts but also simulates actual phishing attacks in a role-playing game to encourage the player to practice defending themselves.

**Pointer:** [Game](http://research.zkwen.site/whatdothack/)

</div>
</div>

# 📖 Full Publications

Symbol \* indicates that I am the (co-)corresponding author. My current citation status is: <a href='https://scholar.google.com/citations?user=apCH14IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
    

| Venue   | Title  | Author(s) | Theme(s) | 
| :-----: | ------ | --------- | -------- |
| **ISCI Journal** | [DPGazeSynth: Enhancing Eye-Tracking Virtual Reality Privacy With Differentially Private Data Synthesis](articles/ren24dpgazesynth.pdf) | Xiaojun Ren, Jiluan Fan, Ning Xu, Shaowei Wang, [Changyu Dong](https://changyudong.site/), **Zikai Wen\*** | Privacy |
| **VLDB'24** | [Privacy Amplification via Shuffling: Unified, Simplified, and Tightened](articles/wangprivacy24.pdf) | Shaowei Wang, Yun Peng, Jin Li, **Zikai Wen**, Zhipeng Li, Shiyu Yu, [Di Wang](https://shao3wangdi.github.io/), Wei Yang | Privacy | 
| **AIS&P'23** | [Email Reading Behavior-Informed Machine Learning Model To Predict Phishing Susceptibility](articles/xuemail23.pdf) | Ning Xu, Jiluan Fan, **Zikai Wen\*** | Security |
| **ISCI Journal** | [The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-sharing Decision](articles/weninfluence23.pdf) | **Zikai Alex Wen**, Jingyu Jia, Hongyang Yan, [Yaxing Yao](http://yaxingyao.com/), Zheli Liu, [Changyu Dong](https://changyudong.site/) | Privacy |
| **VIS EA'23** | [Time Walk: Blending Presence and History through AR Visualization](articles/waitime23.pdf) |  [Wai Tong](https://wtong2017.github.io/), [Linping Yuan](http://yuanlinping.top/), **Zikai Alex Wen\***, [Huamin Qu](http://huamin.org/) | Gaming |
| **CHI Play EA'22** | [CollectiAR: Computer Vision-Based Word Hunt for Children with Dyslexia](articles/feicollectiar22.pdf) | Danlu Fei, Ze Gao, [Linping Yuan](http://yuanlinping.top/), **Zikai Alex Wen\*** | EdTech, Gaming |
| **IEEE GEM'22** | [What Features Influence Impact Feel? A Study of Impact Feedback in Action Games](articles/linfeatures22.pdf)  | Zhonghao Lin, Haihan Duan, **Zikai Alex Wen**, [Wei Cai](https://faculty.washington.edu/weicaics/index.html) | Gaming |
| **IEEE GEM'22** | [Understanding the Challenges of Team-Based Live Streaming for First-person Shooter Games](articles/liunderstanding22.pdf)  | Jiaye Li, Minghao Li, **Zikai Alex Wen**, [Wei Cai](https://faculty.washington.edu/weicaics/index.html) | Gaming |
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
- *2023* [**The E-learning Ancillary Facilities Grant Co-investigator ($30 Million HKD)**](https://elafp.edb.edcity.hk/projects.php?lang=en) from QEF, Hong Kong
- *2022* [**The Fellowship of China Postdoctoral Science Foundation ($80K RMB)**](https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/) from CPSF, China
- *2022* [**Outstanding Service Award**](awards/mmsp-service22.pdf) from IEEE MMSP
- *2017* **The Student Game Design Competition Runner-Up** at ACM CHI 
- *2014* **The Andrew McGettrick Prize** from University of Strathclyde, Glasgow
- *2014* **The Outstanding Graduate of Beijing** from Beijing Municipal Education Commission

<!--# 📖 Educations-->
<!--- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!---->
<!--# 💬 Invited Talks-->
<!--- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. -->
<!--- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->
<!---->
<!--# 💻 Internships-->
<!--- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.-->
<!--# Backup Pub.-->
<!--| **SOUPS EA'22** | [New Differential Privacy Communication Pipeline and Design Framework](articles/jiadpcommunication22.pdf) | Jingyu Jia, **Zikai Alex Wen\***, [Zheli Liu](https://cc.nankai.edu.cn/2019/0515/c15392a183642/page.htm), [Changyu Dong](https://changyudong.site/) | S&P, HCI | -->
<!--| **ASSETS EA'22** | [Designing a Data Visualization Dashboard for Pre-Screening Hong Kong Students with Specific Learning Disabilities](articles/fungdashboard22.pdf) | Ka Yan Fung, **Zikai Alex Wen\***, [Haotian Li](https://haotian-li.com/), [Xingbo Wang](https://andy-xingbowang.com/), [Shenghui Song](https://eeshsong.home.ece.ust.hk/), [Huamin Qu](http://huamin.org/) | HCI |-->
<!--| **ASSETS EA'22** | [Designing a Game for Pre-Screening Students with Specific Learning Disabilities in Chinese](articles/funggame22.pdf) | Ka Yan Fung, Kuen Fung Sin, **Zikai Alex Wen**, Lik-Hang Lee, [Shenghui Song](https://eeshsong.home.ece.ust.hk/), [Huamin Qu](http://huamin.org/)| HCI|
-->
