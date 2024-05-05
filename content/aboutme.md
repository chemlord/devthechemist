---
title: My About Page
type: landing

sections:
  - block: portfolio
    id: portfolio
    content:
      title: My Portfolio
      subtitle: 'A showcase of my work'
      text: 'Explore projects and case studies related to my field.'
      # Portfolio specific configurations
      count: 10
      filters:
        folders:
          - projects   # Assuming your projects are stored in a folder named 'projects'
        tags: ""      # Filter by specific tags if needed
      sort_by: 'Date'  # Sorting criterion
      sort_ascending: false
    design:
      view: grid   # Display portfolio items in a grid layout
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      count: 5
      filters:
        folders:
          - post
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: card

---
