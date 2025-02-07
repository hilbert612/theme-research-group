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
        featured: true     # Add this line
        exclude_featured: false  # Add this line
      sort_by: 'weight'    # Sort by weight parameter
      sort_ascending: true  # Lower weight appears first
    design:
      columns: '2'
      view: showcase
      flip_alt_rows: false

  # Recent publications section
  - block: collection
    content:
      title: Recent Publications
      text: "Discover our latest research"
      filters:
        folders:
          - publication
        featured: false    # Add this line
        exclude_featured: true   # Add this line
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation

banner:
  caption: ""
  image: ""
---

