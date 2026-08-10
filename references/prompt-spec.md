# Cyclone Progression staged prompt specification

The outputs are a single continuous transformation. Generate sequentially: original source → Stage 1 → Stage 2 → Stage 3. Never generate each stage independently from the original.

## Stage 1 — 30% Initial Morph

```text
Edit the single uploaded source image into the first, readable stage of cyclone transformation. Preserve approximately 70% of the source and transform approximately 30% into cyclone structure.

Keep the original subject immediately recognizable: [subject], [silhouette], [pose or arrangement], [main color blocks], and [key landmarks]. Transform only these high-value regions first: [region 1], [region 2], and optionally [region 3]. Let [hair / fabric / smoke / waves / brushstrokes / long line / central mark] begin to form wispy spiral cloud bands. Let [visual center or negative space] suggest an emerging eye, but do not complete the eye or eyewall.

Keep original edges, material cues, linework, and negative space visible so the viewer can clearly understand what is changing. Create an organic hybrid, not a collage, sticker, or finished satellite photograph. Original framing and composition must remain unchanged.

Use restrained deep navy, blue-grey, silver-white, and subtle cool cyan atmospheric accents. Avoid full abstraction, generic hurricane imagery, fantasy vortex, galaxy, portal, black hole, tornado, perfect geometric spiral, unrelated objects, text, logos, UI, watermark, excessive glow, and obvious CGI.
```

## Stage 2 — 60% Medium Morph

```text
Edit Stage 1 as the primary bridge image, with the original source as a secondary identity reference. Continue the exact transformation; do not restart from a new composition or storm center. Preserve approximately 40% source recognizability and transform approximately 60% into cyclone structure.

Carry forward Stage 1’s [center], [rotation direction], [first transformed regions], and [major visual anchors]. Keep the source’s most recognizable [silhouette / pose / landmark / color rhythm] visible, but allow most outer contours, textures, hair, fabric, or long lines to become layered cloud bands. Complete the eye and begin a coherent asymmetric eyewall. Increase cloud density, atmospheric depth, and satellite realism while retaining a readable source-to-storm hybrid.

The result must look like the same image halfway through transformation, not an independent style variation. Preserve original aspect ratio. Avoid a finished generic typhoon, unrelated objects, text, logos, UI, watermark, fantasy vortex, perfect symmetry, excessive glow, and obvious CGI.
```

## Stage 3 — 100% Full Cyclone

```text
Edit Stage 2 as the primary bridge image, with the original source as a secondary identity reference. Complete the exact transformation begun across the previous stages. Carry forward Stage 2’s [storm center], [rotation direction], [eye and eyewall placement], [major cloud bands], and at least three source-derived structural signals.

Dissolve all literal source appearance—person, object, room, illustration, logo, clothing, face, or linework—into physically believable atmospheric structure. Preserve the source only as hidden visual DNA in the storm’s center, proportions, flow, tonal rhythm, and cloud-band arrangement.

Create a fully coherent top-down orbital meteorological satellite photograph: clear natural eye, dense asymmetric eyewall, layered spiral rainbands, broad outer cloud bands, realistic cloud physics, natural atmospheric scattering, high dynamic range, deep navy ocean or atmospheric gaps, silver-white cumulonimbus clouds, restrained blue-grey/cyan tones, documentary realism, immense regional scale, cold powerful mood, original aspect ratio.

The final image must feel like Stage 2 completing its transformation, not like a generic stock cyclone. Avoid fantasy vortex, galaxy, black hole, portal, tornado funnel, cartoon, anime, line art, ink texture, obvious CGI, excessive glow, lens flare, text, logos, weather-map UI, watermark, and unrelated objects.
```

## Optional four-stage mode

When the user explicitly requests four images, use these levels and inherit each image from the previous one:

```text
20% → 45% → 70% → 100%
```

Do not simply split the final prompt into four copies. The 20% stage preserves almost all of the source; 45% introduces a clear hybrid; 70% is nearly atmospheric; 100% is the full satellite cyclone.

## Optional mood modifier

Use the default satellite mood unless the user explicitly asks for a psychedelic, hippie, or orange-editorial direction.

```text
Visual mood: optional 1960s psychedelic hippie poster sensibility, organic hand-screen-printed grain, flowing tie-dye color transitions, deep indigo, turquoise, teal, saffron yellow, burnt orange, coral, magenta, violet, and cream. Integrate the colors into the cyclone’s cloud flow and preserve the eye, eyewall, rainbands, outer bands, inherited center, and source-derived structure. No text, logos, decorative symbols, glossy neon CGI, or unrelated objects.
```

### Orange Editorial Cyclone

Use this mood when the user refers to **橙线气旋｜Orange Line Cyclone**, a black-white-orange editorial workbench feel, or the supplied visual reference.

```text
Visual mood: orange-editorial cyclone, with a bright white, silver-white, or pale grey cloud-field canvas; near-black structural shadows, deep cloud gaps, broken lines, and negative space; and vivid orange used sparingly as the visual center, a few spiral bands, eyewall highlights, or action-signal accents. Translate the source’s modular editorial rhythm—cards, borders, alignment, wide whitespace, labels, and sectioning—into storm geometry. At 30%, keep the black/white/orange organization and source layout readable while only local lines, borders, or accents begin to curl. At 60%, let most modules dissolve into one inherited storm center and coherent cloud flow. At 100%, remove readable UI, buttons, logos, and text; preserve only the source’s center, proportions, spacing rhythm, and color relationship as hidden visual DNA. The result must still be a believable cyclone with eye, eyewall, rainbands, and outer cloud bands. No orange gradient, sticker collage, information poster, cyberpunk neon, 3D interface, random icons, or invented text.
```

## Follow-up prompts

### A — Preserve more source

```text
Edit the selected lower-stage image only. Restore [specific source anchors] and reduce cyclone coverage while keeping the transformation visible. Preserve the existing composition and do not create a finished generic satellite cyclone.
```

### B — Balance at 60%

```text
Edit the 60% stage only. Preserve the source’s signature features while strengthening the cloud transition, emerging eye, eyewall depth, and atmospheric realism. Keep the inherited center and band flow unchanged.
```

### C — Push to 100%

```text
Edit the 100% stage only. Increase satellite realism, cloud density, eyewall depth, and atmospheric scale while preserving the inherited center, rotation, major band placements, and at least three source-derived structural signals. Do not create a generic stock typhoon.
```

## Selection copy

After the three stages are returned, show:

```text
请选择下一步：

A｜保留更多原图：回到 30% 阶段，进一步强化主体识别。
B｜平衡深化：以 60% 阶段为基础，继续调整原图与气旋的比例。
C｜推进终态：以 100% 阶段为基础，继续增强卫星台风质感。
```
