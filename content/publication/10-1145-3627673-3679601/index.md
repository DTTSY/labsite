---
title: 'ACDM: An Effective and Scalable Active Clustering with Pairwise Constraint'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xun Fu
- Wen-Bo Xie
- Bin Chen
- Tao Deng
- Tian Zou
- Xin Wang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-04-13T07:19:58.172523Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 33rd ACM International Conference on Information
  and Knowledge Management*'
publication_short: ''

doi: 10.1145/3627673.3679601

abstract: 'Clustering is fundamentally a subjective task: a single dataset can be
  validly clustered in various ways, and without further information, clustering systems
  cannot determine the appropriate clustering to perform. This underscores the importance
  of integrating constraints into clustering, enabling users to convey their preferences
  to the system. Active constraint-based clustering approaches prioritize the identification
  of the most valuable constraints to inquire about, striving to achieve effective
  clustering with the minimal number of constraints needed. We propose an  <u>A</u>
  ctive  <u>C</u> lustering with  <u>D</u> iffusion  <u>M</u> odel (ACDM). ACDM applies
  the nearest-neighbor technique to construct a diffusion graph, and utilizes an online
  framework to refine the clustering result iteratively. In each iteration, (a) nodes
  with high uncertainty and representativeness are selected in batch mode, (b) then
  a novel neighborhood-set-based query is used for categorizing the selected nodes,
  using pairwise constraints, and (c) the categorized nodes are used as source nodes
  in the diffusion model for cluster refinement. We experimentally demonstrate that
  ACDM outperforms state-of-the-art methods in terms of clustering quality and scalability.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- active clustering
- knowledge management
- pairwise constraints
- scalable clustering
- semi-supervised clustering

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'https://github.com/Traveler-fx/ACDM'
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
#   url: https://doi.org/10.1145/3627673.3679601
---

