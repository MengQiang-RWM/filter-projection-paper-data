# 过滤与投影：大模型语义站位的条件依赖性

## 论文

- `main.pdf`：Filtering-Projection: Conditional Dependence of Semantic Stance in Large Language Models（英文版）

## 原始实验数据

本仓库包含论文《过滤与投影：大模型语义站位的条件依赖性》的全部原始对话数据。

## 数据说明

- 所有数据均为原始对话记录，未经修改
- 评分记录位于模型回复中，格式为“离散性得分：X.X”或类似表述
- 读者可直接从原始对话中提取评分

## 仓库结构

data/
├── deepseek/      # DeepSeek 对话数据
├── qianwen/       # 千问对话数据
├── doubao/        # 豆包对话数据
└── cross_model/   # 跨模型对比数据

## 复现说明

任何研究者可依据论文第3节的实验协议，在任意大语言模型上复现本研究的测量流程。

本仓库中的原始对话文件与实验协议的对应关系如下：

| 实验协议 | 对应数据文件 |
| :--- | :--- |
| 协议一：独立节点评分 | `deepseek阶段一数据.docx`<br>`千问阶段一.docx` |
| 协议二：递进追问 | `DEEPSEEK分析阶段.docx`<br>`QIANWEN分析阶段.docx`<br>`边缘词对比典型实例.docx` |
| 协议三：元认知回溯 | `千问隐藏知识挖掘.docx`<br>`千问与DEEPSEEK可复现对比.docx` |
| 可靠性检验 | `实验可靠性.docx` |
| 对照实验 | `对照组双实验小萝莉干扰.docx` |
| 豆包阶梯实验 | `豆包离散性阶梯实验.docx` |

## 许可证

MIT License

## 作者

孟强 | mengqiang.meigui@outlook.com
