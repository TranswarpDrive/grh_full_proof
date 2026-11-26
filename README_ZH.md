# Dirichlet 广义黎曼猜想的 Theta 格证明

[English](README.md) | **简体中文**

本仓库收录了中英文两份数学文稿，对 Lean 项目 [lsernau/grh-lean](https://github.com/lsernau/grh-lean) 所提出的 Dirichlet 广义黎曼猜想证明进行自然语言重构。文稿由 ChatGPT 整理撰写，采用传统数学论文中的文字与公式阐述论证。

## 文稿

| 语言 | PDF | 页数 |
| --- | --- | ---: |
| 英语 | [grh_full_proof_en.pdf](grh_full_proof_en.pdf) | 538 |
| 简体中文 | [grh_full_proof_zh.pdf](grh_full_proof_zh.pdf) | 465 |

## 数学论证概要

论证所针对的命题是：Dirichlet L 函数的所有非平凡零点均位于临界线 Re(s) = 1/2 上。主要步骤包括：

1. 利用圆分 CM 域上的稀疏权重编码平滑素数余项。
2. 通过局部 theta 微分的整除性构造短自守形式，再利用 Poincaré 算子的矩估计得到近满维张成。
3. 借助晶体同余、Selmer 扭曲、特殊值比较及投影分母控制整格体积。
4. 比较体积上下界，消去公共主项，得到单侧平方根尺度的素数余项界。
5. 运用正 Laplace 变换与二次扭曲的弱零密度估计排除临界线右侧的零点，再利用函数方程完成另一侧的论证。

## 来源与署名

- 原始 Lean 项目：[lsernau/grh-lean](https://github.com/lsernau/grh-lean)。
- 所据源码版本：[`72fead102f663d5c7a407964a13dc0cf9d977207`](https://github.com/lsernau/grh-lean/tree/72fead102f663d5c7a407964a13dc0cf9d977207)。
- 文稿整理撰写：ChatGPT，2026 年 11 月 26 日。

原始数学论证归属于原项目。本仓库文稿为供研读与审查的 AI 自然语言重构，并非独立发现或对证明正确性的认证。撰写过程中未运行 Lean，文稿亦未经独立同行评议。
