# 辫子哥哥气旋化｜生成案例与提示词

这组案例使用仓库既有的辫子哥哥 IP 参考图，统一保留：黑色蓬松发型、长辫子、友好的圆眼、黑色线稿和深色传统服饰。提示词中的“approved Bianzi Ge IP reference”指作者现有 IP 参考图，不是新增角色设定。

## 0. 横图 + 1:1 拼接展示图

- 文件：`examples/covers/cover-showcase-wide-square-2400x760-v1.png`
- 用途：在 README、Obsidian 或案例文章里并排展示两种封面规格
- 说明：这是确定性排版拼图，左侧为公众号横图，右侧为 1:1 方形拼图；不重新生成或改写原图文字。

## 1. 公众号横图封面

- 文件：`examples/covers/cover-wechat-wide-1926x816-v1.png`
- 用途：公众号横向封面
- 画面约束：左侧标题留白，右侧 IP 与卫星气旋

```text
Use case: ads-marketing. Asset type: WeChat official-account wide cover, horizontal editorial banner, no border. Input Image 1 is the approved Bianzi Ge IP reference; Input Image 2 is a previously approved Bianzi Ge cyclone illustration. Primary request: create a wide cover for the one-click cyclone transformation Skill. Keep Bianzi Ge recognizable with swept black hair, long braided ponytail, friendly face and dark traditional robe. Place the character on the right third, with a large elegant satellite-typhoon spiral flowing behind him. Reserve a clean warm-off-white area on the left for the headline. Render this exact Chinese title in very bold black Chinese sans-serif typography, split into two lines: “人出不去，图片先卷起来”. Add a single thin orange underline beneath the second line. Scene/backdrop: warm editorial paper background, deep navy and silver-white cloud bands, restrained orange brush accents. Composition/framing: wide 2.36:1 banner, strong left-to-right reading path, character and cyclone fully visible, large margins, high thumbnail readability. Style: polished ink illustration with subtle screen-print grain, playful but premium, slightly hippie without becoming psychedelic clutter. Constraints: exact title text only; no subtitle, no logo, no watermark, no extra text, no UI, no weather map labels, no lightning, no disaster imagery, preserve IP identity and clean composition.
```

## 2. 1:1 公众号拼图

- 文件：`examples/covers/cover-wechat-square-1254x1254-v1.png`
- 用途：公众号方形分享图、正文插图或卡片封面
- 画面约束：标题在上，IP 与三阶段小图在下

```text
Use case: infographic-diagram. Asset type: square 1:1 social cover collage, no border. Input Image 1 is the approved wide cover style and Bianzi Ge IP; Input Image 2 is the approved original-to-30%-60%-100% visual progression reference. Create a polished square editorial collage for the same cyclone Skill. Render the exact Chinese title “人出不去，图片先卷起来” in very bold black Chinese sans-serif type across the top third, split into two lines, with one short orange underline. Under the title, compose a clean three-part visual collage: a small but readable Bianzi Ge IP portrait integrated with a cyclone, plus three compact visual progression panels suggesting original, partial cyclone, and full cyclone transformation. Keep the panels coherent and not like unrelated stock images. Warm off-white background, deep navy and silver-white cloud textures, restrained orange accents, subtle screen-print grain. Style should match the wide cover. Composition: 1:1 square, title remains dominant and legible at thumbnail size, visual collage below, no subtitle, no logo, no watermark, no extra text, no UI, no weather map labels, no lightning, no disaster imagery.
```

## 3. 工作台里的气旋化

- 文件：`examples/ip/bianzi-ip-cyclone-desk-1086x1448-v1.png`
- 用途：正文案例、Skill 使用说明、视频转场

```text
Use case: illustration-story. Asset type: reusable no-text Bianzi Ge IP case illustration. Preserve the approved Bianzi Ge identity: swept black hair, long braided ponytail, friendly round eyes, black ink linework, dark traditional robe. Scene: Bianzi Ge sits at a small warm editorial desk, calmly looking at a single image card while a compact cyclone grows out of the card and curls around the desk. The cyclone must look like satellite cloud bands, with a clear eye and layered spiral flow. Style: hand-drawn ink illustration with subtle screen-print grain, warm off-white paper, deep navy and silver-white cloud bands, restrained orange strokes. Composition: portrait 3:4, character centered-left, clear silhouette, generous margins. No text, no labels, no logo, no watermark, no UI, no extra characters, no photorealism, no disaster mood, no lightning, no random symbols.
```

## 4. 三阶段观察

- 文件：`examples/ip/bianzi-ip-cyclone-stages-1086x1448-v1.png`
- 用途：解释 30% → 60% → 100% 的连续变化

```text
Use case: illustration-story. Asset type: reusable no-text Bianzi Ge IP case illustration. Preserve the approved Bianzi Ge identity: swept black hair, long braided ponytail, friendly round eyes, black ink linework, dark traditional robe. Scene: Bianzi Ge stands in side profile holding a small blank image card; the card dissolves into three concentric cyclone stages, with the braid echoing the same spiral motion. Make the three stages visually distinct from light partial wind to a dark complete satellite cyclone, but keep the character readable and calm. Style: editorial ink illustration, subtle hand-printed grain, warm off-white paper, navy, silver-white and small orange accents. Composition: portrait 3:4, clear side profile, balanced negative space, no text. No labels, no logo, no watermark, no UI, no extra characters, no photorealism, no disaster mood, no lightning, no random typography.
```

## 5. 迷幻嬉皮气旋

- 文件：`examples/ip/bianzi-ip-cyclone-hippie-1086x1448-v1.png`
- 用途：嬉皮气质选项、风格化案例展示

```text
Use case: stylized-concept. Asset type: reusable no-text Bianzi Ge IP case illustration. Preserve the approved Bianzi Ge identity: swept black hair, long braided ponytail, friendly round eyes, black ink linework and dark traditional robe. Scene: Bianzi Ge floats gently inside a playful psychedelic cyclone, with the braid forming a looping orbit around him; the cyclone has layered indigo, teal, coral, orange, magenta and purple cloud bands, while the eye remains a clean deep navy center. The mood is hippie, curious and life-affirming, not chaotic or dangerous. Style: hand-printed editorial illustration with visible grain, expressive ink contour lines, warm off-white negative space. Composition: portrait 3:4, centered character, bold swirling rhythm, no text. No labels, no logo, no watermark, no UI, no extra characters, no photorealism, no lightning, no disaster imagery, no random symbols or typography.
```

## 统一负面约束

- 不把 IP 画成真实人物照片。
- 不加入气象地图、预警标签、UI、按钮、二维码或随机文字。
- 不让气旋变成灾难场面；它是视觉实验和创作隐喻。
- 无文字插画必须保持可复用，不把标题、平台 Logo 或发布日期烧录进图像。
