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
        tag: Featured      # 添加标签过滤
        featured: true     # 保持 featured 标记
      sort_by: 'weight'
      sort_ascending: true
    design:
      columns: '2'
      view: citation
      flip_alt_rows: false

  # Recent publications section
  - block: collection
    content:
      title: Recent Publications
      text: "Discover our latest research"
      filters:
        folders:
          - publication
        exclude_featured: true   # 排除 featured 文章
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '2'
      view: citation

banner:
  caption: ""
  image: ""
---

