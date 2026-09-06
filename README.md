# Fine-Grained-Error-Analysis-and-Prompt-Sensitivity-in-LLM-Mathematical-Reasoning

**这是*某高校*人工智能导论的课程大作业**

## 作业要求
```
为鼓励大家接触与了解人工智能科研与实践，课程设计部分提供若干个候选任务，你可以任选其一完成
具体来说，你需要先了解该任务的主要内容和相应的评测数据集，然后要在至少 1 个数据集上跑通 1 种算法，并得到结果；
在此基础上，你还可以进一步调研更多的能够用于提升性能的方法或者自行设计算法，并进行实验分析
最后，你需要提交一份技术报告（格式参照2025NeurlPS，7页以内），我们会仿照学术会议的方式，构建一个线上提交平台，并邀请同学们担任审稿人，为其他同学进行评分。


大模型数学推理增强
Benchmark:
GSM8K
Math
参考思路：可以首先使用各种开源基座 LLM 得到评测结果，然后尝试调研提升基座模型数学推理能力的方法并试运行。
```
## 项目结构
```
paper-repo/
├── neurips_2025.tex
├── myrefs.bib
├── neurips_2025.bbl
├── neurips_2025.pdf
├── neurips_2025.sty
├── figures/
├── 原 会议模板/
├── README.md
├── LICENSE
└── .gitignore
```

## 技术报告相关

1. 在NeurIPS（2025）会议模板基础上改写，使用textlive编译运行，使用.bib作引用（所以在编译的时候需要额外点击Bib Tex）
2. 主要研究了llm对于数学问题回答准确率的影响因素，包括同一种提示词下llm回答的稳定性，qwen-plus、qwen-turbo在 No-CoT,Zero-shot-CoT, Few-shot CoT 三种不同提示词下回答的表现
3. 发现了GMS8K数据集存在题目水平的错误

## 说明
```diff
- 本项目的技术报告仅仿照NeurIPS，格式并不完全符合
! 个人观点，转载请说明出处
+ 若有大神愿意指点修改，感激不尽
```
