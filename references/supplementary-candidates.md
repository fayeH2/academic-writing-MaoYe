# 数据库外相关候选与作者消歧

以下为 OpenAlex 检索得到、尚未在基础 DBLP 目录或一手补充列表中确认的相关线索。它们与计算机学院单位或既有合作者网络有联系，但身份、版本或出版细节仍待出版物一手证据核验。**不将它们当作已完成归属的论文全集，不用于风格归纳。**

本次抓取 [OpenAlex 作者候选 A5100682790](https://api.openalex.org/authors/A5100682790) 的作品列表返回 501 条，其中 216 条按题名或 DOI 与基础目录匹配，另有 285 条未匹配；后者大量为同名混入。作者汇总计数与分页作品数也存在差别，所以不把作者页的总数直接当作论文数。
下列保留 63 条有相关性线索的候选；学校/合作者列表能确认的新增项已放入主目录 S 编号，避免重复计入本表。

通讯字段不采用 OpenAlex 的 false 值作否定判断：字段缺失或数据库未标注都可能导致 false。下列通讯身份统一待核验。

## 不应混入的典型记录

| 例子 | 排除或暂不归属的理由 |
|---|---|
| Exploiting geographical influence for collaborative point-of-interest recommendation | Mao Ye 的单位为 Pennsylvania State University，与目标身份不匹配 |
| Multi-Class 3D Object Detection with Single-Class Supervision | Mao Ye 的单位为 UT Austin，不能仅凭同名归属 |
| Big Data in Finance | 金融院系、Illinois / NBER 身份，与目标研究者不匹配 |
| Influence of the Maximum Blur Radius on Depth Sensor Based on Liquid Crystal Lens | 单位虽同为 UESTC，但学院为 Optoelectronic Science and Engineering；不按同一学校合并 |

## 相关候选列表

### C01 · 2013 · Drift Compensation for Electronic Nose by Semi-Supervised Domain Adaption

作者：Qihe Liu, Xue Li, Mao Ye, Shuzhi Sam Ge, Xiaosong Du。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：University of Electronic Science and Technology of China, School of Computer Science and Engineering, Chengdu, China；Sch. of Comput. Sci. & Eng., Univ. of Electron. Sci. & Technol. of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2020033987)；[DOI](https://doi.org/10.1109/jsen.2013.2285919)。

### C02 · 2015 · Domain adaption of vehicle detector based on convolutional neural networks

作者：Xudong Li, Mao Ye, Min Fu, Pei Xu, Tao Li。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, Center for Robotics and Key Laboratory for Neuro Information of Ministry of Education, University of Electronic Science and Technology of China, Chengdu, 611731, P. R. China；Univ. of Electronic Sci. and Tech. of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W827974120)；[DOI](https://doi.org/10.1007/s12555-014-0119-z)。

### C03 · 2009 · New stability and stabilization for switched neutral control systems

作者：Lianglin Xiong, Shouming Zhong, Mao Ye, Shi-Liang Wu。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054, PR China；School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 610054, PR China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2030045734)；[DOI](https://doi.org/10.1016/j.chaos.2009.03.093)。

### C04 · 2011 · Abnormal crowd behavior detection using size-adapted spatio-temporal features

作者：Bo Wang, Mao Ye, Xue Li, Fengjuan Zhao。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 610054, P. R. China；State Key Lab. for Novel Software Technology, Nanjing University, Nanjing, P. R. China；Nanjing University；University of Electronic Science and Technology of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2074508921)；[DOI](https://doi.org/10.1007/s12555-011-0511-x)。

### C05 · 2009 · pth moment exponential synchronization analysis for a class of stochastic neural networks with mixed delays

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054, People’s Republic of China；School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054, People's Republic of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2049883300)；[DOI](https://doi.org/10.1016/j.cnsns.2009.07.018)。

### C06 · 2016 · Head Pose Estimation Based on Robust Convolutional Neural Network

作者：Jiao Bao, Mao Ye。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China , Center for Robotics, Key Laboratory for NeuroInformation of Ministry of Education, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2582720287)；[DOI](https://doi.org/10.1515/cait-2016-0083)。

### C07 · 2022 · Variable Rate Independently Recurrent Neural Network (IndRNN) for Action Recognition

作者：Yanbo Gao, Chuankun Li, Shuai Li, Xun Cai, Mao Ye, Hui Yuan。数据库列 Mao Ye 第 5 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4220656863)；[DOI](https://doi.org/10.3390/app12073281)。

### C08 · 2009 · Improved Robust Stability Criteria of Uncertain Neutral Systems with Mixed Delays

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2002785272)；[DOI](https://doi.org/10.1155/2009/294845)。

### C09 · 2025 · Knowledge Adaptation for Cross-Domain Moving Infrared Small Target Detection

作者：Dengyan Luo, Yanping Xiang, Hu Wang, Luping Ji, Mao Ye。数据库列 Mao Ye 第 5 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China；School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, P.R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4413822402)；[DOI](https://doi.org/10.1109/tgrs.2025.3604069)。

### C10 · 2008 · Finding the optimal number of clusters using genetic algorithms

作者：Yongguo Liu, Mao Ye, Jun Peng, Hong Wu。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2120136896)；[DOI](https://doi.org/10.1109/iccis.2008.4670864)。

### C11 · 2022 · A Deep Attention Model for Action Recognition from Skeleton Data

作者：Yanbo Gao, Chuankun Li, Shuai Li, Xun Cai, Mao Ye, Hui Yuan。数据库列 Mao Ye 第 5 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4213111496)；[DOI](https://doi.org/10.3390/app12042006)。

### C12 · 2012 · Rapid and robust traffic accident detection based on orientation map

作者：Jinglei Zhou, Mao Ye, Jian Ding, Songan Mao, Huixiong John Zhang。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：Univ. of Electronic Science and Technology of China (China)。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2152610079)；[DOI](https://doi.org/10.1117/1.oe.51.11.117201)。

### C13 · 2016 · Mobile phone-based internet of things human action recognition for E-health

作者：Jiao Bao, Mao Ye, Yumin Dou。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2597497695)；[DOI](https://doi.org/10.1109/icsp.2016.7877972)。

### C14 · 2013 · Object detection using voting spaces trained by few samples

作者：Pei Xu, Mao Ye, Xue Li, Lishen Pei, Pengwei Jiao。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：Univ. of Electronic Science and Technology of China (China)。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2154637874)；[DOI](https://doi.org/10.1117/1.oe.52.9.093105)。

### C15 · 2009 · Discrete nonlinear inequalities in time control systems

作者：Kelong Zheng, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, Sichuan, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2141674881)；[DOI](https://doi.org/10.1109/icacia.2009.5361069)。

### C16 · 2022 · Single-pixel imaging via adaptive Stockwell basis selection

作者：Zixin Tang, Jianwei Zhang, Zhenyu Xu, Mao Ye, Yiguang Liu。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, Sichuan Province, 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4212935478)；[DOI](https://doi.org/10.1016/j.ijleo.2022.168717)。

### C17 · 2010 · Graph Cut segmentation with automatic editing for Industrial images

作者：Jinglei Zhou, Mao Ye, Xudong Zhang。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China；School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1975108959)；[DOI](https://doi.org/10.1109/icicip.2010.5565294)。

### C18 · 2015 · Random Forest with Adaptive Local Template for Pedestrian Detection

作者：Tao Xiang, Tao Li, Mao Ye, Zijian Liu。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, Center for Robotics, University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1873415448)；[DOI](https://doi.org/10.1155/2015/767423)。

### C19 · 2014 · Unconstrained face verification by optimally organizing multiple classifiers

作者：Renjie Huang, Tao Li, Mao Ye, Yumin Dou。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, Key Laboratory for NeuroInformation of Ministry of Education, University of Electronic Science and Technology of China, Chengdu, 611731, P. R. China；Univ. of Electronic Sci. and Tech. of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2030214874)；[DOI](https://doi.org/10.1007/s12555-013-0294-3)。

### C20 · 2013 · An efficient fire detection method based on orientation feature

作者：Tao Li, Mao Ye, Feng Pang, Haiyang Wang, Jian Ding。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 611731, P. R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2067933917)；[DOI](https://doi.org/10.1007/s12555-012-9314-y)。

### C21 · 2010 · BIBO stability of switched uncertain neutral control system

作者：Jinzhong Cui, Lianglin Xiong, Mao Ye。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 610054, P. R. China；Univ. of Electronic Sci. and Tech. of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2062140036)；[DOI](https://doi.org/10.1007/s12555-010-0427-x)。

### C22 · 2017 · Person re-identification based on viewpoint correspondence pattern

作者：Lan Lin, Dan Liu, Xudong Li, Feng Zhang, Mao Ye。数据库列 Mao Ye 第 5 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：Department of Computer Science and Engineering, University of Electronic Science and Technology, Sichuan, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2791424146)；[DOI](https://doi.org/10.1109/iccwamtip.2017.8301461)。

### C23 · 2019 · Self-Evolutionary Pose Distillation

作者：Feng Zhang, Hong Hu, Hanbin Dai, Liangbo Zhou, Mao Ye。数据库列 Mao Ye 第 5 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：Department of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China；University of Electronic Science and Technology of China,Department of Computer Science and Engineering,Chengdu,China,611731。
- 入口：[OpenAlex 原始记录](https://openalex.org/W3016537083)；[DOI](https://doi.org/10.1109/iccwamtip47768.2019.9067547)。

### C24 · 2016 · Domain adaptation of image classification exploiting target adaptive collaborative local-neighbor representation

作者：Song Tang, Zhixian Chen, Lijuan Chen, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science & Engineering, University of Electronic Science and Technology of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2765685101)；[DOI](https://doi.org/10.1109/iccwamtip.2016.8079827)。

### C25 · 2020 · Optical frequency and phase information-based fusion approach for image rotation symmetry detection

作者：Ronggang Huang, Yiguang Liu, Yunan Zheng, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China, Chengdu, Sichuan Province 610054, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W3025482980)；[DOI](https://doi.org/10.1364/oe.390224)。

### C26 · 2021 · Two-stage Multi-frame Cooperative Quality Enhancement on Compressed Video

作者：Shengjie Chen, Mao Ye。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4200277519)；[DOI](https://doi.org/10.1109/icicip53388.2021.9642200)。

### C27 · 2010 · A hybrid fire detection using Hidden Markov Model and luminance map

作者：Liqiang Wang, Mao Ye, Yuanxiang Zhu。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China；State Key Laboratory for Novel Software Technology, Nanjing University, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1971427327)；[DOI](https://doi.org/10.1109/miaca.2010.5528510)。

### C28 · 2009 · Real Time ROI Generation for Pedestrian Detection

作者：Xin Zhao, Mao Ye, Yingying Zhu, Chuanzhi Zhong, Jinglei Zhou。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2157229019)；[DOI](https://doi.org/10.1109/cise.2009.5366155)。

### C29 · 2009 · New Improved Exponential Stability Criteria for Discrete‐Time Neural Networks with Time‐Varying Delay

作者：Zixin Liu, Shu Lv, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2022938639)；[DOI](https://doi.org/10.1155/2009/874582)。

### C30 · 2014 · Image Classification Based on KPCA and SVM with Randomized Hyper-parameter Optimization

作者：Lin Li, Jin Lian, Yue Wu, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China , Chengdu 611731 , China；University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2141629367)；[DOI](https://doi.org/10.14257/ijsip.2014.7.4.29)。

### C31 · 2015 · Object Detection Based on Two Level Fast Matching

作者：Yumin Dou, Mao Ye, Pei Xu, Lishen Pei, Zhenghua Liu。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering Center for Robotics , University of Electronic Science and Technology of China Chengdu 611731 , P.R. China；School of Computer Science and Engineering Center for Robotics, University of Electronic Science and Technology of China Chengdu 611731, P.R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2557656373)；[DOI](https://doi.org/10.14257/ijmue.2015.10.12.36)。

### C32 · 2017 · A new keyframe decision mechanism with translation constraint for visual slam

作者：Yan Gan, Mao Ye, Guanyu Xing, Fanyu Zeng。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, P.R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2792829312)；[DOI](https://doi.org/10.1109/iccwamtip.2017.8301468)。

### C33 · 2010 · Robust Bibo Stabilization Analysis For Discrete-Time Uncertain System

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1424280566)；[DOI](https://doi.org/10.5281/zenodo.1060595)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C34 · 2014 · A hierarchical method for pedestrian detection with random forests

作者：Tao Xiang, Tao Li, Mao Ye, Xiao Nie, Chao Zhang。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2038802954)；[DOI](https://doi.org/10.1109/icosp.2014.7015198)。

### C35 · 2010 · Improved Robust Stability Criteria For Discrete-Time Neural Networks

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2109772319)；[DOI](https://doi.org/10.5281/zenodo.1080237)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C36 · 2020 · Improving person re-identification by attention and multi-attributes

作者：Xin Zheng, Lan Lin, Mao Ye, Li Wang, Chunlin He。数据库列 Mao Ye 第 3 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4403489054)；[DOI](https://doi.org/10.11834/jig.190185)。

### C37 · 2014 · Robust low‐rank image representations by deep matrix decompositions

作者：Chenxue Yang, Mao Ye, Xudong Li, Zijian Liu, Song Tang, Tao Li。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：The School of Computer Science and Engineering Center for Robotics Key Laboratory for NeuroInformation of Ministry of Education University of Electronic Science and Technology of China Chengdu 611731 People's Republic of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2069706744)；[DOI](https://doi.org/10.1049/el.2014.2873)。

### C38 · 2015 · Fast object detection based on several samples by training voting space

作者：Pei Xu, Mao Ye, Lishen Pei, Yumin Dou, Hongyi Chen。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：University of Electronic Science and Technology of China, School of Computer Science and Engineering, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2297749809)；[DOI](https://doi.org/10.1134/s1054661815040227)。

### C39 · 2005 · Multistability of competitive neural networks with different time scales

作者：Mao Ye。数据库列 Mao Ye 第 1 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：Computational Intelligence Laboratory, School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China；Sch. of Comput. Sci. & Eng., Univ. of Electron. Sci. & Technol. of China, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2133419206)；[DOI](https://doi.org/10.1109/icccas.2005.1495263)。

### C40 · 2009 · Advanced Gronwall-Bellman-Type Integral Inequalities And Their Applications

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1523945860)；[DOI](https://doi.org/10.5281/zenodo.1058783)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C41 · 2008 · Exponentially Stable Conditions of Parametric Uncertainty Impulsive Switched Systems with Time Delay

作者：Zixin Liu, Shu Lv, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School ofApplied Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China；Sch. of Appl. Comput. Sci. & Eng., Univ. of Electron. Sci. & Technol. of China, Chengdu。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2091439473)；[DOI](https://doi.org/10.1109/icacia.2008.4770045)。

### C42 · 2004 · Global convergence analysis of a PCA learning algorithm

作者：Mao Ye, Yue Wu, Yi Zhang。数据库列 Mao Ye 第 1 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2150023147)；[DOI](https://doi.org/10.1109/icccas.2004.1346358)。

### C43 · 2009 · Pth Moment Exponential Synchronization Of A Class Of Chaotic Neural Networks With Mixed Delays

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2245002316)；[DOI](https://doi.org/10.5281/zenodo.1079283)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C44 · 2013 · Convergence Analysis Of An Alternative Gradient Algorithm For Non-Negative Matrix Factorization

作者：Chenxue Yang, Mao Ye, Zijian Liu, Tao Li, Jiao Bao。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1477404654)；[DOI](https://doi.org/10.5281/zenodo.1091363)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C45 · 2009 · New Stabilization For Switched Neutral Systems With Perturbations

作者：Lianglin Xiong, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 3 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1768085054)；[DOI](https://doi.org/10.5281/zenodo.1331508)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C46 · 2009 · Delay-Dependent Stability Analysis For Uncertain Switched Neutral System

作者：Lianglin Xiong, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 3 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1800705493)；[DOI](https://doi.org/10.5281/zenodo.1084911)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C47 · 2014 · Contour abstraction based on salient points

作者：Yumin Dou, Mao Ye, Renjie Huang, Pei Xu, Tao Li。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, P.R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1971518696)；[DOI](https://doi.org/10.1109/iciea.2014.6931465)。

### C48 · 2014 · A Constrained Algorithm Based NMFαfor Image Representation

作者：Chenxue Yang, Tao Li, Mao Ye, Zijian Liu, Jiao Bao。数据库列 Mao Ye 第 3 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W1987885488)；[DOI](https://doi.org/10.1155/2014/179129)。

### C49 · 2008 · WITHDRAWN: Intrinsic subsequence decomposition for sequence data and its application to computer intrusion detection

作者：Yingying Zhu, Mao Ye, Xue Li, Naiqi Liu。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 610054, PR China；School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 610054, PR China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2028340478)；[DOI](https://doi.org/10.1016/j.eswa.2008.08.049)。
- **状态警示：题名带 WITHDRAWN，不能按正常有效发表成果引用；需核实撤回与替代版本。**

### C50 · 2013 · Convergence analysis of a non-negative matrix factorization algorithm based on Gibbs random field modeling

作者：Chenxue Yang, Mao Ye, Zijian Liu。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, 610054, P.R. China；Univ. of Electronic Sci. and Tech. of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2043965806)；[DOI](https://doi.org/10.1007/s12190-013-0646-4)。

### C51 · 2013 · Improved SOFI algorithm for blind extraction of smooth signals

作者：Jianbin Gao, Qi Xia, Jianping Li, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science & Engineering, University of Electronic Science and Technology of China, Chengdu, People's Republic of China and State Key Laboratory for Novel Software Technology, Nanjing University,Nanjing, People's Republic of China；(School of Computer Science & Engineering, University of Electronic Science and Technology of China, Chengdu, People's Republic of China and State Key Laboratory for Novel Software Technology, Nanjing University, Nanjing, People's Republic of China)。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2065908349)；[DOI](https://doi.org/10.1108/03321641311296972)。

### C52 · 2014 · Unconstrained face verification assisted by pairwise visual pre-estimation on key facial points

作者：Renjie Huang, Mao Ye, Yumin Dou, Pei Xu, Tao Li。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu, P.R. China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2080053234)；[DOI](https://doi.org/10.1109/iciea.2014.6931466)。

### C53 · 2009 · Exponential Stability And Periodicity Of A Class Of Cellular Neural Networks With Time-Varying Delays

作者：Zixin Liu, Shu Lü, Shouming Zhong, Mao Ye。数据库列 Mao Ye 第 4 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2108371104)；[DOI](https://doi.org/10.5281/zenodo.1329205)。
- 这是 Zenodo 存储记录，需继续核实原始出版物、年份及是否与其他版本重复。

### C54 · 2009 · Blind image separation by combining neighborhood information

作者：Mao Ye, Qihe Liu, Fan Li, Yongguo Liu。数据库列 Mao Ye 第 1 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology, Chengdu, China；School of Computer Science and Engineering, University of Electronic Science and Technology of China Chengdu 610054 China)。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2133157887)；[DOI](https://doi.org/10.1109/icccas.2009.5250460)。

### C55 · 2010 · FECG extraction from nonlinear mixture based on minimization of mutual information

作者：Dongxiao Ren, Mao Ye, Ying Yin, Yuanxiang Zhu。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2326606392)；[DOI](https://doi.org/10.3724/sp.j.1187.2010.00680)。

### C56 · 2004 · High Order Relaxation Schemes on Phase Transition Equations

作者：Mao Ye。数据库列 Mao Ye 第 1 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：School of Computer Science and Engineering,UESTC,Chengdu,610054,China)。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2348712207)。

