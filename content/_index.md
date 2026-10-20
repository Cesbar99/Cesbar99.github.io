---
title: ''
summary: 'Cesare Barbera — PhD candidate working on uncertainty quantification, probabilistic calibration, conformal prediction, and human-AI decision making.'
date: 2026-10-04
type: landing

  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'Some due introductions'
        education: ''
        interests: ''
    design:
      spacing:
        padding: [1, 0, 1, 0]
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        featured_only: true
      archive:
        enable: true
        link: /publications/
        text: See all publications
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      page_type: blog
      count: 20
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: news-list
      spacing:
        padding: [0, 0, 0, 0]

  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: resume-awards
    id: grants-awards
    content:
      title: Grants & Awards
      username: me
---
