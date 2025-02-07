---
title: Publications
type: landing
cms_exclude: true

sections:
  # 特色论文部分
  - block: collection
    id: featured
    content:
      title: Featured Publications
      text: "Our key research highlights"
      filters:
        folders:
          - publication
        featured_only: true
        exclude_featured: false    # 添加这行，确保不排除featured论文
      sort_by: 'weight'
      sort_ascending: true
    design:
      columns: '1'    # 改为单列以获得更好的布局
      view: featured_scholar  # 更改为新的视图
      flip_alt_rows: false

  # 最近论文部分
  - block: collection
    content:
      title: Recent Publications
      text: "Discover our latest research"
      filters:
        folders:
          - publication
        exclude_featured: true
      count: 0    # 显示所有论文
      sort_by: 'date'
      sort_ascending: false
    design:
      columns: '1'    # 改为单列以保持一致性
      view: scholar   # 使用类似 Google Scholar 的视图
      flip_alt_rows: false

banner:
  caption: ""
  image: ""
---

