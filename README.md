# 项目主要参考论文
## 1.Safe-by-design control for Euler–Lagrange systems
基于拉格朗日系统，使用ZCBF构造状态的约束，满足系统的安全
## 2.Provably Safe Control of Lagrangian Systems in Obstacle-Scattered Environments
基于拉格朗日系统，研究复杂环境下的安全控制
## 3.Computing Large Convex Regions of Obstacle-Free Space Through Semidefinite Programming
在复杂环境中构建椭圆形安全区域
## 4.High-Order Barrier Functions: Robustness, Safety, and Performance-Critical Control
研究高阶系统中的CBF的应用
## 5.Safety-Certified Consensus Control of Multi-Agent Systems Based on Finite-Time Control Barrier Function
基于CBF，研究了多智能体的一致性控制避障

# 初步实现思路
## 1.实现单智能体基于CBF的复杂环境下避障
复杂环境下构造安全区域
由安全区域构造CBF
构造QP求解控制输入
控制机器人到达目标位置
## 2.实现多智能体的编队避障（已实现）
实现编队
实现CBF避障
## 3.实现多智能体复杂环境下编队避障
