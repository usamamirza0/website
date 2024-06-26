---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
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
      title: Journal Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: conf
    content:
      title: Conference Proceedings
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: card
  - block: experience
    id: experience
    background: #000
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistantship
          company: Imaging and Computational Neuroscience Lab
          company_url: 'http://www.icon.bilkent.edu.tr/'
          location: Ankara
          date_start: '2021-09-05'
          date_end: ''
          description: Developing novel techniques for MRI Synthesis and Reconstruction
        - title: Teaching Assistantship
          company: Bilkent University
          company_url: 'https://ee.bilkent.edu.tr/en/'
          location: Ankara
          date_start: '2021-09-05'
          date_end: ''
          description: Engineering Mathematics I & II
        - title: Internship
          company: Supernet
          company_url: 'https://super.net.pk/'
          location: Islamabad
          date_start: '2021-02-04'
          date_end: '2021-04-05'
          description: Worked on Satellite Communication
        - title: Research Internship
          company: TUKL-NUST Research & Development Center
          company_url: 'https://tukl.seecs.nust.edu.pk/'
          location: Islamabad
          date_start: '2019-06-10'
          date_end: '2019-09-30'
          description: Worked on the acceleration of Deep Neural Networks on FPGAs
    design:
      columns: '2'
---
