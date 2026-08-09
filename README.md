# 气旋三阶

这是一个把图片逐步变成气旋的 Skill。

它不会直接把一张图变成一张无关的台风图，而是按三个阶段生成：

**30% → 60% → 100%**

## 同一张图的三步变化

<table>
  <tr>
    <td><img src="examples/source.png" alt="原图" width="220"></td>
    <td><img src="examples/stage-30.png" alt="30% 初始气旋化" width="220"></td>
    <td><img src="examples/stage-60.png" alt="60% 中度气旋化" width="220"></td>
    <td><img src="examples/stage-100.png" alt="100% 完全气旋化" width="220"></td>
  </tr>
  <tr>
    <th>原图</th>
    <th>30%</th>
    <th>60%</th>
    <th>100%</th>
  </tr>
</table>

第一张里，人物还很清楚，只让头发、辫子和衣服边缘开始变成旋涡。第二张保留人物关系，但大部分结构已经变成云系。第三张完全进入卫星台风影像，只在旋转中心、旋臂走向和明暗关系里留下原图的记忆。

## 迷幻嬉皮版

气旋化不一定只有冷蓝色卫星照片，也可以保留一点 60 年代海报、手工印刷、万花筒和迷幻音乐海报的感觉。

<p align="center">
  <img src="examples/hippie-cyclone.png" alt="迷幻嬉皮气旋化示例" width="620">
</p>

这个方向会使用更大胆的靛蓝、青绿、橙黄、珊瑚、洋红和紫色，但仍然保留气旋的中心、眼墙和旋臂结构。它是可选的视觉方向，不会替代默认的冷峻卫星风格。

## 使用方式

1. 上传一张图片。
2. 自动生成 30%、60%、100% 三个阶段。
3. 从结果中选择下一步：
   - **A｜保留更多原图**
   - **B｜平衡深化**
   - **C｜推进终态**

支持人物、动物、建筑、房间、产品、车辆、Logo、插画、植物、风景和抽象纹理。

## 文件

- [`SKILL.md`](SKILL.md)：完整流程、交互规则和质量标准
- [`references/prompt-spec.md`](references/prompt-spec.md)：三阶段提示词
- [`examples/`](examples/)：示例图片

如果明确要求，也可以改成四阶段：**20% → 45% → 70% → 100%**。
