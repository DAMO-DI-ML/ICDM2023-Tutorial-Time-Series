Welcome to our ICDM’23 Tutorial, “Robust Time Series Analysis and Applications: A Interdisciplinary Approach”.


##  Tutorial Date, Time, Location
- **Date**: Sunday, 12/03/2023 (mm/dd/yyyy)
- **Time**: 14:30-17:30
- **Location**: Room 6, Shanghai, China
- **Remote Zoom Meeting Information**: Zoom ID: 91649466943, Password: 202312


## Tutorial Description

Time series data is ubiquitous in various real-world applications, such as Artificial Intelligence for IT Operations (AIOps) in cloud computing, AI-powered Business Intelligence (BI) in E-commerce, Artificial Intelligence of Things (AIoT), etc. In real-world scenarios, time series often exhibit complex patterns with trend, seasonality, outlier, and noise. In addition, as more time series data are collected, handling the massive amount of data efficiently is crucial in many applications. These significant challenges exist in various tasks, such as forecasting, anomaly detection, and fault cause localization. Therefore, designing effective, efficient, and explainable models for different tasks, which are robust enough to address the aforementioned challenging patterns and noise in real-world applications, is of great theoretical and practical interest. 

This tutorial summarizes state-of-the-art algorithms of robust time series analysis through an interdisciplinary approach ranging from robust statistics, signal processing, optimization, and the most recent deep learning-based methods. We will not only introduce the principle of time series algorithms but also provide insights into applying various techniques from multiple disciplines effectively in practical, real-world industrial applications.

Specifically, we organize the tutorial in a bottom-up framework. Firstly, We present preliminaries from different disciplines, including robust statistics, signal processing, optimization, deep learning, and explainable AI (XAI). Then, we identify and discuss those most-frequently processing blocks in robust time series analysis, including periodicity detection, trend filtering, seasonal-trend decomposition, and time series similarity. These blocks can be integrated into different time series tasks as general built-in blocks. Lastly, we discuss recent advances in multiple time series tasks, including forecasting, autoscaling, anomaly detection, and fault cause localization, as well as practical lessons learned from large-scale time series applications in industrial scenarios.


## Tutorial Materials and Outline

### Tutorial [[slides]](https://1drv.ms/b/s!AvjVET3jp-5QiKpr8CHlUPXgscLROA?e=byB68O)
### Tutorial Outline

   
1. Preliminaries 
   - Real-world Challenges and Motivations for Robustness

   - Robust Statistics: Robust Regression, M-estimators

   - Signal Processing: Fourier Transform, Wavelet Transform

   - Optimization Algorithms: Alternating Direction Method of Multipliers (ADMM), Majorize-Minimization (MM) Algorithm

   - Deep Learning: RNN, CNN, Transformer, Data Augmentation, and LLMs

   - Explainable Artificial Intelligence (XAI): GAM, LIME, SHAP, Integrated Gradient, PINN
   
2. Robust Time Series Processing Blocks 
   - Time Series Periodicity Detection
   - Time Series Trend Filtering
   - Time Series Seasonal-Trend Decomposition
   - Time Series Similarity

3. Robust Time Series Applications and Practices 
   - Forecasting: Statistical Models, Tree Models, Deep Ensemble, Transformer, and LLMs for Forecasting
   - Autoscaling (from Forecasting to Decision-Making): Query Modeling, Scaling Decision
   - Anomaly Detection: Decomposition Model, Deep State Space Model, Graph Model, Transformer
   - Fault Cause Localization (from Anomaly Detection to Localization): Rule Set Learning, Root Cause Analysis
   - XAI for Time Series Data

