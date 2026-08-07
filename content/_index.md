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

        **PhD Researcher** in Computational Mechanics at **University de Technologie de Compiegene (UTC)** — Multiphysics & Multiscale Modeling of Fatigue Failure
    design:
      css_class: 'min-h-[80vh] flex items-end justify-right pb-16 md:pb-24 px-6 md:px-14'
      background:
        image:
          filename: Cover Photo.jpg
          filters:
            brightness: 0.6
        text_color_light: true
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        Research on multi-physics and multi-scale modeling of fatigue failure, combining computational mechanics with data-driven methods — with a broader interest in scientific machine learning, uncertainty quantification, and computational physics.
    design:
      columns: '1'
  - block: markdown
    id: bio-teaser
    content:
      title: ''
      subtitle: ''
      text: |-
        ![Dharamraj Yadav](/media/me.png)

        Dharamraj Yadav is a PhD Researcher in Computational Mechanics. His research focuses on multi-physics and multi-scale modeling of fatigue failure, combining computational modeling with data-driven methods. [Learn more about Dharamraj →](bio/)
    design:
      columns: '1'
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
