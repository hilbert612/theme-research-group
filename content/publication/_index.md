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
        featured_only: true    # Changed this line
      sort_by: 'weight'
      sort_ascending: true
    design:
      columns: '2'
      view: article-grid    # Changed view style
      flip_alt_rows: false

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
      columns: '2'
      view: citation
      spacing:
        padding: ["20px", "0", "20px", "0"]

banner:
  caption: ""
  image: ""
---

