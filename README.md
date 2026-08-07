# jovi-photo · AI 摄影艺术转化 Skill 统一套件库

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![AGY Skills](https://img.shields.io/badge/Antigravity-Skills-blueviolet.svg)](https://github.com/Jovifei/jovi-photo)

**`jovi-photo`** 是一套专为 AI 编码助手与图像生成引擎打造的**摄影艺术转化 Skill 套件**。通过对真实摄影作品的形体提炼、空间重组、手撕纸质缝合、田野标本归档与物理破框构图，将普通照片转化为具备独立美学价值的艺术纸刊、编辑画报与视觉标本。

---

## 📚 借鉴与立足的 4 个基准 Skill

本套件在研发过程中，深度学习与借鉴了以下 4 个基准 Skill 的色彩规则、留白比例与排版架构：

1. **`gc-minimal-zine-poster-v0-1`** (日韩极简 Zine 海报)
   - *借鉴点*：标准模式四段式 Prompt 编译器、大面积米白纸面留白 (70%+ Radiance)、单一高彩色彩锚点策略。
2. **`photo-abstract-editorial`** (摄影与抽象双联画报)
   - *借鉴点*：上下/左右双联对照版式、真景实物与抽象形体对话的叙事框架。
3. **`scene-distillation-zine-v1-3`** (场景纯插画提炼)
   - *借鉴点*：复杂繁琐细节（树叶、人群、纹理）的大块图形化压缩语法。
4. **`scenes-gathered-zine-v1-3`** (拾景纸刊·手撕拼贴)
   - *借鉴点*：手撕纸张边缘的白色纤维拉丝质感、真景为锚的画面结构。

---

## 🎨 全新统一命名套件：`jovi-` 系列 5 大 Core Skills

为了保证套件家族的**统一美学识别度**，所有全新研制的 Skill 均采用 **`jovi-[功能特点]-v1-0`** 统一命名规范：

```text
.claude/skills/
├── jovi-torn-world-portal-v1-0/      # 1. 现实撕裂传送门
├── jovi-scene-essence-minimal-v1-0/   # 2. 场景极简精粹
├── jovi-photo-specimen-journal-v1-0/ # 3. 摄影标本日志
├── jovi-chromatic-gesture-zine-v1-0/ # 4. 高彩轨迹拼贴纸刊
└── jovi-frame-escape-print-v1-0/     # 5. 冲印破框
```

---

### 1. `jovi-torn-world-portal-v1-0` · 现实撕裂传送门

- **核心特点**：
  物理性撕开真实照片，露出生长在撕口内部、下方或背后的**手绘水彩/版画平行世界**。支持“暗藏世界揭示”、“奇幻世界延伸”与“微观内构剖析”三种叙事模式，核心主体可跨越撕裂边界同时存在于两个世界。
- **视觉特征**：
  自然剖面撕口、锯齿毛边、撕口内部为细腻插画、手绘元素与照片实景形成超现实穿越感。
- **最适应的照片类型**：
  具有强烈叙事焦点、空间穿越感、建筑/车辆结构清晰、水面/天际线天然分割线明显的照片（如：车轮、路标、游乐园摩天轮、雪山湖泊）。

---

### 2. `jovi-scene-essence-minimal-v1-0` · 场景极简精粹

- **核心特点**：
  支持**上下双联**（横图/俯视）或 **左右并排**（竖图/塔楼）版式。将照片精粹提取为最少的几何色块、结构线条与径向透视骨架，配备**单一强色彩锚点**与优雅的诗意主副标题。
- **视觉特征**：
  米白/象牙色纸面背景、径向同心圆/斜向透视骨架保留、标志性装饰细节（雕塑/塔尖）保留、单色彩锚点强对比。
- **最适应的照片类型**：
  城市天际线、古建筑仰视/天井内院、寺庙塔楼、斜向透视街景、蓬皮杜类工业结构建筑。

---

### 3. `jovi-photo-specimen-journal-v1-0` · 摄影标本日志

- **核心特点**：
  **完全拒绝手绘插画**！直接使用原图真实照片的**撕纸碎片与轮廓剪影**组装标本页，搭配精密的**田野考察手记标注**（虚线轨迹 N/S/E/W、测量刻度标尺线、黄色档案标贴 `■`、坐标编号）。
- **视觉特征**：
  真实照片撕纸毛边、轮廓剪影跨越撕纸条带、垂直测量刻度线（带有 `01`, `07`, `5` 刻度）、全大写英文标题 + 中文随笔序号。
- **最适应的照片类型**：
  旅行风光、草原骑行/独坐人像、河畔水边风景、公路与地质自然考察类照片。

---

## 4. `jovi-chromatic-gesture-zine-v1-0` · 高彩轨迹拼贴纸刊

- **核心特点**：
  手撕照片局部嵌入大面积暖米色纸面（70%+ 留白），周围环境简化为**半调网点 (Halftone)**、**版画色块 (Woodblock)** 或干刷笔触，一条**高饱和度高彩轨迹线**（洋红/宝蓝/朱红/亮粉）物理性横跨撕纸边界。
- **视觉特征**：
  高彩线条横跨撕口连接实景与纸面、复古印刷半调网点、手撕纤维毛边、打字机微型英文诗句（如 `At the waterline`, `Speed / Weight / Distance`）。
- **最适应的照片类型**：
  海岸水线、救生塔/沙滩、快艇/货轮水面、荷塘柳影等具有强运动轨迹、水面延伸或视觉动态的照片。

---

## 5. `jovi-frame-escape-print-v1-0` · 冲印破框

- **核心特点**：
  干净裁切的白色厚边冲印相框（含相机品牌型号标注，如 `Nikon Z 50` / `Fujifilm X-E1`）偏离中心放置于纯色平涂背景上，照片中最具方向延伸感的元素**无缝溢出相框**，延伸进背景色中。
- **视觉特征**：
  干净裁切框边（非撕纸毛边！）、原图提取的平涂纯色背景、破框元素无缝衔接、完整保持真实摄影质感。
- **最适应的照片类型**：
  中式飞檐屋脊、石拱桥、盛开花枝、雄伟山峰尖顶等具有强方向延伸感与几何出框冲印质感的照片。

---

## 🛠️ 套件结构一览 (Repository Architecture)

```text
jovi-photo/
├── README.md                           # 统一套件说明文档
└── .claude/
    └── skills/
        ├── gc-minimal-zine-poster-v0-1/        # [基准] 日韩极简 Zine 海报
        ├── photo-abstract-editorial/           # [基准] 摄影与抽象双联画报
        ├── scene-distillation-zine-v1-3/       # [基准] 场景纯插画提炼
        ├── scenes-gathered-zine-v1-3/          # [基准] 拾景纸刊·手撕拼贴
        ├── jovi-torn-world-portal-v1-0/        # [jovi-] 现实撕裂传送门
        ├── jovi-scene-essence-minimal-v1-0/    # [jovi-] 场景极简精粹
        ├── jovi-photo-specimen-journal-v1-0/  # [jovi-] 摄影标本日志
        ├── jovi-chromatic-gesture-zine-v1-0/  # [jovi-] 高彩轨迹拼贴纸刊
        └── jovi-frame-escape-print-v1-0/      # [jovi-] 冲印破框
```

---

## 🚀 安装与使用指南

### 在 Google Antigravity / Claude Agentic coding 中使用

将本仓库克隆或复制至您的项目根目录或 customizations 目录下：

```bash
# 克隆仓库
git clone https://github.com/Jovifei/jovi-photo.git
```

在对话中直接调用指定 Skill 即可生成对应风格的艺术图像：

- *"用 $jovi-torn-world-portal-v1-0 处理这张照片"*
- *"用 $jovi-scene-essence-minimal-v1-0 生成建筑精粹海报"*
- *"用 $jovi-photo-specimen-journal-v1-0 制作旅行标本日志"*
- *"用 $jovi-chromatic-gesture-zine-v1-0 制作海岸高彩拼贴"*
- *"用 $jovi-frame-escape-print-v1-0 生成飞檐破框照片"*

---

## 📄 License

MIT © [Jovifei](https://github.com/Jovifei)
