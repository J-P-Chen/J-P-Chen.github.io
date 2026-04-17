---
title: ''
summary: ''
date: 2026-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # 确认这里只写 admin，对应 authors 下的文件夹名
      username: admin
      text: ''
      headings:
        about: '关于我'
        education: '教育背景'
        interests: '研究方向'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 科学研究 (My Research)'
      subtitle: ''
      text: |-
        我的主要研究方向集中在：
        * **应急救援技术研究**
        * **3D LiDAR SLAM 感知算法**
        * **点云信息处理**
        * **人工智能技术**
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: 代表性论文 (Featured Publications)
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: 全部论文 (Recent Publications)
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
