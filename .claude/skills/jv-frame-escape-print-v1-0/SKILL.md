---
name: jv-frame-escape-print-v1-1
description: "Transform a user-supplied photo into a vertical 3:5 Frame Escape Print poster where truthful photography is contained inside a physical white photo print frame (with clean even white borders and a wider bottom border featuring camera brand text and exposure data) placed off-center against a single solid background color extracted from the scene, while ONE specific directionally charged element (hanging branches, soaring peaks, bridge arches, extending rooflines) physically breaks out through the clean frame border into the surrounding flat background with seamless continuation. Replaces the torn-paper edge of scenes-gathered-zine with a clean camera print frame and directional breakout mechanics while inheriting its complete scene-reading framework, spatial geometry, and prompt compiler. Use when the user wants a tactile photo-print aesthetic where reality escapes its white printed border into a flat tonal background field."
---

# 冲印破框 · Frame Escape Print v1.1

Create a calm, tactile poster from a supplied photo. Inheriting the full scene analysis engine, visual weight priority system, and prompt compiler structure from **scenes-gathered-zine-v1-3**, this style replaces the hand-torn paper boundary with a **clean white photo print frame** floating on a **single solid background color**, where **one directionally charged element physically breaks out through the white frame border into the surrounding background**.

Preserve the signature core tenets: **真景为锚、相框成界、破框成势、纯色成场、极简呼吸**:

- Keep the photographic scene truthful inside and outside the frame;
- Extract one single solid color from the scene's dominant color tone to form a flat, untextured background field;
- Place a crisp white photo print frame (Polaroid / developed print style) off-center on the canvas, with clean even white side/top borders and a wider bottom border displaying camera brand typography and exposure data;
- Identify the single most directionally charged element in the photo and let it physically break through the white frame border;
- Align the breakout direction strictly with the element's actual extension vector: downward hanging branches escape from the bottom border (frame shifted upper), upward soaring spires/peaks escape from the top border (frame shifted lower), lateral extending arches/bridges escape from the left or right border (frame shifted to opposite side);
- Ensure the escaping element forms a seamless, unbroken continuation of photographic reality from inside the frame to outside in the background field;
- Keep frame edges clean, sharp, and rectangular—completely free of torn paper fibers, deckled edges, or paper grain.

Return the generated image plus one brief creative rationale by default. Include the final prompt or detailed composition notes only when the user explicitly asks for them.

## Decision Priority

Resolve conflicts in this order:

1. Preserve the scene's identity and key spatial relationships.
2. Keep the photographic portion inside and outside the frame truthful, seamless, and un-stylized.
3. Identify the single most directionally charged element (escaping subject) and determine its true physical extension vector.
4. Align frame placement on the canvas directly against the escape direction (downward → escape bottom border, frame placed in upper canvas; upward → escape top border, frame placed in lower canvas; leftward → escape left border, frame placed right).
5. Extract 1 dominant solid color from the scene for the background field (100% solid flat color fill, no paper texture, no gradients, no noise).
6. Render a clean, crisp white photo print frame with precise rectangular borders (no hand-torn edges, no exposed fibers, no aging).
7. Format authentic camera brand text (FUJIFILM / NIKON / SEAGULL, etc.) and exposure metrics on the wider bottom white border.
8. Maintain clean crisp frame boundaries where the photo does not escape.
9. Add one restrained micro-text element if specified without weakening the frame-escape hierarchy.

Preserve relationships before details. Ensure structural breakout integrity before aesthetic decoration.

## Standing Consent and Privacy

- Treat a supplied reference photo plus a request to make, transform, or continue a poster as consent to use image generation; do not ask again.
- Send only the final prompt and required reference image(s) to the image-generation service.
- Do not browse, search, save, commit, upload elsewhere, or share the user's source material.
- Do not introduce unrelated personal information. Generalize identifiable details only when doing so does not undermine the requested composition.
- Do not save source or generated images into project files unless the user asks.

## Read the Photograph First

Build an internal **Scene Card**:

- **Core subjects:** the 1–2 elements that make the scene identifiable.
- **Directionally charged element (Escaping Subject):** the single element with the strongest physical extension vector (hanging branches, soaring spire, arching bridge, sweeping roofline, mountain peak, leading road).
- **Escape Vector & Frame Placement:**
  * Branches/vines/waterfalls hanging **DOWN** → escape from **BOTTOM** border → frame placed in **UPPER** canvas.
  * Spire/peak/tree canopy soaring **UP** → escape from **TOP** border → frame placed in **LOWER** canvas.
  * Bridge/roofline extending **LEFT** → escape from **LEFT** border → frame shifted **RIGHT**.
  * Path/ridge extending **RIGHT** → escape from **RIGHT** border → frame shifted **LEFT**.
