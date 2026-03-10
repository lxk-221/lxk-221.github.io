---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载简历
        url: uploads/XuKun_Li_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: backgrounds/stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📰 动态'
      subtitle: ''
      text: |-
        - **2026年2月**: 在 arXiv 发布 **DECO** - 面向双手灵巧操作的解耦多模态扩散Transformer，支持触觉感知。**Xukun Li**, Yu Sun, Lei Zhang, et al. [arXiv:2602.05513](https://arxiv.org/abs/2602.05513)
        - **2026年2月**: 在 arXiv 发布 **MOSAIC** - 人形机器人运动追踪与遥操作的全栈系统。 Bo-Sheng Huang*, Yibo Peng*, **Xukun Li***, et al. (*Equal contribution) [arXiv:2602.08594](https://arxiv.org/abs/2602.08594)
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 论文
      subtitle: '(*: 共同一作, †: 通讯作者)'
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: list
      columns: 1
---
