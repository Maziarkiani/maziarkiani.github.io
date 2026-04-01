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
  # Displays your avatar, name, social links, summary, and skills.
  # (Pulls data automatically from 'data/authors/me.yaml')
  # ==============================================================================
  - block: resume-biography-3
    content:
      username: me
      text: ''
      # The section titles you want to display in the right column
      headings:
        about: ''
        interests: ''
        skills: 'Technical and Research Skills'
    
    design:
      # The animated purple/blue background
      background:
        gradient_mesh:
          enable: true

      # Typography and image styling
      name:
        size: md 
      avatar:
        size: medium 
        shape: circle 
        
      # Manual Spacing Override: [Top, Right, Bottom, Left]
      spacing:
        padding: ['3rem', '0', '1rem', '0'] 

  # ==============================================================================
  # 3. EDUCATION & EXPERIENCE SECTION (Middle of page)
  # Generates a full-width timeline of your academic and industry background.
  # (Pulls data automatically from 'data/authors/me.yaml')
  # ==============================================================================
  - block: experience
    content:
      title: Education & Experience
      username: me
    design:
      # Breathing room above and below the timeline
      spacing:
        padding: ['2rem', '0', '3rem', '0']
  
  # ==============================================================================
  # 4. RECENT PUBLICATIONS SECTION (Bottom of page)
  # Automatically lists your papers in a clean citation format.
  # (Pulls data from markdown files inside your 'content/publication/' folder)
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
      
      # Manual Spacing Override to pull it tighter to the timeline above
      spacing:
        padding: ['1rem', '0', '1rem', '0']
---