- **Spatial invariants:** horizon, relative positions, scale, perspective, facing direction, path, silhouette, or overlap that must survive.
- **Dominant gesture:** gravity hanging, upward growth, perspective convergence, lateral sweep, or diagonal axis.
- **Solid Background Color Selection:** 1 dominant color extracted from the photo's atmosphere (e.g. night navy `#1E293B`, moss green `#334155`, sand beige `#E2E8F0`, terracotta `#7C2D12`, sky blue `#38BDF8`), desaturated 15–25% for a calm, flat background.
- **Visual-weight map:** weight created by area, darkness, saturation, subject placement, and frame edge tension.
- **Native camera atmosphere:** estimated camera model, lens characteristics, and existing color profile.
- **Semantic minimum:** the smallest combination of forms and relationships that keeps the photo recognizable inside and escaping the frame.

Treat the photo as the factual ground truth for both inside and outside the frame.

## Photo-Specific Prompt Compiler

Resolve these visible fields in order:

1. **Canvas:** 3:5 vertical aspect ratio, 100% solid flat background color (no paper texture, no grain), flat orthographic scan view.
2. **Attention geometry:** off-center white photo print frame position, escaping element breakout path, background quiet field, and eye movement.
3. **Scene invariants:** exact realistic photography inside the frame boundary.
4. **Photo–frame allocation:** what remains framed inside the white border and what breaks out into the solid background color.
5. **Escaping subject selection:** the exact element that physically breaks through the frame border and its seamless photographic continuation outside.
6. **Frame specification:** clean crisp white photo print border (top/sides ~10–12% width, bottom ~20–25% width), wider bottom margin with camera brand label and exposure data.
7. **Breakout mechanics:** clean rectangular border interruption where the element escapes; seamless continuation from frame interior to background field with 100% photographic realism.
8. **Solid background field:** 100% solid flat color, zero texture, zero gradients, zero paper grain.
9. **Reproduction texture:** photographic resolution, realistic lens depth, clean printed frame edges.
10. **Micro-text system:** camera brand typography on bottom white border, optional restrained English/Chinese scene caption.
11. **Mood and hard avoids:** emotional temperature and prohibited aesthetics.

Compile only instructions that can become visible pixels. Do not include design-theory explanations or internal metadata in the final prompt.

## Directional Breakout & Frame Placement System

The core visual mechanism of Frame Escape Print v1.1 relies on strictly matching the physical extension of the subject to the escaping border and frame placement:

### 1. Downward Escape (Gravity & Hanging)
- **Subject Types:** Hanging willow/flower branches (wisteria, cherry blossom), drooping vines, hanging lanterns/signs, vertical waterfalls, dripping water drops.
- **Escape Border:** **BOTTOM** border of the white frame.
- **Frame Canvas Position:** Shifted to the **UPPER** 55–65% of the canvas.
- **Cropping & Continuation Logic:** The frame interior houses the upper scene (tree trunk, roofline, upper bridge). Ground or lower water is cropped away, allowing the hanging branches or water drops to break cleanly through the bottom white border into the solid background field below.

### 2. Upward Escape (Growth & Soaring)
- **Subject Types:** Pagoda spires, clock tower tips, mountain peaks, soaring skyscrapers, upward-growing tree crowns, soaring bird flocks, upward-curving roof eaves.
- **Escape Border:** **TOP** border of the white frame.
- **Frame Canvas Position:** Shifted to the **LOWER** 55–65% of the canvas.
- **Cropping & Continuation Logic:** The frame interior houses the lower building base, street level, or mountain foot. Upper sky clutter is cropped away, letting the spire or peak break cleanly through the top white border into the solid background field above.

### 3. Leftward Escape (Lateral Extension)
- **Subject Types:** Arch bridges extending left, horizontal tree boughs, leftward rooflines, sea piers/jetties, curved shorelines.
- **Escape Border:** **LEFT** border of the white frame.
- **Frame Canvas Position:** Shifted to the **RIGHT** 55–65% of the canvas.
- **Cropping & Continuation Logic:** The frame is positioned on the right side of the canvas, giving ample background space on the left for the arch or branch to break through the left white border.

### 4. Rightward Escape (Lateral Extension)
- **Subject Types:** Flying bird flocks migrating right, highway curves sweeping right, train tracks leading right, extending branches.
- **Escape Border:** **RIGHT** border of the white frame.
- **Frame Canvas Position:** Shifted to the **LEFT** 55–65% of the canvas.
- **Cropping & Continuation Logic:** The frame is positioned on the left side of the canvas, leaving quiet background space on the right for the element to break through the right white border.

---

## Photo-Print Frame & Border Specification

Replace all hand-torn paper edge treatments from scenes-gathered-zine with a clean, physical camera print frame:

- **Border Aesthetics:** Crisp, perfectly straight, sharp rectangular white photo border (similar to a classic 35mm photo print or Polaroid border).
- **Proportions:** 
  * Top, Left, Right borders: equal width (~10–12% of photo width).
  * Bottom border: noticeably wider (~20–25% of photo height) to serve as a vintage photo margin.
- **Camera Brand & Exposure Text:**
  * Placed on the wider bottom white margin.
  * Left side: Camera Brand & Model (e.g. `FUJIFILM X-T4`, `NIKON Z 6II`, `SEAGULL DF-2000`, `HASSELBLAD 500C/M`, `CANON AE-1`).
  * Right side: Technical Exposure Data (e.g. `f/2.8  1/500s  ISO 100  35mm`).
  * Typography: Small, crisp typewriter serif or monospaced camera metadata font in dark gray or muted black (`#333333`).
