---
layout: post
section-type: post
category: project
date: 2016-01-10T00:00:00Z
tagline: Genetic Basis of Glioblastoma 
tags:
- machine learning
- biomedical informatics
- Bayesian networks
- structure learning 
title: Identifying a Genetic Basis for Cellularity in Glioblastoma Patients 
---

Abstract:
Certain cancers have exceedingly high mortality rates and lack of treatment. Glioblastoma is the most aggressive brain cancer, has no clear prevention or treatment plan, and its causes are thoroughly unclear. These characteristics contribute to a 90 day median survival rate without treatment and a 95-97% mortality rate within 5 years of diagnosis. To try to identify a genetic basis for Glioblastoma, we developed a methodology to predict cellularity, the relative proportion of tumor cells, in Glioblastoma patients using a large range of molecular data. We obtained gene expression and isoform-level data from TCGA as features. These 20,000 plus features were used to learn an ensemble of Bayesian networks used as priors using the max-min hill climbing structure-learning algorithm. Using Bayesian model averaging and traditional hill-climbing, another ensemble of Bayesian networks was learned using the previous ensemble as a strong structural prior. The final models help support the fact that the causes of Glioblastoma are unclear as well as the fact that trying to predict cellularity from a genetic perspective is futile. The accuracy of these models are not significantly better than predicting the mean or median cellularity seen across a group of patients for each and every patient.


