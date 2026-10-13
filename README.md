# bci-learning

脑机接口（BCI）自学记录。生命科学背景，保研至中科院神经科学研究所，读研前系统补齐干实验技能与算法思维。

## 学习路线（总时长约 10–12 个月，每周 15–20 小时）

| 阶段 | 时间 | 内容 | 状态 |
|---|---|---|---|
| 认知期 | 大四上 10–11 月 | BCI 整体认知 + Python 入门 + Git/工具链 | 🔵 进行中 |
| 筑基期 | 11 月–次年 2 月 | Python 三件套（NumPy/Pandas/Matplotlib）+ 线性代数 + 概率统计 + 傅里叶/信号处理 | ⚪ |
| 算法期 | 2–5 月 | 机器学习（吴恩达或李宏毅二选一）+ PyTorch 实战 + sklearn | ⚪ |
| 专项期 | 5–8 月 | MNE-Python / EEGLAB 脑电预处理 + 公开数据集复现（CSP+SVM → EEGNet） | ⚪ |
| 衔接期 | 8 月–入学 | 读神经所意向课题组论文 + 整理复现报告 + 联系导师 | ⚪ |

## 目录结构

```
├── phase1-python/      # 第 1–2 月：Python 基础练习（小甲鱼课程配套）
├── phase2-math-dsp/    # 数学与信号处理笔记
├── phase3-ml-dl/       # 机器学习 / 深度学习练习
├── phase4-eeg/         # 脑电数据处理与数据集复现（核心成果区）
├── notes/              # 每周学习日志（每周至少 1 篇）
└── README.md
```

## 资源备忘

- **Python 入门**：B站小甲鱼《零基础入门学习Python》（爬虫/GUI 跳过）
- **科学计算**：莫烦 Python（NumPy/Pandas/Matplotlib）、北理工《Python数据分析与展示》
- **Git**：廖雪峰 Git 教程（会 add/commit/push 即可）
- **机器学习**：吴恩达 Machine Learning Specialization 或 李宏毅《机器学习》（二选一）
- **PyTorch**：刘二大人《PyTorch深度学习实践》
- **脑电工具**：MNE-Python 官方教程、EEGLAB
- **公开数据集**：PhysioNet EEG Motor Movement/Imagery、BCI Competition IV、MOABB

## 规则

1. 每天都敲代码，练习推送到对应 phase 目录
2. 每周在 `notes/` 写学习日志（学了什么、卡在哪里、下周计划）
3. 不懂的先搜报错信息，再查文档，30 分钟解决不了再求助
4. 课程只看一套，不贪多
