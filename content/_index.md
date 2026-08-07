---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    id: hero
    content:
      title: ''
      text: |-
        # Dharamraj Yadav

        PhD Researcher in Computational Mechanics at University de Technologie de Compiegene (UTC) — Multiphysics & Multiscale Modeling of Fatigue Failure
    design:
      css_class: 'min-h-[80vh] flex items-end justify-center pb-16 md:pb-24 px-6 md:px-14'
      background:
        image:
          filename: Cover Photo.jpg
          filters:
            brightness: 0.6
        text_color_light: true
  - block: markdown
    id: bio-teaser
    content:
      title: 'Bio'
      subtitle: ''
      text: |-
        ![Dharamraj Yadav](/media/me.png)

        Research on multi-physics and multi-scale modeling of fatigue failure, combining computational mechanics with data-driven methods — with a broader interest in scientific machine learning, uncertainty quantification, and computational physics. Dharamraj Yadav is a PhD Researcher in Computational Mechanics. His research focuses on multi-physics and multi-scale modeling of fatigue failure, combining computational modeling with data-driven methods. [Learn more about Dharamraj →](bio/)
    design:
      columns: '1'
      spacing:
        padding: ['6rem', '1.5rem', '1rem', '1.5rem']
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: resume-skills
    content:
      username: me
      title: 'Skills'
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
      layout: title-side
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
---
