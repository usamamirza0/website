---
title: 'MRI Reconstruction with Fourier-Constrained Diffusion Bridges'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammad U Mirza
  - Onat Dalmaz
  - Hasan A Bedel
  - Gokberk Elmas
  - Alper Gungor
  - Tolga Çukur

date: '2023-12-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Medical Imaging meets NeurIPS 2023
publication_short:

abstract: 'Diffusion-based image priors have gained recent traction in MRI reconstruction. Common diffusion priors use a multi-step transformation to map Gaussian noise onto fully-sampled MRI data. However, this transformation diverges from the desired reconstruction transformation from undersampled to fully-sampled data, yielding suboptimal results. To overcome this limitation, we introduce Fourier-constrained diffusion bridges (FDB; https://github.com/icon-lab/FDB) for accelerated MRI reconstruction. FDB learns a multi-step transformation from undersampled to fully-sampled data guided by two degradation operators: random noise addition and random frequency removal. Unlike common diffusion priors that use an asymptotic endpoint (e.g., Gaussian noise), FDB performs a finite transformation with an endpoint based on moderately degraded data. Unlike common diffusion bridges that assume learnable forward and backward processes, FDB improves learning by injecting a task-relevant Fourier-domain constraint via its frequency removal operator. Demonstrations on brain MRI show that FDB outperforms state-of-the-art reconstruction methods including previous diffusion priors.'

# Summary. An optional shortened abstract.
summary: Presented in Medical Imaging meets NeurIPS 2023

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
