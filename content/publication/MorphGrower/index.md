---
title: 'Mitigating Misleading Chain-of-Thought Reasoning with Selective Filtering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nianzu Yang
  - Kaipeng Zeng
  - Haotian Lu
  - admin
  -  Zexin Yuan
  -  Danni Chen
  -  Shengdian Jiang
  -  Jiaxiang Wu
  -  Yimin Wang
  -  Junchi Yan
  

# Author notes (optional)
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-05-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The Proceedings of the 41st International Conference on Machine Learning*
publication_short: In *ICML'24*

abstract: Neuronal morphology is essential for studying brain functioning and understanding neurodegenerative disorders. As acquiring real-world morphology data is expensive, computational approaches for morphology generation have been studied. Traditional methods heavily rely on expert-set rules and parameter tuning, making it difficult to generalize across different types of morphologies. Recently, MorphVAE was introduced as the sole learning-based method, but its generated morphologies lack plausibility, i.e., they do not appear realistic enough and most of the generated samples are topologically invalid. To fill this gap, this paper proposes **MorphGrower**, which mimicks the neuron natural growth mechanism for generation. Specifically, MorphGrower generates morphologies layer by layer, with each subsequent layer conditioned on the previously generated structure. During each layer generation, MorphGrower utilizes a pair of sibling branches as the basic generation block and generates branch pairs synchronously. This approach ensures topological validity and allows for fine-grained generation, thereby enhancing the realism of the final generated morphologies. Results on four real-world datasets demonstrate that MorphGrower outperforms MorphVAE by a notable margin. Importantly, the electrophysiological response simulation demonstrates the plausibility of our generated samples from a neuroscience perspective. Our code is available at https://github.com/Thinklab-SJTU/MorphGrower.

# Summary. An optional shortened abstract.
# summary: 

tags: [Neuronal Morphology, Data Augmentation, Machine Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2401.09500'
url_code: 'https://github.com/Thinklab-SJTU/MorphGrower'
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
