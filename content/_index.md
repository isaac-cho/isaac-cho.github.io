---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-06-29
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      headings:
        about: 'Short Bio'
        education: ''
        interests: ''
        
      text: ''
      # # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      # headings:
      #   about: ''
      #   education: ''
      #   interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

        
      
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I am a computer scientist working at the intersection of data visualization, visual analytics, immersive analytics, virtual reality, extended reality, augmented reality, and 3D user interfaces.

        My research investigates how people perceive, interact with, and make decisions using visual and immersive systems. I design and evaluate interactive technologies that support data exploration, spatial interaction, collaborative analysis, and human-centered sensemaking.

        Please feel free to reach out for research collaboration.
    design:
      columns: '1'

  - block: markdown
    id: news
    content:
      title: News
      text: |-
        - **Aug 2026** — Served on the International Program Committee (IPC) for IEEE Virtual Reality and 3D User Interfaces (IEEE VR).
        - **Aug 2026** — Two papers were accepted to the IEEE TVCG Special Track and one paper to the Conference Track at IEEE ISMAR 2026.
        - **June 2026** — Elevated to IEEE Senior Member.
        - **April 2026** — Joined the Editorial Board of Computers & Graphics as an Associate Editor.
        
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     page_type: post
  #     count: 10
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     offset: 0
  #     order: desc
  #   design:
  #     view: date-title-summary
  #     spacing:
  #       padding: [0, 0, 0, 0]

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card


  # - block: cta-card
  #   demo: true # Only display this section in the HugoBlox Kit demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       Demo section removed from the public homepage.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
---