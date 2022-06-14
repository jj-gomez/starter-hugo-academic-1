---
title: 'Direct and Sparse Deformable Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jose Lamarca
  - admin
  - José MM Montiel
  - Juan D Tardós
  

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-09-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Submitted to * IEEE Robotics and Automation Letters* **(Under revision)**
publication_short: Submitted *RA-L* **(Under revision)**

abstract: Deformable Monocular SLAM algorithms recover the localization of a camera in an unknown deformable environment. Current approaches use a template-based deformable tracking to recover the camera pose and the deformation of the map. These template-based methods use an underlying global deformation model. In this paper, we introduce a novel deformable camera tracking method with a local deformation model for each point. Each map point is defined as a single textured surfel that moves independently of the other map points. Thanks to a direct photometric error cost function, we can track the position and orientation of the surfel without an explicit global deformation model. In our experiments, we validate the proposed system and observe that our local deformation model estimates more accurately and robustly the targeted deformations of the map in both laboratory-controlled experiments and in-body scenarios undergoing non-isometric deformations, with changing topology or discontinuities. 


tags: [endoscopy, camera tracking, monocular]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2109.07370.pdf'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/1XJFbLsp_76eGqDisJj8Sjcljaf3F1c94/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Direct and Sparse Deformable Tracking processing
Hamlyn Dataset sequence 6, results after frames #750, #1115
and #1153. Bottom: The map composed of sparse surfels.
Top: Camera Trajectory in green.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

