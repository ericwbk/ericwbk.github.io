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

蚂蚁集团算法专家, 研究生毕业于复旦大学上海市数据科学重点实验室, 本科毕业于中国海洋大学计算机专业. 2019年研究生毕业加入蚂蚁集团, 一直从事金融风控算法研究工作. 目前在蚂蚁集团担任图风控算法负责人，大模型安全-数据安全算法负责人. 建设了图风控算法框架GeaSec, 包括基于torch的GNN算法代码库GREAT(GNN based Risk Exploration Algorithms using Torch)和图上异常检测工具(GAD tools). 与上下游的技术, 业务同学打造图机器学习标准工作流 GMLOps. 在VLDBJ, IJCAI, WWW等人工智能顶级会议上发表过论文. 在相关方向有一些研究<a href='https://scholar.google.com/citations?user=AsSLgc8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 2022年发表在VLDBJ的方法eRiskCom获得中国互联网大会反诈创新奖. 2023年作为核心成员和算法负责人合作举办[基于预训练模型的社区发现和团伙挖掘](https://tugraph.antgroup.com/blog?id=15)比赛(蚂蚁TuGraph团队&之江实验室). 我的研究兴趣主要包括: 
- Graph Neural Networks
- Dynamic Graph
- Community Detection
- Fraud Detection
- Risk Control
- Machine Learning

# 🎓 Educations 

+ *2016.06 - 2019.01*, 硕士, 复旦大学 计算机学院, Shanghai China. 
  - "华为杯"全国研究生数学建模竞赛三等奖, 2018.
  - 参与国家重点研发计划 "SKA科学数据处理关键技术研究" 项目, 在第四届数据科学大会(昆明)发表Oral "基于深度学习的脉冲星搜索", 参加第二届国际射电天文研讨会(贵州), 展示Poster "A Pulsar Search Pipeline by Deep Learning" . 参与胜利油田物探研究院项目 "大数据管理及数据挖掘方法研究技术", 基于Bi-LSTM等方法进行储层预测研究.  
