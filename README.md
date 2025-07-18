# BUAA Data Science 2025

> Topic: Predicting Student Dropout Risk in Higher Education
>
> 本项目聚焦高等教育中学生辍学风险的预测，基于葡萄牙某高职院校的学生数据，使用多种机器学习模型挖掘影响因素，并建立可解释的预测框架。

## 简介

学生辍学问题长期影响教育公平与资源效率。我们利用教育数据挖掘（EDM）技术，围绕“辍学 / 在读 / 毕业”三种状态构建多分类模型，进一步将任务简化为“辍学 vs 未辍学”的二分类问题，显著提升模型性能，辅助识别高风险学生并提出干预建议。

- 数据来源：Kaggle 数据集 [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention/data)
- 样本数：4424 名学生
- 特征维度：
  - **学业成绩类**：平均成绩、已修课程数、课程通过数等
  - **经济与背景类**：学费缴纳情况、年龄、专业、家庭背景等
- 目标变量：学生最终状态（Dropout / Enrolled / Graduate）

## 运行方法

只需运行 `jupyter notebook` 即可，逐块执行。

