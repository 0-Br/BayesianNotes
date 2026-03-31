# BayesianNotes

**贝叶斯方法与自助采样笔记**

> 清华大学「量子力学」课程笔记

## 内容

本笔记系统整理了概率统计中两种重要方法的理论基础与数学描述。

### 贝叶斯方法（Bayesian Methods）

回顾贝叶斯理论的发展脉络——从 Bayes 与 Laplace 的早期工作到现代贝叶斯统计的成熟。阐述先验分布、似然函数与后验分布的数学关系，推导贝叶斯公式，并讨论贝叶斯推断的核心思想：将未知参数视为随机变量，通过观测数据更新信念。

### 自助采样（Bootstrap）

介绍 Efron 于 1979 年提出的 Bootstrap 方法：从已有样本中有放回地重采样，构造统计量的经验分布，从而在不依赖参数假设的前提下进行区间估计和假设检验。给出 Bootstrap 的数学定义、采样过程及其在统计推断中的典型应用。

## 文件结构

```
├── report.tex                              LaTeX 源文件
├── report.pdf                              编译后的 PDF
└── assets/
    ├── Prior and Posterior Distribution.png 先验与后验分布示意图
    └── Bootstrap Sample.png                Bootstrap 采样示意图
```

## 编译

```bash
xelatex report.tex
```

需要 `ctex` 宏包以支持中文排版。
