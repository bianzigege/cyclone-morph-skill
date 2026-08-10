---
name: cyclone-morph-skill
description: "User-facing image transformation flow for “气旋三阶｜Cyclone Progression”, a universal cyclone-ization skill. Turn any single uploaded subject—portrait, person, animal, object, product, building, vehicle, logo, artwork, room, landscape, or abstract shape—through three linked stages at approximately 30%, 60%, and 100% cyclone transformation, with optional psychedelic hippie and orange-editorial visual moods. Use when the user asks to cyclone-ize, typhoon-ize, hurricane-ize, stormify, or transform an image into satellite typhoon imagery."
---

# 气旋三阶｜Cyclone Progression

## Core idea

Transform anything into a cyclone through a visible, continuous progression. Do not create three unrelated style variations and do not jump directly to the final typhoon.

- **30%｜初始气旋化**：原图最清楚，只让少数高价值区域开始云化、旋涡化。
- **60%｜中度气旋化**：原图仍然可辨认，但大部分主体结构已经进入气旋语言。
- **100%｜完全气旋化**：完全成为真实卫星台风影像，同时保留原图的视觉 DNA。

Each stage must inherit the previous stage’s center, flow, rotation direction, major band placement, and source-derived features. The transformation should read as:

```text
原图 → 局部开始气旋化 → 大部分结构气旋化 → 完全卫星气旋
```

Three stages are the default because they provide a clear visual story without overwhelming the user. If the user explicitly asks for four stages, use **20% → 45% → 70% → 100%** and preserve the same sequential inheritance.

## User flow

### 1. Accept and lock one source image

Use exactly one source image per progression. Accept any clear subject: people, faces, animals, clothing, products, architecture, vehicles, rooms, landscapes, logos, illustrations, handwriting, symbols, food, plants, or abstract textures.

If multiple images are attached or the intended source is ambiguous, ask the user to select one before proceeding. Do not silently combine sources.

If no image is attached, show:

> 欢迎使用 **气旋三阶｜Cyclone Progression**。
>
> 上传任何一张图片，我会依次生成 30%、60%、100% 三个气旋化阶段，让你看到原图如何一步步变成卫星台风。

### 2. Analyze the source before generating

Build an internal visual structure map. Record:

- subject category, silhouette, pose or arrangement, defining features, and visual center;
- dominant lines, curves, directional flow, and asymmetry;
- major light/dark masses, colors, texture, and density;
- foreground, middle ground, background, and negative space;
- at least three source signals that must survive the full progression.

Choose which features transform early and which remain as recognition anchors until later stages. Preserve visual DNA rather than making a literal cutout. Simplify only secondary clutter.

### 3. Generate the three linked stages

Generate exactly three images by default, in order. Complete and inspect each stage before using it as the reference for the next stage. Do not generate all three independently from the original source.

#### Stage 1 — 30%｜初始气旋化

Generate directly from the source. Keep approximately 70% source recognizability and 30% cyclone treatment.

- Preserve the subject’s silhouette, pose, face or object landmarks, composition, and dominant colors.
- Transform only two or three high-value regions.
- Let hair, fabric, smoke, water, brushstrokes, or long lines begin to form wispy spiral bands.
- Let the visual center or negative space begin to suggest an eye, but do not complete the eye or eyewall.
- Keep some original edges, ink lines, material cues, or background so the viewer immediately recognizes the source.

This stage is a readable bridge, not a finished satellite photograph and not a generic hurricane.

#### Stage 2 — 60%｜中度气旋化

Generate from **Stage 1 plus the original source**. Keep approximately 40% source recognizability and 60% cyclone treatment.

- Preserve the main subject relationship, but allow most outer contours and textures to become cloud bands.
- Complete the eye and begin a coherent eyewall.
- Carry Stage 1’s transformation areas forward; do not restart from a new storm center.
- Keep enough pose, silhouette, color rhythm, or signature features for the source to remain discoverable at a glance.
- Increase atmospheric depth, cloud density, and satellite realism, while allowing a hybrid source-to-storm appearance.

Stage 2 should look like the same image halfway through transformation, not a second independent style.

#### Stage 3 — 100%｜完全气旋化

Generate from **Stage 2 plus the original source as a secondary identity reference**. Keep 0% literal source appearance and 100% cyclone imagery, but preserve at least three source-derived structural signals as hidden visual DNA.

