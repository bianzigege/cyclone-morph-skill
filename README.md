<div align="center">
  <img src="examples/stage-100.png" alt="完全气旋化示例" width="760">
  <br><br>
  <h1>气旋三阶</h1>
  <p>把一张图，慢慢变成一场气旋。</p>
  <p>
    <a href="SKILL.md">查看 Skill</a>
    ·
    <a href="references/prompt-spec.md">查看提示词</a>
    ·
    <a href="https://github.com/bianzigege/cyclone-morph-skill/releases/latest">下载 Skill 包</a>
  </p>
</div>

## 不是直接套一个台风滤镜

这个 Skill 会让同一张图片经过三个连续阶段：

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="examples/source.png" alt="原图" width="190"></td>
      <td align="center">→</td>
      <td align="center"><img src="examples/stage-30.png" alt="30% 初始气旋化" width="190"></td>
      <td align="center">→</td>
      <td align="center"><img src="examples/stage-60.png" alt="60% 中度气旋化" width="190"></td>
      <td align="center">→</td>
      <td align="center"><img src="examples/stage-100.png" alt="100% 完全气旋化" width="190"></td>
    </tr>
    <tr>
      <th>原图</th>
      <th></th>
      <th>30%</th>
      <th></th>
      <th>60%</th>
      <th></th>
      <th>100%</th>
    </tr>
  </table>
</div>

30% 保留原图，局部开始变成旋涡；60% 让大部分结构进入云系；100% 完全成为卫星台风，但仍然继承原图的中心、流向和明暗关系。

## 两种气质

默认是冷峻的卫星影像，也可以切换成更有手工海报和迷幻嬉皮感觉的版本。

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="examples/stage-100.png" alt="冷峻卫星风格" width="390"></td>
      <td align="center"><img src="examples/hippie-cyclone.png" alt="迷幻嬉皮风格" width="390"></td>
    </tr>
    <tr>
      <th>冷峻卫星</th>
      <th>迷幻嬉皮</th>
    </tr>
  </table>
</div>

嬉皮版本会使用更大胆的靛蓝、青绿、橙黄、珊瑚、洋红和紫色，并加入轻微的手工印刷颗粒，但气旋的眼、眼墙和旋臂结构不变。

## 使用

1. 上传一张图片。
2. 自动生成 30%、60%、100% 三个阶段。
3. 选择下一步：保留更多原图、平衡深化，或推进终态。

支持人物、动物、建筑、房间、产品、车辆、Logo、插画、植物、风景和抽象纹理。

## 文件

- [`SKILL.md`](SKILL.md) — 主流程和交互规则
- [`references/prompt-spec.md`](references/prompt-spec.md) — 三阶段提示词
- [`examples/`](examples/) — 示例图片

用户明确要求时，也可以使用四阶段：**20% → 45% → 70% → 100%**。
