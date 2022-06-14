---
title: 'Tracking monocular camera pose and deformation for SLAM inside the human body'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - José MM Montiel
  - Juan D Tardós
  

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE/RSJ International Conference on Intelligent Robots and Systems* **(Under revision)**
publication_short: In *IROS 2022* **(Under revision)**

abstract: Monocular SLAM in deformable scenes will open the way to multiple medical applications like computer-assisted navigation in endoscopy, automatic drug delivery or autonomous robotic surgery. In this paper we propose a novel method to simultaneously track the camera pose and the 3D scene deformation, without any  assumption about environment topology or shape. The method uses an illumination-invariant photometric method to track image features and estimates camera motion and deformation combining reprojection error with spatial and temporal regularization of deformations. Our results in simulated colonoscopies show the method's accuracy and robustness in complex scenes under increasing levels of deformation. Our qualitative results in human colonoscopies from Endomapper dataset show that the method is able to successfully cope with the challenges of real endoscopies like deformations, low texture and strong illumination changes. We also compare with previous tracking methods in simpler scenarios from Hamlyn dataset where we obtain competitive performance, without needing any topological assumption.


tags: [endoscopy, camera tracking, monocular]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2204.08309.pdf'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/cpVHMvPjLL8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Tracking the camera pose and scene deformation
in a human colonoscopy from Endomapper dataset. Top:
images from the sequence. Bottom: camera trajectory in blue,
undeformed map points in black and map point deformation
trajectories in red.'
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
