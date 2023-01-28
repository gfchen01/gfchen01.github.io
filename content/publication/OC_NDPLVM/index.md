---
title: 'Rethinking the Parameter Learning of the Nonliear Dynamical Probabilistic Latent Variable Model'

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
publication: SUBMITTED to IEEE Transactions on Automation Science and Engineering (T-ASE)
# publication_short: PSE

abstract: Nonlinear dynamical probabilistic latent variable model (NDPLVM) and its variants have been widely applied in industrial sequential data modeling cases like anomaly detection & diagnosis and inferential sensor. However, previous works mainly concentrate on model architecture design, which may hinder their application for the ignorance of the following issues -- (1), parameter learning algorithm principle; (2), inference network input variable; (3), moment expressions for nonlinear neural network structure. To address these issues, we propose a principled model named optimal control-NDPLVM (OC-NDPLVM), derive its parameter learning algorithm, and simplify its moment expressions in this paper. Specifically, we first propose the OC-NDPLVM and its parameter learning objective from stochastic differential theory principally. On this basis, we address issue 1) by converting the parameter learning problem into an optimization problem and deriving the parameter learning procedure based on the alternating direction method of multipliers framework. Meanwhile, we address issue 2) in the optimal control subproblem in the optimization procedure based on issue 1). After that, we address issue 3) by conducting the mean and variance expressions simplification to make the model computation tractable. Finally, we conduct two industrial inferential sensor downstream tasks to demonstrate the effectiveness of OC-NDPLVM.

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
