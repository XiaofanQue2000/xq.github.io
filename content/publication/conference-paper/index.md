---
title: 'Optimal Transport of Diverse Unsupervised Tasks for Robust Learning from Noisy Few-Shot Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Qi Yu

# Author notes (optional)


date: '2024-09-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In European Conference on Computer Vision 2024
publication_short: In *ECCV*

abstract: Noisy few-shot learning (NFSL) presents novel challenges primarily due to the interplay between noisy labels and limited training data. While data cleansing offers a viable solution to address noisy labels in the general learning settings, it exacerbates information loss in FSL due to limited training data, resulting in inadequate model training. To best recover the underlying task manifold corrupted by the noisy labels, we resort to learning from uniquely designed  unsupervised auxiliary tasks to compensate for information loss. Using unsupervised tasks can effectively avoid additional annotation costs and minimize the risk of introducing additional label noises. However, a randomly constructed unsupervised task may misguide the model to learn sample-specific features that are likely to compromise the primary few-shot learning task due to the noisy weak learning signals. We propose to conduct novel auxiliary task selection to ensure the intra-diversity among the unlabeled samples within a task. Domain invariant features are then learned from carefully constructed auxiliary tasks to best recover the original data manifold. We conduct a theoretical analysis to derive novel generalization bounds for learning with auxiliary tasks. Extensive experiments are conducted to demonstrate that our method outperforms existing noisy few-shot learning methods under various in-domain and cross-domain few-shot classification benchmarks. 

# Summary. An optional shortened abstract.
summary: We propose a novel FSL framework with auxiliary tasks that utilize carefully selected unlabeled data under noisy settings.

tags:
  - Noisy Few-shot Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05600.pdf
url_code: https://github.com/ritmininglab/DUNT/tree/main
url_poster: ''
url_project: https://eccv2024.ecva.net/virtual/2024/poster/1929
url_slides: ''
url_video: https://www.youtube.com/watch?v=74MyPegy_is&t=5s

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
