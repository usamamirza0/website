---
# Leave the homepage title empty to use the site title
title:
date: 2026-09-28
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publication
    content:
      title: Publications
      text: '### Journal Articles'
      # Show all items (the default is 5)
      count: 0
      filters:
        folders:
          - publication
        publication_type: '2'
    design:
      columns: '2'
      view: card
  # The next two blocks have no title so they read as a continuation of
  # Publications (see assets/scss/custom.scss).
  - block: collection
    id: conf
    content:
      text: '### Conference Papers'
      count: 0
      filters:
        folders:
          - publication
        tag: Conference Paper
    design:
      columns: '2'
      view: citation
  - block: collection
    id: abstracts
    content:
      text: '### Conference Abstracts & Workshop Papers'
      count: 0
      filters:
        folders:
          - publication
        tag: Abstract
    design:
      columns: '2'
      view: citation
  - block: experience
    id: experience
    content:
      title: Experience
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Research Assistant
          company: ICON Lab, National Magnetic Resonance Research Center (UMRAM)
          company_url: 'http://www.icon.bilkent.edu.tr/'
          location: Ankara
          date_start: '2021-09-05'
          date_end: ''
          description: |2-
            * Developed Fourier-constrained diffusion bridges for accelerated MRI reconstruction (first author, IEEE TMI 2026; code: [github.com/icon-lab/FDB](https://github.com/icon-lab/FDB)).
            * Designed frequency-domain diffusion models for accelerated MRI and upscaling diffusion bridges for MRI super-resolution (first author, SIU 2023–2026).
            * Contributed to pFLSynth, a personalized federated learning model for multi-contrast MRI synthesis across institutions (Medical Image Analysis 2024).
        - title: Graduate Teaching Assistant
          company: Bilkent University
          company_url: 'https://ee.bilkent.edu.tr/en/'
          location: Ankara
          date_start: '2021-09-05'
          date_end: ''
          description: 'Courses: Engineering Mathematics I & II, Linear System Theory, Neural Networks'
        - title: Reviewer
          company: IEEE Transactions on Medical Imaging
          company_url: 'https://www.embs.org/tmi/'
          date_start: '2024-01-01'
          date_end: ''
        - title: Research Intern
          company: TUKL Research and Development Lab, NUST
          company_url: 'https://tukl.seecs.nust.edu.pk/'
          location: Islamabad
          date_start: '2019-06-10'
          date_end: '2019-09-30'
          description: |2-
            * Surveyed FPGA accelerator architectures for deep neural networks.
            * Worked with Vivado HLS (C/C++) and Xilinx Vivado on Zynq FPGA platforms.
            * Prepared neural network models in Python for FPGA deployment.
    design:
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      title: Honors & Awards
      date_format: '2006'
      items:
        - title: ISMRM Summa Cum Laude Merit Award
          organization: International Society for Magnetic Resonance in Medicine (ISMRM), Singapore
          organization_url: 'https://www.ismrm.org/'
          date_start: '2024-05-04'
          description: Oral presentation on Fourier-constrained diffusion bridges for accelerated MRI
        - title: Outstanding Cambridge Learner Award
          organization: Cambridge Assessment International Education
          organization_url: 'https://www.cambridgeinternational.org/'
          date_start: '2015-01-01'
          description: Highest mark in the world in O-Level Mathematics
    design:
      columns: '2'
---
