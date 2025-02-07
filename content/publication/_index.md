---
title: Publications
type: landing
view: citation
sections:
  - block: collection
    id: highlight-publications
    content:
      title: Highlight Publications
      subtitle: ''
      text: 'Featured research highlights from our group'
      filters:
        folders:
          - publication
        featured: true     # 确保这里设置为 true
        highlight: true    # 确保这里设置为 true
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: compact
      columns: '1'

  - block: collection
    id: recent-publications
    content:
      title: Recent Publications
      text: 'Our latest research publications'
      filters:
        folders:
          - publication
        featured: false    # 确保这里设置为 false
        highlight: false   # 确保这里设置为 false
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: compact
      columns: '1'
banner:
  caption: ''
  image: ''
---

