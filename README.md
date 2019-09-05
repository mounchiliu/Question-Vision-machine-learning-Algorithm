# Ref: http://www.shenlanxueyuan.com/

## SLAM

**Q. 在视觉SLAM前段进行跟踪建图过程中, 一般可分为基于特征点、基于直接法和基于半直接法三种方式。一下属于基于半直接法的视觉SLAM是**

- LSD-SLAM
- SVO
- ORB-SLAM
- PTAM

**ANS:**

----------------------------------------------------------------------------------------------------------------------------------

**Q. 一下哪个SLAM系统中没有回环检测 (小觅智能)**
- ORB-SLAM
- VINS
- LSD
- SVO

**ANS:**

----------------------------------------------------------------------------------------------------------------------------------

**Q. 基础矩阵F、本质矩阵E和单应矩阵H的自由度分别是什么? (小觅智能)**

**ANS:**

----------------------------------------------------------------------------------------------------------------------------------

**Q. 下面没有使用线段特征的为: (小觅智能)**
- LIBVISO2
- PL-SLAM
- PL-VIO
- SVO 2.0

**ANS:**

----------------------------------------------------------------------------------------------------------------------------------

## AR & VR & Autonomous driving

**Q. 下列哪项不是AR的关键技术?** (16 June)
- 人机交互
- 图像识别与追踪
- SLAM
- 显示技术
- 图像分割

**ANS:** E ？(Not Sure)

----------------------------------------------------------------------------------------------------------------------------------

**Q. 关于AR和VR, 一下那些说法是错误的(多选)** (悉见科技)
- 在AR体验中, 用户能看到真实世界; 在VR体验中, 用户看不到真实世界
- 在AR体验中, 用户可以和真实世界发生交互; 在VR体验中, 用户不会和真实世界发生交互
- AR设备的跟踪都是由 inside-out tracking实现的; VR设备的跟踪都是由outside-in tracking 实现的
- AR头显设备可以设计为也支持VR体验; VR头显设备可以设计为也支持AR体验

**ANS:** B & C

- A. 
AR增强现实, 是对用户看到的现实世界进行增强
VR虚拟现实, 是切断用户和真实世界的视线, 完全虚拟出场景让用户体验

- B. 
在VR体验中, 用户可以和现实世界交互。E.g. 在自由行走的VR体验中, 现实世界的障碍物也会被注册在虚拟场景中, 让用户能“看”到障碍物, 避免碰撞

- C. 
AR设备跟踪基本上都是inside-out, 但是现在也有很多VR设备采用了多摄像头和IMU融合(Fusion)的inside-out tracking, 避免了部署灯塔的繁琐

- D. 
有的AR头显, 可以切断外部视线, 实现VR; 有的VR设备, 也可以通过摄像头的方式实现video see-through AR

Reference: 
inside-out tracking https://blog.csdn.net/shenshen211/article/details/79008013
            
outside-in tracking https://xinreality.com/wiki/Outside-in_tracking

----------------------------------------------------------------------------------------------------------------------------------           
**Q. 哪些不是无人驾驶关键技术?** (17 June)
- 环境感知
- 定位与导航
- 类脑智能
- 协同访问

**ANS:** C

----------------------------------------------------------------------------------------------------------------------------------

## Machine learning

**Q. 以下方向中, 相比于传统算法, 深度学习还没有达到state-of-the-art的是:** (13 June)
- 图像去噪音
- 机器翻译
- 语音识别
- 场景分割

**ANS:** A

----------------------------------------------------------------------------------------------------------------------------------

**Q. 自然语言处理(NLP)以下哪项不是NLP领域的研究方向:** (14 June)
- 机器翻译
- 推荐系统
- 问答系统
- 信息提取
- 文本分类

**ANS:** B

----------------------------------------------------------------------------------------------------------------------------------

**Q. 按照学习形式来分, 机器学习可以分为监督学习、无监督学习和强化学习三类。以下算法中不属于监督学习(supervised learning)的是:** (15 June)
- 决策树(Decision Tree)
- 朴素贝叶斯(Naive Bayes Classifier)
- 逻辑回归(Logistic Regression)
- K-means算法

**ANS:** D

K-means是聚类 属于unsupervised learning
Reference: https://zhuanlan.zhihu.com/p/26304729
Note: 朴素贝叶斯基于各特征之间相互独立

----------------------------------------------------------------------------------------------------------------------------------

**Q. 下列哪项不是SVM的优势? (网易)**
- 可以和核函数(kernel function)结合
- 通过调参往往可以得到很好的分类效果
- 训练速度快
- 泛化(Generalization)能力好

**ANS:**


----------------------------------------------------------------------------------------------------------------------------------

## Algorithm & Maths

**有20个人去看电影, 电影票50元。其中只有10个人有50元, 另外10个人都只有一张面值100元的纸币, 电影院没有其他钞票可以找零, 问有多少种找零的方法? (网易)**

**ANS:**

----------------------------------------------------------------------------------------------------------------------------------

## Other applications

**小米的只能音箱属于** (18 June)
- 互联网智能化
- 商业智能化
- 实体世界智能化
- 自主智能化

**ANS:** C

把声音环境数字化, 类似的还有阿里巴巴的"城市大脑"把交通流量数字化, Face++的技术将面孔数字化等等

----------------------------------------------------------------------------------------------------------------------------------


