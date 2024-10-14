---
title: GCCIS PhD Colloquium Series

event: GCCIS PhD Colloquium Series

location: SLA 2150
address:
  street: 1 Lomb Memorial Dr
  city: Rochester 
  region: NY
  postcode: '14623'
  country: United States

summary: In this talk, I will present my research paper on noisy few-shot learning (NFSL). As a typical learning to learning with noisy label method, data cleansing failed in few-shot learning (FSL) due to the scarcity of training data. It exacerbates information loss in FSL due to limited training data, resulting in inadequate model training. To best recover the underlying task manifold corrupted by the noisy labels, we resort to learning from uniquely designed unsupervised auxiliary tasks to compensate for information loss. Using unsupervised tasks can effectively avoid additional annotation costs and minimize the risk of introducing additional label noises. However, a randomly constructed unsupervised task may misguide the model to learn sample-specific features that are likely to compromise the primary few-shot learning task due to the noisy weak learning signals. We propose to conduct novel auxiliary task selection to ensure the intra-diversity among the unlabeled samples within a task. Domain invariant features are then learned from carefully constructed auxiliary tasks to best recover the original data manifold.
abstract: In this talk, I will present my research paper on noisy few-shot learning (NFSL). As a typical learning to learning with noisy label method, data cleansing failed in few-shot learning (FSL) due to the scarcity of training data. It exacerbates information loss in FSL due to limited training data, resulting in inadequate model training. To best recover the underlying task manifold corrupted by the noisy labels, we resort to learning from uniquely designed unsupervised auxiliary tasks to compensate for information loss. Using unsupervised tasks can effectively avoid additional annotation costs and minimize the risk of introducing additional label noises. However, a randomly constructed unsupervised task may misguide the model to learn sample-specific features that are likely to compromise the primary few-shot learning task due to the noisy weak learning signals. We propose to conduct novel auxiliary task selection to ensure the intra-diversity among the unlabeled samples within a task. Domain invariant features are then learned from carefully constructed auxiliary tasks to best recover the original data manifold. 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-10-11T11:00:00Z'
date_end: '2024-10-11T12:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com'
url_pdf: ''
url_slides: 'https://slideshare.net'
url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
