# 杨思涵 · Yang Sihan

**数据分析师** ｜ 天津财经大学 · 数据科学与大数据技术 · 2027 届

![Status](https://img.shields.io/badge/2027届-秋招中-2f5de3)
![Location](https://img.shields.io/badge/天津-武清-555)
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-MySQL%20%2F%20HiveQL-4479A1?logo=mysql&logoColor=white)

[**在线作品集**](https://mason2119.github.io) ｜ 3384144812@qq.com ｜ 15620055694

---

习惯先用数据定位瓶颈，再谈策略。

做过 **272 万条埋点数据的增长归因**、**39 家医疗机构的省级项目驻点交付**、
**8,400 个观测的 A 股因子模型对比**，以及 **BERT 与 LLM 的对照实验**。
五个项目覆盖业务分析、机器学习、金融量化、统计检验、NLP —— 不是同一套方法的重复。

---

## 精选项目

### 01 · [直播平台用户行为分析与增长策略](https://github.com/mason2119/live-user-behavior-analysis)

面向 MAU 2.72 亿的出海直播平台，围绕「留存 — 转化 — 付费 — 生态」四层问题做端到端分析。

| 指标 | 结果 |
| --- | --- |
| 留存魔法数字 | 首日观看 ≥10 分钟，次日留存 25.34% → **71.48%（+46.14pp）** |
| A/B 实验 | 14,473 人实验，整体留存 **+12.48%**（P=3.95e-98） |
| 生命周期瓶颈 | 马尔可夫链定位 Engaged→Casual 转化率仅 **7%** |

`Python` `Pandas` `Scikit-learn` `马尔可夫链` `A/B 测试` `Wilcoxon`

---

### 02 · [基于 BERT 与 LLM 优化策略的学术文本分类](https://github.com/mason2119/cnki-bert-llm-classification)

仅凭论文标题判断是否发表于经济学顶级期刊，对比 BERT 微调与 LLM 递进式提示优化。

| 指标 | 结果 |
| --- | --- |
| Few-shot 准确率 | **62.00%**，较 Zero-shot 基线 +4.67pp |
| 反超 BERT | 8 个示例的零参数更新，**超过** 700 条数据 + 5 轮微调（59.33%）**2.67pp** |
| CoT 可解释性 | 特异性 54.67% → **64.00%**，假阳性 44 → 27 例 |

`PyTorch` `Transformers` `BERT 微调` `Ollama` `Qwen2.5-7B` `Few-shot` `CoT`

---

### 03 · [CAPM vs Fama-French 三因子](https://github.com/mason2119/capm-vs-fama-french)

100 只沪深 300 成分股 × 84 个月度（2018–2024），逐股回归比较两种定价模型。

| 指标 | 结果 |
| --- | --- |
| 拟合优度 | 平均 R² 0.2370 → **0.3709（+56%）**，100 只股票全部改善 |
| 因子显著性 | 市场因子 97% 显著（\|t\|=5.8）；HML 载荷 66% 显著 |
| 反直觉发现 | 拟合更好 ≠ 误差更小 —— 显著 Alpha 比例反从 10% 升到 **16%** |

`statsmodels` `因子模型` `时间序列回归` `横截面分析`

---

### 04 · [老年人生活满意度分布特征研究](https://github.com/mason2119/class2020-life-satisfaction)

CLASS 2020 的 11,304 名老年人样本，「分布检验 → 秩检验 → 相关 → Logistic」四层证据链。

| 指标 | 结果 |
| --- | --- |
| 核心效应 | 自评健康差者生活不满意几率 **OR=5.473**（95%CI 4.99–6.00） |
| 证据一致性 | K-S D=0.359 / Wilcoxon r=0.341 / Spearman rs=0.407，四层同向 |
| 零发现 | 性别在四层检验中**全部不显著**（p=0.553 / 0.098 / 0.098 / 0.291） |

`SciPy` `statsmodels` `K-S 检验` `Logistic 回归` `效应量`

---

### 05 · [银行客户流失预测：四模型对比](https://github.com/mason2119/bank-churn-prediction)

在 20.37% 流失率的不平衡数据上对比四种算法，重点是指出准确率的陷阱。

| 指标 | 结果 |
| --- | --- |
| 最佳模型 | 随机森林准确率 **0.870**、AUC **0.8521** |
| 陷阱 | 召回率仅 0.4733 —— 一半以上真实流失客户被漏掉 |
| 基线 | 「全判不流失」即可得 **79.63%**，决策树的 0.783 几乎没学到东西 |

`scikit-learn` `随机森林` `MLP` `KNN` `不平衡数据` `特征重要性`

---

## 实习

**天津健康医疗大数据有限公司 · 数据分析助理**（2025/07–2025/09，四川达州驻点）

国家传染病智能监测预警前置软件达州实施项目：覆盖 39 家医疗机构（28 公立 + 11 民营，7 个区县）上报数据质量监控，
4 类核心数据完整率均达 **100%**，推动 39 家机构「安装—部署—正式应用—转正」4 项指标全部 100%，
待处理信息及时完成率 **99.98%**，担任项目专班日报汇报人。

---

## 技术栈

| 类别 | 内容 |
| --- | --- |
| 数据处理 | Python（Pandas / NumPy）、SQL（MySQL / HiveQL）、Excel、网络爬虫 |
| 机器学习 | 逻辑回归、随机森林、MLP、K-Means、LinearSVC、马尔可夫链、超参搜索 |
| 深度学习 | PyTorch、Transformers、BERT 微调、Ollama 本地部署 LLM |
| 统计与实验 | A/B 实验、Wilcoxon、K-S 检验、卡方检验、Logistic 回归、效应量 |
| 可视化 | Matplotlib、Seaborn、Tableau |

---

## 联系

- 邮箱：3384144812@qq.com
- 电话：15620055694
- 作品集：[mason2119.github.io](https://mason2119.github.io)

> 所有仓库中的指标均可由代码与数据复现；项目来源（独立完成 / 团队 / 课程作业）在各自 README 中如实标注。
