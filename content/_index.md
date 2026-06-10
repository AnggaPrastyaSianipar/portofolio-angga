---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /cv-angga-fiks.pdf
      headings:
        about: ''
        education: ''
        interests: ''
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
      title: 'Professional Profile'
      subtitle: ''
      text: |-
        Welcome to my professional portfolio. I am an Informatics Engineering graduate specializing in Software Engineering, Back-End Architecture, and the development of robust, scalable web applications.

        By leveraging efficient computational approaches, optimized relational database management systems (RDBMS), and industry-standard clean code practices, I am highly committed to building stable, secure, and production-ready digital infrastructures.

        Feel free to connect with me for project collaborations, technical software engineering discussions, or professional career opportunities.
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
      title: Recent Publications
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
      title: Credentials & Certifications
      filters:
        folders:
          - events
    design:
      view: card
  - block: cta-card
    demo: false
    content:
      title: ''
      text: ''
    design:
      card:
        css_class: ''
        css_style: 'display: none !important;'
---