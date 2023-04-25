# proj107-realtime-comm

构建或增强混合双操作系统实时通信

## 项目描述

在汽车/航空/机器人系统中，在强大的SoC上整合多个域是一个重要的趋势。从安全性的角度来看，这些域中的每一个都必须使用自治的操作系统（OS）独立执行。这样的系统被称为混合多操作系统的系统。通常，在常用的混合双OS系统中，实时OS（RTOS）和通用OS（general-purpose OS，GPOS）集成在一起以满足不同的需求。操作系统间通信是此类系统的关键。具体来说，服务通常是由GPOS的RTOS的任务请求的，但是要满足对RTOS的时间效率和可预测性的要求，这是一个挑战，因为通信维护的不确定性和GPOS的分时策略。

## 所属赛道

2022年全国大学生操作系统比赛的“OS功能挑战赛道”

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评选
- 请遵循“2022年全国大学生操作系统比赛”的章程和技术方案要求


## 项目导师

- 姓名：朱城城
- 邮箱：zhuchengcheng22@huawei.com

## 难度

中等

## 参考文档

https://www.sciencedirect.com/science/article/abs/pii/S1383762120300680

## 特征

- 可移植，可扩展性（在任意混合的OS都可通用）
- 高性能（通信的实时性、吞吐量、当通信文件较大时所需时间较短）
- 稳定性，确定性（不发生丢包现象）
- 内存开销较小
- 研究方向：
  - 基于业界中已有方法进行微创新，提高性能，性能的提升，可以涵盖以上特征内容
  - 完全创新，从0到1，提出全新方法，其性能可以在某个方面优于业界的性能，甚至可以所有方面都优于

## 进阶特性

- 双操作系统实时通信的涵盖上述特征较多
- 兼容OpenEuler，将相关功能模块推送至OpenEuler社区

## License

任意开源license都可

## 预期目标

特征中的要求不一定要全部完成，可以选择其中几个方向去研究，再与业界已有的方法进行对比，来体现其性能的优势。选择本项目的同学也可提出自己的新想法，得到导师认可支持后亦可加入预期目标或进阶特性。

