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
        featured: true    # Use featured flag instead of tag
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
        featured: false   # Show non-featured publications
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation

banner:
  caption: ""
  image: ""
---

