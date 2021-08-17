---
title: 墨尔本大学 COMP90049 IML Introduction to machine learning 机器学习导论
date: 2021-07-25 22:28:41
categories: 
- 墨尔本大学 Master of IT
tags: 
- 机器学习
- 算法
---

## 2021 SM1 结课后总结 1

这门课是墨尔本大学 Master of IT， AI方向必修课，价值12.5学分。难度适中，但是期末考试题量很大，博主只做了60%的题。导师Lea，德意志血统，平常很温柔，出题要弄死人。

### 课程分数设置

- 两个简单的编程项目- 30%

  1. 实现knn，此底层开始写，距离公式也要写4个

     1. zoo数据集：https://archive.ics.uci.edu/ml/datasets/Zoo

  2. 朴素贝叶斯

     1. adult数据集：https://archive.ics.uci.edu/ml/machine-learning-databases/adult

     2. 特征相关性分析： PMI

     3. 对收入分类

        

- 一个要写报告的kaggle 比赛，带有research性质-30%
  - kaggle地址：https://www.kaggle.com/c/comp90049-2021-sem1
  - 分类问题，根据twitter内容判断用户地理位置

- 期末考试-40%

  - 题量真的大
  - 需要手动计算各种算法，要训练自己按计算器的速度

### 课程内容

1. 基本概念

   1. 老生常谈的问题

      1. what is machine learning
      2. Why is it important? Some use cases.
      3. What can go wrong?
         1. ethics e.g.
            1. bias on woman
            2. learn racist and sexist data
         2. transparency
            1. Attributes in the data can encode information in an indirect way
               1. home address -> social standing

   2. 特征数据的类型

      1. Nominal

         所谓的categories特征

         1. nominal 转 数字

            1. map category to numbers

               red:0 , blue:1, green:2, yellow:3

               这种方法的缺陷是数字的顺序是按照人为定义的，会让一些特征对应的数字比其他特征小很多

            2. One-hot 独热编码

               “red” = [1, 0, 0, 0] 

               “blue” = [0, 1, 0, 0] 

               “green” = [0, 0, 1, 0] 

               “yellow” = [0, 0, 0, 1]

               解决上面的问题，但是维度会爆炸

      2. Ordinal

         这个类似于nominal 但是有着明显顺序。

         比如 温度特征有 低 中 高

      3. Numerical

         1. Distcretization离散化

            把数据分层分成categories， 比如可以把年纪分成老中幼

            1. equal width
            2. equal frequency
            3. 聚类

   3. 特征Normalization and scaling

      建议看看sklearn scaler的文档

2. knn

   老生常谈 没啥好讲的。注意这门课讲到的inverse distance

3. 概率论

   基础的基础，为了朴素贝叶斯做铺垫，以后再更新 

4. 优化

   

5. 朴素贝叶斯

6. 特征选择

7. 迭代优化

8. 逻辑回归

9. 感知机

10. 神经网络

11. 反向传播

12. 模型评估

13. 决策树

14. 集成学习

15. 无监督学习

16. 半监督学习

17. 异常检测

18. 机器学习公平性

