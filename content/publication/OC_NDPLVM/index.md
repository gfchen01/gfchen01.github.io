---
title: 'Analyzing and Improving Supervised Nonlinear Dynamical Probabilistic Latent Variable Model for Inferential Sensors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhichao Chen
  - Hao Wang
  - admin
  - Le Yao
  - Zhiqiang Ge
  - Zhihuan Song

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-11-01T00:00:00Z'
doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Industrial Informatics
publication_short: T-II

abstract: Nonlinear Dynamical Probabilistic Latent Variable Model (NDPLVM) and its variants, essential in industrial inferential sensors, face challenges in latent space inference and deep learning (DL) backend implementation. The first issue arises from the assumption that covariates directly infer the latent variable, potentially leading to inaccuracies. The second issue involves the discrepancy between the probabilistic distribution function form of NDPLVMs and data sample-based operation of DL backends. Addressing these,this study introduces the Optimal Control-NDPLVM(OC-NDPLVM), a model designed to enhance performance by analyzing NDPLVMs learning and tackling these issues. For the first problem, NDPLVMs’ learning is reinterpreted as an optimization problem, solved by alternating direction method of multipliers, and selecting the inference network’s input via studying optimal solution’s structure. To address the second issue, OC-NDPLVM adapts mean and covariance equations for compatibility with DL backends. This model’s effectiveness is validated through experiments on two inferential sensor datasets.
# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
