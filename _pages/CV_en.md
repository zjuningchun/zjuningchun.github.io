---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- 顶部加中英文切换链接，放在简历最上方 -->
<div style="text-align:right; margin-bottom: 20px;">
  <a href="/">English</a> | <a href="/CV_cn/">中文</a>
</div>
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# About Me
Ningchun Liu, Ph.D, Experimentalist  
National College for Excellent Engineers of Zhejiang University  
Polytechnic Institute of Zhejiang University, Zhejiang Polytechnic Institute  
Zhejiang Key Laboratory of Airspace Perception and Autonomous Unmanned Systems  

Since March 2026, I have been working in <a href="https://pi.zju.edu.cn/">National College for Excellent Engineers of Zhejiang University</a>, focusing on AI4E research and practice courses teaching. From June 2023 to February 2026, I worked as an Assistant Researcher in the Research Center for High Efficiency Computing Infrastructure, <a href="https://www.zhejianglab.org/lab/home">Zhejiang Lab</a>, working on network observability, fault diagnosis, and efficiency &amp; performance optimization for AI infrastructure. In June 2023, I received my Ph.D. degree from the National Engineering Research Center of Advanced Network Technologies, <a href="https://www.bjtu.edu.cn/">Beijing Jiaotong University</a>, under the supervision of <a href="https://eie.bjtu.edu.cn/faculty/7637.html">Prof. Shuai Gao</a>. In July 2016, I received my Bachelor of Engineering degree in Communication Engineering (Rail Transit Signal and Control) from College of Electrical Engineering and Information Technology, <a href="https://www.djtu.edu.cn/">Dalian Jiaotong University</a>.  

My research interest is AI for Engineering (AI4E), Advanced Network Architectures (including Information-Centric Networks (ICN), Software-Defined Networks (SDN), and (AI) Data Center Network), and Network Security.

<!--
I have published more than 10 papers with total <a href='https://scholar.google.com/citations?user=PcebAfcAAAAJ'>google scholar citations <strong><span id='total_cit'></span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=PcebAfcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

<span class='anchor' id='news'></span>
# News
- Apr. 2026, I am honored to be supported by Zhejiang University's AI for LAB Intelligent Experimental Technology Project, with the project entitled "Development of AI Model-Based Practical Teaching Platform for Industrial Quality Inspection".
- Mar. 2026, I joined Zhejiang University in Hangzhou, China.
<!--
<span style="color:red;">Apr. 2024</span>: I am honored to be invited to serve as the Session Chair on 2024 The 9th International Conference on Computer and Communication Systems (<a href="https://www.icccs.org/icccs2024.html">ICCCS 2024</a>).
-->
<span class='anchor' id='publications'></span>

# Selected Publications 

