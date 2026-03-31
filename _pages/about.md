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

蚂蚁集团算法专家, 研究生毕业于复旦大学计算机技术专业。2019年加入蚂蚁集团，目前担任用户认知团队负责人，负责用户理解、用户表征、推荐系统、图算法等能力建设。核心工作包括提出了基于LLM的用户理解大模型FIND，图风控算法框架Geasec，团伙挖掘基础框架Risk-alike，这些能力在蚂蚁和阿里内部广泛应用。加入蚂蚁后先后担任图风控算法团队负责人、大模型安全-数据安全算法团队负责人、用户认知算法团队负责人等。2023年联合清华、北邮、中山、交大、复旦、之江实验室、淘天集团发布了行业内第一个[《图风控行业技术报告》](https://mdn.alipayobjects.com/huamei_evip3z/afts/file/A*ezdlRLEMOf4AAAAAAAAAAAAADoGbAQ/%E5%9B%BE%E9%A3%8E%E6%8E%A7%E8%A1%8C%E4%B8%9A%E6%8A%80%E6%9C%AF%E6%8A%A5%E5%91%8A.pdf)。在VLDBJ/IJCAI/WWW/KDD等人工智能顶级会议上发表过论文<a href='https://scholar.google.com/citations?user=AsSLgc8AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>。2022年发表在VLDBJ的方法eRiskCom获得中国互联网大会反诈创新奖，2023年作为核心成员和算法负责人合作举办[基于预训练模型的社区发现和团伙挖掘](https://tugraph.antgroup.com/blog?id=15)比赛(蚂蚁TuGraph团队&之江实验室)，建设的大模型数据安全全链路防御系统已经在蚂蚁自研大模型全面上线。2024年打造的基于大模型的用户表征生成和自然语言圈人系统“AI智选”入选2024世界人工智能大会WAIC大模型典型示范应用。

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
  - 2024.01 ~ Now 蚂蚁用户认知和算法团队负责人，负责用户基础认知、用户表征生成、推荐系统等能力建设，同时负责新业务中feeds流推荐建设、新业务人群定向投放、全量支付宝账户准入/使用风险防控等业务场景。打造的用户理解大模型FIND在100多个场景应用。
  - 2022.08 ~ 2024.01 蚂蚁大安全机器智能团队全图风控引擎算法团队负责人/大模型数据安全算法团队负责人. 打造安全图算法框架GeaSec( Graph extended analysis for Alipay Security ), 包括基于torch的GNN算法代码库GREAT(GNN based Risk Exploration Algorithms using Torch)和图上异常检测工具(GAD tools). 与上下游的技术, 业务同学打造图机器学习标准工作流 GMLOps, 该能力被蚂蚁内外16个部门使用。
  - 2020.07 ~ 2022.08 (P6) 研发了基于图风控技术的黑产发现全链路解决方案, 开发了Risk-SEED、TransProbe等核心算法, 在多个场景落地。
  - 2019.01 ~ 2020.07 (P5) 支付宝"你敢付我敢赔" 账安险骗赔算法owner; 研发了风控领域的 look-alike算法——Risk-alike, 并在蚂蚁、淘宝、高德等数十个场景应用, 该项技术获得 [2021 中国互联网大会信通院反诈创新优秀案例奖](https://baijiahao.baidu.com/s?id=1705330758899415939&wfr=spider&for=pc). 2023年成为阿里云商业化[最佳实践案例](https://www.alibabacloud.com/help/zh/graph-compute/latest/the-graph-compute-solution-for-account-recognition?spm=a2c63.p38356.0.0.16fa3e2cd41fJE).
- *2018.07 - 2018.09*, [Intern]腾讯社交与效果广告部, Shanghai China。
- *2018.05 - 2018.07*, [Intern]蚂蚁集团大安全决策科学, Hangzhou China。
- *2018.02 - 2018.05*, [Intern]上海七牛云AI Lab, Shanghai China。

# 🌏 Activities 
- [2025.10 上海交通大学合作课程] 上海交大-蚂蚁联合课程现场讲授“面向多源异构数据的预训练大模型”.
- [2025.05 A2M互联网架构与AI技术峰会] 用户理解范式重构：蚂蚁FIND大模型的多源数据对齐与营销决策效率跃迁. [链接](https://a2m.msup.com.cn/course?aid=4488&cid=18257&city=shanghai)
- [2024.12清华冬季课程] 清华-蚂蚁联合课程现场讲授支付宝《蚂蚁用户认知体系建设》
- [2024全球软件工程技术大会-深圳] 业务架构实践专场分享“支付宝用户认知体系建设”
- [2023.12清华冬季课程] 清华-蚂蚁联合课程现场讲授支付宝业务安全《支付宝中场战事》
- [图风控行业技术报告2023发布, 36Kr深度采访] 图风控，数智经济的“新技术革命”. [链接](https://m.36kr.com/p/2559133262372231)
- [ICDM 2023 TPC] Tentative Program Committee, Workshop on Incomplete Streaming Data Analysis （[ISDA 2023](https://isda2023.github.io/)） in conjunction with the IEEE International Conference on Data Mining （[ICDM 2023](https://www.cloud-conf.net/icdm2023/)）, 2023.
- [TuGraph×DataFun 线下Meetup] 2023.07.29 线下&线上分享 [图风控算法框架GeaSec介绍&案例分享](https://mp.weixin.qq.com/s/Fr442WW4mUx9A_U6i9byhw)

# 📄 Publications 
- [HPDC 2026] Chengying Huan, Ziheng Meng, Zhengyi Yang, Yongchao Liu, Jie Zhang, Qing Wang, Jing Wang, Shaonan Ma, Zhibin Wang, Mingxing Zhang, Rong Gu, `Baokun Wang`, Guihai Chen, Chen Tian. "BCCE: block-centric GPU co-design for real-time range-top-k query at scale". 35th ACM International Symposium on High-Performance Parallel and Distributed Computing, 2026.<font color='#FF0000'> (CCF A) </font>
- [WWW 2025]Bin Dou, `Baokun Wang`<font color='#FF0000'> (correspondence) </font>, Yun Zhu, Xiaotong Lin, Yike Xu, Xiaorui Huang, Yang Chen, Yun Liu, Shaoshuai Han, Yongchao Liu, Tianyi Zhang, Yu Cheng, Weiqiang Wang and Chuntao Hong. Transferable and Forecastable User Targeting Foundation Model.<font color='#FF0000'> (Oral) </font>[[PDF]](https://arxiv.org/pdf/2412.12468)<font color='#FF0000'> (CCF A) </font>
- [ECMLPKDD 2024]Boci Peng, Yongchao Liu, He Xiao, Sheng Tian, `Baokun Wang`, Chuntao Hong, Yan Zhang. Subgraph Retrieval Enhanced by Graph-Text Alignment for Commonsense Question Answering.[[PDF]](https://arxiv.org/pdf/2411.06866)<font color='#FF0000'> (CCF B) </font>
- [ECMLPKDD 2024]Sheng Tian, Xintian Zeng, Yifei Hu, `Baokun Wang`<font color='#FF0000'> (correspondence) </font>, Yongchao Liu, Yue Jin, Changhua Meng, Chuntao Hong, Tianyi Zhang, Weiqiang Wang. GraphRPM: Risk Pattern Mining on Industrial Large Attributed Graphs[[PDF]](https://arxiv.org/pdf/2411.06878)<font color='#FF0000'> (CCF B) </font>
- [KDD 2024]Yunfei Liu, Jintang Li, Yuehe Chen, Ruofan Wu, `Baokun Wang`, Jing Zhou, Sheng Tian, Shuheng Shen, Xing Fu, Changhua Meng, Weiqiang Wang, Liang Chen.Revisiting Modularity Maximization for Graph Clustering: A Contrastive Learning Perspective.[[PDF]](https://arxiv.org/pdf/2406.14288)<font color='#FF0000'> (CCF A) </font>
- [ICLR 2024]Jintang Li, Huizhe Zhang, Ruofan Wu, Zulun Zhu, `Baokun Wang`, Changhua Meng, Zibin Zheng, Liang Chen*. A Graph is Worth 1-bit Spikes: When Graph Contrastive Learning Meets Spiking Neural Networks. [[PDF]](https://arxiv.org/pdf/2305.19306.pdf)<font color='#FF0000'> (CCF A) </font>
- [ICDMw 2023]Jiawang Dan, Ruofan Wu, Yunpeng Liu, `Baokun Wang`, Changhua Meng, Tengfei Liu, Tianyi Zhang, Ningtao Wang, Xing Fu, Qi Li, and Weiqiang Wang. Self-supervision meets kernel graph neural models: From architecture to augmentations[[PDF]](https://arxiv.org/pdf/2310.11281) <font color='#FF0000'> (CCF B) </font>
- [IJCAI 2023] Sheng Tian, Jihai Dong, Jintang Li, Wenlong Zhao, Xiaolong Xu, `Baokun Wang`, Bowen Song, Changhua Meng, Tianyi Zhang, Liang Chen. SAD: Semi-Supervised Anomaly Detection on Dynamic Graphs.[[PDF]](https://arxiv.org/pdf/2305.13573) <font color='#FF0000'> (CCF A) </font>
- [WWW 2023] Yuchen Zhou, Yanan Cao, Yongchao Liu, Yanmin Shang, Peng Zhang, Zheng Lin, Yun Yue, `Baokun Wang`, Xing Fu and Weiqiang Wang. Multi-Aspect Heterogeneous Graph Augmentation. <font color='#FF0000'> (CCF A) </font>
- [VLDBJ 2022] Fanzhen Liu, Zhao Li, `Baokun Wang`<font color='#FF0000'> (co-first author) </font>, Yihua Kang, Jia Wu, Jian Yang, Jiaming Huang, Yiqing Zhang, Weiqiang Wang, Shan Xue, Surya Nepal, Quanzheng Sheng. eRiskCom: an e-commerce risky community detection platform. The VLDB Journal 31, 1085–1101 (2022). <font color='#FF0000'> (CCF A) </font>
[[HTML]](https://doi.org/10.1007/s00778-021-00723-z) [[PDF]](/pdf/2022_VLDBJ_eRiskCom.pdf)
- [Arxiv, FIND v3]Ziyi Gao, Yike Xu, Jiahao Yuan, `Baokun Wang`<font color='#FF0000'> (correspondence) </font>, Jinyong Wen, Xiaotong Lin, Yun Liu, Xing Fu, Yu Cheng, Yongchao Liu, Weiqiang Wang, Zhongle Xie. Instruction-aware User Embedding via Synergistic Language and Representation Modeling.[[PDF]](https://arxiv.org/pdf/2510.11016)
- [Arxiv, FIND v2]Chuan He, Yang Chen, Wuliang Huang, Tianyi Zheng, Jianhu Chen, Bin Dou, Yice Luo, Yun Zhu, `Baokun Wang`<font color='#FF0000'> (correspondence) </font>, Yongchao Liu, Xing Fu, Yu Cheng, Chuntao Hong, Weiqiang Wang, Xin-Wei Yao, Zhongle Xie. Learning Unified User Quantized Tokenizers for User Representation.[[PDF]](https://arxiv.org/abs/2508.00956)
- [Arxiv]Jintang Li, Zheng Wei, Jiawang Dan, Jing Zhou, Yuchang Zhu, Ruofan Wu, `Baokun Wang`, Zhang Zhen, Changhua Meng, Hong Jin, Zibin Zheng, Liang Chen. Hetero$^2$Net: Heterophily-aware Representation Learning on Heterogenerous Graphs[[PDF]](https://arxiv.org/pdf/2310.11664)
- [Arxiv]Jintang Li, Jiawang Dan, Ruofan Wu, Jing Zhou, Sheng Tian, Yunfei Liu, `Baokun Wang`, Changhua Meng, Weiqiang Wang, Yuchang Zhu, Liang Chen, Zibin Zheng. LasTGL: An Industrial Framework for Large-Scale Temporal Graph Learning[[PDF]](https://arxiv.org/abs/2311.16605)
- [Arxiv] Jiafu Wu, Mufeng Yao, Dong Wu, Mingmin Chi, `Baokun Wang`, Ruofan Wu, Xin Fu, Changhua Meng and Weiqiang Wang. DEDGAT: Dual Embedding of Directed Graph Attention Networks for Detecting Financial Risk[J/OL]. https://arxiv.org/abs/2303.03933, 2023-3. [[PDF]](https://arxiv.org/pdf/2303.03933.pdf)

# 📝 Patents 

- [已授权发明专利 CN111311408B] 电子交易属性识别方法及装置 . 2020.02.
- [已授权发明专利 CN110705996A] 基于特征掩码的用户行为识别方法、系统、及装置 2020.01.
- [已授权发明专利 CN111523831B] 风险团伙的识别方法、装置、存储介质和计算机设备 2020.11.

# 🏅 Honors and Awards
- *2024.07* [国家级]“安全智选：基于用户理解大模型的服务创新”入选世界人工智能大会WAIC大模型典型示范应用
- *2023.12* [市级]上海金融科技优秀解决方案（面向金融安全的全图风控解决方案）
- *2021.12* [公司级]蚂蚁集团学术之星（学术贡献奖）
- *2021.07* [协会级]2021世界互联网大会信息通信行业反诈创新项目优秀奖（Risk-alike欺诈团伙发掘 - 全图风控技术）
- *2021.05* KDDCUP 2021 PCQM4M-LSC Track [5th](https://ogb.stanford.edu/kddcup2021/results/)
- *2021.03* [公司级]蚂蚁集团CV数据隐私保护大赛第8名（100+团队）
- *2021.03* [部门级]蚂蚁集团 机器智能 "鲁班大师奖"，"OCB红草莓奖"
- *2019.09* [部门级]蚂蚁集团 风险与决策中心新人奖 “万万没想到奖”
- *2019.06* [学院级]复旦大学计算机学院研究生奖学金一等奖.
- *2016.06* [校级]中国海洋大学优秀学生、优秀毕业生.

  
