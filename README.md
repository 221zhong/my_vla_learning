# My VLA Learning

面向 Vision-Language-Action（VLA）模型的学习与研究资料，重点覆盖机器人数据集选型、VLA 技术演化、面向 Franka 的动作建模路线，以及 Skill 一致性与跨场景复用。

## 在线阅读

**[打开 My VLA Learning 网站](https://221zhong.github.io/my_vla_learning/)**

- [开放机器人数据集综述](docs/datasets/robot-dataset-review.html)：比较主流开放数据集的观测、动作、标注及 Franka 适配价值。
- [VLA 理论与算法路线](docs/vla-theory/vla-theory-franka.html)：梳理 Diffusion、Flow Matching、Action Expert、FAST、ActionCodec、π0/π0.5 与 G0.5。
- [Skill 一致性与跨场景复用](docs/vla-theory/vla-skill-consistency.html)：比较整轨迹语言、显式 Skill 标签与自动发现 Latent Skill，包含训练目标、数据格式、模型结构、消融实验和评价指标。

在线页面：<https://221zhong.github.io/my_vla_learning/docs/vla-theory/vla-skill-consistency.html>

## 目录

```text
my_vla_learning/
├── index.html
├── assets/figures/
│   ├── robot-dataset-map.png
│   └── vla-skill-consistency-routes.png
├── docs/datasets/
│   ├── robot-dataset-review.html
│   └── robot-dataset-review.md
└── docs/vla-theory/
    ├── vla-skill-consistency.html
    ├── vla-theory-franka.html
    └── vla-theory-franka.md
```

推送到 `main` 分支后，GitHub Actions 会自动部署 GitHub Pages。
