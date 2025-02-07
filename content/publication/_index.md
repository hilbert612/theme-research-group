---
title: Publications
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional banner image (relative to `static/media/` folder).
banner:
  caption: ""
  image: ""

sections:
  # Featured/Highlighted publications
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
      flip_alt_rows: false

  # Recent publications
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      count: 0
      offset: 0
      order: desc
    design:
      columns: '2'
      view: citation
---

