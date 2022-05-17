---
title: 'DWT-CV: Dense weight transfer-based cross validation strategy for model selection in biomedical data analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jianhong Cheng
  - Hulin Kuang
  - Qichang Zhao
  - Yahui Wang
  - Lei Xu
  - Jin Liu
  - Jianxin Wang

# Author notes (optional)
author_notes:
  - 'First'


date: '2022-05-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-04-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Future Generation Computer Systems*
publication_short: In *FGCS*

abstract: Model selection for deep learning algorithms is an extremely important step in the process of extracting knowledge from limited data, especially in biomedical data. The common approach is to adopt cross-validation techniques to randomly divide a small subset of the training set as the validation data for parameter tuning and model selection. However, this method may choose a sub-optimal model due to insufficient data utilization, and the process, such as -fold cross-validation, is cumbersome and time-consuming. In this study, we propose a dense weight transfer-based cross validation (DWT-CV) strategy for biomedical data analysis and use this strategy to improve the generalization of deep learning algorithms with reduced training time using weight transfer learning. DWT-CV utilizes a dense weight aggregation and weight transfer mechanism to make the model more general and converge faster during the cross validation. The effectiveness of the proposed strategy is evaluated on multiple experiments with three different domains including biomedical image classification, drug–target affinity prediction, and medical image segmentation. Extensive experimental results demonstrate that our proposed DWT-CV strategy can make several deep learning benchmark methods perform better on multiple biomedical datasets, which implies that it may be an alternative to the traditional cross validation criterion for model selection.

# Summary. An optional shortened abstract.
summary: We propose a dense weight transfer-based cross validation (DWT-CV) strategy for biomedical data analysis and use this strategy to improve the generalization of deep learning algorithms with reduced training time using weight transfer learning.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.s
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
