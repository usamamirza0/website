---
title: 'MRI Reconstruction with Fourier-Constrained Diffusion Bridges'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Onat Dalmaz
  - Muhammad U Mirza
  - Gokberk Elmas
  - Muzaffer Özbey
  - Salman UH Dar
  - Emir Ceyani
  - Salman Avestimehr
  - Tolga Çukur

date: '2022-11-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-29T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: Multi-institutional collaborations are key for learning generalizable MRI synthesis models that translate source-onto target-contrast images. To facilitate collaboration, federated learning (FL) adopts decentralized training and mitigates privacy concerns by avoiding sharing of imaging data. However, FL-trained synthesis models can be impaired by the inherent heterogeneity in the data distribution, with domain shifts evident when common or variable translation tasks are prescribed across sites. Here we introduce the first personalized FL method for MRI Synthesis (pFLSynth) to improve reliability against domain shifts. pFLSynth is based on an adversarial model that produces latents specific to individual sites and source-target contrasts, and leverages novel personalization blocks to adaptively tune the statistics and weighting of feature maps across the generator stages given latents. To further promote site specificity, partial model aggregation is employed over downstream layers of the generator while upstream layers are retained locally. As such, pFLSynth enables training of a unified synthesis model that can reliably generalize across multiple sites and translation tasks. Comprehensive experiments on multisite datasets clearly demonstrate the enhanced performance of pFLSynth against prior federated methods in multi-contrast MRI synthesis.

# Summary. An optional shortened abstract.
summary: Presented in NeurIPS Medical Imaging Meets 2022

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10223912'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false
---
