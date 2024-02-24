---
title: 'One Model to Unite Them All: Personalized Federated Learning of Multi-Contrast MRI Synthesis'

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
  - Kader K Oguz
  - Salman Avestimehr
  - Tolga Çukur

date: '2024-02-23T00:00:00Z'
doi: 'https://doi.org/10.1016/j.media.2024.103121'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Medical Image Analysis*'
publication_short: '*MEDIA*'

abstract: Curation of large, diverse MRI datasets via multi-institutional collaborations can help improve learning of generalizable synthesis models that reliably translate source- onto target-contrast images. To facilitate collaborations, federated learning (FL) adopts decentralized model training while mitigating privacy concerns by avoiding sharing of imaging data. However, conventional FL methods can be impaired by the inherent heterogeneity in the data distribution, with domain shifts evident within and across imaging sites. Here we introduce the first personalized FL method for MRI Synthesis (pFLSynth) that improves reliability against data heterogeneity via model specialization to individual sites and synthesis tasks (i.e., source-target contrasts). To do this, pFLSynth leverages an adversarial model equipped with novel personalization blocks that control the statistics of generated feature maps across the spatial/channel dimensions, given latent variables specific to sites and tasks. To further promote communication efficiency and site specialization, partial network aggregation is employed over later generator stages while earlier generator stages and the discriminator are trained locally. As such, pFLSynth enables multi-task training of multi-site synthesis models with high generalization performance across sites and tasks. Comprehensive experiments demonstrate the superior performance and reliability of pFLSynth in MRI synthesis against prior federated methods.

# Summary. An optional shortened abstract.
summary: Curation of large, diverse MRI datasets via multi-institutional collaborations can help improve learning of generalizable synthesis models that reliably translate source- onto target-contrast images. To facilitate collaborations, federated learning (FL) adopts decentralized model training while mitigating privacy concerns by avoiding sharing of imaging data. However, conventional FL methods can be impaired by the inherent heterogeneity in the data distribution, with domain shifts evident within and across imaging sites. Here we introduce the first personalized FL method for MRI Synthesis (pFLSynth) that improves reliability against data heterogeneity via model specialization to individual sites and synthesis tasks (i.e., source-target contrasts). To do this, pFLSynth leverages an adversarial model equipped with novel personalization blocks that control the statistics of generated feature maps across the spatial/channel dimensions, given latent variables specific to sites and tasks. To further promote communication efficiency and site specialization, partial network aggregation is employed over later generator stages while earlier generator stages and the discriminator are trained locally. As such, pFLSynth enables multi-task training of multi-site synthesis models with high generalization performance across sites and tasks. Comprehensive experiments demonstrate the superior performance and reliability of pFLSynth in MRI synthesis against prior federated methods.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S136184152400046X'
url_code: 'https://github.com/icon-lab/pFLSynth'
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
