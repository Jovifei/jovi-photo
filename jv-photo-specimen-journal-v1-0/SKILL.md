---
name: jv-photo-specimen-journal-v1-0
description: >-
  Transform a user-supplied photo into a single standalone photo-fragment field-notes
  specimen collage poster on warm aged ivory paper. Uses actual photographic fragments,
  torn photo strips, or silhouette subject cutouts directly from the original image with
  raw hand-torn fibrous paper edges. Features subtle field-notes annotations: dotted
  trajectory lines marked with compass directions (N, S, E, W), vertical survey measurement
  scale lines with tick marks, small yellow accent blocks (■), small secondary photo disk
  cutouts, a concise poetic English title, a Chinese sub-caption with serial numbering, and
  micro archival coordinates. Outputs a single independent artwork without combining the
  source photo.
---

# 摄影标本日志 · Photo Specimen Journal v1.0

将用户提供的照片转化为**一张单独的标本日志艺术海报**。

核心信条：**不使用手绘或插画，直接将摄影拆解为纸质碎片与轮廓剪影，辅以手记线条、测量刻度与地理坐标，重构旅行者的视觉标本。**

Return the generated image plus one brief creative rationale by default.

---

## 核心视觉逻辑

本风格的独特性在于：**完全拒绝手绘插画**，使用真实的**照片撕纸碎片**（Photo Fragments）和**主体轮廓剪切**（Silhouette Cutouts）进行空间重排与标本化归档。

在暖米白/象牙色纸面中央，将原图拆解为1~3块带有**真实手撕毛边**的照片碎片或主体轮廓剪影，并配以极其精致的**田野手记标注线条**（虚线轨迹、测量刻度尺、方位节点、小黄色色彩标贴、诗意英文、中文小标题、序列号/坐标）。单图呈现为独立的撕纸拼贴画报。

---

## Decision Priority

1. **照片碎片保真**：下半部分的碎片/剪影必须由原图的真实摄影剪裁而成，保留真实的摄影质感和色彩，绝不转化为插画或矢量色块。
2. **手撕纸张边缘**：照片碎片边缘必须展现清晰的不规则手撕毛边、白色纸纤维拉丝和厚度感。
3. **田野标注与刻度系统**：必须包含精致的虚线轨迹（带 N/S/E/W 等方位指示）或垂直测量标尺线（带刻度与数字）。
4. **留白与呼吸感**：下半部分60%~75%为干净的米白纸面。
5. **双语文字与序列号**：必须配备一行诗意英文 + 一行中文短句/序列号。

---

## Standing Consent and Privacy

- 将用户提供的照片视为已获得使用同意。
- 仅将最终提示词和参考图发送给图像生成服务。
- 不浏览、保存或分享用户上传的原始素材。

---

## Step 1：建立标本卡片（Scene Card）

- **Primary Cutout（核心拆解主体）**：原图中的人物、骑行车辆、特定风景段落或标志性地貌。
- **Decomposition Mode（碎片拆解模式）**：判断选择哪种碎片拆解组合（见 Step 2）。
- **Annotation Lines（标注线条类型）**：虚线轨迹（方位节点）或 测量刻度标尺轴线（带微型数字与刻度）。
- **Poetic Caption（诗意命名）**：为场景提炼英文诗意标题与中文小小随笔。

---

## Step 2：四种碎片拆解模式（Decomposition Modes）

根据原图的构图特点，选择以下四种拆解模式之一：

### 模式A：全景横向撕条（Horizontal Strip Panorama）
- **适用**：远山、雪山、地平线、海边等大视角风景照片。
- **表现**：将照片水平撕成1~2条宽带状的撕纸碎片，上下边缘呈不规则手撕毛边。主人物或雪山包含在碎片中。
- **布局**：碎片居中横向放置。

### 模式B：主体轮廓剪影 + 背景撕纸条带（Silhouette Cutout + Background Strip）
- **适用**：人物骑车、跑步、站立于开阔草原/公路/风景中的场景。
- **表现**：主体人物及其交通工具/设备被精确沿**轮廓剪切**（上半身扣除原图背景），而下半身或下轮廓则放置在一块横向撕纸的风景/草地条带之上，营造立体破框感。
- **布局**：剪影主体跨越撕纸条带边界，悬浮于米白纸面上。

### 模式C：主体剪切 + 关联细节小片（Subject Cutout + Context Disks）
- **适用**：草原草地、人物独坐/俯卧、静物/露营场景。
- **表现**：主体人物及其紧邻地面被剪切为一块不规则撕纸基座；在其旁侧附带1~2个**圆形或椭圆形**的极小照片撕纸贴片（展示背景山石或小屋细节）。
- **布局**：主体居中，小切片附着在侧上方或右侧。

