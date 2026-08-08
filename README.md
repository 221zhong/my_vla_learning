# My VLA Learning

面向 Vision-Language-Action（VLA）模型的学习与研究资料，重点覆盖机器人数据集选型、VLA 技术演化以及面向 Franka 的动作建模路线。

## 在线阅读

**[打开 My VLA Learning 网站](https://221zhong.github.io/my_vla_learning/)**

- [开放机器人数据集综述](docs/datasets/robot-dataset-review.html)：比较主流开放数据集的观测、动作、标注及 Franka 适配价值。
- [VLA 理论与算法路线](docs/vla-theory/vla-theory-franka.html)：梳理 Diffusion、Flow Matching、Action Expert、FAST、ActionCodec、π0/π0.5 与 G0.5。

## 目录

```text
my_vla_learning/
├── index.html
├── assets/figures/robot-dataset-map.png
├── docs/datasets/
│   ├── robot-dataset-review.html
│   └── robot-dataset-review.md
└── docs/vla-theory/
    ├── vla-theory-franka.html
    └── vla-theory-franka.md
```

推送到 `main` 分支后，GitHub Actions 会自动部署 GitHub Pages。
