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
      css_class: 'mb-0 pb-0'
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 2. Education (Custom Markdown so it won't crash and won't show jobs)
  - block: markdown
    content:
      title: 'Education'
      subtitle: ''
      text: |-
        **M.Sc. in Language Technologies and Digital Humanities**  
        *University of Turin* (2023 - 2026)  
        Focused on Computational Linguistics, NLP (Information Retrieval, Sentiment Analysis, Language Modeling, Corpus Linguistics), and Cognitive Neuroscience (Brain Plasticity, Aesthetics, Gamification).
        <br><br>

        **B.A. in English Language and Translation**  
        *Shahrekord University* (2013 - 2017)  
        Focused on Linguistics (syntax, semantics, pragmatics, morphology) and translation studies.
    design:
      columns: '1'
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
