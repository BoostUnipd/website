---
title: 'Machine Learning Pipelines with Modern Big Data Tools for High Energy Physics'
authors:
  - Migliorini-Matteo
  - Canali-Luca
  - Castellotti-Riccardo
  - Zanetti-Marco
 author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: '2020-06-15'
doi: '10.1007/s41781-020-00040-0'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-06-15'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Computing and Software for Big Science*
publication_short: 

abstract: >
The effective utilization at scale of complex machine learning (ML)
techniques for HEP use cases poses several technological challenges,
most importantly on the actual implementation of dedicated end-to-end
data pipelines. A solution to these challenges is presented, which
allows training neural network classifiers using solutions from the
Big Data and data science ecosystems, integrated with tools, software,
and platforms common in the HEP environment. In particular, Apache
Spark is exploited for data preparation and feature engineering,
running the corresponding (Python) code interactively on Jupyter
notebooks. Key integrations and libraries that make Spark capable of
ingesting data stored using ROOT format and accessed via the XRootD
protocol, are described and discussed. Training of the neural network
models, defined using the Keras API, is performed in a distributed
fashion on Spark clusters by using BigDL with Analytics Zoo and also
by using TensorFlow, notably for distributed training on CPU and GPU
resources. The implementation and the results of the distributed
training are described in detail in this work.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Machine Learning
  - Data Processing
  - High Energy Physics
featured: false

#links:
#  - name: Custom Link
#    url: http://example.org
url_pdf: https://link.springer.com/article/10.1007/s41781-020-00040-0
url_code:
url_dataset:
url_poster: 
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

