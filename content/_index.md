---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |-
        # Dharamraj Yadav

        PhD Researcher in Computational Mechanics — Multiphysics & Multiscale Modeling of Fatigue Failure
    design:
      css_class: 'min-h-[70vh] flex items-center justify-center text-center'
      background:
        image:
          filename: cover.svg
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
    content:
      title: ''
      subtitle: ''
      text: |-
        Dharamraj Yadav is a PhD Researcher in Computational Mechanics. His research focuses on multi-physics and multi-scale modeling of fatigue failure.

        [Learn more about Dharamraj →](bio/)
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
---