### 模式D：有机水域/地貌轮廓切片（Organic Contour Slice）
- **适用**：有弯曲河流、山峰起伏或特殊海岸线的场景。
- **表现**：水体或山体顺应其自然轮廓被切裁为有机形状的撕纸片，不同山峰或地形撕成独立的小片重叠。
- **布局**：呈自然地形标本贴片解构。

---

## Step 3：撕纸毛边与材质质感

- **撕口毛边**：照片碎片的边缘露出米白色的原始纸纤维，断口呈浅锯齿状与不规则起伏。
- **微阴影**：碎片与剪影下方投下极柔和、极浅的贴片阴影，营造2.5D纸张拼贴厚度感。
- **照片本身**：完全保持原图的高清晰度、光影和自然色彩，不改变为插画。

---

## Step 4：田野手记标注系统（Field-Notes System）

下半部分的留白区域配备极其精细的**田野考察手记**排版：

1. **虚线方位轨迹（Dashed Trajectory Line）**：
   - 碎片上方悬浮一条极细的弯曲虚线（Dotted line），标有英文方位字母（如 `N ········ S` 或 `W ········ K ········ E`）。

2. **测量刻度标尺轴线（Measurement Scale Line）**：
   - 碎片左侧或旁侧可配备一条极细的**垂直/水平测量标尺线**，带有细微的刻度线与微型数字（如 `01`, `07`, `5`），增加考察测量文献感。

3. **微型色彩标贴（Micro Color Accents）**：
   - 在角落或编号旁可配有极小的**黄色亮色小方块（■）**或标记点（如 `■ 01`），增加标本档案点缀感。

4. **主标题（Poetic English Title）**：
   - 全大写衬线体（Serif）或复古打字机字体（Typewriter Font），字距宽松。
   - 示例：`THE ROAD CONTINUES`, `THE RIVER HAS ALL DAY`, `FOLLOW THE SUNNY LIGHT`, `THE LAKE DREAMS IN BLUE`, `THE MOUNTAIN KEEPS THE LIGHT`。

5. **中文随笔与序列号（Chinese Sub-caption & Serial）**：
   - 极小的细黑体或宋体，紧跟在主标题下方或左右角落。
   - 格式：`[中文短句] — [页码/序号]`（如 `阳光不漫长 — 01 / 04`, `白云沉，慢一点 — 03 / 04`）。

6. **微型坐标/档案编码（Micro Coordinates）**：
   - 碎片角落边缘印有极小的打字机代码或数值（如 `GRASSLAND AFTER RAIN FIELD NOTE 01`）。

---

## Step 5：提示词编译规范

编译为四段英文提示词：

**段落1 - 版式与画布**：
Vertical diptych layout, upper 50% is the original photo, lower 50% is a warm ivory/aged paper field-notes specimen page.

**段落2 - 照片撕纸碎片与剪影**：
描述拆解模式（全景撕条/轮廓剪影+背景撕条/主体剪切+细节圆片/有机地形切片），强调保留原图真实摄影质感，边缘为不规则手撕白色纸纤维。

**段落3 - 田野标注与刻度系统**：
细虚线轨迹带方位节点（N/S/E）、垂直测量标尺刻度线、小黄色色彩标记块（■）、打字机微型坐标编码、柔和贴片阴影。

**段落4 - 文字与避免事项**：
全大写英文诗意标题、中文小标题与序号，明确禁止任何手绘插画、矢量色块、商业海报元素。

---

## 质量检查门（Quality Gate）

- 下半部分使用的是**真实照片撕纸碎片/轮廓剪影**，而不是手绘/矢量插画？
- 碎片边缘是否有清晰的白色手撕纸张毛边？
- 是否包含虚线轨迹（N/S/E/W）或测量刻度标尺线？
- 是否包含全大写诗意英文标题 + 中文随笔序号？
- 留白区域是否达到 60%~75%？
- 是否完全避开了插画化、动漫化或矢量简化？

---

## 硬性禁止（Hard Avoids）

- 手绘插画、水彩渲染、矢量扁平色块（必须使用原图照片碎片）；
- 没有毛边的数码蒙版硬边缘；
- 强烈的 3D 渲染效果；
- 过于拥挤的碎片排列（必须有大面积留白）；
- 商业广告 Logotypes 或现代 UI 元素。

---

## 输出格式

默认返回：

```
![Photo Specimen Journal](生成图像)

**创作思路**

[一段简短的中文说明，解释：选择了哪种照片碎片拆解模式、田野手记标注与刻度线的设定、诗意标题与随笔的含义。]
```
