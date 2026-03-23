---
title: 'Learning Fourier-Constrained Diffusion Bridges for MRI Reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammad U Mirza
  - Onat Dalmaz
  - Hasan A Bedel
  - Gokberk Elmas
  - Yilmaz Korkmaz
  - Alper Gungor
  - Salman UH Dar
  - Kader K Oguz
  - Tolga Çukur

date: '2026-03-13T00:00:00Z'
doi: '10.1109/TMI.2026.3673956'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: *IEEE Transactions on Medical Imaging*
publication_short: *IEEE TMI*

abstract: Although MRI reconstruction requires a dealiasing transformation from undersampled to fully-sampled data, task-agnostic diffusion priors sample images via a denoising-based generative trajectory from an asymptotic start-point of Gaussian noise onto fully-sampled data. Since aliasing artifacts in MR images carry spatial structure deviating from Gaussian noise, this noise-governed trajectory can cause suboptimal artifact suppression. To address this limitation, we introduce the first Fourier-constrained diffusion bridge (FDB) for MRI reconstruction in the literature. Unlike task-agnostic diffusion priors, FDB does not rely on noise in its forward process and instead learns a dealiasing transformation between a start-point of undersampled data and the end-point of fully-sampled data. The start-point is derived via a stochastic Fourier-constrained degradation operator that removes a progressively growing set of spatial frequencies. Unlike cold/soft diffusion priors that use an asymptotic start-point of severely degraded measurements, FDB uses a realistically undersampled start-point to ensure closer alignment of model input between training and test distributions. Unlike existing diffusion bridges that use degradations based on weighted linear averages and noise addition, FDB implements degradations based on binary removal of compact k-space sets to conform to the physics of accelerated MRI. To further improve image quality, FDB leverages a novel sampling algorithm based on progressive dealiasing by continually correcting recovered k-space data across reverse diffusion steps.

# Summary. An optional shortened abstract.
summary: Although MRI reconstruction requires a dealiasing transformation from undersampled to fully-sampled data, task-agnostic diffusion priors sample images via a denoising-based generative trajectory from an asymptotic start-point of Gaussian noise onto fully-sampled data. Since aliasing artifacts in MR images carry spatial structure deviating from Gaussian noise, this noise-governed trajectory can cause suboptimal artifact suppression. To address this limitation, we introduce the first Fourier-constrained diffusion bridge (FDB) for MRI reconstruction in the literature. Unlike task-agnostic diffusion priors, FDB does not rely on noise in its forward process and instead learns a dealiasing transformation between a start-point of undersampled data and the end-point of fully-sampled data. The start-point is derived via a stochastic Fourier-constrained degradation operator that removes a progressively growing set of spatial frequencies. Unlike cold/soft diffusion priors that use an asymptotic start-point of severely degraded measurements, FDB uses a realistically undersampled start-point to ensure closer alignment of model input between training and test distributions. Unlike existing diffusion bridges that use degradations based on weighted linear averages and noise addition, FDB implements degradations based on binary removal of compact k-space sets to conform to the physics of accelerated MRI. To further improve image quality, FDB leverages a novel sampling algorithm based on progressive dealiasing by continually correcting recovered k-space data across reverse diffusion steps.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/iel8/42/4359023/11433825.pdf'
url_code: 'https://github.com/icon-lab/FDB'
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
