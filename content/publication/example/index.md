---
title: 'Classification of autism spectrum disorder'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jianxing Wang
  - Yi Pan

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2019-02-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*
publication_short: In *NC*

abstract: Autism spectrum disorder (ASD) is a common neurodevelopmental disorder that seriously affects communication and sociality of patients. It is crucial to accurately identify patients with ASD from typical controls (TC). Conventional methods for the classification of ASD/TC mainly extract morphological features independently at different regions of interest (ROIs), rarely considering the connectivity between these ROIs. In this study, we construct an individual brain network as feature representation, and use a deep neural network (DNN) classifier to perform ASD/TC classification. Firstly, we construct an individual brain network for each subject, and extract connectivity features between each pair of ROIs. Secondly, the connectivity features are ranked in descending order using F-score, and the top ranked features are selected. Finally, the selected 3000 top features are used to perform ASD/TC classification via a DNN classifier. An evaluation of the proposed method has been conducted with T1-weighted MRI images from the Autism Brain Imaging Data Exchange I (ABIDE I) by using ten-fold cross validation. Experimental results show that our proposed method can achieve the accuracy of 90.39% and the area under receiver operating characteristic curve (AUC) of 0.9738 for ASD/TC classification. Comparison of experimental results illustrates that our proposed method outperforms some state-of-the-art methods in ASD/TC classification.

# Summary. An optional shortened abstract.
summary: We construct an individual brain network as feature representation, and use a deep neural network (DNN) classifier to perform ASD/TC classification.

tags: []

# Display this page in the Featured widget?
featured: true

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
