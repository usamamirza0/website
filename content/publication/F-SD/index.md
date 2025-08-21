---
title: 'Frequency-Based Soft Diffusion Model for Accelerated MRI Reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Muhammad U Mirza
  - Mustafa Arda Aydın
  - Tolga Çukur

date: '2025-06-25T00:00:00Z'
doi: '10.1109/SIU66497.2025.11112367'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 33rd Signal Processing and Communications Applications Conference 2025
publication_short: SIU 2025

abstract: "Magnetic Resonance Imaging (MRI) is a powerful diagnostic tool, but its clinical utility is often hindered by long scan times. MRI reconstruction techniques aim to reduce scan times by enabling recovery of high quality MRI images from undersampled k-space acquisitions. This work introduces a novel diffusion model for MRI reconstruction that incorporates two key strategies: k-space spatial frequency removal and noise addition. During the forward diffusion process, k-space data points are progressively removed, simulating the undersampling process encountered in accelerated MRI scans. Simultaneously, images are corrupted via Gauss noise addition to enhance robustness against noise. This dual approach enables the diffusion model to learn the underlying image features while explicitly accounting for the acquisition process for accelerated MRI scans. Our results demonstrate that the proposed techniques offer superior image quality compared to conventional diffusion models in various undersampling rates. This work highlights that injecting prior knowledge on accelerated data acquisitions processes in MRI into diffusion models can help enhance reconstruction performance."

# Summary. An optional shortened abstract.
summary: Presented in 33rd Signal Processing and Communications Applications Conference (SIU 2025)

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/11112367'
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
