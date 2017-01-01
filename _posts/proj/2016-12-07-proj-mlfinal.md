---
layout: post
title: CS5785 Machine Learning Final Project
category: projects
---

The [final of CS5785-Machine Learning](https://inclass.kaggle.com/c/cornell-cs5785-2016-fall-final/) required us to build a large-scale image search engine.

<!--more-->

**TL;DR**: We ranked the first place in the Kaggle competition.

In the project, we addressed the task of cross-modal retrieval problem specifying in using natural language query to retrieve related images. We utilized image features extracted by state-of-the-art deep learning techniques and combined them with natural language processing methods. We employed SVMs to map query vectors to object tag space, PLS regressions to find a common sub-space for query vectors and image features„ and proposed an ensemble meta algorithm to blend our models. Experimental results demonstrated that our proposed approach effectively utilized cross-modal information and explored their underlying relation, outperforming all other teams on Kaggle competition.

Here is one figure from our paper.

![](/images/proj-aml.png)

