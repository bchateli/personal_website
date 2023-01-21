---
title: 'Efficient Deep Unfolding for SISO-OFDM Channel Estimation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Baptiste CHATELIER
  - Luc LE MAGOAROU
  - Getachew REDIETEAB

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2022-10-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ICC*
publication_short: In *ICC*

abstract: In modern communication systems, channel state information is of paramount importance to achieve capacity. It is then crucial to accurately estimate the channel. It is possible to perform SISO-OFDM channel estimation using sparse recovery techniques. However, this approach relies on the use of a physical wave propagation model to build a dictionary, which requires perfect knowledge of the system's parameters. In this paper, an unfolded neural network is used to lighten this constraint. Its architecture, based on a sparse recovery algorithm, allows SISO-OFDM channel estimation even if the system's parameters are not perfectly known. Indeed, its unsupervised online learning allows to learn the system's imperfections in order to enhance the estimation performance. The practicality of the proposed method is improved with respect to the state of the art in two aspects, constrained dictionaries are introduced in order to reduce sample complexity and hierarchical search within dictionaries is proposed in order to reduce time complexity. Finally, the performance of the proposed unfolded network is evaluated and compared to several baselines using realistic channel data, showing the great potential of the approach.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#  - name: Link to PDF
#  - url: https://ieeexplore.ieee.org/document/9771690

url_pdf: 'https://arxiv.org/pdf/2210.06588.pdf'
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

