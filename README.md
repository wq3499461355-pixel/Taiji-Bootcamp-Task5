# Taiji-Bootcamp-Task5

针对太极计划（Taiji Program）选拔赛任务五的完整实现。

## 📂 目录结构说明

### 1. [lisa_time_frequency](./lisa_time_frequency) (Subtask 5.1)
**子任务一：LDC 数据可视化分析**
* **功能**：读取 LDC 原始数据 (`.h5`)，通过 **WDM (小波变换)** 和 **FRFT (分数阶傅里叶变换)** 生成引力波信号的时频图。
* **核心成果**：展示了 MBHB 信号在旋近阶段的频率演化特征。

### 2. [taiji_parameter_estimation](./taiji_parameter_estimation) (Subtask 5.2)
**子任务二：MBHB 参数估计与精度分析**
* **功能**：修改采样逻辑，将观测时长从默认扩展至 **5 天** ($t_c - 4d$ to $t_c + 1d$)。
* **核心成果**：
    * 生成的 `vmbhb_example_corner.png` 展示了高精度的后验分布。
    * 通过长时相干积累，显著降低了 **啁啾质量 (Chirp Mass)** 和 **亮度距离 (Luminosity Distance)** 的测量误差。

---
