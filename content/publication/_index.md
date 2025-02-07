---
title: Publications
type: landing
cms_exclude: true

sections:
  # Featured publications section
  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: "Our key research highlights"
      filters:
        folders:
          - publication
        featured: true
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '1'    # Full width for better readability
      view: google_scholar    # Custom citation view
      spacing:
        padding: ["20px", "0", "20px", "0"]

  # Recent publications section
  - block: collection
    content:
      title: Recent Publications
      text: "Discover our latest research"
      filters:
        folders:
          - publication
        exclude_featured: true
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '1'    # Full width for better readability
      view: google_scholar    # Custom citation view
      spacing:
        padding: ["20px", "0", "20px", "0"]

banner:
  caption: ""
  image: ""
---

