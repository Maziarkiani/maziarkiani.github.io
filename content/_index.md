---
# ==============================================================================
# 1. PAGE SETUP
# Basic configurations for your homepage
# ==============================================================================
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # The default spacing applied between all sections globally
  spacing: '2.5rem'

sections:
  # ==============================================================================
  # 2. BIO & PROFILE SECTION (Top of page)
  # ==============================================================================
  - block: resume-biography-3
    content:
      username: me
      text: ''
      # The button remains removed as requested!
      
      # We kept 'education' here so the two boxes show up, 
      # but we completely removed 'experience' so your jobs stay hidden!
      headings:
        about: ''
        education: 'Education'
        interests: ''
        skills: 'Technical and Research Skills'
    
    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md 
      avatar:
        size: medium 
        shape: circle 
        
      # Manual Spacing Override: [Top, Right, Bottom, Left]
      spacing:
        padding: ['3rem', '0', '1rem', '0'] 

  # ==============================================================================
  # 3. RECENT PUBLICATIONS SECTION (Bottom of page)
  # ==============================================================================
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
      
      # Manual Spacing Override to pull it tighter to the section above
      spacing:
        padding: ['1rem', '0', '1rem', '0']
---
