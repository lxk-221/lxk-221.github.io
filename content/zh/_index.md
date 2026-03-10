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
  - block: markdown
    content:
      title: '📝 代表性论文'
      subtitle: ''
      text: |-
        <div class="publication-card" style="display: flex; gap: 1.5rem; margin-bottom: 2rem; align-items: flex-start;">
          <div style="flex-shrink: 0; width: 200px;">
            <a href="https://arxiv.org/abs/2602.05513">
              <img src="media/publications/deco-teaser.png" alt="DECO" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
            </a>
          </div>
          <div style="flex: 1;">
            <h4 style="margin: 0 0 0.5rem 0;"><a href="https://arxiv.org/abs/2602.05513">DECO: Decoupled Multimodal Diffusion Transformer for Bimanual Dexterous Manipulation with a Plugin Tactile Adapter</a></h4>
            <p style="margin: 0 0 0.5rem 0; color: #666; font-size: 0.9rem;"><strong>Xukun Li</strong>, Yu Sun, Lei Zhang, Bosheng Huang, Yibo Peng, Yuan Meng, Haojun Jiang. Shaoxuan Xie, Guocai Yao, Alois Knoll, Zhenshan Bing, Xinlong Wang, Zhenguo Sun</p>
            <p style="margin: 0 0 0.75rem 0; font-size: 0.9rem;">面向双手灵巧操作的解耦多模态扩散Transformer，配备轻量级触觉适配器。成功率达72.25%，相比基线提升21%。</p>
            <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
              <a href="https://arxiv.org/abs/2602.05513" style="padding: 0.25rem 0.75rem; background: #e3f2fd; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">arXiv</a>
              <a href="https://baai-humanoid.github.io/DECO-webpage/" style="padding: 0.25rem 0.75rem; background: #e8f5e9; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">项目主页</a>
              <a href="https://arxiv.org/pdf/2602.05513" style="padding: 0.25rem 0.75rem; background: #fff3e0; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">PDF</a>
            </div>
          </div>
        </div>

        <div class="publication-card" style="display: flex; gap: 1.5rem; margin-bottom: 2rem; align-items: flex-start;">
          <div style="flex-shrink: 0; width: 200px;">
            <a href="https://arxiv.org/abs/2602.08594">
              <img src="media/publications/mosaic-teaser.png" alt="MOSAIC" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
            </a>
          </div>
          <div style="flex: 1;">
            <h4 style="margin: 0 0 0.5rem 0;"><a href="https://arxiv.org/abs/2602.08594">MOSAIC: Bridging the Sim-to-Real Gap in Generalist Humanoid Motion Tracking and Teleoperation with Rapid Residual Adaptation</a></h4>
            <p style="margin: 0 0 0.5rem 0; color: #666; font-size: 0.9rem;">Zhenguo Sun, Bo-Sheng Huang*, Yibo Peng*, <strong>Xukun Li*</strong>, Jingyu Ma, Yu Sun, Zhe Li, Haojun Jiang, Biao Gao, Zhenshan Bing†, Xinlong Wang†, Alois Knoll (*Equal contribution, †Corresponding author)</p>
            <p style="margin: 0 0 0.75rem 0; font-size: 0.9rem;">开源的人形机器人运动追踪与遥操作全栈系统，通过快速残差适应弥合仿真到现实的差距。</p>
            <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
              <a href="https://arxiv.org/abs/2602.08594" style="padding: 0.25rem 0.75rem; background: #e3f2fd; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">arXiv</a>
              <a href="https://baai-humanoid.github.io/MOSAIC/" style="padding: 0.25rem 0.75rem; background: #e8f5e9; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">项目主页</a>
              <a href="https://arxiv.org/pdf/2602.08594" style="padding: 0.25rem 0.75rem; background: #fff3e0; border-radius: 4px; font-size: 0.85rem; text-decoration: none;">PDF</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: 精选发表
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
---
