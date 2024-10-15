---
title: 🎉 Our paper titled "Optimal Transport of Diverse Unsupervised Tasks for Robust Learning from Noisy Few-Shot Data" is accepted by ECCV 2024!
summary: To best recover the underlying task manifold corrupted by the noisy labels, we resort to learning from uniquely designed unsupervised auxiliary tasks to compensate for information loss.
date: 2024-07-03

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

authors:
  - admin

tags:
  - Noisy Few-shot Learning
  - Optimal Transport
  - Diverse Unsupervised Tasks
---


## Overview

Noisy few-shot learning (NFSL) presents novel challenges primarily due to the interplay between noisy labels and limited training data. To best recover the underlying task manifold corrupted by the noisy labels, we resort to learning from uniquely designed unsupervised auxiliary tasks to compensate for information loss. 

## Motivation

While training robust models from noisy data has been intensively investigated in standard settings, learning from noisy few-shot data is only sparsely explored in existing literature. Noisy few-shot learning (NFSL) presents novel challenges primarily due to the interplay between noisy labels and limited training data. Within each training task, FSL operates with few training samples per class, making each data point highly valuable. Hence, the model tends to be more sensitive to variations in the training data and noisy labels can more easily cause the model to learn incorrect patterns, compromising its ability to accurately generalize to new tasks. Furthermore, identifying and rectifying label noises also becomes more challenging. The scarcity of data makes it harder to distinguish between true class characteristics and erroneous annotations.

## Methodology

The DUNT framework (see Fig. 2) is composed of a shared feature extractor, the task classifier for task i and the domain critic. The feature extractor takes input from both the primary tasks and the auxiliary tasks; the classifiers predict the labels for the input and the critic predict the source of the input. The gradient reversal layer (GRL) ensures that the feature distributions over the two domains are made similar.

