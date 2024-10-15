---
title: Our paper titled "Dual-Level Curriculum Meta-Learning for Noisy Few-Shot Learning Tasks" is accepted by AAAI 2024
date: 2023-12-29
authors:
  - admin
tags:
  - Meta Learning
  - Curriculum Learning
  - Noisy Labels

---

The dual-level framework proposes a heuristic class sampling criterion that measures pairwise class boundary complexity to form a class curriculum; it uses effective example sampling through an under-trained proxy model to form an example curriculum. 

## Overview

Few-shot learning (FSL) is essential in many practical applications. However, the limited training examples make the models more vulnerable to label noise, which can lead to poor generalization capability. To address this critical challenge, we propose a curriculum meta-learning model that employs a novel dual-level class-example sampling strategy to create a robust curriculum for adaptive task distribution formulation and robust model training. The dual-level framework proposes a heuristic class sampling criterion that measures pairwise class boundary complexity to form a class curriculum; it uses effective example sampling through an under-trained proxy model to form an example curriculum. By utilizing both class-level and example-level information, our approach is more robust to handle limited training data and noisy labels that commonly occur in few-shot learning tasks. The model has efficient convergence behavior, which is verified through rigorous convergence analysis. 

## Motivation

Traditional techniques for incorporating noise in supervised learning involving large amounts of training data may not be applicable in FSL settings due to two main reasons. First, FSL only has access to limited labeled data, which is insufficient to support traditional techniques that require large amounts of training data. Second, FSL methods typically rely on learning from the differences between tasks, instead of directly learning from individual data points. As a result, techniques that depend on individual data points may not be as effective in FSL settings.

To overcome these limitations, we propose a novel dual-level curriculum meta learning (i.e., DCML) model that can generalize at both the class-level and example-level, while also considering noisy labels in both the meta-training and meta-test datasets. It performs dual-level sampling to dynamically form a task curriculum: (i) Class-level sampling continuously samples a subset of classes that are suitable for meta-training at the current stage and the selected classes forms a subject in the overall curriculum; (ii) Example-level sampling further chooses a subset of clean examples from currently chosen classes to construct the support and query sets.

## Methodology

DCML contains two levels: C-CL and E-CL. In C-CL, a class curriculum is progressively built with a series of subjects τ1,...,τC using the CP-metrics µ and σ. Based on the easy-to-complex curriculum learning intuition, ECPs are first fed into the target model using a small initial µ0 th. Then the values of µth,σth are gradually increased so that the similar but difficult SCPs are included to provide fine-grained classification tasks for training. The NCPs are put in the end of the curriculum and trained insufficiently to avoid overfitting. Some are removed depending on the corruption level. In E-CL, a proxy is used to filter out noise in the example-level by sampling small loss examples of each task. This is achieved by assigning proper weights to examples sampled within each task.
