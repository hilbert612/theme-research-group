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
      columns: '2'    # 改为两列布局
      view: compact    # 使用 compact 视图以获得更类似 WoS 的效果
      flip_alt_rows: true

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
      columns: '2'    # 改为两列布局
      view: compact    # 统一使用 compact 视图
      flip_alt_rows: true

banner:
  caption: ""
  image: ""
---

