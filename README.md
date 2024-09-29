# ai-startup

系统性的学习 AI 的相关知识的计划；主要包含：PyTorch、Hugging Face Transformers、Ray 和 MPS(Apple).

## 学习计划

> 学习计划由 OpenAI o1 生成

- [ ] 第 1-4 周：PyTorch 基础
  - [ ] 目标：掌握 PyTorch 的基本概念和操作
    - [ ] 第 1 周：
    - [ ] Day 1: 安装与环境配置
    - [ ] Day 2: 张量操作基础
    - [ ] Day 3: 自动微分与计算图
    - [ ] Day 4: 简单线性回归模型
    - [ ] Day 5: 数据加载与处理 (Dataset 与 DataLoader)
    - [ ] Day 6: 神经网络模块 (nn.Module)
    - [ ] Day 7: 实现简单的 MLP 模型
  - [ ] 第 2 周：
    - [ ] Day 8: 激活函数与损失函数
    - [ ] Day 9: 优化器与训练循环
    - [ ] Day 10: 模型评估与可视化
    - [ ] Day 11: 实现 CNN 模型
    - [ ] Day 12: 实战项目：手写数字识别 (MNIST)
    - [ ] Day 13: 模型保存与加载
    - [ ] Day 14: PyTorch 常用工具 (torchvision 等)
  - [ ] 第 3 周：
    - [ ] 深入理解 PyTorch 架构，阅读官方文档和教程
  - [ ] 第 4 周：
    - [ ] 实践项目：自己设计并实现一个小型深度学习项目
- [ ] 第 5-8 周：Hugging Face Transformers
  - [ ] 目标：掌握 Transformers 库的使用，能够加载和微调预训练模型。
  - [ ] 第 5 周：
    - [ ] Day 1: Transformers 库介绍与安装
    - [ ] Day 2: 使用 pipeline 进行简单任务 (如情感分析)
    - [ ] Day 3: 加载预训练模型 (BERT, GPT 等)
    - [ ] Day 4: Tokenizer 的使用
    - [ ] Day 5: 文本分类任务实现
    - [ ] Day 6: 微调预训练模型 (基础)
    - [ ] Day 7: 模型评估与结果分析
  - [ ] 第 6 周：
    - [ ] 深入学习 Transformers 架构和工作原理
  - [ ] 第 7 周：
    - [ ] 实践项目：使用 Transformers 进行文本生成或问答系统
  - [ ] 第 8 周：
    - [ ] 阅读 Transformers 相关论文，理解最新研究进展
- [ ] 第 9-12 周：Ray 基础
  - [ ] 目标：掌握 Ray 的基本概念和在分布式计算中的应用。
  - [ ] 第 9 周：
    - [ ] Day 1: Ray 简介与安装
    - [ ] Day 2: Ray Core 基础概念 (Actor, Task)
    - [ ] Day 3: 分布式计算示例
    - [ ] Day 4: Ray Tune 用于超参数优化
    - [ ] Day 5: 使用 Ray Tune 优化 PyTorch 模型
    - [ ] Day 6: Ray Serve 用于模型部署
    - [ ] Day 7: 部署 Transformers 模型
  - [ ] 第 10 周：
    - [ ] 深入理解 Ray 的架构和应用场景
  - [ ] 第 11 周：
    - [ ] 实践项目：使用 Ray 进行分布式训练或部署
  - [ ] 第 12 周：
    - [ ] 综合项目，结合 PyTorch、Transformers 和 Ray 实现一个完整的 AI 应用

## 环境准备

- 我的设备是 Mac M-Chip，所以代码和测试都是基于 MPS
- 开发工具主要使用 VSCode 和 JupyterLab

使用 Conda 管理本地环境以及相关依赖，环境信息保存在 [enviroment.yaml]，在不同的电脑上导入使用如下命令：

```bash
conda env create -f environment.yml
```
