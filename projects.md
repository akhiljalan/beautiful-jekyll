---
layout: page
title: Projects
subtitle: 
---

# Machine Learning for Counterterrorism

<div style="text-align:center" markdown="1">

![Alt Text](img/project-pictures/all_groups_heatmap.png)

</div>

Team: Akhil Jalan, Yakub Akhmerov, Paul Kim

Link: See the [Github repo](https://github.com/berkeley-stat159-f17/project-3-p2-ak-ja-zh/blob/master/main.ipynb)

In this project, my team and I sought to build a classifier to predict the success or failure of a terrorist attack. In addition to building three different classifiers (random forests, neural networks, and LASSO regression), we created map GPS visualizations (credit to Yakub) and heatmaps to roughly quantify similarity of terrorist networks, attack types, and region. 

This was my captsone project for a class in Fall 2017 (Statistics 159).

# Analysis of State of the Union Speeches

<div style="text-align:center" markdown="1">

![Alt Text](img/project-pictures/mds_naive.png)

</div>

Team: Akhil Jalan, Yakub Akhmerov, Ken Zhong 

In this project, my team created a bag-of-words model and K-nearest-neighbors to analyze Presidential state of the union speeches. After forming all of the stemmed words across speeches as a "dictionary", each President was modeled as a vector whose entries were the number of times some word was used. 

In addition to creating a visualization of this high-dimensional vector space using multidimensional scaling to project to 2 dimensions (credit to Yakub), built a K-nearest-neighbors classifier whose training set was some subset of all presidential speeches, and test set was other speeches. While this approach was fairly naive, we got an accuracy of 76% with $k = 1$. 