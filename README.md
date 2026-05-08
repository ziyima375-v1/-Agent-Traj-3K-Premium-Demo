# 🚀 Agent-Traj-3K-Premium-Demo
100 High-Quality multi-language agentic trajectories with CoT and environment feedback for RLHF.
(100条极品多语言 Agent 强化学习轨迹闭环 Demo)

## 🌟 What makes this dataset different? (本数据的核心壁垒)

Most datasets in the market are either static SFT code snippets or hallucinated bugs without real-world context. This dataset is generated via a highly concurrent **Dynamic State Machine Engine** with strict validation.
(市面上的数据多为静态代码或幻觉伪造。本数据由独家研发的高并发动态状态机引擎生成。)

1. **100% Real-World Bugs**: Derived from real GitHub Commits. The model must locate bugs in massive, uncommented files across Python, Java, JS, PHP, etc. 
2. **Golden Self-Correction Trajectories**: Contains valuable PRM negative feedback. When the model makes a wrong edit, the sandbox throws a mock error, forcing the model to rethink in `<thinking>` tags.
3. **Iron-fist Delta Validation**: (AST-level comparison). The sandbox ONLY approves the edit if the new code logic is strictly closer to the historical human Ground-Truth fix. **Survival rate is only 8.7%.**

## 📦 What's inside?
This repository contains `Open_100_Demo.jsonl`, which is a randomly extracted sample of 100 trajectories. 

You can directly use this to fine-tune your 7B/14B code models to experience an immediate boost in SWE-bench scores.

## 💼 Commercial Licensing (商业合作)
The full **Curated Premium Pack** contains **2,900+** highly purified, multi-language trajectories. We also offer customized DaaS (Data as a Service) to run trajectory generation on your private enterprise codebase (1M+ capacity).

For purchasing the full 2.9K pack or enterprise customization, please contact:
**WeChat:** `[18535506004]`