- Dissolve the literal object, person, illustration, room, or logo.
- Carry forward Stage 2’s center, rotation, eye, eyewall, and major band placement.
- Convert the remaining silhouette and material cues into cloud physics.
- Finish as a believable top-down orbital satellite photograph with a clear eye, dense eyewall, spiral rainbands, and outer cloud bands.

Use deep navy ocean or atmospheric gaps, silver-white clouds, restrained blue-grey/cyan tones, realistic cloud physics, natural asymmetry, atmospheric scattering, high dynamic range, and documentary meteorological realism. Stage 3 must feel like Stage 2 completing its transformation, never like a generic stock typhoon.

### 4. Name and present the progression

Use the fixed progression name **气旋三阶｜Cyclone Progression**. Present the images in order:

> **气旋三阶｜Cyclone Progression**
>
> **图 1｜30% 初始气旋化**  
> 原图最清楚，局部结构开始变成旋涡与云带。
>
> **图 2｜60% 中度气旋化**  
> 主体仍然可辨认，但大部分结构已经进入气旋语言。
>
> **图 3｜100% 完全气旋化**  
> 完全成为卫星台风影像，同时保留原图的结构记忆。

Default parameters:

```yaml
stage_levels: [30, 60, 100]
stage_1_preserve: high
stage_2_preserve: medium
stage_3_preserve: structural_only
storm_level: strong
scale_level: regional
output_ratio: original
satellite_realism: very_high
visual_mood: satellite_cold
```

### Optional visual mood

Use **冷峻卫星｜Satellite Cold** by default: deep navy, blue-grey, silver-white clouds, restrained cyan, documentary meteorological realism.

If the user asks for “嬉皮一点”“迷幻一点”“像 60 年代海报” or similar, use **迷幻嬉皮｜Psychedelic Hippie** across the selected stages:

- use organic hand-screen-printed or lightly grainy texture;
- use deep indigo, turquoise, teal, saffron yellow, burnt orange, coral, magenta, violet, and cream;
- keep the cyclone’s eye, eyewall, rainbands, outer bands, center, and inherited source structure;
- integrate color into the cloud flow instead of adding decorative stripes, symbols, or text;
- preserve the staged recognizability rules: 30% still shows the source, 60% remains a hybrid, 100% is fully cyclone-shaped.

Do not make the psychedelic mood the default unless requested. It should feel handmade, free-spirited, and visually warm, not like glossy neon CGI.

If the user asks for “橙线气旋”“黑白橙”“编辑台感”“像这个视觉参考” or similar, use **橙线气旋｜Orange Line Cyclone** across the selected stages:

- use white, silver-white, and pale grey as the cloud-field canvas;
- use near-black for deep cloud gaps, structural shadows, broken lines, and negative space;
- use vivid orange sparingly for the visual center, a few spiral bands, eyewall highlights, or action-signal accents;
- translate the source’s modular layout, cards, borders, alignment, wide whitespace, and editorial rhythm into storm structure;
- preserve the source-to-cyclone progression: at 30% the black/white/orange organization remains readable, at 60% it becomes a hybrid storm system, and at 100% only the organization, center, proportions, and color rhythm remain as hidden source DNA;
- if the source contains text, do not invent or add text: preserve only the original text as a temporary recognition cue at 30%, let it become non-readable line texture by 60%, and remove readable text completely at 100%.

The orange-editorial mood must still read as a cyclone with an eye, eyewall, rainbands, and outer cloud bands. It is not a UI screenshot, information poster, orange gradient, sticker collage, cyberpunk neon effect, or 3D interface render.

### 5. Ask for the next-step choice

After all three stages are shown, provide exactly these three options:

> 请选择下一步：
>
> **A｜保留更多原图**：回到 30% 阶段，进一步强化主体识别。  
> **B｜平衡深化**：以 60% 阶段为基础，继续调整原图与气旋的比例。  
> **C｜推进终态**：以 100% 阶段为基础，继续增强卫星台风质感。

Wait for the user’s choice before generating the next image. Accept `A / B / C`, “第一张 / 第二张 / 第三张”, “30% / 60% / 100%”, and natural-language equivalents. Do not expose internal parameter names.

### 6. Continue from the selected branch

- **A｜保留更多原图**: edit Stage 1 only. Keep the subject immediately recognizable and reduce cyclone coverage if needed.
- **B｜平衡深化**: edit Stage 2 only. Preserve the source’s signature features while strengthening cloud transition and the emerging eyewall.
- **C｜推进终态**: edit Stage 3 only. Increase satellite realism, storm scale, cloud density, and atmospheric drama while preserving the inherited source DNA.

