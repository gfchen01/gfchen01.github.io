---
title: 'Air-FAR: Fast and Adaptable Routing for Aerial Navigation in Large-scale Complex Unknown Environments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Botao He
  - admin
  - Wenshan Wang
  - Cornelia Fermuller
  - Yiannis Aloimonos
  - Ji Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-01T00:00:00Z'
doi: ''

# # Schedule page publish date (NOT publication's date).
# publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: SUBMITTED to International Conference on Robotics and Automation (ICRA 2025)
publication_short: Submitted to ICRA 2025

abstract: This paper presents a novel method for real-time 3D navigation in large-scale, complex environments using a hierarchical 3D visibility graph (V-graph). The proposed algorithm addresses the computational challenges of V-graph construction and shortest path search on the graph simultaneously.  By introducing hierarchical 3D V-graph construction with heuristic visibility update, the 3D V-graph is constructed in $O(K\cdot n^2logn)$ time, which guarantees real-time performance.  The proposed iterative divide-and-conquer path search method can achieve near-optimal path solutions within the constraints of real-time operations. The algorithm ensures efficient 3D V-graph construction and path search. Extensive simulated and real-world environments validated that our algorithm reduces the travel time by 42%, achieves up to 24.8% higher trajectory efficiency, and runs faster than most benchmarks by orders of magnitude in complex environments. The code and developed simulator have been open-sourced to facilitate future research.

# Summary. An optional shortened abstract.
summary: A real-time 3D mapping and path planning algorithm for aerial robot that is up-to x1000 times faster than grid-map based strong benchmarks.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2404.07447'
url_code: 'https://github.com/Bottle101/Interactive-FAR'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_poster: ''
url_project: 'https://www.far-planner.com/air-far-planner'
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
