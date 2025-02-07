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
        categories:
          - Featured Research
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
        exclude_categories:
          - Featured Research
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation

banner:
  caption: ""
  image: ""
---