If the user asks for a fourth image, use the nearest stage as the locked target and generate an intermediate refinement rather than restarting. For a four-stage flow, use 20% / 45% / 70% / 100%.

After a selected follow-up image is generated, present:

> 已完成〔30% / 60% / 100%〕阶段深化。
>
> 你可以继续：**再次深化**、**切换阶段**、**重新上传图片**，或**改成四阶段渐进**。

Interpret follow-ups as follows:

- **再次深化**: keep the current stage and make one targeted retry.
- **切换阶段**: return to the three stage choices.
- **重新上传图片**: restart from Step 1.
- **改成四阶段渐进**: regenerate the progression as 20% → 45% → 70% → 100%.

## Universal source-to-cyclone mapping

Apply the mapping appropriate to the source. Do not force every subject into a face-like eye or a perfectly circular storm.

| Source signal | 30% stage | 60% stage | 100% stage |
|---|---|---|---|
| Hair, fabric, smoke, waves, brushstrokes | A few strands begin to curl | Most strands become cloud bands | All flow becomes layered spiral cloud structure |
| Face, object, building, logo, or central mark | Preserve the form; add an emerging center | Form partly dissolves into eye and eyewall | Form disappears; center and proportions remain as storm DNA |
| Long body, road, branch, cable, or vehicle | Keep the line recognizable with a cloud edge | Convert most of the line into a dominant rainband | Carry the line into the final spiral geometry |
| Windows, gaps, negative space, or holes | Preserve the opening | Add a cloud ring and partial eye | Convert into eye opening, cloud break, or ocean pocket |
| Highlights, gloss, snow, white paper | Preserve material brightness | Turn highlights into cloud tops | Turn all highlights into convective cloud physics |
| Black ink, shadow, dark material, night | Preserve tonal blocks | Expand them into ocean and cloud gaps | Convert them into atmospheric masses and deep ocean |
| Repeated patterns, scales, bricks, beads, grain | Keep repetition readable | Start fracturing it into cloud texture | Convert it into microstructure and broken filaments |

Always carry forward the previous stage’s center, rotation direction, major band placements, and source-derived features. The final stage must contain a readable **eye + eyewall + spiral rainbands + outer cloud bands** system with asymmetry and natural breaks.

## Quality gate

Accept the progression only when:

1. Stage 1 is immediately recognizable as the original source and visibly begins transforming.
2. Stage 2 clearly sits between source and cyclone, with roughly balanced recognizability and atmospheric reconstruction.
3. Stage 3 is fully satellite-cyclone imagery, not a hybrid or illustration.
4. All stages share a coherent center, flow, rotation direction, and major structural relationship.
5. At least three source-derived signals remain discoverable in Stage 3 on closer inspection.
6. Stage 3 has coherent eye, eyewall, rainbands, outer bands, natural asymmetry, and believable cloud physics.
7. No stage contains unrelated objects, text, labels, logos, UI, watermarks, fantasy effects, or obvious CGI.

If Stage 1 is too abstract, restore source silhouette and landmarks; reduce cyclone coverage. If Stage 2 is too close to the source, transform one additional high-value region. If Stage 3 feels unrelated, regenerate it from Stage 2 and explicitly preserve its center, rotation, and band placement. Retry only the failing stage whenever possible.

## Guardrails

- Never create three unrelated style variations; stages must form one continuous transformation.
- Never make the 30% stage a finished generic cyclone.
- Never make the 60% stage skip the visible relationship with the source.
- Never make the 100% stage an unrelated stock typhoon.
- Never preserve the source as a sticker, sharp cutout, floating person, collage panel, or object above clouds.
- Avoid fantasy vortex, galaxy, black hole, portal, tornado, magic circle, oil painting, cartoon clouds, game concept art, obvious 3D render, perfect geometric spirals, excessive bloom, lens flare, text, logos, weather-map overlays, UI, and watermarks.
- Keep the progression understandable: source → 30% → 60% → 100%.
- If image generation is unavailable, return the resolved prompts and explain that no images were created; never imply success.

## Prompt assembly

Read [references/prompt-spec.md](references/prompt-spec.md) for the three staged prompts, optional four-stage mode, and branch-specific retry instructions.