## Journal and Magazines
- 张慧峰, **刘宁春**, 龙卫平, 陆平静, 邹涛, 隆克平, 张汝云, 朱俊. 面向国产算力的超大规模智算集群网络：关键挑战、技术途径与发展趋势[J]. **电信科学**, 2025, 41(12):1-26. (ZHANG Hui-feng, **LIU Ning-chun**, LONG Wei-ping, LU Ping-jing, ZOU Tao, LONG Ke-ping, ZHANG Ru-yun, ZHU Jun. Hyperscale Intelligent Computing Cluster Networks for Domestic Computing Power: Critical Challenges, Technical Pathways, and Future Trends[J]. **Telecommunications Science**, 2025, 41(12): 1-26.) <a href="/files/2025_TS.pdf">[pdf]<a href="/files/2025_TS_bib.txt">[bib]
- Xindi Hou, Shuai Gao, **Ningchun Liu**, Fangtao Yao, Bo Lei, Hongke Zhang, and Sajal K. Das, "L3DML: Facilitating Geo-Distributed Machine Learning in Network Layer," **IEEE Transactions on Network and Service Management**, vol. 22, no. 2, pp. 1391-1408, April 2025. <a href="/files/2025_TNSM.pdf">[pdf]<a href="/files/2025_TNSM_bib.txt">[bib]
- Xindi Hou, Shuai Gao, **Ningchun Liu**, Fangtao Yao, Hongke Zhang, and Sajal K. Das, "L3Geocast: Enabling P4-Based Customizable Network-Layer Geocast at the Network Edge," **IEEE Transactions on Mobile Computing**, vol. 23, no. 8, pp. 8323-8340, Aug. 2024. <a href="/files/2024_TMC.pdf">[pdf]<a href="/files/2024_TMC_bib.txt">[bib]
- **Ningchun Liu**, Shuai Gao, Xindi Hou, Teng Liang, Guobiao He, Hongke Zhang, and Sajal K. Das, "An ICN-Based Secure Task Cooperation in Challenging Wireless Edge Networks," **IEEE Transactions on Network and Service Management**, vol. 21, no. 2, pp. 2140-2154, April 2024. <a href="/files/2024_TNSM.pdf">[pdf]<a href="/files/2024_TNSM_bib.txt">[bib] 
- 柳依岸, 郜帅, 侯心迪, **刘宁春**. 基于可编程平台的标识网络移动性管理机制[J]. **计算机技术与发展**, 2023, 33(10):59-65+114. (LIU Yi-an,GAO Shuai,HOU Xin-di, **LIU Ning-chun**. Mobility Management Mechanism of Smart Identifier Network Based on Programmable Data Plane[J]. **Computer Technology and Development**, 2023, 33(10): 59-65+114.) <a href="/files/2023_JSJ.pdf">[pdf]<a href="/files/2023_JSJ_bib.txt">[bib]
- 柴若楠, 郜帅, 兰江雨, **刘宁春**. 算力网络中高效算力资源度量方法[J]. **计算机研究与发展**, 2023, 60(4): 763-771. (CHAI Ruo-nan, GAO Shuai, LAN Jiang-yu, **LIU Ning-chun**. Efficient Computing Resource Metric Method in Computing-First Network[J]. **Journal of Computer Research and Development**, 2023, 60(4): 763-771.) <a href="/files/2023_JCRD.pdf">[pdf]<a href="/files/2023_JCRD_bib.txt">[bib]
- 缪静莹, 郜帅, 侯心迪, **刘宁春**. 面向多维统一标识体系的标识解析映射机制[J]. **计算机技术与发展**, 2022, 32(12):74-80+141. (MIAO Jing-ying, GAO Shuai, HOU Xin-di, **LIU Ning-chun**. Identity Resolution and Mapping Mechanism for Multidimensional Unified Identity Architecture[J]. **Computer Technology and Development**, 2022, 32(12): 74-80+141.) <a href="/files/2022_JSJ.pdf">[pdf]<a href="/files/2022_JSJ_bib.txt">[bib]
- 郜帅, 侯心迪, **刘宁春**, 张宏科. 多模态网络环境异构标识空间管控架构研究[J]. **通信学报**, 2022,43(4):26-35. (Shuai GAO, Xindi HOU, Ningchun LIU, et al. Research on heterogeneous identifier namespace management and control architecture in polymorphic network environment[J]. Journal on Communications, 2022, 43(4): 26-35.) <a href="/files/2022_通信学报.pdf">[pdf]<a href="/files/2022_通信学报_bib.txt">[bib]
- Guobiao He, Wei Su, Shuai Gao, **Ningchun Liu**, Sajal K. Das, "NetChain: A Blockchain-Enabled Privacy-Preserving Multi-Domain Network Slice Orchestration Architecture," **IEEE Transactions on Network and Service Management**, vol. 19, no. 1, pp. 188-202, March 2022. <a href="/files/2022_TNSM.pdf">[pdf]<a href="/files/2022_TNSM_bib.txt">[bib]
- **Ningchun Liu**, Shuai Gao, Lei Yu, Guobiao He, A Secure and Cached-Enabled NDN Forwarding Plane Based on Programmable Switches, **Wireless Communications and Mobile Computing**, 2022, 4466942, 16 pages, 2022. <a href="/files/2022_WCMC.pdf">[pdf]<a href="/files/2022_WCMC_bib.txt">[bib]
- **刘宁春**, 郜帅, 侯心迪, 国兴昌. 一种信息中心移动自组网中的数据访问控制机制[J]. **北京邮电大学学报**, 2021, 44(2): 54-60. (**LIU Ning-chun**, GAO Shuai, HOU Xin-di, GUO Xing-chang. A Data Access Control Scheme in Information-Centric Mobile Ad Hoc Networks[J]. **Journal of Beijing University of Posts and Telecommunications**, 2021, 44(2): 54-60.) <a href="/files/2021_BYXB.pdf">[pdf]<a href="/files/2021_BYXB_bib.txt">[bib]
- 李旭阳, 郜帅, 国兴昌, **刘宁春**. 基于SDN的组播安全机制[J]. **计算机技术与发展**, 2020, 30(10):111-116. (LI Xu-yang, GAO Shuai, GUO Xing-chang, **LIU Ning-chun**. SDN-based Multicast Security Mechanism[J]. **Computer Technology and Development**, 2020, 30(10): 111-116.) <a href="/files/2020_JSJ_LXY.pdf">[pdf]<a href="/files/2020_JSJ_LXY_bib.txt">[bib]
- 陈红, **刘宁春**, 郜帅, 周华春. 基于SDN的服务驱动组播的设计与实现[J]. **计算机技术与发展**, 2020, 30(12):130-135. (CHEN Hong, **LIU Ning-chun**, GAO Shuai, ZHOU Hua-chun. Design and Implementation of Service Driven Multicast for Software Defined Network[J]. **Computer Technology and Development**, 2020, 30(12): 130-135.) <a href="/files/2020_JSJ_CH.pdf">[pdf]<a href="/files/2020_JSJ_CH_bib.txt">[bib]

