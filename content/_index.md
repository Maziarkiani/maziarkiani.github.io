---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Base spacing
  spacing: '2.5rem'

sections:
  # 1. Clean Biography (No education boxes!)
  - block: resume-biography
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      # Manually pull the bottom margin up
      css_class: 'mb-0 pb-0'
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 2. Dedicated Education Timeline (No work experience!)
  - block: resume-education
    content:
      username: me
    design:
      date_format: '2006'
      # Tighten spacing to flow naturally
      css_class: 'mt-0 pt-0 mb-8'

  # 3. Publications
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
