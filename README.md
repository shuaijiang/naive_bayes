朴素贝叶斯（naive_bayes）
===========
#作者信息（Author）
- Author：shuaijiang
- Email： zhaoshuaijiang8@gmail.com
- Homepage： [http://shuaijiang.github.io](http://shuaijiang.github.io "http://shuaijiang.github.io")
- date: 20141031

#基本思路
朴素贝叶斯法是基于贝叶斯定理与特征条件独立假设的分类方法。其基本的思路是：对于给定的训练数据集，首先基于特征条件独立假设学习输入和输出的联合概率分布，然后基于该模型，对于给定的输入x，利用贝叶斯定理求出后验概率最大的输出y。

#方法特点
朴素贝叶斯法实现简单，学习和预测的效率都很高，是一种比较常用的方法。