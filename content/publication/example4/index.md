---
title: 'MTFIL-Net: automated Alzheimer’s disease detection and MMSE score prediction based on feature interactive learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jin Liu
- Xu Tian
- Jianxin Wang
- Rui Guo
- Hulin Kuang

# Author notes (optional)
author_notes:
  - 'First'


date: '2021-12-9T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-9T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*
publication_short: In *BIBM*

abstract: Automatic detection of Alzheimer’s disease (AD) is conducive to intervention in the disease progression. MMSE score prediction can reveal the development of AD. In recent years, some studies have designed multi-task methods for AD detection and MMSE score prediction to take advantage of the correlation between them. However, how to use the correlation between the two task features is still a problem. To address this challenge, we propose a multi-task feature interactive leanrning network (MTFIL-Net) to perform AD detection and MMSE score prediction. First, we interact the features acquired by CNNs corresponding to the two tasks to take advantage of the feature correlation between the two tasks. The interaction module extracts the shared features of the two tasks and concatenate them with the features of the two task. Then, we design a joint loss based on cross entropy and smooth L1 function. We use the distribution of MMSE scores to dynamically adjust the relationship between the two tasks. We validate our method with subjects from the Alzheimer’s Disease Neuroimaging Initiative (ADNI). We use the ADNI1 dataset for training and testing, and used the ADNI2 dataset as an external validation set. Our proposed MTFIL-Net reached an ACC of 0.86 for AD detection and a correlation coefficient of 0.67 for MMSE score prediction on the ADNI1 dataset, and reached an ACC of 0.85 for AD detection and a correlation coefficient of 0.66 for MMSE score prediction on the ADNI2 dataset. Experiment results show that MTFIL-Net effectively utilizes the correlation between AD and MMSE score.

# Summary. An optional shortened abstract.
summary:  We propose a multi-task feature interactive leanrning network (MTFIL-Net) to perform AD detection and MMSE score prediction.

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
