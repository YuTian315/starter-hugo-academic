---
title: 'MLDRL: Multi-loss disentangled representation learning for predicting esophageal cancer response to neoadjuvant chemoradiotherapy using longitudinal CT images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hailin Yue
  - Jin Liu
  - Junjian Li
  - Hulin Kuang
  - HarrisonBai
  - Jianxin Wang

# Author notes (optional)
author_notes:
  - 'First'


date: '2022-05-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-12T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Medical Image Analysis*
publication_short: In *MIA*

abstract:Accurate prediction of pathological complete response (pCR) after neoadjuvant chemoradiotherapy (nCRT) is essential for clinical precision treatment. However, the existing methods of predicting pCR in esophageal cancer are based on the single stage data, which limits the performance of these methods. Effective fusion of the longitudinal data has the potential to improve the performance of pCR prediction, thanks to the combination of complementary information. In this study, we propose a new multi-loss disentangled representation learning (MLDRL) to realize the effective fusion of complementary information in the longitudinal data. Specifically, we first disentangle the latent variables of features in each stage into inherent and variational components. Then, we define a multi-loss function to ensure the effectiveness and structure of disentanglement, which consists of a cross-cycle reconstruction loss, an inherent-variational loss and a supervised classification loss. Finally, an adaptive gradient normalization algorithm is applied to balance the training of multiple loss terms by dynamically tuning the gradient magnitudes. Due to the cooperation of the multi-loss function and the adaptive gradient normalization algorithm, MLDRL effectively restrains the potential interference and achieves effective information fusion. The proposed method is evaluated on multi-center datasets, and the experimental results show that our method not only outperforms several state-of-art methods in pCR prediction, but also achieves better performance in the prognostic analysis of multi-center unlabeled datasets.

# Summary. An optional shortened abstract.
summary:  we propose a new multi-loss disentangled representation learning (MLDRL) to realize the effective fusion of complementary information in the longitudinal data.

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
