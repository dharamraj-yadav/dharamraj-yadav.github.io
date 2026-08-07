---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: hero-identity
    id: hero
    content:
      username: me
      tagline: 'PhD Researcher in Computational Mechanics at University de Technologie de Compiegene (UTC) — Multiphysics & Multiscale Modeling of Fatigue Failure'
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
      title: 'About Me'
      subtitle: ''
      text: |-
        ![Dharamraj Yadav](/media/me.png)

        Research on multi-physics and multi-scale modeling of fatigue failure, combining computational mechanics with data-driven methods — with a broader interest in scientific machine learning, uncertainty quantification, and computational physics. Dharamraj Yadav is a PhD Researcher in Computational Mechanics. His research focuses on multi-physics and multi-scale modeling of fatigue failure, combining computational modeling with data-driven methods. [Learn more about Dharamraj →](bio/)
    design:
      columns: '1'
  - block: markdown
    id: home-bio
    content:
      title: ''
      subtitle: ''
      text: |-
        ## Education

        **PhD, Computational Mechanics** — Université de Technologie de Compiègne (UTC), France · 2026 – Present
        Thesis: *Multi-physics/multi-scale modelling of fatigue failure*

        **MSc, Mechanical Engineering** — [Institution Name] · 2022 – 2024 · Grade: 8.7/10
        Thesis: [Thesis title]

        **BSc, Mechanical Engineering** — [Institution Name] · 2018 – 2022 · Grade: 8.2/10

        ## Research Interests

        - Multi-physics & multi-scale modeling of fatigue failure
        - Scientific machine learning (SciML)
        - Uncertainty quantification
        - Computational physics

        <a href="/uploads/resume.pdf" class="cv-download-btn">Download CV →</a>
    design:
      columns: '1'
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
