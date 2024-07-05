---
title: 'Interactive-FAR: Interactive, Fast and Adaptable Routing for Navigation Among Movable Obstacles in Complex Unknown Environments'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Botao He
  - Wenshan Wang
  - Ji Zhang
  - Cornelia Fermuller
  - Yiannis Aloimonos

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

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
publication: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024)
publication_short: IROS 2024

abstract: This paper introduces a real-time algorithm for navigating complex unknown environments cluttered with movable obstacles. Our algorithm achieves fast, adaptable routing by actively attempting to manipulate obstacles during path planning and adjusting the global plan from sensor feedback. The main contributions include an improved dynamic Directed Visibility Graph (DV-graph) for rapid global path searching, a real-time interaction planning method that adapts online from new sensory perceptions, and a comprehensive framework designed for interactive navigation in complex unknown or partially known environments. Our algorithm is capable of replanning the global path in several milliseconds. It can also attempt to move obstacles, update their affordances, and adapt strategies accordingly. Extensive experiments validate that our algorithm reduces the travel time by 33%, achieves up to 49% higher path efficiency, and runs faster than traditional methods by orders of magnitude in complex environments. It has been demonstrated to be the most efficient solution in terms of speed and efficiency for interactive navigation in environments of such complexity. We also open-source our code in the docker demo to facilitate future research.

# Summary. An optional shortened abstract.
summary: A efficient navigation system that takes manipulating movable object into account in complex unknown environments.

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
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/5FNN5Us8-2o?si=hHZcYXIRq_JeeBYL'

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
