---
title: Supports estimation via graph sampling

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xin Wang
- Jun-Hao Shi
- Jie-Jun Zou
- Ling-Zhen Shen
- Zhuo Lan
- Yu Fang
- Wen-Bo Xie

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-04-13T08:39:24.747427Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Expert Systems with Applications*'
publication_short: ''

doi: https://doi.org/10.1016/j.eswa.2023.122554

abstract: Frequent pattern mining (FPM), whose goal is to identify patterns with appearance
  frequencies above a specified support threshold on a large graph, has attracted
  increasing attention owing to its diverse applications. The task suffers from an
  issue of support setting, as an inappropriate support threshold may lead to either
  extremely high computational cost along with a huge pattern set or very few patterns
  caused by excessive pruning. Thus, supports estimation is crucial for FPM, since
  an appropriate support threshold enables users to discover a limited number of patterns
  within affordable computational resources. In light of this, we investigate the
  problem of supports estimation under the constraint of pattern number B and propose
  a comprehensive approach to the issue. Our approach leverages a neural network to
  predict the support θB that corresponds to the B-th pattern on a graph G. To train
  the prediction model, we first present a sampling algorithm that leverages typical
  motifs to produce sampled graphs of G under different sampling ratios. Owing to
  the typical structures brought about by motifs, the sampled graphs are embedded
  supports of the top-ranked patterns in proportion to the sampling ratios. We next
  develop techniques to efficiently infer the support θB of the B-th pattern on each
  sampled graph and introduce a method to encode (sampled) graphs with θB and other
  typical features, thereby forming the training data. Extensive experimental studies
  on real-life and synthetic graphs demonstrate the superiority of our approach, compared
  to other baselines.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Supports estimation
- Graph sampling
- Frequent pattern mining
- Motifs

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# links:
# - name: URL
#   url: https://www.sciencedirect.com/science/article/pii/S0957417423030567
---

