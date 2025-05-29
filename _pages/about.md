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

Hi there! I am a **human-computer interaction (HCI)** researcher specializing in **usable privacy and security**. As privacy and security technologies become more advanced, users often passively accept protective measures without fully understanding or verifying them. I believe **user autonomy** is essential for managing privacy and security in today's complex cyberspace, with technology serving primarily as a supportive tool. My research advances this principle by designing evidence-based interactive interventions, such as educational video games, explanatory visualizations, and AI assistants. These digital tools empower users to better protect themselves and make informed decisions about managing their personal information. My research has been published in leading venues including ACM CHI, IEEE S&P, and Information Sciences.

I am a postdoc in the Computer Science Department at [Virginia Tech](https://website.cs.vt.edu/), working with [Prof. Yaxing Yao](https://yaxingyao.cs.vt.edu/). I am fortunate to have worked as a postdoc at [HKUST VIS Lab](http://vis.cse.ust.hk/vislab_homepage/people.html), following my Ph.D. in computer science from [Cornell University](https://www.cs.cornell.edu/) (2021). Before that, I recieved my joint first-class honours bachelor degrees in computer science from [University of Strathclyde, Glasgow, U.K.](https://www.strath.ac.uk/) and [BUCT, Beijing, China](https://www.buct.edu.cn/main.htm).

# 🔥 News
<div class="responsive-scroll-container">
<ul>
    <li><em><strong>2025.04:</strong></em> 🎉 <a href="https://sp2025.ieee-security.org/program.html#collapse-80" style="color:#85754d;">Our paper on facilitating family digital privacy discussions was accepted to IEEE S&P 2025!</a></li>
    <li><em><strong>2025.03:</strong></em> 🎉 <a href="https://csis.gmu.edu/pages/seminars.php?id=2025-03-25-seminar" style="color:#85754d;">Join my Mar 25 GMU guest lecture on user-tailored differential privacy in the digital age!</a></li>
    <li><em><strong>2024.10:</strong></em> 🎉 <a href="https://website.cs.vt.edu/research/Seminars/zikaialex_wen.html" style="color:#85754d;">Join my Oct 25 Virginia Tech talk on interactive gaming & intelligent agent systems for privacy & security!</a></li> 
    <li><em><strong>2024.08:</strong></em> 🎉 <a href="https://www.aminer.cn/ai2000/search_rank?id=562cf8b845cedb3398d18ca9&searchValue=Zikai%20Wen%20(Alex)&yearLeft=2014&yearRight=2024" style="color:#85754d;">I am honored to receive the AI 2000 Most Influential Scholar Award Honorable Mention in security and privacy!</a></li>
    <li><em><strong>2024.07:</strong></em> 🎉 <a href="https://chi2025.acm.org/subcommittees/selecting-a-subcommittee/#user_experience" style="color:#85754d;">I am serving as an Associate Chair of ACM CHI 2025. Please submit your amazing work here!</a></li>
    <li><em><strong>2024.05:</strong></em> 🎉 <a href="https://spei2024.github.io/" style="color:#85754d;">I'm co-organizing a SOUPS workshop on revolutionizing privacy & security EdTech. Join us on Aug 11!</a></li>
    <li><em><strong>2024.02:</strong></em> 🎉 <a href="https://hcil.umd.edu/events/event/bbl-speaker-series-decoding-teenagers-implicit-struggles-with-accessibility-and-safety-in-computing-technologies/" style="color:#85754d;">Join my April 18 UMD BBL talk on teenagers' implicit struggles with info tech safety & accessibility!</a></li>
    <li><em><strong>2023.07:</strong></em> 🎉 <a href="https://chi2024.acm.org/subcommittees/selecting-a-subcommittee/" style="color:#85754d;">I am serving as an Associate Chair of ACM CHI 2024. Please submit your amazing work here!</a></li>
    <li><em><strong>2022.11:</strong></em> 🎉 <a href="https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/" style="color:#85754d;">I have been awarded the Fellowship of China Postdoctoral Science Foundation! A big thank you to my research team!</a></li>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">S&P'25</div><img src='images/sp25-preview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Supporting Family Discussions About Digital Privacy Through Perspective-Taking: An Empirical Investigation](https://doi.ieeecomputersociety.org/10.1109/SP61157.2025.00149) in the proceedings of the IEEE Symposium on Security and Privacy (S&P), 2025.

**Authors:** **Zikai Wen**, Lanjing Liu, Yaxing Yao

**Highlights:** We present on the results of a structured activity promoting perspective-taking in privacy discussions with 13 parent-child dyads. We identified key communication challenges and addressed these challenges through scaffolded, moderated conversations between parents and children, to help families treat privacy as a spectrum and something that is context-dependent.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCI Journal</div><img src='images/dp-poster.jpg' alt="sym" width="100%"></div></div>
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

Symbol \* indicates that I am the (co-)corresponding author. My current citation statistics on Google Scholar: <a href='https://scholar.google.com/citations?user=apCH14IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

| Venue | Title and Authors | Field(s) |
| ----: | :---------------- | :------- |
| **S&P'25** | [Supporting Family Discussions About Digital Privacy Through Perspective-Taking: An Empirical Investigation](articles/wen25supporting.pdf) <br> **Zikai Wen**, <a href="https://lanjing.design" style="text-decoration:none; color:inherit;">Lanjing Liu</a>, <a href="https://yaxingyao.cs.vt.edu/" style="text-decoration:none; color:inherit;">Yaxing Yao</a> | Privacy,<br>EdTech |
| **ISCI Journal** | [DPGazeSynth: Enhancing Eye-Tracking Virtual Reality Privacy With Differentially Private Data Synthesis](articles/ren24dpgazesynth.pdf) <br> Xiaojun Ren, Jiluan Fan, Ning Xu, Shaowei Wang, <a href="https://changyudong.site/" style="text-decoration:none; color:inherit;">Changyu Dong</a>, **Zikai Wen\*** | Privacy |
| **VLDB'24** | [Privacy Amplification via Shuffling: Unified, Simplified, and Tightened](articles/wang24privacy.pdf) <br> Shaowei Wang, Yun Peng, Jin Li, **Zikai Wen**, Zhipeng Li, Shiyu Yu, <a href="https://shao3wangdi.github.io/" style="text-decoration:none; color:inherit;">Di Wang</a>, Wei Yang | Privacy |
| **AIS&P'23** | [Email Reading Behavior-Informed Machine Learning Model to Predict Phishing Susceptibility](articles/xue23mail.pdf) <br> Ning Xu, Jiluan Fan, **Zikai Wen\*** | Security |
| **ISCI Journal** | [The Influence of Explanation Designs on User Understanding Differential Privacy and Making Data-Sharing Decision](articles/wen23influence.pdf) <br> **Zikai Alex Wen**, Jingyu Jia, Hongyang Yan, <a href="https://yaxingyao.cs.vt.edu/" style="text-decoration:none; color:inherit;">Yaxing Yao</a>, Zheli Liu, <a href="https://changyudong.site/" style="text-decoration:none; color:inherit;">Changyu Dong</a> | Privacy |
| **CHI Play EA'22** | [CollectiAR: Computer Vision-Based Word Hunt for Children with Dyslexia](articles/fei22collectiar.pdf) <br> Danlu Fei, Ze Gao, <a href="http://yuanlinping.top/" style="text-decoration:none; color:inherit;">Linping Yuan</a>, **Zikai Alex Wen\*** | EdTech,<br>Gaming |
| **IEEE GEM'22** | [What Features Influence Impact Feel? A Study of Impact Feedback in Action Games](articles/lin22features.pdf) <br> Zhonghao Lin, Haihan Duan, **Zikai Alex Wen**, <a href="https://faculty.washington.edu/weicaics/index.html" style="text-decoration:none; color:inherit;">Wei Cai</a> | Gaming |
| **IEEE GEM'22** | [Understanding the Challenges of Team-Based Live Streaming for First-Person Shooter Games](articles/li22understanding.pdf) <br> Jiaye Li, Minghao Li, **Zikai Alex Wen**, <a href="https://faculty.washington.edu/weicaics/index.html" style="text-decoration:none; color:inherit;">Wei Cai</a> | Gaming |
| **ASSETS EA'21** | [An Intelligent Math E-Tutoring System for Students with Specific Learning Disabilities](articles/wen21math.pdf) <br> **Zikai Alex Wen**, <a href="https://www.yuhangz.com/" style="text-decoration:none; color:inherit;">Yuhang Zhao</a>, Erica Silverstein, Shiri Azenkot | EdTech,<br>Gaming |
| **ASSETS'20** | [Teacher Views of Math E-Learning Tools for Students with Specific Learning Disabilities](articles/wen20teacher.pdf) <br> **Zikai Alex Wen**, Erica O Silverstein, <a href="https://www.yuhangz.com/" style="text-decoration:none; color:inherit;">Yuhang Zhao</a>, Anjelika Lynne S Amog, Katherine Garnett, Shiri Azenkot | EdTech |
| **ASSETS EA'19** | [Teacher Perspectives on Math E-Learning Tools for Students with Specific Learning Disabilities](articles/wen20teacher.pdf) <br> **Zikai Alex Wen**, Anjelika Lynne S Amog, Shiri Azenkot, Katherine Garnett | EdTech |
| **CHI'19** | [What.Hack: Engaging Anti-Phishing Training Through a Role-Playing Cyber Defense Simulation Game](articles/wen19whatdothack.pdf) <br> **Zikai Alex Wen**, <a href="https://linzhiqiu.github.io/" style="text-decoration:none; color:inherit;">Zhiqiu Lin</a>, Rowena Chen, <a href="http://www.cs.cornell.edu/~eland/" style="text-decoration:none; color:inherit;">Erik Andersen</a> | Security,<br>EdTech |
| **CHI EA'17** | [What.Hack: Learn Phishing Email Defence the Fun Way](articles/wen19whatdothack.pdf) <br> **Zikai Alex Wen\***, Yiming Li, Reid Wade, Jeffrey Huang, Amy Wang | Security, EdTech |
| **S&P'16** | [Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts](articles/kosba16hawk.pdf) <br> <a href="https://akosba.github.io/" style="text-decoration:none; color:inherit;">Ahmed Kosba</a>, <a href="https://soc1024.ece.illinois.edu/" style="text-decoration:none; color:inherit;">Andrew Miller</a>, <a href="http://elaineshi.com/" style="text-decoration:none; color:inherit;">Elaine Shi</a>, **Zikai Wen**, <a href="https://www.cs.yale.edu/homes/cpap/" style="text-decoration:none; color:inherit;">Charalampos Papamanthou</a> | Privacy |
| **SAC'14** | [Efficient Protocols for Private Record Linkage](articles/wen14prl.pdf) <br> **Zikai Wen**, <a href="https://changyudong.site/" style="text-decoration:none; color:inherit;">Changyu Dong</a> | Privacy |
| **CCS'13** | [When Private Set Intersection Meets Big Data: an Efficient and Scalable Protocol](articles/dong13psi.pdf) <br> <a href="https://changyudong.site/" style="text-decoration:none; color:inherit;">Changyu Dong</a>, Liqun Chen, **Zikai Wen** | Privacy |



# 🎖 Awards and Grants
- *2024* [**AI 2000 Most Influential Scholar Award Honorable Mention in Security and Privacy**](awards/aminer.png) from AMiner
- *2022* [**The Fellowship of China Postdoctoral Science Foundation ($80K RMB)**](https://cma.hkust-gz.edu.cn/zikai-postdoc-fellowship/) from CPSF
- *2022* [**Outstanding Service Award**](awards/mmsp-service22.png) from IEEE MMSP
- *2017* **The Student Game Design Competition Runner-Up** at ACM CHI 
- *2014* **The Andrew McGettrick Prize** from University of Strathclyde, Glasgow
- *2014* **The Outstanding Graduate of Beijing** from Beijing Municipal Education Commission

# 🎮 Fun Stuff

<div class="game-box">
  <div class="game-box-image">
    <div class="badge">LD#36</div>
    <img src="/images/tori-tori-thumb.png" alt="Tori Tori Panic">
  </div>
  <div class="game-box-text" markdown="1">
**[Tori Tori Panic](https://www.cs.cornell.edu/~zkwen/ld36/)** at Ludum Dare #36

**Team:** Jeff Huang, Yiming Li, Changxu Lu, **Zikai Alex Wen**

**About:** A stealthy archery game made in 72 hours for the _Ancient Technology_ theme. Sneak around, take aim, and quietly shoot unsuspecting birds with pixel-perfect precision. Just don’t let them catch you.

  </div>
</div>
