---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: cv-angga-fiks.pdf
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
      title: ""
      text: |-
        <div style="text-align: center; margin-top: -20px; margin-bottom: 30px;">
          <a href="portfolio-angga.pdf" style="
            display: inline-flex;
            align-items: center;
            padding: 15px 40px;
            background: linear-gradient(90deg, #6366f1 0%, #14b8a6 100%);
            color: white;
            border-radius: 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            transition: transform 0.2s;
          " onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
            <span style="margin-right: 10px;"></span> 
            Download Portfolio PDF
          </a>
        </div>
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Professional Profile'
      subtitle: ''
      text: |-
        Welcome to my professional portfolio. I am an Informatics Engineering graduate specializing in Full-Stack Software Engineering, dynamic web development, and robust end-to-end system architecture.

        By bridging high-performance back-end logic, optimized relational database management systems (RDBMS), and intuitive, responsive front-end interfaces, I am highly committed to building seamless, secure, and production-ready digital products.

        Feel free to connect with me for project collaborations, full-stack software engineering discussions, or professional career opportunities.
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
---