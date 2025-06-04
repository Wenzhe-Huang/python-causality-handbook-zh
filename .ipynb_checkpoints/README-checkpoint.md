# 因果推断：献给求真敢为者

![brave-and-true](/causal-inference-book/images/brave-and-true.png)

[![DOI](https://zenodo.org/badge/255903310.svg)](https://zenodo.org/badge/latestdoi/255903310)  
[![MIT License](https://img.shields.io/badge/code-MIT-brightgreen.svg)](LICENSE)  
[![CC BY-NC-SA 4.0](https://img.shields.io/badge/translation-CC%20BY--NC--SA%204.0-blue.svg)](LICENSE-zh.md)  

> **原书名**：Causal Inference for The Brave and True  
> **原作者**：[Matheus Facure](https://github.com/matheusfacure/python-causality-handbook)  
> **中文译者**：黄文喆（Wenzhe Huang）、许文立（Wenli Xu)｜澳门城市大学金融学院  
> **联系方式**：carlzhe@outlook.com｜wlxu@cityu.edu.mo  
> **Live demo（中文版）**：<https://Wenzhe-Huang.github.io/python-causality-handbook-zh/>  
> **Live demo（英文版）**：<https://matheusfacure.github.io/python-causality-handbook/>  


## 👥 关于本译本

本项目由澳门城市大学金融学院的许文立教授与本科生黄文喆合作翻译，作为课程学习与学术研究的一部分进行。  
译文旨在帮助中文读者更好理解因果推断的核心思想与方法，并保留原书的逻辑结构与风格。  
译文仅代表译者个人理解，欢迎通过 Issues 提出修订建议。所有翻译内容遵循 CC BY-NC-SA 4.0 协议，禁止商业用途，转载请注明出处。


## 📖 如果你也在思考因果——

- 想知道为什么“看上去有效”不等于“真的有用”？  
- 想用代码复现一个 A/B 实验的逻辑？  
- 想从直觉理解 DAG，再转向回归、倾向得分、工具变量的数理框架？  
- 希望在中文语境下，读懂每一行模型背后的假设与推理？

那么，这本书，也许就是你一直在等的那一本。


## 📚 致谢与参考资料

本书的理论基础主要来自计量经济学，融合了许多学者在因果推断领域的前沿成果。核心概念与方法参考了以下代表性资料：

* [Cross-Section Econometrics](https://joshuaangrist.com/econometrics/)
* [Mastering Mostly Harmless Econometrics](https://mixtape.scunning.com/)
* [Mostly Harmless Econometrics](https://press.princeton.edu/books/hardcover/9780691120355/mostly-harmless-econometrics)
* [Mastering 'Metrics](https://www.masteringmetrics.com/)
* [Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)

这些书籍作者包括：

[Joshua Angrist](https://economics.mit.edu/faculty/angrist)、
[Alberto Abadie](https://www.hks.harvard.edu/faculty/alberto-abadie)、
[Christopher Walters](https://eml.berkeley.edu/~cwalters/)、
[Miguel Hernán](https://www.hsph.harvard.edu/miguel-hernan/)、
[Jamie Robins](https://www.hsph.harvard.edu/james-robins/)


## 🚦 翻译进度

### 第一部分（核心概念与模型） ✅ 已完成

| 章次 | 英文标题                                                | 中文标题          |
| -- | --------------------------------------------------- | ------------- |
| 01 | Introduction to Causality                           | 因果性导论         |
| 02 | Randomised Experiments                              | 随机实验          |
| 03 | Stats Review: The Most Dangerous Equation           | 统计回顾：最危险的方程   |
| 04 | Graphical Causal Models                             | 图形因果模型        |
| 05 | The Unreasonable Effectiveness of Linear Regression | 线性回归的惊人有效性    |
| 06 | Grouped and Dummy Regression                        | 分组与虚拟变量回归     |
| 07 | Beyond Confounders                                  | 超越混杂因素        |
| 08 | Instrumental Variables                              | 工具变量          |
| 09 | Non-compliance and LATE                             | 不依从性与局部平均处理效应 |
| 10 | Matching                                            | 匹配法           |
| 11 | Propensity Score                                    | 倾向得分          |
| 12 | Doubly Robust Estimation                            | 双重稳健估计        |
| 13 | Difference-in-Differences                           | 双重差分法         |
| 14 | Panel Data and Fixed Effects                        | 面板数据与固定效应     |
| 15 | Synthetic Control                                   | 合成控制法         |
| 16 | Regression Discontinuity Design                     | 断点回归设计        |

> 第一部分已全部翻译完成，内容涵盖因果推断的基础理论与经典方法，适合入门和系统学习者阅读。欢迎对术语、表达或结构提出建议。

### 第二部分（进阶方法与应用） 🚧 翻译中

| 章次 | 英文标题                                                  | 中文标题           |
| -- | ----------------------------------------------------- | -------------- |
| 17 | Predictive Models 101                                 | 预测模型入门         |
| 18 | Heterogeneous Treatment Effects and Personalization   | 异质性处理效应与个性化    |
| 19 | Evaluating Causal Models                              | 因果模型的评估        |
| 20 | Plug-and-Play Estimators                              | 即插即用估计量        |
| 21 | Meta Learners                                         | 元学习器           |
| 22 | Debiased/Orthogonal Machine Learning                  | 去偏/正交化机器学习     |
| 23 | Challenges with Effect Heterogeneity and Nonlinearity | 处理效应异质性与非线性的挑战 |
| 24 | The Difference-in-Differences Saga                    | 双重差分法的演化历程     |
| 25 | Synthetic Difference-in-Differences                   | 合成双重差分法        |

> 聚焦因果推断中的个性化建模与复杂现实问题，引入机器学习方法应对异质性、非线性与模型评估挑战。

### 附录 ⏳ 待开始
> 附录内容为原书作者后续新增章节，涉及预测、模型偏差修正与共形推断等话题，将在第二部分翻译完成后启动。

## 📜 许可协议（License）

本项目采用“双许可证”机制，分别适用于代码与翻译内容：

| 内容类型       | 适用范围               | 许可证             | 链接                                  |
| ---------- | ------------------ | --------------- | ----------------------------------- |
| 📁 代码与英文原文 | 原始 notebook、示例代码等  | MIT License     | [查看 LICENSE](./LICENSE)             |
| 📁 中文翻译内容  | `causal-inference-book/` 目录下所有文件 | CC BY-NC-SA 4.0 | [查看 LICENSE-zh.md](./LICENSE-zh.md) |

> 🔒 *MIT 允许商用与闭源再利用，只要求保留版权声明；CC-BY-NC-SA 则禁止商业用途，要求署名并采用相同许可协议传播译文。*