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
        text: Download CV
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
      title: '📰 News'
      subtitle: ''
      text: |-
        - **Feb 2026**: Released **DECO** on arXiv - a decoupled multimodal diffusion transformer for bimanual dexterous manipulation with tactile sensing. **Xukun Li**, Yu Sun, Lei Zhang, et al. [arXiv:2602.05513](https://arxiv.org/abs/2602.05513)
        - **Feb 2026**: Released **MOSAIC** on arXiv - a full-stack system for humanoid motion tracking and teleoperation. Bo-Sheng Huang*, Yibo Peng*, **Xukun Li***, et al. (*Equal contribution) [arXiv:2602.08594](https://arxiv.org/abs/2602.08594)
    design:
      columns: '1'
  - block: markdown
    id: papers
    content:
      title: Selected Publications
      subtitle: '(*: Equal contribution, †: Corresponding author)'
      text: |-
        <p class="text-sm text-gray-500 dark:text-gray-500 -mt-2 mb-6 text-center">(*: Equal contribution, †: Corresponding author)</p>

        {{< publication
          title="DECO: Decoupled Multimodal Diffusion Transformer for Bimanual Dexterous Manipulation with a Plugin Tactile Adapter"
          authors="<strong>Xukun Li*</strong>, Yu Sun*, Lei Zhang, Bosheng Huang, Yibo Peng, Yuan Meng, Haojun Jiang, Shaoxuan Xie, Guocai Yao, Alois Knoll, Zhenshan Bing<sup>†</sup>, Xinlong Wang<sup>†</sup>, Zhenguo Sun."
          year="2026"
          type="arXiv preprint"
          abstract="A decoupled multimodal diffusion transformer for bimanual manipulation with a lightweight tactile adapter."
          image="publication/deco/featured.png"
          Project="https://baai-humanoid.github.io/DECO-webpage/"
          Arxiv="https://arxiv.org/abs/2602.05513"
          Code="https://github.com/BAAI-Humanoid/DECO"
          Dataset="https://huggingface.co/datasets/BAAI-Humanoid/DECO-50"
        >}}

        {{< publication
          title="MOSAIC: Bridging the Sim-to-Real Gap in Generalist Humanoid Motion Tracking and Teleoperation with Rapid Residual Adaptation"
          authors="Zhenguo Sun*, Bo-Sheng Huang*, Yibo Peng*, <strong>Xukun Li*</strong>, Jingyu Ma, Yu Sun, Zhe Li, Haojun Jiang, Biao Gao, Zhenshan Bing<sup>†</sup>, Xinlong Wang<sup>†</sup>, Alois Knoll."
          year="2026"
          type="arXiv preprint"
          abstract="An open-source, full-stack system for humanoid motion tracking and whole-body teleoperation with rapid residual adaptation."
          image="publication/mosaic/featured.png"
          Project="https://baai-humanoid.github.io/MOSAIC/"
          Arxiv="https://arxiv.org/abs/2602.08594"
          Code="https://github.com/BAAI-Humanoid/MOSAIC"
          Dataset="https://huggingface.co/datasets/BAAI-Humanoid/MOSAIC_Dataset"
        >}}
    design:
      columns: '1'
---