## Conference Papers
- **Ningchun Liu**, Aiyue Wang, Anyi Tang, Geyang Xiao, Jun Zhu, Tao Zou, "Data-driven Remaining Useful Life Prediction for Optical Modules in Intelligent Computing Networks," **2025 Global Reliability and Prognostics and Health Management Conference (PHM-Xian)**, Xian, China, 2025, pp. 1-4. <a href="/files/2025_PHM_Liu.pdf">[pdf]<a href="/files/2025_PHM_Liu_bib.txt">[bib]
- Aiyue Wang, **Ningchun Liu**, Congqi Shen, Jun Zhu, Tao Zou, "Fine-Grained Health Monitoring of Optical Modules in Computing Clusters using Transformers," **2025 Global Reliability and Prognostics and Health Management Conference (PHM-Xian)**, Xian, China, 2025, pp. 1-6. <a href="/files/2025_PHM_Wang.pdf">[pdf]<a href="/files/2025_PHM_Wang_bib.txt">[bib]
- **Ningchun Liu**, Shuai Gao, Teng Liang, Xindi Hou, Lei Yu, and Hongke Zhang, "A Privacy-Preserving Timing Attacks Mitigation in Information-Centric Edge Networks," **2023 IEEE International Conference on High Performance Computing & Communications, Data Science & Systems, Smart City & Dependability in Sensor, Cloud & Big Data Systems & Application (HPCC/DSS/SmartCity/DependSys)**, Melbourne, Australia, 2023, pp. 24-29. <a href="/files/2023_HPCC.pdf">[pdf]<a href="/files/2023_HPCC_bib.txt">[bib]
- Anyi Tang, Gang Niu, Xuanrui Zhu, Jianfeng Li, and **Ningchun Liu**, "A Three-Interface Data-based Wireless Communication Timeout Fault Diagnosis Method for China Train Control System," **2023 Global Reliability and Prognostics and Health Management Conference (PHM-Hangzhou)**, Hangzhou, China, 2023, pp. 1-4. <a href="/files/2023_PHM.pdf">[pdf]<a href="/files/2023_PHM_bib.txt">[bib]
- Peidai Liu, Shuai Gao, Xindi Hou, **Ningchun Liu**, "An Access Control Mechanism in Smart Identifier Network," **2023 8th International Conference on Computer and Communication Systems (ICCCS)**, Guangzhou, China, 2023, pp. 440-444. <a href="/files/2023_ICCCS.pdf">[pdf]<a href="/files/2023_ICCCS_bib.txt">[bib]
- Lei Yu, Shuai Gao, **Ningchun Liu**, Hongchao Wang, Wei Su, "A Cache-enabled NDN Forwarding Plane based on Programmable Switches," **2022 International Conference on Networking and Network Applications (NaNA)**, Urumqi, China, 2022, pp. 152-156. <a href="/files/2022_NaNA.pdf">[pdf]<a href="/files/2022_NaNA_bib.txt">[bib]
- **Ningchun Liu**, Shuai Gao, Teng Liang, Xindi Hou, Sajal K. Das, "An ICN-based Secure Task Cooperation Scheme in Challenging Wireless Edge Networks," **2022 International Conference on Computer Communications and Networks (ICCCN)**, Honolulu, HI, USA, 2022, pp. 1-7. <a href="/files/2022_ICCCN.pdf">[pdf]<a href="/files/2022_ICCCN_bib.txt">[bib]
- Xindi Hou, Shuai Gao, **Ningchun Liu**, and Gaofeng Hong, "Enabling granularity-customizable geocast in network layer using P4-based software defined network," In Proceedings of the **ACM SIGCOMM Workshop on Future of Internet Routing & Addressing (FIRA '22)**, New York, NY, USA, 2022, pp. 18–24. <a href="/files/2022_SIGCOMM.pdf">[pdf]<a href="/files/2022_SIGCOMM_bib.txt">[bib]
- Jiahui Sun, **Ningchun Liu**, Shuai Gao, Wei Su, "A Secure Identifier-to-Locator Mapping Mechanism in Smart Identifier Network," **2021 International Conference on Networking and Network Applications (NaNA)**, Lijiang City, China, 2021, pp. 437-442. <a href="/files/2021_NaNA.pdf">[pdf]<a href="/files/2021_NaNA_bib.txt">[bib]
- Xingchang Guo, **Ningchun Liu**, Xindi Hou, Shuai Gao, Huachun Zhou, "An Efficient NDN Routing Mechanism Design in P4 Environment," **2021 2nd Information Communication Technologies Conference (ICTC)**, Nanjing, China, 2021, pp. 28-33. <a href="/files/2021_ICTC.pdf">[pdf]<a href="/files/2021_ICTC_bib.txt">[bib]
- Jiarui Yue, Yajuan Qin, Shuai Gao, Wei Su, Guobiao He, **Ningchun Liu**, "A Privacy-Preserving Route Leak Protection Mechanism Based on Blockchain," **2021 IEEE International Conference on Information Communication and Software Engineering (ICICSE)**, Chengdu, China, 2021, pp. 264-269. <a href="/files/2021_ICICSE.pdf">[pdf]<a href="/files/2021_ICICSE_bib.txt">[bib]
- **Ningchun Liu**, Shuai Gao, Ningho Hou, "CDAC: A Collaborative Data Access Control Scheme in Named Data Networking," **2019 2nd International Conference on Hot Information-Centric Networking (HotICN)**, Chongqing, China, 2019, pp. 44-49. <a href="/files/2019_HotICN.pdf">[pdf]<a href="/files/2019_HotICN_bib.txt">[bib]

## Ph.D. Dissertation
- Research on Key Technologies for Securing Content in
Information-centric Edge Networks, June. 2023.  <a href="/files/Ningchun_Dissertation.pdf">[pdf] 

## Patents
- 王爱阅, 华梓强, 刘宁春, 沈丛麒, 朱俊, 邹涛. 一种光模块细粒度健康度评估方法、系统、装置及介质. 发明专利. 2025.07.30. ZL202511056327.5（已授权）
- 沈丛麒, 刘宁春, 王爱阅, 华梓强, 邹涛. 网络故障检测方法、设备及存储介质. 发明专利. 2025.07.08. CN202510937646.0（已公开）
- 徐琪, 刘宁春, 凃化清, 朱俊, 邹涛, 张汝云. 一种网络入侵检测方法、装置、电子装置和存储介质. 发明专利. 2023.11.17. CN202311540062.7（已公开）
- 陈少华, 齐迪, 曾洁, 刘宁春, 尹浩, 庄子艾. 一种耦合谐振无线环境监测装置. 实用新型专利. 2015.02.10. ZL201520095321.4（已授权）

<span class='anchor' id='service'></span>

# Service

## TPC Member
- ICCCS 2024 (also as Session Chair)
- ICBCTIS 2024

## Reviewer
- **IEEE Journals**: IEEE Transactions on Network and Service Management
- **Elsevier Journals**: Digital Communications and Networks (DCN)
- **Spring Nature**: The Journal of Supercomputing, BMC Medical Informatics and Decision Making
- **Conferences**: IEEE ICC 2022, IEEE ICCCN 2025, IEEE PHM 2023 & 2025, ICIEIS 2024, ICCCS 2024, MEIE 2024, CSAE 2023

<span class='anchor' id='teaching'></span>

# Teaching Experience
## Zhejiang University
- Large Language Models Development and Deployment Practice, Spring 2025-2026

## Beijing Jiaotong University
- C Language Course, Fall 2017-2018, Fall 2018-2019, Fall 2019-2020

## Dalian Jiaotong University
- Microcontroller Principles and Applications, Fall 2015-2016


<span class='anchor' id='news'></span>

# Links
- <a href="https://pi.zju.edu.cn/">浙江大学国家卓越工程师学院  
- <a href="https://www.zhejianglab.org/">之江实验室  
- <a href="https://www.bjtu.edu.cn/">北京交通大学  
- <a href="https://www.djtu.edu.cn/">大连交通大学

# Template of This Page
Thanks to Yi Ren for his open source contribution, template link [AcadHomepage ![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io?style=social)](https://github.com/RayeRen/acad-homepage.github.io).
