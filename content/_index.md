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
  - block: bio-merged
    id: bio-teaser
    content:
      username: me
      photo: /media/me.png
      learn_more_url: bio/
      about_text: |-
        Research on multi-physics and multi-scale modeling of fatigue failure, combining computational mechanics with data-driven methods — with a broader interest in scientific machine learning, uncertainty quantification, and computational physics. Dharamraj Yadav is a PhD Researcher in Computational Mechanics. His research focuses on multi-physics and multi-scale modeling of fatigue failure, combining computational modeling with data-driven methods.
      education_text: |-
        **PhD, Computational Mechanics** — Université de Technologie de Compiègne (UTC), France · 2026 – Present
        Thesis: *Multi-physics/multi-scale modelling of fatigue failure*

        **MSc, Mechanical Engineering** — [Institution Name] · 2022 – 2024 · Grade: 8.7/10
        Thesis: [Thesis title]

        **BSc, Mechanical Engineering** — [Institution Name] · 2018 – 2022 · Grade: 8.2/10
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      columns: '1'
      spacing:
        padding: ['6rem', '1.5rem', '1rem', '1.5rem']
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
