---
permalink: /
title: ""
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

Youkun Shi is a Postdoctoral Fellow in the Department of computing at The Hong Kong Polytechnic University, working under the supervision of *[**Prof. Daniel Xiapu Luo**](https://www4.comp.polyu.edu.hk/~csxluo/)*. He earned the Ph.D. degree in June 2024 from Fudan University, advised by *[**Prof. Yuan Zhang**](https://yuanxzhang.github.io/)* and *[**Prof. Min Yang**](https://scholar.google.com/citations?user=UnKf9FIAAAAJ&hl=en)*. His research focuses on system security, especially **web security**. To date, he has published 5 first-author papers in top-tier conferences. His research has been adopted by leading companies such as Alibaba and Huawei, and acknowledged in security advisories from major companies such as Google, Apache, and IBM.

Moreover, Youkun Shi is the co-founder of a great CTF Team at Fudan University, named Whitzard. The team has participated in numerous prestigious world-wide CTF competitions, achieving commendable rankings.

# 🔥 News
- [*2025.06*] &nbsp;🎉 Two papers accepted by [**USENIX Security 2025**](https://www.usenix.org/conference/usenixsecurity25)! 
- [*2025.05*] &nbsp;🎉 One talk accepted by [**BlackHat USA 2025**](https://www.blackhat.com/us-25/)!
- [*2025.05*] &nbsp;🎉 Our vulnerability detection work on microservice-structured web apps received <span style="color:#B00C00">**Distinguished Paper Award**</span> at [**IEEE S&P 2025**](https://sp2025.ieee-security.org/)!
- [*2025.03*] &nbsp;🎉 One paper accepted by [**ACM CCS 2025**](https://www.sigsac.org/ccs/CCS2025/)!
- [*2025.03*] &nbsp;🎉 Two papers accepted by [**IEEE S&P 2025**](https://sp2025.ieee-security.org/)!

# 📖 Background
- *2024.11 - now*, Postdoc, The Hong Kong Polytechnic University, Department of Computing.
- *2019.09 - 2024.06*, Ph.D, Fudan University, School of Computer Science.
- *2015.09 - 2019.06*, B.Eng, China University of Mining and Technology, School of Computer Science.

# 📝 Publications 

## 👍🏻 Lead Publications

1. `USENIX SEC'25` **XSSky: Detecting XSS Vulnerabilities through Local Path-Persistent Fuzzing** [<span class="pdf">PDF</span>]()     
  <span style="color:blue">Youkun Shi</span>, Yuan Zhang, Tianhao Bai, Feng Xue, Jiarun Dai, Fengyu Liu, Lei Zhang, Xiapu Luo, Min Yang.   
  In *Proceedings of the 34th USENIX Security Symposium (USENIX SEC)*, August, 2025.   
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>

1. `S&P'25` **MOCGuard: Automatically Detecting Missing-Owner-Check Vulnerabilities in Java Web Applications** [<span class="pdf">PDF</span>](/papers/mocguard-oakland25.pdf)  
  Fengyu Liu<sup>\*</sup>, <span style="color:blue">Youkun Shi<sup>\*</sup></span>, Yuan Zhang, Guangliang Yang, Enhao Li, Min Yang (*\* co-first authors*).  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025.   
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>

1. `WWW'24` **RecurScan: Detecting Recurring Vulnerabilities in PHP Web Applications** [<span class="pdf">PDF</span>](/papers/recurscan-www24.pdf)  
  <span style="color:blue">Youkun Shi</span>, Yuan Zhang, Tianhao Bai, Lei Zhang, Xin Tan, Min Yang.  
  In *Proceedings of the 33rd ACM Web Conference (WWW)*, May, 2024.   
  <span style="color:#B00C00">*CCF-A, Top Web Research Conference*</span>

1. `ASE'22` **Precise (Un)Affected Version Analysis for Web Vulnerabilities** [<span class="pdf">PDF</span>](/papers/afv-ase22.pdf)  
  <span style="color:blue">Youkun Shi</span>, Yuan Zhang, Tianhan Luo, Xiangyu Mao, Min Yang.  
  In *Proceedings of the 37th IEEE/ACM International Conference on Automated Software Engineering (ASE)*, October, 2022.   
  <span style="color:#B00C00">*CCF-A, Top Software Engineering Conference*</span>

1. `USENIX SEC'22` **Backporting Security Patches of Web Applications** [<span class="pdf">PDF</span>](/papers/skyport-security22.pdf)    
  <span style="color:blue">Youkun Shi</span>, Yuan Zhang, Tianhan Luo, Xiangyu Mao, Yinzhi Cao, Ziwen Wang, Yudi Zhao, Zongan Huang, Min Yang.  
  In *Proceedings of the 31st USENIX Security Symposium (USENIX SEC)*, August, 2022.   
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>


## 🤝 Other Publications

1. `USENIX SEC'25` **Make Agent Defeat Agent: Automatic Detection of Taint-Style Vulnerabilities in LLM-based Agents** [<span class="pdf">PDF</span>]()  
  Fengyu Liu, Yuan Zhang, Jiaqi Luo, Jiarun Dai, Tian Chen, Letian Yuan, Zhengmin Yu, <span style="color:blue">Youkun Shi</span>, Ke Li, Chengyuan Zhou, Hao Chen, Min Yang.  
  In *Proceedings of the 34th USENIX Security Symposium (USENIX SEC)*, August, 2025.   
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>

1. `CCS'25` **BACScan: Automatic Black-Box Detection of Broken-Access-Control Vulnerabilities in Web Applications** [<span class="pdf">PDF</span>]()   
  Fengyu Liu, Yuan Zhang, Enhao Li, Wei Meng, <span style="color:blue">Youkun Shi</span>, Qianheng Wang, Chenlin Wang, Zihan Lin, Min Yang.  
  In *Proceedings of the 32nd ACM Conference on Computer and Communications Security (CCS)*, October 2025.   
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>

1. `S&P'25` **Detecting Taint-Style Vulnerabilities in Microservice-Structured Web Applications** [<span class="pdf">PDF</span>](/papers/mscan-oakland25.pdf) <span class="award">Distinguished Paper Award</span>  
  Fengyu Liu, Yuan Zhang, Tian Chen, <span style="color:blue">Youkun Shi</span>, Guangliang Yang, Zihan Lin, Min Yang, Junyao He, Qi Li.  
  In *Proceedings of the 46th IEEE Symposium on Security and Privacy (S&P)*, May 2025.    
  Presented at **BlackHat USA 2025** [[Talk Abstract](https://www.blackhat.com/us-25/briefings/schedule/#detecting-taint-style-vulnerabilities-in-microservice-structured-web-applications-46427)]  
  <span style="color:#B00C00">*CCF-A, Security BIG4 Conference*</span>


# 🎖 Honors and Awards
- *2024*, [Huawei TopMinds Program Offer](https://career.huawei.com/reccampportal/portal5/topminds.html)
- *2024*, Outstanding PhD Graduates, Shanghai (Top 5%)
- *2024*, Academic Star, Fudan University (Top 30)
- *2022*, National Scholarship for Ph.D. Candidates (Top 0.2%)
- *2018*, National Scholarship for B.S. Candidates (Top 0.2%)
- *2017*, National Scholarship for B.S. Candidates (Top 0.2%)

# 🏆 Skill Competitions
- *2021*, 🏆 Champion, 6th XCTF International League (Final Round)
- *2021*, 🏆 Champion, 2nd XiangYun Cup Cybersecurity Competition (Final Round)
- *2020*, 🏆 Champion, 4th X-NUCA Cybersecurity Competition (Final Round)
- *2020*, 🏆 Champion, 13th National College Student Information Security Contest (Final Round)
- *2020*, 🏆 Champion, 4th Hangzhou Cybersecurity Skills Competition (Final Round)
- *2019*, 🏆 Champion, 3rd X-NUCA Cybersecurity Competition (Final Round)
- *2019*, 🥈 Runner-up, 5th XCTF International League (Final Round)
- *2019*, 🥈 Runner-up, 1st OGeek Cup Cybersecurity Competition (Final Round)
- *2019*, 🏆 Champion, 3rd Tencent RisingStar Cybersecurity Competition (Final Round)
- *2019*, 🏆 Champion, 3rd Hangzhou Cybersecurity Skills Competition (Final Round)
- *2018*, 🏆 Champion, 2nd Hangzhou Cybersecurity Skills Competition (Final Round) 

# 👨‍💻 Services
## Journal Reviewing
- ``TDSC`` [IEEE Transactions on Dependable and Secure Computing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858)



