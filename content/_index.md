---
# Leave the homepage title empty to use the site title
title:
date: 2024-05-03
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: header_undergrad-chemistry-lab-csb.webp
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Hey There!'
      subtitle: 'Welcome to my personal portfolio 👋'
      text: |-
        I'm Devraj Bagchi and I'm a Biochemistry and Molecular Biology Honours student at Trent University. My academic interests lie deeply in Synthetic Organic Chemistry, specifically Carbonyl chemistry, which I explore both theoretically and through sample analysis via analytical instrumentation and data documentation critical for high-standard research.

        As a hobby, I've also developed skills in front-end web development and UI design, learning languages such as Go, HTML, CSS, and Python, which I enjoy applying to create and manage my own academic portfolio.

        **Specialties:** My Laboratory proficiencies include but are not limited to TLC, FT-IR, ¹H NMR, GC-MS, HPLC, IEC, SEC, and UV-Vis spectroscopy, biohazard handling, aspetic technique, etc.


    design:
      columns: '1'
  - block: collection
    content:
      title: Featured Articles
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
