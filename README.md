# Machine-Learning-Project-Predicting-House-Prices
机器学习项目：研究美国爱荷华州艾姆斯市2006年至2010年的住房数据，来建立预测模型
方法：
  I.通过特征工程来
    a.去除缺失值超过5%的特征
    b.去除有缺失值的非数值特征
    c.其他有缺失值的数值列填充众数
    d.转换时间列
    e.去除明显无关特征
  II.通过特征选择来
    a.去除和目标相关系数小于0.4的特征
    b.去除共线性特征（通过heatmap图）
    c.去除低方差/变化（小于0.015）特征
    d.类型类特征的虚拟化（dummy code,去除分类超过10的特征）
  III.通过scikit-learn线性回归模型来训练和预测
  IV.通过KFolds方法来检验证Mean Squared Error
    
    