- **Breakout Handoff:**
  * The white frame border remains crisp and unbroken along 3 sides.
  * Along the 4th side, the white border is cleanly interrupted ONLY where the escaping element passes through.
  * The escaping element continues beyond the white border into the solid background color with 100% photographic realism, matching the colors, lighting, and detail of the frame interior.

---

## Solid Background Color Engine (Replaces Paper Texture)

Unlike the warm beige fibrous paper texture of scenes-gathered-zine, Frame Escape Print v1.1 uses a **single solid background color**:

- **Color Extraction:** Extract 1 dominant hue from the photograph (e.g. deep slate navy `#1E293B` from a night scene, warm sand beige `#E2E8F0` from an ancient building, soft olive moss `#334155` from a foliage scene, dusk terracotta `#7C2D12` from a sunset).
- **Processing:** Lower the saturation of the extracted color by 15–25% to create a quiet, non-competing backdrop field.
- **Surface Quality:** 100% solid flat color fill. **STRICTLY PROHIBIT** paper grain, fibrous texture, canvas weave, noise filters, water stains, or color gradients.

---

## Composition System

### Flexible Layout Ranges

- **Frame Area:** Photo print frame occupies roughly 45–60% of the total poster canvas area.
- **Background Quiet Field:** Solid background color occupies roughly 40–55% of the total canvas area.
- **Escape Depth:** The escaping element extends into the background field by approximately 20–50% of the frame's height or width.
- **Single Subject Constraint:** Exactly ONE element breaks out through the frame border. Do not create multiple breakout points across different sides.

---

## Micro-Text System

Text in Frame Escape Print v1.1 is concise, quiet, and embedded within the camera print aesthetic:

### Primary Text (Camera Metadata)
- Always rendered on the bottom white margin of the photo frame.
- Includes camera model and shot settings (e.g. `NIKON Z 50  |  35mm f/1.8 1/1000s`).

### Secondary Optional Text (Editorial / Poetic Line)
- If the user supplies text, reproduce it verbatim.
- If authored, write one short line (English 5 words max, Chinese 8 characters max).
- Can be placed quietly inside the bottom frame margin or floating in a quiet corner of the solid background field.
- Font: Small typewriter serif or clean monospaced font in dark gray.

---

## Prompt Shape

Write the final generation prompt as four compact paragraphs:

1. **Canvas and Solid Background:** Vertical 3:5 aspect ratio canvas, single 100% solid flat background color (specify exact color name/hex tone extracted from photo, zero paper grain, zero texture), orthographic scan view. Explicitly state that the prompt uses the provided reference photo as ground truth.
2. **Photo Print Frame:** Off-center white photo print frame (specify direction: shifted upper/lower/left/right), crisp rectangular white borders (equal top/sides, wider bottom border), bottom margin featuring typewriter text `[CAMERA BRAND MODEL]` on left and `[EXPOSURE METRICS]` on right. Frame interior contains an exact, faithful reproduction of the provided reference photo.
3. **Escaping Subject & Directional Breakout:** Precise description of the single escaping element breaking through the [TOP / BOTTOM / LEFT / RIGHT] white border into the flat background color. Emphasize seamless photographic continuation across the border, matching realism, lighting, and detail.
4. **Reproduction Quality & Hard Avoids:** High-fidelity photographic realism both inside and outside the frame, clean crisp cut edges, zero torn paper fibers, zero paper texture, zero extra breaking elements, strict scene reproduction.

---

## Generation Workflow

1. Inspect the supplied reference photo.
2. Build the Scene Card: identify core subject, escaping element, true physical extension direction, and extract 1 solid background color.
3. Determine frame placement based on the directional breakout matrix (downward → escape bottom, frame upper; upward → escape top, frame lower; lateral → escape left/right, frame opposite).
4. Select matching camera brand and exposure data for the bottom white frame margin.
5. Compile the four-paragraph prompt (ensuring Paragraph 2 explicitly requires faithful reproduction of the reference photo).
6. Call `generate_image` with the reference photo absolute path included in `ImagePaths`.
7. Inspect the result for directional accuracy, clean frame edges, solid background fill, and seamless photographic breakout.
8. Return the generated image and a brief Chinese creative rationale.

---

## Hard Avoids

Avoid hand-torn fibrous paper edges, paper grain texture, aged paper speckles, water stains, gradients in background, centered default frame placement, multiple breaking elements, altering photographic quality into illustration/watercolor/vector, fuzzy or sticker-like breakout outlines, missing camera brand text on bottom margin, and 3D floating shadows.

---

## Output Format

By default, return:

```markdown
![Frame Escape Print v1.1](absolute-image-path-or-rendered-image)

**创作思路**

[One short Chinese paragraph explaining the escaping subject analysis, chosen breakout direction, frame placement logic, solid background color selection, and camera brand pairing.]
```
