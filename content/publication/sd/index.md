---
title: 'SD-DefSLAM: Semi-Direct Monocular SLAM for Deformable and Intracorporeal Scenes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jose Lamarca
  - Javier Morlana
  - José MM Montiel
  - Juan D Tardós
  

# Author notes (optional)
#author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
  -
  -

date: '2020-10-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation 2021*
publication_short: In *ICRA 2021* **(Under revision)**

abstract: Conventional SLAM techniques strongly rely on scene rigidity to solve data association, ignoring dynamic parts of the scene. In this work we present Semi-Direct DefSLAM (SD-DefSLAM), a novel monocular deformable SLAM method able to map highly deforming environments, built on top of DefSLAM. To robustly solve data association in challenging deforming scenes, SD-DefSLAM combines direct and indirect methods':' an enhanced illumination-invariant Lucas-Kanade tracker for data association, geometric Bundle Adjustment for pose and deformable map estimation, and bag-of-words based on feature descriptors for camera relocation. Dynamic objects are detected and segmented-out using a CNN trained for the specific application domain. We thoroughly evaluate our system in two public datasets. The mandala dataset is a SLAM benchmark with increasingly aggressive deformations. The Hamlyn dataset contains intracorporeal sequences that pose serious real-life challenges beyond deformation like weak texture, specular reflections, surgical tools and occlusions. Our results show that SD-DefSLAM outperforms DefSLAM in point tracking, reconstruction accuracy and scale drift thanks to the improvement in all the data association steps, being the first system able to robustly perform SLAM inside the human body. 


tags: [endoscopy, camera tracking, monocular, optical flow]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2010.09409.pdf'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=gkcC0IR3X6A&ab_channel=DefSLAM'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'SD-DefSLAM working on Dataset1 of Hamlyn dataset. Left: features tracked in the endoscopic image using photometric techniques. Right: camera motion and growing deformable map estimated by minimizing geometric error'
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

