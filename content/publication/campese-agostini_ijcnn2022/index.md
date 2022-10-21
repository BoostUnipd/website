---
title: 'Beyond Transformers: fault type detection in maintenance tickets with Kernel Methods, Boost Decision Trees and Neural Networks'
authors:
  - campese-stefano
  - agostini-federico
  - pazzini-jacopo
  - Davide Pozza
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2022-09-30'
doi: '10.1109/IJCNN55064.2022.9892980'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-21'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 International Joint Conference on Neural Networks (IJCNN)*
publication_short: 

abstract: >
  The proper handling of customer tickets and main-tenance requests is pivotal for enterprises as it directly impacts customer satisfaction. The ability to rapidly and efficiently react and solve reported issues is in fact a key factor from the customers' perspective, resulting in positive feedback for the company, leading to higher economic and brand-image revenues. The automatic detection of failures from maintenance tickets and support requests can grant faster and more efficient reactions to customers' equipment failures as well as reduced maintenance costs. The analysis of support and maintenance requests is a well-known problem in Natural Language Processing (NLP). State-of-the-art solutions in this field rely on Transformers models, pre-trained on large text corpora, and then fine-tuned on the specific downstream task. However, due to their intrinsic nature, support requests are highly domain-specific and usually similar to short telegraph messages, where the focus is typically encapsulated in short sequences rather than in long dependencies. Hence, ad-hoc methods for pattern recognition might provide comparable performances with respect to Transformers. In this work, two alternative approaches are proposed, based on: Kernel Meth-ods in conjunction with Boost Decision Trees (SpectrumBoost), and Neural Networks for Multiple Representation Learning (DeepMRL). These models have been tested and compared against state-of-the-art models on a real-world set of 131305 maintenance tickets in the Italian language, suggesting that the proposed models outperform Transformers both in the prediction accuracy and in the time and computational resources required for their training.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Kernel Methods
  - Neural Networks
  - NLP
  - Industry
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9892980
url_code:
url_dataset:
url_poster: IJCNN_poster.pdf
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption:
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

