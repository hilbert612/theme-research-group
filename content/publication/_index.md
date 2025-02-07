---
title: Publications
type: landing
cms_exclude: true

sections:
  # 索引系统
  - block: tag_cloud
    content:
      title: Publication Index
      # 选择要显示的分类方式
      taxonomy: publication_types
      # 显示年份标签
      show_years: true
      # 期刊标签
      show_venue: true
    design:
      columns: '1'
      font_size_min: 0.7
      font_size_max: 1.5

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

