# [kaggle_taitanic](https://www.kaggle.com/competitions/titanic)
入门的第一个kaggle竞赛，第一次做一个完整的项目，还是蛮麻烦的。讲讲大致流程吧
1. 预处理：这里主要是处理nan项和正则化normalize部分数值项
2. 特征工程：个人认为这是这个的项目里面最重要的一部分。把特征做好其实比模型调参要重要，也更困难。毕竟数据质量决定上限。下面给出一些积累到的方法
   2.1. 删除部分无关列，如Cabin对生存关系不大
   2.2. 从已有的信息中增加更多信息，如从Name列中增加Miss，Mrs等信息
   2.3. 只保存某一项feature的有效信息，如只保留ticket项的尾号
