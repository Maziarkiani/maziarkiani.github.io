---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      # Name heading sizing to accommodate long or short names
      name:
        size: md

      # Avatar customization
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'My Research & Professional Focus'
      subtitle: ''
      text: |-
        My academic research in NLP is primarily focused on Information Retrieval (IR), Language Modeling, Corpus Linguistics and the Information Disorder.

        In addition to the core NLP work, I am partly focused on Cognitive Neuroscience—including brain plasticity, aesthetics and gamification—to build a deeper analytical foundation for understanding user behavior and human-computer interaction.
    design:
      columns: '1'

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
