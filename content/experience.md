---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  # 1. Shrink the default global spacing
  spacing: 4rem'

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true
      # 2. Add manual tight spacing (Top, Right, Bottom, Left)
      spacing:
        padding: ['2.5rem', '0', '2.5rem', '0']

  - block: resume-skills
    content:
      title: Skills & Tools
      username: me
    design:
      spacing:
        padding: ['3rem', '0', '3rem', '0']

  - block: resume-languages
    content:
      title: Languages
      username: me
    design:
      spacing:
        padding: ['3rem', '0', '3rem', '0']
---
