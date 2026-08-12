# nuclear-physics-rmf-eos

**核物理研究线**：相对论平均场（RMF）/ 对称能 / 中子星状态方程的自底向上系统性导览（纯静态 HTML，GitHub Pages 托管，无后端依赖）。

## 这是什么

从"核物理怎么数数"讲起的知识站点：度量衡 → 液滴模型 → 费米气体 → 相对论多体 → 核力介子图像 → 平均场近似 → RMF 自洽求解 → 饱和与结合能 → 对称能 → 状态方程（EOS）→ TOV 中子星质量-半径计算 → 天文观测约束。**主线页内嵌完整的 RMF + TOV 求解器**，所有数值（饱和密度、E/A、M*/M、对称能、M_TOV）都由浏览器内脚本现场解出来。

## 站点地图（怎么逛）

### ① 主线页

| 文件 | 内容 |
|---|---|
| [index.html](https://wadesha.github.io/nuclear-physics-rmf-eos/index.html) | **主线 16 节**：学习地图（难度阶梯+三条读法）→ 第 1–4 节前置知识（度量衡 / 液滴模型 / 费米气体 / 相对论多体，各配交互）→ 第 5–9 节核力与 RMF 自洽求解 → 第 10 节对称能 → 第 11–13 节 EOS、TOV 与观测约束 → 第 14 节收束 → 第 15 节术语表。含 4 个交互演示：B/A 液滴曲线、σ 场自洽迭代、对称能、TOV 质量-半径。 |

### ② 实验与专题支线（从主线导航进入）

| 文件 | 主题 | 核心内容 |
|---|---|---|
| [nuclear_experiments.html](https://wadesha.github.io/nuclear-physics-rmf-eos/nuclear_experiments.html) | **核物质与中子星实验** | 从地面实验室到宇宙实验室：结合能质量表 → 巨单极共振（K₀≈231 MeV）→ 中子皮（PREX-II / CREX，L 之争）→ 重离子碰撞（SπRIT）→ 脉冲星质量（2.08 M☉ 生死线）→ NICER 半径 → GW170817 潮汐形变，七路约束交汇成 EOS"允许走廊"。 |
| [element_origins.html](https://wadesha.github.io/nuclear-physics-rmf-eos/element_origins.html) | **元素起源** | 大爆炸核合成（前 20 分钟造出 H/He/Li）→ 恒星燃烧（C 到 Fe）→ s 过程 / r 过程 → 中子星并合造金（GW170817 实测）。"你身体里的每个原子从哪来"。 |
| [gravitational_waves.html](https://wadesha.github.io/nuclear-physics-rmf-eos/gravitational_waves.html) | **引力波与多信使** | LIGO / Virgo 干涉仪原理（4 km、质子直径万分之一的精度）、GW170817 全过程（引力波 + 千新星 + 造金）、下一代台阵（LISA / ET / PTA）。 |
| [ns_interior.html](https://wadesha.github.io/nuclear-physics-rmf-eos/ns_interior.html) | **中子星内部结构** | 一茶匙 10 亿吨的物质里发生了什么：超子软化悖论、夸克物质、相变、双子星分支、2 M☉ 生死线——EOS 的最高密度战场。 |
| [heavy_ion_collisions.html](https://wadesha.github.io/nuclear-physics-rmf-eos/heavy_ion_collisions.html) | **重离子碰撞实验** | 把原子核加速到近光速对撞（TPC / 中子墙 / 谱仪）、π⁻/π⁺ 比、集体流、输运模型——在地面实验室复现中子星内部的密度。 |

## 每页都有的功能

- **☰ 顶部折叠目录**：右上角展开，自动从章节生成，滚动时高亮当前位置
- **◐ 深/浅主题切换**：右下角小圆钮，一键切换并记忆偏好
- **一句话直觉**：每章开头先用生活语言说清"这一步在干什么"
- **术语表**：每站末尾，术语首次出现时配一句通俗解释
- **交互演示**：数值由页内脚本实时计算（主线页的 RMF/TOV 求解器、液滴模型 B/A 曲线等）

## 模型说明

主线页使用一个校准过的教学参数集（饱和密度约 0.145 fm⁻³、E/A ≈ −14.8 MeV、M*/M ≈ 0.65、对称能 ≈ 35 MeV），所有页面数字均由此模型当场计算；页面内已注明该参数集偏硬、M_TOV 基值高于观测窗口，作为"机制演示"而非文献拟合结果。

## 技术说明

- 纯静态 HTML + 原生 JavaScript + Canvas，无任何外部依赖、无后端、无跟踪
- 全部内容为公开文献知识的系统化整理（含文献年份与数据来源标注），页面本身不含任何个人信息
