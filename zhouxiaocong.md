# PCB 设计知识总结

PCB（Printed Circuit Board，印制电路板）是电子设备的核心组成部分。

## 核心设计流程与要点

1. **原理图 (Schematic)**: 确保电气连接逻辑正确。
   - 技巧：掌握网络标签、批量属性编辑等。
2. **布局 (Layout)**:
   - 栅格系统：利用 Snap System 进行精准对齐。
   - 模块化：根据电路功能（如电源、信号处理）进行分区。
3. **布线 (Routing)**:
   - 线宽计算：根据电流大小决定（如 20mil 对应电流承载能力）。
   - 地平面：模拟地与数字地的分割与单点连接。
   - 开尔文连接：在精密采样电路中使用四线制走线。
4. **规则检查 (DRC)**: 确保间距、线宽等符合代工厂工艺。
5. **输出**: Gerber 文件是生产的标准格式。

## 推荐学习资源（来自收藏夹）

- [原理图设计技巧 (Altium Designer)](https://www.altium.com/cn/documentation/altium-designer/schematic-placement-editing-techniques?version=18.1#e2dece9d78363e516cbc1606d5b1ec7d)
- [PCB 栅格系统说明](https://www.altium.com/cn/documentation/altium-designer/pcb-cursor-snap-system)
- [电流与线宽/过孔的关系表](https://blog.csdn.net/ADHEREVICTOR/article/details/101040590)
- [PCB 布局布线实战规则](https://blog.csdn.net/zhi_Alanwu/article/details/127588384)
- [Gerber 文件输出指南](https://www.jlc.com/portal/server_guide_10171.html)
- [PCB 开尔文走线设计](https://wiki.lceda.cn/zh-hans/design-production/pcb-design/knowledge-point/pcb-kelvin-connection.html)
- [模拟地与数字地隔离技术](https://www.cnblogs.com/wangyongming/archive/2010/10/06/an.html)
