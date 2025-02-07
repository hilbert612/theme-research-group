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
        featured_only: true
      sort_by: 'weight'
      sort_ascending: true
    design:
      columns: '2'
      view: article-grid
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
      count: 0    # Show all publications
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '2'
      view: article-grid    # Changed to match Featured Publications
      flip_alt_rows: false

banner:
  caption: ""
  image: ""
---

