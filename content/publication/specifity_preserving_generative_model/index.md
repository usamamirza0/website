---
title: 'A Specificity-Preserving Generative Model for Federated MRI Translation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Onat Dalmaz
  - Muhammad U Mirza
  - Gokberk Elmas
  - Muzaffer Özbey
  - Salman UH Dar
  - Tolga Çukur

date: '2022-10-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2012-10-07T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:
publication_short:

abstract: MRI translation models learn a mapping from an acquired source contrast to an unavailable target contrast. Collaboration between institutes is essential to train translation models that can generalize across diverse datasets. That said, aggregating all imaging data and training a centralized model poses privacy problems. Recently, federated learning (FL) has emerged as a collaboration framework that enables decentralized training to avoid sharing of imaging data. However, FL-trained translation models can deteriorate by the inherent heterogeneity in the distribution of MRI data. To improve reliability against domain shifts, here we introduce a novel specificity-preserving FL method for MRI contrast translation. The proposed approach is based on an adversarial model that adaptively normalizes the feature maps across the generator based on site-specific latent variables. Comprehensive FL experiments were conducted on multi-site datasets to show the effectiveness of the proposed approach against prior federated methods in MRI contrast translation.

# Summary. An optional shortened abstract.
summary: Presented in MICCAI Workshop on “Distributed, Collaborative and Federated Learning” (MICCAI-DeCaF 2022)

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-031-18523-6_8'
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