+ *2012.09 - 2016.06*, 学士, 中国海洋大学 计算机科学与技术专业, Qingdao China. 
  - 全国大学生数学建模大赛全国一等奖，2014. [链接](http://www.mcm.edu.cn/html_cn/node/252a2e1c3edcd257c78f37a156a81209.html)
  - 美国大学生数学建模竞赛二等奖（Honorable Mention）, 2016. [链接](http://www.ouc.edu.cn/7d/2e/c10639a97582/pagem.psp)
  - 学生工作: 中国海洋大学大学生职业发展协会 主席团成员、环境保护协会秘书处部长、Chinese-Pakistan Iron Brother Club 创始人、"明职顾问" 工作室创始人、班级班长.
  - 保送至复旦大学继续攻读研究生学位（Rank 8th/91）. [链接](https://cs.fudan.edu.cn/13/8f/c24257a267151/page.htm)

# 🏭 Career

- *2019.01 - Now*, 蚂蚁集团算法专家, Shanghai China.
  - 2022.08 ~ 至今 (P7) 蚂蚁大安全机器智能团队全图风控引擎算法负责人. 打造安全图算法框架GeaSec( Graph extended analysis for Alipay Security ).打造的能力被蚂蚁内外16个部门使用.
  - 2020.07 ~ 2022.08 (P6) 研发了基于图风控技术的黑产发现全链路解决方案, 开发了Risk-SEED、TransProbe等核心算法, 在多个场景落地.
  - 2019.01 ~ 2020.07 (P5) 支付宝"你敢付我敢赔" 账安险骗赔算法owner; 研发了风控领域的 look-alike算法——Risk-alike, 并在蚂蚁、淘宝、高德等数十个场景应用, 该项技术获得 [2021 中国互联网大会信通院反诈创新优秀案例奖](https://baijiahao.baidu.com/s?id=1705330758899415939&wfr=spider&for=pc). 2023年成为阿里云商业化[最佳实践案例](https://www.alibabacloud.com/help/zh/graph-compute/latest/the-graph-compute-solution-for-account-recognition?spm=a2c63.p38356.0.0.16fa3e2cd41fJE).
- *2018.05 - 2018.07*, [Intern]腾讯社交与效果广告部, Shanghai China.
- *2018.02 - 2018.05*, [Intern]上海七牛云AI Lab, Shanghai China.

# 🌏 Activities 
- [ICDM 2023 TPC] Tentative Program Committee, Workshop on Incomplete Streaming Data Analysis （[ISDA 2023](https://isda2023.github.io/)） in conjunction with the IEEE International Conference on Data Mining （[ICDM 2023](https://www.cloud-conf.net/icdm2023/)）, 2023.
- [TuGraph×DataFun 线下Meetup] 2023.07.29 线下&线上分享 [图风控算法框架GeaSec介绍&案例分享](https://mp.weixin.qq.com/s/Fr442WW4mUx9A_U6i9byhw)

# 📄 Publications 
- [Arxiv]Jintang Li, Jiawang Dan, Ruofan Wu, Jing Zhou, Sheng Tian, Yunfei Liu, Baokun Wang*, Changhua Meng, Weiqiang Wang, Yuchang Zhu, Liang Chen*, Zibin Zheng. LasTGL: An Industrial Framework for Large-Scale Temporal Graph Learning[[PDF]](https://arxiv.org/abs/2311.16605)
- [ICDMw 2023]Jiawang Dan, Ruofan Wu, Yunpeng Liu, `Baokun Wang`, Changhua Meng, Tengfei Liu, Tianyi Zhang, Ningtao Wang, Xing Fu, Qi Li, and Weiqiang Wang. Self-supervision meets kernel graph neural models: From architecture to augmentations
- [IJCAI 2023] Sheng Tian, Jihai Dong, Jintang Li, Wenlong Zhao, Xiaolong Xu, `Baokun Wang`, Bowen Song, Changhua Meng, Tianyi Zhang, Liang Chen. SAD: Semi-Supervised Anomaly Detection on Dynamic Graphs.
- [WWW 2023] Yuchen Zhou, Yanan Cao, Yongchao Liu, Yanmin Shang, Peng Zhang, Zheng Lin, Yun Yue, `Baokun Wang`, Xing Fu and Weiqiang Wang. Multi-Aspect Heterogeneous Graph Augmentation.
- [VLDBJ 2022] Fanzhen Liu, Zhao Li, `Baokun Wang`, Yihua Kang, Jia Wu, Jian Yang, Jiaming Huang, Yiqing Zhang, Weiqiang Wang, Shan Xue, Surya Nepal, Quanzheng Sheng. eRiskCom: an e-commerce risky community detection platform. The VLDB Journal 31, 1085–1101 (2022). 
[[HTML]](https://doi.org/10.1007/s00778-021-00723-z) [[PDF]](/pdf/2022_VLDBJ_eRiskCom.pdf)
- [Arxiv] Jiafu Wu, Mufeng Yao, Dong Wu, Mingmin Chi, `Baokun Wang`, Ruofan Wu, Xin Fu, Changhua Meng and Weiqiang Wang. DEDGAT: Dual Embedding of Directed Graph Attention Networks for Detecting Financial Risk[J/OL]. https://arxiv.org/abs/2303.03933, 2023-3. [[PDF]](https://arxiv.org/pdf/2303.03933.pdf)

# 📝 Patents 

- [已授权发明专利 CN111311408B] 电子交易属性识别方法及装置 . 2020.02.
- [已授权发明专利 CN110705996A] 基于特征掩码的用户行为识别方法、系统、及装置 2020.01.
- [已授权发明专利 CN111523831B] 风险团伙的识别方法、装置、存储介质和计算机设备 2020.11.

# 🏅 Honors and Awards
- *2023.12* 上海金融科技优秀解决方案（面向金融安全的全图风控解决方案）
- *2021.07* 2021世界互联网大会信息通信行业反诈创新项目优秀奖（Risk-alike欺诈团伙发掘 - 全图风控技术）
- *2021.05* KDDCUP 2021 PCQM4M-LSC Track [5th](https://ogb.stanford.edu/kddcup2021/results/)
- *2021.03* 蚂蚁集团CV数据隐私保护大赛第8名（100+团队）
- *2021.03* 蚂蚁集团 机器智能 "鲁班大师奖"，"OCB红草莓奖"
- *2019.06* 复旦大学计算机学院研究生奖学金一等奖.
- *2016.06* 中国海洋大学优秀学生、优秀毕业生.

  
