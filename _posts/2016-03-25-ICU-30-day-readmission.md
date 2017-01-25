---
layout: post
section-type: post
category: project
date: 2016-03-25T00:00:00Z
tagline: ICU 30-day readmission 
tags:
- machine learning
- subgraph augmented non-negative matrix factorization 
- 30-day readmission rate 
title: ICU 30-day Readmission Prediction 
---

Abstract:
The Intensive Care Unit (ICU) has the highest mortality rates of any hospital wing with approximately 500,000 deaths annually in the United States. The patient population is extremely ill and undergo many interventions at one time, making the population very vulnerable to adverse outcomes. Readmission rate, specifically 30-day readmission rate, can help to identify actionable items that can improve patient care drastically. In this paper, we predict 30-day readmission rate at the ICU level for 1276 patients using the MIMIC-II dataset. For prediction, we first used Subgraph Augmented Non-Negative Matrix Factorization (SANMF), an unsupervised feature learning method, which discovers groups of subgraph-encoded temporal progression trends. We used logistic regression with and without regularization for the classification portion of the task. To combat over-fitting stratified cross-validation with both 3 and 5 folds was used. Our results show an AUC of around 0.55. Thus, it seems very difficult to predict 30-day readmission rates using physiological time series measurements. This leads us to believe that both the causes of readmission are highly variable and general ICU cases have little similarity.

