---
title: 'Search-Based Path Planning among Movable Obstacles'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhongqiang Ren
  - Bunyond Suvonov
  - admin
  - Botao He
  - Yijie Liao
  - Cornelia Fermuller
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

abstract: This paper investigates Path planning Among Movable Obstacles (PAMO), which seeks a minimum cost collision-free path among static obstacles from start to goal while allowing the robot to push away movable obstacles (i.e., objects) along its path when needed. To develop planners that are complete and optimal for PAMO, the planner has to search a giant state space involving both the location of the robot as well as the locations of the objects, which grows exponentially with respect to the number of objects. The main idea in this paper is that, only a small fraction of this giant state space needs to be explored during planning as guided by a heuristic, and most of the objects far away from the robot are intact, which thus leads to runtime efficient algorithms. Based on this idea, this paper introduces two PAMO formulations, i.e., biobjective and resource constrained problems in an occupancy grid, and develops PAMO*, a search method with completeness and solution optimality guarantees, to solve the two problems. We then further extend PAMO* to hybrid-state PAMO* to plan in continuous spaces with high-fidelity interaction between the robot and the objects. Our results show that, PAMO* can often find optimal solutions within a second in cluttered environments with up to 400 objects.

# Summary. An optional shortened abstract.
summary: Search based planning algorithms on grid maps for solving path planning among movable obstacles problem. 

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
