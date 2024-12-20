# DDMPC
数据驱动模型预测控制（Data-driven Model Predictive Control, DMPC）是一种结合了模型预测控制（MPC）和数据驱动控制技术的先进控制方法。其核心思想是利用历史数据来消除参数失配带来的影响，并进一步提高控制性能

模型预测控制（MPC）是一种通过建立系统的动态模型，在每一个控制时刻使用这个模型来预测系统未来的行为，并基于这些预测生成一个优化控制序列的方法。然而，传统的MPC在实际应用中面临一些局限性，例如需要准确的系统模型和复杂的终端约束设计。为了克服这些限制，数据驱动模型预测控制应运而生。

数据驱动模型预测控制利用历史数据和实时信息进行系统建模和控制决策，从而避免了对精确系统模型的依赖。这种方法不仅适用于线性系统，还可以扩展到非线性系统。

