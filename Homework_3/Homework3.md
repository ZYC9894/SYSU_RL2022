<center><H1>Homework 3</H1><center>



## Task MPE（Multi-agent Particle Environment）

<strong>(coding)</strong>在`MPE`的`simple spread`环境中实现MADDPG、VDN、QMIX三个算法，对于三个算法有如下要求：

1. 所有算法均采用参数共享。
2. 不能修改原始环境的任何文件。不能修改环境返回的奖励值。QMIX需要全局状态，可通过对obs的理解自行定义。
3. 奖励值最终至少收敛到-5.5。
4. MADDPG、VDN与环境交互的episode数量不超过50000，QMIX与环境交互的次数不做限制。
4. 详细分析不同全局状态对QMIX算法性能的影响，类似于多智能体课件中MAPPO对全局状态的分析一样。

## Submission

作业提交内容：需提交一个zip文件，包括代码以及实验报告PDF。实验报告需要给出每题的reward曲线图以及使用的算法介绍。如果不同的题有不同的超参数，请在代码或者实验报告中说明。

zip文件命名格式: RL_20220421\_张三\_homework3；如果需提交不同版本，则命名格式：RL_20220421\_张三\_homework3_v2等。

作业提交方式：zhangyc8@mail2.sysu.edu.cn

MPE环境：https://github.com/openai/multiagent-particle-envs

**作业提交截止日期：2022年07月12日** 

