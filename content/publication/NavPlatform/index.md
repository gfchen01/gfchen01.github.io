---
title: 'AIM-Nav: A FullStack Platform for Data-Driven Navigation Research'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Botao He
  - Shibo Zhao
  - Yiannis Aloimonos
  - Wenshan Wang
  - Ji Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-01T00:00:00Z'
doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

We present Navigation Development Environment 2, a low-cost modularized full-stack navigation system for upstream learning-based navigation research. The system has two parts: 1) a lightweight software stack on-board for geometric navigation, including SLAM, traversability analysis, and long-horizon path planning. 2) Customizable simulation environments based on Unity, featuring the same sensor and motion model as the real-world platform, photo-realistic rendering, and automatic data annotation. Our navigation algorithm relies only on a single low-cost LiDAR-IMU module and the onboard computer. This enables deployment on popular platforms without extra costs or extrinsic calibration effort, e.g. Unitree Go2. In the experiments, we show its localization, collision avoidance, and planning performance in various environments. We also show the usage of our system in fine-tuning 3D object detection and language navigation in custom environments. Guidelines and tutorials are provided for the setup of the system on popular platforms and integration with upstream modules.
# Summary. An optional shortened abstract.
summary: Full-stack navigation systems on Unitree Go2 and Diablo, aiming to provide a low-cost and ready-to-use platform for AI navigation research.

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
url_project: 'https://www.far-planner.com/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

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
