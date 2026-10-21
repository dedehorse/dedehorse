<p align="center">
  <picture>
    <source media="(max-width: 600px)" srcset="assets/hero-mobile.svg" />
    <img src="assets/hero.svg" width="100%" alt="dedehorse 的像素实验室：代码、电路与数学模型" />
  </picture>
</p>

<p align="center"><b>中南大学在读研究生 · 嵌入式 / FPGA / 数学建模 / 端侧 AI</b></p>
<p align="center">把问题写成模型，把想法做成能运行的东西。</p>

<p align="center">
  <a href="#钻研中-ing">钻研中 ing</a> ·
  <a href="#公开项目">公开项目</a> ·
  <a href="#数模档案">数模档案</a> ·
  <a href="#实验与学习">实验与学习</a>
</p>

---

Hi，我是 **dedehorse**。从智能车的摄像头、控制环和串口波形，到 FPGA、端侧 AI 与数学建模，边做边学，也把调试过程和实验边界记录下来。

**C / 嵌入式** &nbsp; · &nbsp; **Python** &nbsp; · &nbsp; **Verilog** &nbsp; · &nbsp; **控制与优化**

## 钻研中 ing

> 实验台还亮着，下面是近期正在推进的项目。

### FPGA 器材核对系统

**进行中 · 正式工程整理 / 相机冻结实验**  
推进多槽图像冻结、分类和异常图音反馈；完成实板与时序验证。

### 节奏可视学习屏

**进行中 · 面向听障学生的节拍练习原型**  
继续验证 HDMI 画面与音频、跟拍反馈和延迟校准。

<sub>两个项目均在本地开发中，记录每一次上板、调试和功能迭代。</sub>

## 公开项目

<a href="https://github.com/dedehorse/21th-smart-car-vofa"><img src="assets/vofa.svg" width="100%" alt="项目 01：智能车 VOFA+ 遥测与调参" /></a>

### 智能车 · VOFA+ 调试与控制

基于 TC387 的智能车工程，围绕赛道感知、方向与速度控制、无线遥测和在线调参展开。

**C · TC387 · VOFA+** &nbsp; / &nbsp; [查看代码与说明 →](https://github.com/dedehorse/21th-smart-car-vofa)

<a href="https://github.com/dedehorse/21th-smart-car-three-cascade-loop"><img src="assets/cascade.svg" width="100%" alt="项目 02：智能车三串级控制实验" /></a>

### 智能车 · 三串级控制实验

探索方向 / 角度、角速度与速度环的分层控制，配套图像处理和调试输出。**实验版本，实车验证尚不完整。**

**C · 控制算法 · 图像处理** &nbsp; / &nbsp; [查看代码与说明 →](https://github.com/dedehorse/21th-smart-car-three-cascade-loop)

## 数模档案

从数据处理、模型求解，到图表、论文与结果复核。

**01 / 电池退化与寿命预测** · 2026 策联杯 A 题  
数据审计、SOH 短期预测、寿命外推与不确定性分析、充电策略多目标优化。  
<sub>本地已有代码、图表与论文。</sub>

**02 / 微网与外部电网电力调控** · 2026 国赛 C 题  
调控策略建模、结果计算、图表与论文材料整理。  
<sub>本地已有代码与交付材料。</sub>

**03 / 复杂地形车机协同配送** · 湖南省研究生数模题目实践  
道路网络、无人车–无人机协同、调度与选址优化、独立结果校验。  
<sub>本地已有代码、结果与论文。</sub>

**04 / 数模工作流与工具整理**  
分析建模 → 代码出图 → 流程图 → 论文 → 验收；维护阶段报告与使用记录。  
<sub>本地工作流与 skills。这里展示简介，完整材料仍在本地整理。</sub>

## 实验与学习

<details>
<summary><b>嵌入式、FPGA 与端侧 AI</b></summary>

| 项目 | 实践内容 | 状态 |
| :--- | :--- | :--- |
| **手写识别与 STM32 部署** | MNIST / EMNIST、模型转换、X-CUBE-AI、STM32 与 PC 上位机 | 本地工程与实验 |
| **STM32H7R3 摄像头实验** | 图像采集、LCD 显示、二值化与 PC 端查看 | 板级实验与调试 |
| **H7R3 界面动画** | 像素动画帧、资源转换与 Flash 存储 | 本地界面实验 |
| **膝关节监测原型** | STM32H7 方案、模拟数据与随机森林训练 | 方案与算法原型，未完成完整系统验证 |
| **FPGA 多媒体实验** | 相机、TF 图片、HDMI 显示与音频 | 已有实板基础，继续集成验证 |
| **EDA-Robot 机器狗** | 电路、结构、固件与组装资料学习 | 第三方项目学习 / 复现资料整理 |

</details>

<details>
<summary><b>机器学习与计算机视觉</b></summary>

| 方向 | 项目与练习 |
| :--- | :--- |
| 目标检测 | YOLOv5 口罩检测：数据集整理、训练与推理工程 |
| 图像分类 | CIFAR-10 分类实验；花卉图像分类学习项目 |
| 结构化数据 | 房价预测、Titanic 生存预测学习项目 |
| 图像工具 | 二维码与条形码识别脚本 |

从基础练习开始，逐步补齐数据处理、训练、评估与部署。

</details>

<details>
<summary><b>AI 工具与工作流</b></summary>

- Codex skills 与数模流程整理：减少重复配置，让过程和结果更容易复核。
- AI 辅助写作、文档排版与演示材料制作。
- Agent、MCP 与桌面工具的配置和使用实践。

</details>

---

<p align="center"><b>Code, circuits & curiosity.</b><br /><sub>认真记录每一个跑起来的小东西。</sub></p>
