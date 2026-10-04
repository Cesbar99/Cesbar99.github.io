---
title: ''
summary: 'Cesare Barbera — PhD candidate working on uncertainty quantification, probabilistic calibration, conformal prediction, and human-AI decision making.'
date: 2026-10-04
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I work on **machine learning under uncertainty**, with a focus on methods that make predictive systems more reliable and useful when decisions matter.

        My research spans **probabilistic calibration**, **uncertainty quantification**, **conformal prediction**, and **human-AI decision making**. I am particularly interested in how models can communicate uncertainty, decide when to defer or acquire more information, and support people in making better decisions.

        More broadly, I am interested in the intersection between reliable machine learning and decision-making systems.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
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
      count: 10
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
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
