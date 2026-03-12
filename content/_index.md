---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Base spacing
  spacing: '2rem'

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
      # Manually pull the bottom margin up
      css_class: 'mb-0 pb-0'
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: resume-experience
    content:
      username: me
    design:
      date_format: '2006'
      is_education_first: true
      # Tighten spacing to flow naturally
      css_class: 'mt-0 pt-0 mb-8'

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
