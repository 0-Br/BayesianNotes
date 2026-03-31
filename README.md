# BayesianNotes

贝叶斯方法与自助采样笔记 | Notes on Bayesian Methods & Bootstrap — 清华大学《量子力学》课程笔记

## 内容

本笔记用 LaTeX 撰写，涵盖以下两个主题：

1. **贝叶斯方法（Bayesian Methods）** — 发展历史、数学描述（先验分布、后验分布、似然与贝叶斯公式）及核心理解
2. **自助采样（Bootstrap Sample）** — 定义、数学描述及统计推断中的应用

## 文件结构

```
.
├── report.tex          # LaTeX 源文件
├── report.pdf          # 编译后的 PDF
└── assets/             # 插图
    ├── Prior and Posterior Distribution.png
    └── Bootstrap Sample.png
```

## 编译

```bash
xelatex report.tex
```

需要安装 `ctex` 宏包以支持中文排版。
