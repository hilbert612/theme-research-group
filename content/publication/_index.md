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
        tag: Featured          # Add tag filter
        featured: true         # Keep featured flag
      count: 0                # Show all featured items
      sort_by: 'weight'       # Sort by weight
      sort_ascending: true    # Show lowest weight first
    design:
      columns: '1'
      view: google_scholar
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
        exclude_featured: true   # Exclude featured articles
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '1'
      view: google_scholar
      spacing:
        padding: ["20px", "0", "20px", "0"]

banner:
  caption: ""
  image: ""
---

