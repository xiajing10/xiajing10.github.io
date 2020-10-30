---
title: Interview Notes
categories:
  - career
tags: job hunting, interview
published: true
---

# Interview Notes

Tips: 中文为国内职位，英文为在瑞典职位。
不定时更新。

## 华为 （NLP算法工程师）

一面 2020.10.22 远程 约1h

**PART ONE** (ca. 30min)  
自我介绍
聊做过的项目和细节
- 跨语言模型迁移学习：
怎么实现，词向量来源（预训练），怎么做到在一个语义空间里（Alignment）
- 关键词抽取（论文项目）：怎么实现，抓取候选词的具体细节(!)，为什么只参考标题和摘要

其他：
有无做过非词向量的NLP项目
有无接触过实际产品线

**PART TWO**  (ca. 30min)  
现场写代码 - 最短路径 （可用任何方法，自定义输入图的结构）

备注：  
HW消费者云服务部 - 搜索推荐系统和NLP基础任务（分词，词性标注，关键词抽取等）

**待提升点**
1. 回答项目时顺序： 背景-目的-方法
突出使用该方法的原因（研究新方法，希望自动化处理，适用于文献类文章，主题模型不熟/非研究方向）
若需要，可提及其他工业界的做法思路及比较
2.  复习时注重课上学过的算法 （搜索排序，图-最短路径，编辑距离-动态规划，面向对象编程）

**需补充知识点**
1. 词向量对齐（Alignment）
2. 基于传统特征建模（非词向量）的NLP任务实现

二面 2020.10.28 远程 1h10min

**PART ONE**  
自我介绍  
**PART TWO**   
现场代码: [最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/)   
注意区分： 最长公共子串 （子串字符必须连续，子序列可不连续）  
例： `abcde`, `adjabce` 最长公共子串 `abc`, 最长公共子序列 `abce`
**PART THREE**
为什么转行  
聊做过的项目（基本同一面）  
对NLP近几年的最新技术有没有什么了解  
情景问题：query的意图识别怎么做，怎么找特征


## 科大讯飞 
Notes: 春招末尾，两面都没有写代码，无笔试

一面 2020.04 
聊项目相关
- 机器翻译的课程项目，目的，技术，有什么发现
技术相关
- 命令行实现查看文档字数，读取文档内容
- 如果文档过大（一次读入会占满内存）应该怎么读
- python里加入测试的方法（`assert`）

二面 2020.04
聊项目相关
- 毕业论文(当时正在做):讲项目思路从大到小，不涉及具体技术（除非面试官后来问到）  

技术相关
- BERT 原理
- 熵是什么，公式
- 决策树原理是什么

（这是第一次面国内的技术岗，很懵，也不知道该怎么说项目，很多技术概念也没有准备，而且当时因为忙论文的事比较焦虑。感激这次的面试官教了很多。）

----

## Volvo Cars - Data Scientist (ca. 3h)

**PART ONE**
Casual Talk
Introduction of current team and future aims

**PART TWO**  
Self introduction + my thesis project  
Q: why not topic modelling  
Q: how to encode words   
Q: why just abstract and title  

**PART THREE**  
A case:  
The manager wants to test whether the amount of visitor on a website increase after a typical change.

A/B testing

think about:  
- the type of data
- how would you do initial analysis and in which dimension
- how to test the number increase or not (simulate data distribution, significant test, confidence interval, etc.)

**PART FOUR**  
Very detailed discussion about `Data Challenge`

**Improvements in the future**


**Knowledge**
1.  Process and concepts of prediction task (Time series analysis model, machine learning model, etc.)
2.  Boxplot

------------




