# jovi-photo · AI 摄影艺术转化 Skill 统一套件库

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AGY Skills](https://img.shields.io/badge/Antigravity-Skills-blueviolet.svg)](https://github.com/Jovifei/jovi-photo)

**`jovi-photo`** 是一套专门面向 AI 编码助手（Google Antigravity、Claude Agentic IDE）与图像生成引擎打造的**摄影艺术转化 Skill 套件**。

本仓库**仅跟踪与维护全新重构创新的 `jv-` 前缀核心 Skill 目录**，为您提供从照片手撕拼贴、极简形体提炼、田野考察标本到冲印破框构图的全套艺术转换方案。

---

## 📌 仓库目录结构 (Repository Structure)

仓库仅跟踪核心自定义 Skill 与说明文档，干净无冗余：

```text
jovi-photo/
├── README.md                           # 统一套件说明与使用指南
├── .gitignore                          # 忽略非跟踪文件
└── .claude/
    └── skills/
        ├── jv-torn-world-portal-v1-0/      # 1. 现实撕裂传送门
        ├── jv-scene-essence-minimal-v1-0/   # 2. 场景极简精粹
        ├── jv-photo-specimen-journal-v1-0/ # 3. 摄影标本日志
        ├── jv-chromatic-gesture-zine-v1-0/ # 4. 高彩轨迹拼贴纸刊
        └── jv-frame-escape-print-v1-0/     # 5. 冲印破框
```

---

## 🔗 借鉴与学习的 4 个基准 Skill

在开发 **`jv-`** 系列 Skill 时，我们深度学习并借鉴了开源社区中 4 个优秀 Skill 的色彩逻辑、留白率与排版架构。为保持仓库简洁，借鉴的 Skill 不保存在本仓库代码中，请参考原开源地址：

1. **`gc-minimal-zine-poster-v0-1`** (日韩极简 Zine 海报)
   - *借鉴点*：四段式 Standard Prompt 编译器架构、大面积米白纸面留白 (70%+ 空置率)、高饱和度色彩锚点约束。
   - *参考链接*：[Antigravity / Claude Skills Community]
2. **`photo-abstract-editorial`** (摄影与抽象双联画报)
   - *借鉴点*：上下/左右双联画报版式、真实摄影与抽象几何色块对齐解构。
   - *参考链接*：[Antigravity / Claude Skills Community]
3. **`scene-distillation-zine-v1-3`** (场景纯插画提炼)
   - *借鉴点*：将繁复树叶、建筑纹理、人群压缩为少数安静大面积形体的提炼法则。
   - *参考链接*：[Antigravity / Claude Skills Community]
4. **`scenes-gathered-zine-v1-3`** (拾景纸刊·手撕拼贴)
   - *借鉴点*：真实照片手撕纸边缘（手撕白色纤维拉丝）与手记排版系统。
   - *参考链接*：[Antigravity / Claude Skills Community]

---

## 🎨 `jv-` 统一前缀 Skill 深度详解与最佳使用指南

所有新创作 Skill 均采用 **`jv-`** 统一前缀（简短且具识别度）。以下是 5 个 Skill 的详细视觉法则、最佳适用照片与推荐 Prompt。

---

### 1. `jv-torn-world-portal-v1-0` · 现实撕裂传送门

#### 📖 视觉美学法则
物理性撕开真实照片，露出暗藏在撕口内部、下方或背后的**手绘水彩/版画平行世界**。
- **三种叙事模式**：
  1. *暗藏世界揭示*（撕开显现水下雪怪、机械结构、剖面空间）
  2. *奇幻世界延伸*（撕开延伸出卡通天空、游乐场、透视路标）
  3. *微观内构剖析*（撕开展示建筑/设备内部透视图）
- **核心逻辑**：照片主体可跨越撕裂边界同时存在于两个世界。

#### 📷 最佳推荐适用照片
- 具有明确**撕裂裁切线**的照片：车轮弧线、路标斜线、建筑剖面、海岸线、水面与陆地交界线。
- 画面叙事感强、主体突出（如汽车、摩托车、摩天轮、雪山湖泊）。

#### 💬 最佳 Agent 对话 Prompt
> *"使用 $jv-torn-world-portal-v1-0，分析这张照片的撕口位置，顺着路标/车轮的线条撕开照片，露出背后奇幻的手绘水彩平行世界。"*

---

### 2. `jv-scene-essence-minimal-v1-0` · 场景极简精粹

#### 📖 视觉美学法则
将照片精粹提取为最少的几何色块与结构线条，支持**上下双联**或**左右并排**：
- **五种渲染手法**：几何色块(A) + 结构线条(B) + 水彩淡洗(C) + 有机团簇(D) + **径向透视几何排列(E)**。
- **单色彩锚点规则**：整图仅保留 1 个最鲜艳的强色（如朱红斜坡、金色塔尖、暗红瓦片），占面积 1~5%，其余中性色柔和化。
- **空间结构保留**：完整保留原图的同心圆天井仰视、斜向透视消点与天际线骨架。
- **文字系统**：左下角诗意英文主标题 + 斜体副标题（如 `Sky Held by Walls / Light rises, and the courtyard breathes.`）。

#### 📷 最佳推荐适用照片
- 城市天际线、高迪式同心圆天井仰视、寺庙塔楼、斜向透视鸟瞰街景、蓬皮杜类钢架工业建筑。

#### 💬 最佳 Agent 对话 Prompt
> *"使用 $jv-scene-essence-minimal-v1-0，采用左右并排/上下双联版式，保留原图的径向透视骨架，提取一个朱红/金色色彩锚点，生成场景极简海报。"*

---

### 3. `jv-photo-specimen-journal-v1-0` · 摄影标本日志

#### 📖 视觉美学法则
**完全拒绝手绘插画**！直接使用原图真实照片的**撕纸碎片与轮廓剪影**进行标本化归档：
- **四种碎片拆解模式**：
  1. *全景横向撕条*（宽幅风光撕切）
  2. *轮廓剪影 + 背景条带*（人物手撕突破剪影悬浮）
  3. *主体剪切 + 细节圆片*（附带圆形小切片）
  4. *有机地貌切片*（河流/山体自然轮廓切片）
- **田野手记标注**：虚线轨迹带方位节点 (`N ····· S`)、**垂直测量刻度标尺线 (`01`, `07`, `5`)**、黄色档案标贴 (`■ 01`)、微型坐标与双语随笔序号 (`阳光不漫长 — 01/04`)。

#### 📷 最佳推荐适用照片
- 旅行风光、草原骑行/独坐人像、河畔靠坐、公路与自然考察照片。

#### 💬 最佳 Agent 对话 Prompt
> *"使用 $jv-photo-specimen-journal-v1-0，将这张照片中的人物切出轮廓剪影，配上测量刻度尺与方位虚线轨迹，制作一张旅行标本日志页。"*

---

### 4. `jv-chromatic-gesture-zine-v1-0` · 高彩轨迹拼贴纸刊

#### 📖 视觉美学法则
真景照片局部位居大面积暖米色纸面（70%+ 留白），周围环境简化为**半调网点 (Halftone Dots)**、**版画色块 (Woodblock)** 或干刷笔触：
- **高彩轨迹跨界**：一条高饱和度/荧光感的高彩线条（洋红/宝蓝/朱红/亮粉）**物理性横跨手撕照片边缘**，连接照片实景、纸面插画与打字机微字。
- **打字机微字**：一行 3~5 个单词的打字机字体英文短句（如 `At the waterline`, `Speed / Weight / Distance`）。

#### 📷 最佳推荐适用照片
- 海岸水线、沙滩救生塔、快艇/货轮水面、池塘荷影等具有强运动轨迹、水线延伸或视觉动态的照片。

#### 💬 最佳 Agent 对话 Prompt
> *"使用 $jv-chromatic-gesture-zine-v1-0，撕开照片边缘，用一条鲜艳的洋红/宝高彩线条横跨撕纸边界，背景采用复古半调网点简化。"*

---

### 5. `jv-frame-escape-print-v1-0` · 冲印破框

#### 📖 视觉美学法则
干净裁切的白色厚边冲印相框（含相机品牌型号标注，如 `NIKON Z 50` / `FUJIFILM X-E1`）偏离中心放置于**纯色平涂背景**上：
- **破框方向法则**：照片中最具延伸方向感的元素（飞檐、拱桥、花枝、山峰）无缝溢出框外 20~50%，延伸进纯色背景中。
- **相框反向偏移**：相框位置偏向破框反方向，给破框主体留出延伸空间。
- **真实摄影质感**：框内框外照片部分均保持真实摄影质感（干净裁切，非手撕毛边）。

#### 📷 最佳推荐适用照片
- 中式飞檐屋脊、石拱桥、盛开花枝、雄伟山峰尖顶等具有强方向延伸感的照片。

#### 💬 最佳 Agent 对话 Prompt
> *"使用 $jv-frame-escape-print-v1-0，识别这张照片中最具延伸感的飞檐/拱桥/花枝，让其破框而出延伸进纯色背景，框底部配上相机品牌型号。"*

---

## 🛠️ 安装与 AI Agent 配置指南 (Installation & Setup)

### 第一步：克隆仓库到本地项目

将仓库克隆到您的 AI Agent 工作区（例如 Google Antigravity 或 Claude Agentic IDE 的 `.claude/skills` 目录）：

```bash
# 切换到您的 Agent 项目根目录
cd /path/to/your/project

# 克隆 jovi-photo 仓库中的 skills
git clone https://github.com/Jovifei/jovi-photo.git temp_jovi && mv temp_jovi/.claude/skills/jv-* .claude/skills/ && rm -rf temp_jovi
```

或者将本仓库作为项目子模块引用：

```bash
git submodule add https://github.com/Jovifei/jovi-photo.git .claude/skills/jovi-photo
```

---

### 第二步：与 Agent 对话交互的最佳实践

要在 Antigravity 或 Claude IDE 中完美触发对应的 Skill，请遵循以下交互习惯：

1. **拖入/上传您的参考照片**；
2. **在对话中直接带有 `$jv-` 前缀声明指定 Skill**；
3. **附带一句具体的意图描述**（例如破框方向、色彩偏好或文字内容）。

#### 💡 5 个 Skill 最佳 Prompt 模板：

```text
1. 现实撕裂传送门：
"请用 $jv-torn-world-portal-v1-0 帮我处理这张照片。沿着建筑/车轮的轮廓撕开，撕口内部展现手绘水彩的奇幻平行世界。"

2. 场景极简精粹：
"请用 $jv-scene-essence-minimal-v1-0 制作一张极简海报。采用左右双联，提取一个朱红色的色彩锚点，配上诗意英文主副标题。"

3. 摄影标本日志：
"请用 $jv-photo-specimen-journal-v1-0 转化这张旅行照片。把人物做成剪影，加上垂直测量刻度尺和方位虚线轨迹，做成标本日志页。"

4. 高彩轨迹拼贴纸刊：
"请用 $jv-chromatic-gesture-zine-v1-0 转化这张海岸照片。背景用半调网点简化，用一条鲜艳的洋红线条穿过手撕照片边缘。"

5. 冲印破框：
"请用 $jv-frame-escape-print-v1-0 处理这张飞檐/花树照片。从白色相框中破框而出延伸进纯色背景，底部带上相机型号标注。"
```

---

## 📜 开源协议 (License)

[MIT License](LICENSE) © 2026 [Jovifei](https://github.com/Jovifei)