### C57 · 2013 · Ultrasound Image Segmentation Using Graph Cuts with Deformable Prior

作者：Lin Li, Yue Wu, Mao Ye。数据库列 Mao Ye 第 3 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China, No. 2006, Xiyuan Ave, West Hi-Tech Zone, Chengdu, 611731, Sichuan, People’s Republic of China；University of Electronic Science and Technology of China, No. 2006, Xiyuan Ave, West Hi-Tech Zone, Chengdu, 611731, Sichuan, People's Republic of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2463216481)；[DOI](https://doi.org/10.1007/978-94-007-7618-0_150)。

### C58 · 2012 · CONVERGENCE ANALYSIS OF THE EAPG ALGORITHM FOR NON-NEGATIVE MATRIX FACTORIZATION †

作者：Chenxue Yang, Mao Ye。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：未提供。
- 入口：[OpenAlex 原始记录](https://openalex.org/W267794171)；[DOI](https://doi.org/10.14317/jami.2012.30.3_4.365)。

### C59 · 2016 · A Fast and Practical Contour Completion Approach with Chord-to-Point Distance

作者：Yumin Dou, Mao Ye, Renjie Huang, Xudong Li, Bao Jiao。数据库列 Mao Ye 第 2 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering ,；Center for Robotics, University of Electronic Science and Technology of China, Chengdu, 611731, P.R. China；School of Computer Science and Engineering,。
- 入口：[OpenAlex 原始记录](https://openalex.org/W2933362205)；[DOI](https://doi.org/10.14257/ijsip.2016.9.3.27)。

### C60 · 2024 · Multi-View Subspace Clustering Via Simultaneously Cycle Projection and Similarity Learning

作者：Tao Xiang, Liu Jie, Qiao Wenshen, Xiao Siying, Mao Ye。数据库列 Mao Ye 第 5 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China,Chengdu,China,611731。
- 入口：[OpenAlex 原始记录](https://openalex.org/W4407694182)；[DOI](https://doi.org/10.1109/iccwamtip64812.2024.10873718)。

### C61 · 2026 · IGDA-ICMH: an Importance Guided Feature and Network Dual Adaptation Framework towards Image Compression for Machine and Human Vision

作者：Yanbo Gao, X Zhao, Shuai Li, Xun Cai, Mao Ye, Li Li。数据库列 Mao Ye 第 5 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W7171424653)；[DOI](https://doi.org/10.1109/tcsvt.2026.3717373)。

### C62 · 2026 · Learning from Target-Like Candidates: Motion Prototype Reasoning for Moving Infrared Small Target Detection

作者：Bolin Wan, Mao Ye, Yuchen He, Hu Wang, Yuman Wang, Dengyan Luo, Luping Ji。数据库列 Mao Ye 第 2 作者。
- 归属线索：题名领域及合作者有相关线索；仅凭此不能确认本人。
- 单位原始字段：University of Electronic Science and Technology of China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W7211883969)；[DOI](https://doi.org/10.1109/tgrs.2026.3730866)。

### C63 · 2026 · Synergizing motion and depth: A distilled dual-branch network for moving infrared small target detection

作者：Dengyan Luo, Yanping Xiang, Hu Wang, Luping Ji, Song Tang, Mao Ye。数据库列 Mao Ye 第 6 作者。
- 归属线索：数据库记录的作者单位包含电子科大计算机院系。
- 单位原始字段：School of Computer Science and Engineering, University of Electronic Science and Technology of China, Chengdu 611731, China。
- 入口：[OpenAlex 原始记录](https://openalex.org/W7212050089)；[DOI](https://doi.org/10.1016/j.isprsjprs.2026.08.038)。
