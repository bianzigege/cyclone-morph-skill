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

## 三种气质

默认是冷峻的卫星影像，也可以切换成迷幻嬉皮或黑白橙的编辑台气旋感。

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="examples/stage-100.png" alt="冷峻卫星风格" width="390"></td>
      <td align="center"><img src="examples/hippie-cyclone.png" alt="迷幻嬉皮风格" width="390"></td>
      <td align="center"><img src="examples/reference-orange-editorial-cyclone.png" alt="橙线气旋视觉参考" width="390"></td>
    </tr>
    <tr>
      <th>冷峻卫星</th>
      <th>迷幻嬉皮</th>
      <th>橙线气旋</th>
    </tr>
  </table>
</div>

嬉皮版本会使用更大胆的靛蓝、青绿、橙黄、珊瑚、洋红和紫色，并加入轻微的手工印刷颗粒，但气旋的眼、眼墙和旋臂结构不变。

新增的 **橙线气旋｜Orange Line Cyclone** 借用编辑台的白底、黑色结构线、模块秩序和少量橙色行动信号，再把它们逐级卷入同一个气旋中心。参考图只提供色彩与结构气质，最终 100% 阶段不会保留 UI、按钮或可读文字。

<div align="center">
  <img src="examples/reference-orange-editorial-cyclone.png" alt="橙线气旋视觉参考" width="760">
</div>

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

## 辫子哥哥气旋化案例

这组案例把 Skill 的视觉语言延伸到作者自己的 IP：保留辫子、黑色线稿和传统服饰，再让气旋成为角色的环境、动作和结构的一部分。

### 带标题封面

<div align="center">
  <img src="examples/covers/cover-wechat-wide-1926x816-v1.png" alt="公众号横图封面" width="900">
  <br><br>
  <img src="examples/covers/cover-wechat-square-1254x1254-v1.png" alt="公众号方形拼图封面" width="520">
</div>

### 无文字 IP 插画

<div align="center">
  <table>
    <tr>
      <td><img src="examples/ip/bianzi-ip-cyclone-desk-1086x1448-v1.png" alt="辫子哥哥在工作台进行气旋化创作" width="260"></td>
      <td><img src="examples/ip/bianzi-ip-cyclone-stages-1086x1448-v1.png" alt="辫子哥哥观察三阶段气旋" width="260"></td>
      <td><img src="examples/ip/bianzi-ip-cyclone-hippie-1086x1448-v1.png" alt="迷幻嬉皮气旋中的辫子哥哥" width="260"></td>
    </tr>
  </table>
</div>

对应的生成提示词与使用说明见 [`references/generated-case-prompts.md`](references/generated-case-prompts.md)。
