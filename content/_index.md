---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # 这里会去读取你个人的资料文件
      username: admin
      text: ''
      # 简历下载按钮设置
      button:
        text: 下载简历 (Download CV)
        url: uploads/resume.pdf
      headings:
        about: '关于我'
        education: '教育背景'
        interests: '研究方向'
    design:
      background:
        gradient_mesh:
          enable: true
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
        我的主要研究方向集中在**应急救援技术装备物资研究**与 **3D LiDAR SLAM** 感知算法。

        面对复杂多变的灾害场景，传统的定位与建图方法往往面临多维退化的挑战。我致力于通过引入轻量级特征增强策略、深度空频融合机制以及高效的动态目标检测算法，提升装备在极端环境下的感知鲁棒性与泛化能力。
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