4. Further Reading:
   - AI for Time Series (AI4TS) Papers, Tutorials, and Surveys [\[GitHub link\]](https://github.com/qingsongedu/awesome-AI-for-time-series-papers)



## Key References Published by Lecturers
- **[NeurIPS'22]** Tian Zhou, Ziqing Ma, Xue Wang, Qingsong Wen, Liang Sun, Tao Yao, Wotao Yin, Rong Jin, "FiLM: Frequency improved Legendre Memory Model for Long-term Time Series Forecasting", in Proc. 36th Conference on Neural Information Processing Systems (NeurIPS 2022), New Orleans, LA, Dec. 2022.  [[arXiv]](https://arxiv.org/abs/2205.08897) 
- **[NeurIPS'22]** Chenxiao Yang, Qitian Wu, Qingsong Wen, Zhiqiang Zhou, Liang Sun, Junchi Yan, "Variational Context Adjustment for Temporal Event Prediction under Distribution Shifts," in Proc. 36th Annual Conference on Neural Information Processing Systems (NeurIPS 2022), New Orleans, LA, Dec. 2022.
- **[ICML'22]** Tian Zhou, Ziqing Ma, Qingsong Wen, Xue Wang, Liang Sun, Rong Jin, "FEDformer: Frequency Enhanced Decomposed Transformer for Long-term Series Forecasting," in Proc. 39th International Conference on Machine Learning (ICML 2022), Baltimore, Maryland, July 17-23, 2022. [[arXiv]](https://arxiv.org/abs/2201.12740) [[code]](https://github.com/MAZiqing/FEDformer)
- **[KDD'22]** Weiqi Chen, Wenwei Wang, Bingqing Peng, Qingsong Wen, Tian Zhou, Liang Sun, "Learning to Rotate: Quaternion Transformer for Complicated Periodical Time Series Forecasting", in Proc. 28th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD 2022), Washington DC, Aug. 2022.[[paper]](https://dl.acm.org/doi/abs/10.1145/3534678.3539234)
- **[arXiv'22]** Qingsong Wen, Tian Zhou, Chaoli Zhang, Weiqi Chen, Ziqing Ma, Junchi Yan, Liang Sun, "Transformers in Time Series: A Survey," in arXiv preprint arXiv:2202.07125, 2022 [[arXiv]](https://arxiv.org/abs/2202.07125) [[Github]](https://github.com/qingsongedu/time-series-transformers-review)
- **[arXiv'22]** Tian Zhou, Ziqing Ma, Xue Wang, Qingsong Wen, Liang Sun, Tao Yao, Wotao Yin, Rong Jin, "FiLM: Frequency improved Legendre Memory Model for Long-term Time Series Forecasting", arXiv.2205.08897, 2022. [[arXiv]](https://arxiv.org/abs/2205.08897)
- **[IJCAI'21]** Qingsong Wen, Liang Sun, Fan Yang, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu, "Time Series Data Augmentation for Deep Learning: A Survey," in the 30th International Joint Conference on Artificial Intelligence (IJCAI 2021), Montreal, Canada, Aug. 2021. [[arXiv]](https://arxiv.org/abs/2002.12478). Note: Selected by Paper Digest into **Most Influential IJCAI Papers (Version: 2022-02), Rank 1st** (1/600+ IJCAI'21 papers) [[link]](https://www.paperdigest.org/2022/02/most-influential-ijcai-papers-2022-02/)
- **[ICASSP'22]** Chaoli Zhang\*, Zhiqiang Zhou\*, Yingying Zhang\*, Linxiao Yang\*, Kai He\*, Qingsong Wen\*, Liang Sun\* (\*Equally Contributed), "NetRCA: An Effective Network Fault Cause Localization Algorithm," in Proc. IEEE 47th International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2022), Singapore, May 2022. [[arXiv]](https://arxiv.org/abs/2202.11269). Note: **ICASSP‘22 AIOps Challenge, First Place** (1/382, Team Name: MindOps) [[link]](https://www.aiops.sribd.cn/home/finalRank)
- **[arXiv'22]** Tian Zhou, Jianqing Zhu, Xue Wang, Ziqing Ma, Qingsong Wen, Liang Sun, Rong Jin, "TreeDRNet: A Robust Deep Model for Long Term Time Series Forecasting", arXiv:2206.12106. [[arXiv]](https://arxiv.org/abs/2206.12106)
- **[ICDE'22]** Huajie Qian, Qingsong Wen, Liang Sun, Jing Gu, Qiulin Niu, Zhimin Tang, "RobustScaler: QoS-Aware Autoscaling for Complex Workloads," in Proc. IEEE 38th International Conference on Data Engineering (ICDE 2022), Kuala Lumpur, Malaysia, May 2022. [[arXiv]](https://arxiv.org/abs/2204.07197), Media Coverage: [[Mo4Tech]](https://www.mo4tech.com/ali-cloud-and-dharma-institute-ahpa-elastic-forecasting-paper-was-accepted-by-icde.html) [[Alicloudnative]](https://mp.weixin.qq.com/s/-aZd9SvNPYuQc4nEwiNzvQ) [Zhihu](https://zhuanlan.zhihu.com/p/495126311) [[1024sou]](https://www.1024sou.com/article/892152.html)
- **[SIGMOD'21]** Qingsong Wen, Kai He, Liang Sun, Yingying Zhang, Min Ke, Huan Xu, "RobustPeriod: Time-Frequency Mining for Robust Multiple Periodicity Detection," in Proc. ACM SIGMOD International Conference on Management of Data (SIGMOD 2021), Xi'an, China, Jun. 2021. [[arXiv]](https://arxiv.org/abs/2002.09535)
- **[KDD'20]** Qingsong Wen, Zhe Zhang, Yan Li, Liang Sun, "Fast RobustSTL: Efficient and Robust Seasonal-Trend Decomposition for Time Series with Complex Patterns," in Proc. 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD 2020), San Diego, CA, Aug. 2020. [[paper]](https://www.kdd.org/kdd2020/accepted-papers/view/fast-robuststl-efficient-and-robust-seasonal-trend-decomposition-for-time-s)
- **[AAAI'19]** Qingsong Wen, Jingkun Gao, Xiaomin Song, Liang Sun, Huan Xu, Shenghuo Zhu, "RobustSTL: A Robust Seasonal-Trend Decomposition Algorithm for Long Time Series," in Proc. 33th AAAI Conference on Artificial Intelligence (AAAI 2019), Honolulu, Hawaii, Jan. 2019. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4480/4358), Media Coverage: [[Alibaba Tech]](https://alibabatech.medium.com/looking-for-trends-in-the-iot-era-enhanced-time-series-analysis-with-robuststl-fd00b9afe157)
- **[IJCAI'19]** Qingsong Wen, Jingkun Gao, Xiaomin Song, Liang Sun, Jian Tan, "RobustTrend: A Huber Loss with a Combined First and Second Order Difference Regularization for Time Series Trend Filtering," in Proc. 28th International Joint Conference on Artificial Intelligence (IJCAI 2019), Macao, China, Aug. 2019. [[arXiv]](https://arxiv.org/abs/1906.03751)
- **[ICASSP'20]** Qingsong Wen, Zhengzhi Ma, Liang Sun, "On Robust Variance Filtering and Change of Variance Detection," in Proc. IEEE 45th International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2020), Barcelona, Spain, May 2020. [[paper]](https://ieeexplore.ieee.org/document/9053548)
- **[ICASSP'21]** Qingyang Xu, Qingsong Wen, Liang Sun, "Two-Stage Framework for Seasonal Time Series Forecasting," in Proc. IEEE 46th International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2021), Toronto, Canada, Jun. 2021. [[arXiv]](https://arxiv.org/pdf/2103.02144.pdf)
- **[ICASSP'21]** Linxiao Yang, Qingsong Wen, Bo Yang, Liang Sun, "A Robust and Efficient Multi-Scale Seasonal-Trend Decomposition," in Proc. IEEE 46th International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2021), Toronto, Canada, Jun. 2021. [[paper]](https://drive.google.com/file/d/17ewVAL-mdwH6QoIka1ZrzAAoyXtph8a3/view)
- **[KDD'20 WS]** Jingkun Gao, Xiaomin Song, Qingsong Wen, Pichao Wang, Liang Sun, Huan Xu, "RobustTAD: Robust Time Series Anomaly Detection via Decomposition and Convolutional Neural Networks,"  in ACM SIGKDD Workshop on Mining and Learning from Time Series (KDD-MiLeTS 2020), San Diego, CA, Aug. 2020. [[arXiv]](https://arxiv.org/abs/2002.09545)
- **[TKDE'22]** Longyuan Li, Junchi Yan, Qingsong Wen, Yaohui Jin, and Xiaokang Yang, "Learning Robust Deep State Space for Unsupervised Anomaly Detection in Contaminated Time-Series," IEEE Transactions on Knowledge and Data Engineering (TKDE), 2022. [[paper]](https://ieeexplore.ieee.org/document/9773982)
- **[TPWRS'22]** Yihong Zhou, Zhaohao Ding, Qingsong Wen, Yi Wang, "Robust Load Forecasting towards Adversarial Attacks via Bayesian Learning," IEEE Transactions on Power Systems (TPWRS 2022), 2022. [[paper]](https://ieeexplore.ieee.org/document/9775206)
- **[CIKM'22]** Chaoli Zhang, Tian Zhou, Qingsong Wen, Liang Sun, "TFAD: A Decomposition Time Series Anomaly Detection Architecture with Time-Freq Analysis,” in Proc. 31st ACM International Conference on Information and Knowledge Management (CIKM 2022), Atlanta, GA, Oct. 2022. 
- **[CIKM'22]** Xiaomin Song, Qingsong Wen, and Liang Sun, "Robust Time Series Dissimilarity Measure for Outlier Detection and Periodicity Detection,” in Proc. 31st ACM International Conference on Information and Knowledge Management (CIKM 2022), Atlanta, GA, Oct. 2022. 
- **[CIKM'21]** Yingying Zhang, Zhengxiong Guan, Huajie Qian, Leili Xu, Hengbo Liu, Qingsong Wen, Liang Sun, Junwei Jiang, Lunting Fan, Min Ke, "CloudRCA: A Root Cause Analysis Framework for Cloud Computing Platforms," in Proc. 30th ACM International Conference on Information and Knowledge Management (CIKM 2021), Queensland, Australia, Nov. 2021. [[arXiv]](https://arxiv.org/abs/2111.03753)
- **[ICCV'19]** Linxiao Yang, Ngai-Man Cheung, Jiaying Li, and Jun Fang. Deep clustering by gaussian mixture variational autoencoders with graph embedding. In Proc. of the IEEE/CVF International Conference on Computer Vision (ICCV 2019), pages 6440–6449, 2019. [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_Deep_Clustering_by_Gaussian_Mixture_Variational_Autoencoders_With_Graph_Embedding_ICCV_2019_paper.pdf)
- **[KDD'19]** Ming Lin, Xiaomin Song, Qi Qian, Hao Li, Liang Sun, Shenghuo Zhu, and Rong Jin. 2019. Robust Gaussian process regression for real-time high precision GPS signal enhancement. In Proc. of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD 2019). 2838–2847. [[arXiv]](https://arxiv.org/abs/1906.01095)
- **[AAAI'22]** Yan Li, Rui Xia, Chunchen Liu, and Liang Sun. 2022. A Hybrid Causal Structure Learning Algorithm for Mixed-type Data. In Proc. of the AAAI Conference on Artificial Intelligence (AAAI 2022), 2022. [[paper]](https://www.aaai.org/AAAI22Papers/AAAI-12541.LiY.pdf)
- **[NeurIPS'21]** Fan Yang, Kai He, Linxiao Yang, Hongxia Du, Jingbang Yang, Bo Yang, and Liang Sun. 2021. Learning Interpretable Decision Rule Sets: A Submodular Optimization Approach. in Proc. of Advances in Neural Information Processing Systems (NeurIPS 2021), 2021. [[paper]](https://proceedings.neurips.cc/paper/2021/file/eaa32c96f620053cf442ad32258076b9-Paper.pdf)


## Short Bio of Lecturers

<img align="left" src="files/QingsongWen.jpeg" width="150" > **[Qingsong Wen](https://sites.google.com/site/qingsongwen8)** is a Staff Engineer with Alibaba DAMO Academy-Decision Intelligence Lab at Bellevue, WA, USA, working in the areas of intelligent time series analysis, data-driven intelligence decisions, machine learning, and signal processing. Before that, he worked at Futurewei, Qualcomm, and Marvell in the areas of big data and signal processing, and received his M.S. and Ph.D. degrees in Electrical and Computer Engineering from Georgia Institute of Technology, Atlanta, USA. He has published over 60 top-ranked journal and conference papers, received AAAI/IAAI 2023 Deployed Application Award, and won the First Place in 2022 ICASSP Grand Challenge Competition (AIOps in Networks). He is an Associate Editor for Neurocomputing, Guest Editor for IEEE Internet of Things Journal, and Guest Editor for Applied Energy. He is an IEEE senior member, and a member of the IEEE Machine Learning for Signal Processing Technical Committee. He also serves as Organizer/Co-Chair of the Workshop on AI for Time Series at AAAI'24, KDD'23, IJCAI'23, and ICDM'23. 


<img align="left" src="files/LinxiaoYang.png" width="150" > **[Linxiao Yang]()** is a Senior Engineer with Alibaba DAMO Academy, working in the fields of time series analysis, pattern mining, and interpretable machine learning. He received the B.S. degree in electrical engineering from Southwest Jiaotong University, Chengdu, China, and the Ph.D. degree in Communication and Information Engineering from the University of Electronic of Science and Technology of China, Chengdu, China. He won the First Place in 2022 ICASSP Grand Challenge (AIOps in Networks) Competition. His research interests include data-driven decision making, efficient optimization methods, interpretable machine learning, and signal processing.


<img align="left" src="files/TianZhou.jpeg" width="150" > **[Tian Zhou]()** is a Senior Algorithm Engineer in Alibaba DAMO Lab, working mainly on time series forecasting and sequence modeling. He has worked on all aspects ranging from practical model designing to theoretical foundations. Prior to joining Alibaba, Tian obtained a BS in chemistry from Tsinghua University, an MS in Statistics from Rutgers-New Brunswick, an MS in Machine Learning from Rutgers-New Brunswick, and a PhD from Rutgers-New Brunswick, focusing on computational chemistry for organometalic catalysts.



<img align="left" src="files/weiqi.jpeg" width="150" > **[Weiqi Chen]()** is currently an engineer at DAMO Academy-Decision Intelligence Lab at Hangzhou, China. He received B.S. from Xi'an Jiaotong University and M.S. from Zhejiang University in computer Science an Technology. His research interest includes data mining, machine learning, and Graph Neural Networks, with a focus on time series analysis like time series forecasting and time series anomaly detection, as well as their related applications, e.g., electricity forecasting and weather prediction.


<img align="left" src="files/bingqing.jpeg" width="150"> **[Bingqing Peng]()** is a senior engineer at DAMO Academy Decision Intelligence Lab, Alibaba Group. Before that, She worked at Vaisala as a Data Scientist in the areas of Applied Meteorology Science and Renewable Energy Forecasting. She received B.S. from Nanjing University with major in Mathematics and M.S. in Statistics from University of Washington Seattle. Her research includes data mining and machine learning, with a focus on time series analysis in industrial applications in renewable energy forecasting and weather forecasting.



<img align="left" src="files/LiangSun.jpeg" width="150" > **[Liang Sun](https://scholar.google.com/citations?user=8JbrsgUAAAAJ&hl=en)** a Senior Staff Engineer at DAMO Academy, Alibaba Group, Bellevue, USA. He received B.S.(2003) from Nanjing University, and Ph.D.(2011) from Arizona State University, both in computer science. Dr. Sun has over 60 publications including 2 books in the fields of machine learning and data mining. His work on dimensionality reduction won the KDD 2010 Best Research Paper Award Honorable Mention, and won the Second Place in KDD Cup 2012 Track 2 Competition. He also won the First Place in 2022 ICASSP Grand Challenge (AIOps in Networks) Competition. At Alibaba Group, he is working on temporal data mining, including time series anomaly detection, forecasting, and their applications.


## Related Tutorial
- KDD 2022 Tutorial: Robust Time Series Analysis and Applications: An Industrial Perspective [[Link]](https://github.com/DAMO-DI-ML/KDD2022-Tutorial-Time-Series)




