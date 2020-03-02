## Client's Default Prediction Model Construction on Lending Club Public data

**目标**

本项目主要目的是构建一个精准的用户违约模型，数据主要采用Lending Club公开数据集。在此我们主要是采用机器学习的方法。

**方法**

1. 特征工程，包括数据数据清洗和特征选择，本项目中主要剔除不相关的变量。除此之外我们首先进行EDA对剩下的变量进行分析以保证变量可解释性。之后在再对这些变量进行相关性性分析进一步剔除变量。最后补全缺失值
2. 使用机器学习方法XGBoost和其他模型进行训练，并且调参。

**结果**

XGBoost模型AUC值为0.7，略高于其他模型



