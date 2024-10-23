---
title: 'AI-Navigation Development Environment: A Research Platform for Semantic Navigation and Robot Learning with Mobile Robots in Real-World'

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

abstract: Training and deploying deep-learning-based navigation algorithms on real-world robot systems is challenging. A major reason is the cost, calibration, and engineering iterations required to build a robust real-world mobile platform to collect training data and execute higher-level commands safely. We present the AI-Navigation Development Platform, a low-cost modularized navigation system for learning-based navigation research built on commercialized sensors and hardware platforms. The system takes a goal point, then drives the robot system to that position, and handles localization and mapping, obstacle avoidance, and global planning. We also release rich simulations for each hardware platform with the same sensor and motion model to streamline the testing of users' algorithms. In our experiments, we show 1. the robustness of navigation, it can traverse kilometer scale trajectories safely with drift smaller than 0.5m. 2. low-cost but high-quality data collection, examples of generating KITTI-style datasets in both custom simulation and real-world environments. 3. ready-to-use with custom AI modules, examples of language navigation using our system.

# Summary. An optional shortened abstract.
summary: Full-stack navigation systems on Unitree Go2 and Diablo, aiming to privide a low-cost and ready-to-use platform for AI-navigation research.

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
