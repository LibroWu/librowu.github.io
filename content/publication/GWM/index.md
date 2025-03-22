---
title: 'Graph World Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tao Feng
  - admin
  - Guanyu Lin
  - Jiaxuan You

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-03-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: World models (WMs) demonstrate strong capabilities in prediction, generation, and planning tasks. Existing WMs primarily focus on unstructured data while cannot leverage the ubiquitous structured data, often represented as graphs, in the digital world. While multiple graph foundation models have been proposed, they focus on graph learning tasks and cannot extend to diverse multi-modal data and interdisciplinary tasks. To address these challenges, we propose the Graph World Model (GWM), a world model that supports both unstructured and graph-structured states with multi-modal information and represents diverse tasks as actions. The core of a GWM is a generic message-passing algorithm to aggregate structured information, either over a unified multi-modal token space by converting multi-modal data into text (GWM-T) or a unified multi-modal embedding space by modality-specific encoders (GWM-E). Notably, GWM introduces action nodes to support diverse tasks, where action nodes are linked to other nodes via direct reference or similarity computation. Extensive experiments on 6 tasks from diverse domains, including multi-modal generation and matching, recommendation, graph prediction, multi-agent, retrieval-augmented generation, and planning and optimization, show that the same GWM outperforms or matches domain-specific baselines' performance, benefits from multi-hop structures, and demonstrate strong zero-shot/few-shot capabilities on unseen new tasks.

# Summary. An optional shortened abstract.
# summary: 

tags: [Graph]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#   projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#   slides: ""
---
