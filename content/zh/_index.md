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
        - **2026年2月**: 在 arXiv 更新 **DECO**. **Xukun Li***, Yu Sun*, Lei Zhang, Bosheng Huang, Yibo Peng, Yuan Meng, Haojun Jiang, Shaoxuan Xie, Guocai Yao, Alois Knoll, Zhenshan Bing<sup>†</sup>, Xinlong Wang<sup>†</sup>, Zhenguo Sun. [arXiv:2602.05513](https://arxiv.org/abs/2602.05513)
        - **2026年2月**: 在 arXiv 更新 **MOSAIC**.  Zhenguo Sun*, Bo-Sheng Huang*, Yibo Peng*, <strong>Xukun Li*</strong>, Jingyu Ma, Yu Sun, Zhe Li, Haojun Jiang, Biao Gao, Zhenshan Bing<sup>†</sup>, Xinlong Wang<sup>†</sup>, Alois Knoll. [arXiv:2602.08594](https://arxiv.org/abs/2602.08594)
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: 论文
      subtitle: '(*: 共同一作, †: 通讯作者)'
      text: |-
        <p class="text-sm text-gray-500 dark:text-gray-500 -mt-2 mb-6 text-center">(*: 共同一作, †: 通讯作者)</p>

        {{< publication
          title="DECO: Decoupled Multimodal Diffusion Transformer for Bimanual Dexterous Manipulation with a Plugin Tactile Adapter"
          authors="<strong>Xukun Li</strong>, Yu Sun, Lei Zhang, Bosheng Huang, Yibo Peng, Yuan Meng, Haojun Jiang, Shaoxuan Xie, Guocai Yao, Alois Knoll, Zhenshan Bing, Xinlong Wang, Zhenguo Sun"
          year="2026"
          type="arXiv preprint"
          abstract="面向双手灵巧操作的解耦多模态扩散Transformer，支持触觉感知。"
          image="publication/deco/featured.png"
          pdf="https://arxiv.org/pdf/2602.05513"
          arxiv="https://arxiv.org/abs/2602.05513"
          project="https://baai-humanoid.github.io/DECO-webpage/"
        >}}

        {{< publication
          title="MOSAIC: Bridging the Sim-to-Real Gap in Generalist Humanoid Motion Tracking and Teleoperation with Rapid Residual Adaptation"
          authors="Zhenguo Sun, Bo-Sheng Huang*, Yibo Peng*, <strong>Xukun Li*</strong>, Jingyu Ma, Yu Sun, Zhe Li, Haojun Jiang, Biao Gao, Zhenshan Bing<sup>†</sup>, Xinlong Wang<sup>†</sup>, Alois Knoll"
          year="2026"
          type="arXiv preprint"
          abstract="面向人形机器人运动追踪与遥操作的全栈系统，支持快速残差适应。"
          image="publication/mosaic/featured.png"
          pdf="https://arxiv.org/pdf/2602.08594"
          arxiv="https://arxiv.org/abs/2602.08594"
          project="https://baai-humanoid.github.io/MOSAIC/"
        >}}
    design:
      columns: '1'
---
