---
title: ''
summary: ''
date: 2026-01-01
type: landing

design:
  spacing: '6rem'

sections:
  # 1. 个人基础信息与简介 (直接替代原先会报错的 resume-biography 模块)
  - block: markdown
    content:
      title: 'Jiaping Chen'
      subtitle: 'Ph.D. Researcher'
      text: |-
        <style>
          /* 强制突破模板默认的排版宽度限制 */
          .prose { max-width: 1000px !important; }
          .article-style { max-width: 1000px !important; }
        </style>
        
       🏢 **Affiliation:** National Institute of Natural Hazards, Ministry of Emergency Management

       💻 **Major:** Electronic Science and Technology

    design:
      columns: '1'
      background:
        gradient_mesh:
          enable: false

  # 2. 教育背景 (直接以列表形式展示)
  - block: markdown
    content:
      title: '🎓 Education'
      text: |-
        * **Ph.D. in Electronic Science and Technology** *Beijing University of Technology*

    design:
      columns: '1'

  # 3. 科学研究方向
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My main research interests are focused on:
        * **Emergency Rescue Technology**
        * **3D LiDAR SLAM Perception Algorithms**
        * **Point Cloud Information Processing**
        * **Artificial Intelligence Technology**
    design:
      columns: '1'

  # 4. 发表论文 (彻底弃用自动关联，直接硬编码列出你提供的文章，隐去作者列表)
  - block: markdown
    content:
      title: '📝 Publications'
      text: |-
        * **Small but mighty: A Lightweight Feature Enhancement Strategy for LiDAR Odometry in Challenging Environment**. *Remote Sensing*.

        * **An Intelligent Measurement Method and System for Vehicle Passing Angles**. *Applied Sciences-Basel*.
          
        * **Deep Spatial-Frequency Fusion for Loop Closure Descriptor Construction**. *Measurement Science and Technology*.

        * **An Efficient Network for 3D Point Cloud Moving Object Detection in Autonomous Driving Environments**. *Intelligent Service Robotics*.
    design:
      columns: '1'
---
