# 分割

## 前言

自动驾驶感知解决方案不仅涉及目标检测，还包括分割。这两个解决方案经常结合使用，以提供对环境更全面的理解。车辆分割通常是语义分割的一个子任务，因为它不仅涉及定位物体，还涉及对图像中的每个像素进行分类。这些结果可用于识别车辆周围环境中的不同物体，如道路、行人、车辆、建筑物等。

语义分割的结果还可以帮助系统识别障碍物的位置和类型，使得在路径规划过程中能够考虑避障策略。系统可以选择系统地绕过障碍物或分析语义信息来选择更安全的绕行路线。

- 基于摄像头
- 基于激光雷达
- 基于融合

## 基于摄像头

### 车辆分割

车辆分割是自动驾驶中的一项任务，旨在从图像或视频中精确分离出车辆所占的区域。其结果可以为自动驾驶系统提供关键的感知信息，帮助车辆理解周围环境并做出适当决策。

::: tip NOTE
基于BEV（Bird's Eye View，鸟瞰图）的算法已在ISSPA中进行了模拟测试，并将尽快与代码仓库同步。
:::