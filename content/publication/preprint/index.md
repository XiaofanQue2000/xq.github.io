---
title: Dual-Level Curriculum Meta-Learning for Noisy Few-Shot Learning Tasks
authors:
- admin
- Qi Yu
date: "2024-02-27T00:00:00Z"
doi: https://doi.org/10.1609/aaai.v38i13.29392

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the AAAI Conference on Artificial Intelligence"
publication_short: In "AAAI 2024"



abstract: Few-shot learning (FSL) is essential in many practical applications. However, the limited training examples make the models more vulnerable to label noise, which can lead to poor generalization capability. To address this critical challenge, we propose a curriculum meta-learning model that employs a novel dual-level class-example sampling strategy to create a robust curriculum for adaptive task distribution formulation and robust model training. The dual-level framework proposes a heuristic class sampling criterion that measures pairwise class boundary complexity to form a class curriculum; it uses effective example sampling through an under-trained proxy model to form an example curriculum. By utilizing both class-level and example-level information, our approach is more robust to handle limited training data and noisy labels that commonly occur in few-shot learning tasks. The model has efficient convergence behavior, which is verified through rigorous convergence analysis. Additionally, we establish a novel error bound through a hierarchical PAC-Bayesian analysis for curriculum meta-learning under noise. We conduct extensive experiments that demonstrate the effectiveness of our framework in outperforming existing noisy few-shot learning methods under various few-shot classification benchmarks. Our code is available at https://github.com/ritmininglab/DCML.

# Summary. An optional shortened abstract.
summary: We propose a curriculum meta-learning model that employs a novel dual-level class-example sampling strategy to create a robust curriculum for adaptive task distribution formulation and robust model training.

tags:
- Curriculum Learning

featured: true

links:
url_pdf: https://ojs.aaai.org/index.php/AAAI/article/view/29392
url_code: https://github.com/ritmininglab/DCML


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---



