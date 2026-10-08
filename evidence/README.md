# evidence：标签、来源与边界、编号索引（不自动读）

## 标签
- **[作者原则]**：来自作者 Skill 的规则。JIN 2026-10-08 说"虽然仅真人 但它也是视频提示词的正确指示"。我们没有对照数据，也没有用它生成过真人成片，所以不给把握等级。
- **[JIN 治理]、[JIN 核心原则]**：JIN 的话或治理规则；核心原则和修改治理前三条逐字抄自通用仓库入口（修改治理第二条的问句加了"（真人）"，后两条是本仓库补充）。
- **[整理者核对]**：整理者（写这些卡的 Claude）读作者原文时发现的问题——数值不一致、例子自相矛盾等；不是作者的话。
- **[本 Skill 的处理]**：为适配 JIN 的流程做的取舍，不是作者原文。
- 卡片里的中文是概括与翻译；引号或代码块里的英文是作者原话，已逐段对回存档。

## 来源与边界
- 作者 Skill：`higgsfield-seedance-prompt-builder`，版本 4.4.2（CINEDANCE）；文件头声明 `license: MIT`，`metadata` 里有 `version: "4.4.2"`、`role: "hybrid-director"`；文件内没有作者署名；JIN 2026-10-08 提供；没有核实发布页。存档：[references](../references/author-cinedance-v442.md)。
- 性质：英文写成，给 Claude 当系统提示用；面向 Seedance 2.0／Higgsfield Seedance 的电影风格提示词，例子都是真人场景；文中提到独立的 `cinedance-auditor`、`cinedance-workbench` 两个 Skill，本仓库和通用仓库里都没有。
- 边界：
  1. 作者的断言（如"Seedance 按画面内容而不是数字推视场"）没有对照数据。
  2. 作者面向 Seedance 2.0／Higgsfield Seedance；我们用豆包与 LibTV（2.0／2.5），表现是否一致没有核对。
  3. 英文规则迁移到中文提示词，没有验证。
  4. 作者例子里的人名、地点、数值（Cal、Oli、Horace、小巷、0.35 秒、12°）只是示例，不是规格。
  5. 例子里有自相矛盾处（R09 的变焦推轨、R06／R10 的荷兰角度数），已在卡里标出。

## 与通用仓库已有 cinedance-v4 分支的关系
- 通用仓库的 `skills/practical-case-skills/cinedance-v4/` 是早期 CINEDANCE V4 的"保留性整理分支"（来源是用户提供的 `CINEDANCE HIGGSFIELD SKILL.md`，不是逐字镜像；它的说明是实操证据，不自动覆盖 JIN 的规则）。名称和结构相近，应是同一条线的较早版本，未核实。
- 本仓库的来源是 v4.4.2 原文，并逐字存档。两边重叠的：第一帧占位、站位、身体朝向与视线分开、参考分工、物理、灯光、上下文隔离、静默 QA。旧分支里没有而 v4.4.2 有的：可行性否决与让步顺序、创意手法翻译器、按镜头任务选视场、180° 快门、角色行为系统、审查口径（旧分支是整理版，原 V4 有没有这些未核实）。
- 优先级沿用那个分支 README 的第 4 条：外部 Skill 与 JIN 已验证经验冲突时，不覆盖旧经验，保留差异，靠成片判断。
- 已知差别：旧分支写"JIN 主 Skill 不强制每镜使用固定角度"（视场数字当参考）；v4.4.2 以度数为主要数值语言，但也说模型不照数字走。见 [open-decisions](open-decisions.md) 第 3 项。
- 两边各存一份有重复。第一版按 JIN 的选择（通用仓库不改）并存；是否合并或互相指路，等 JIN 定。

## 把握怎么来
[作者原则] →（JIN 的真人成片单次验证，记在 [cases](cases/README.md)）→（同类规则在不同任务重复成立）。升级由 JIN 的成片评价和对照决定，不由我推测；单次观察不写成规则；失败也要记。

## 编号索引
| 编号 | 条目 | 文件 |
|---|---|---|
| R01–R04 | 先判可行与让步顺序；每镜八问与一镜一个主要任务；动笔前先画世界地图；提取当前镜头、成稿结构与正向约束 | topics/t1-design.md |
| R05–R07 | 第一帧与空间站位；机位写成物理位置；运镜要有任务且物理上做得到 | topics/t2-space-camera.md |
| R08 | 视场角由内容决定 | topics/t3-optics.md |
| R09–R10 | 创意手法翻译器；具体手法的写法（Guy Ritchie 式能量、急变焦、荷兰角、激进广角、甩镜、手法密度） | topics/t4-devices.md |
| R11–R13 | 角色行为系统与景别决定表演颗粒度；物理；180° 快门运动模糊与动作质量锁 | topics/t5-performance-physics.md |
| R14–R16 | 光线按场景类型选；声音与对白；风格与质量锁 | topics/t6-light-style-audio.md |
| R17 | 参考只用当前有效的，并分清它管什么、不管什么 | topics/t7-refs.md |
| R18–R20 | 常见失败的修法；审查口径；终检清单与入口自检的对应 | topics/t8-audit.md |

## 证据文件
- [classification](classification.md)：作者每个章节的去向与处理。
- [open-decisions](open-decisions.md)：作者做法与 JIN 现有做法冲突或没有对应、等 JIN 定的事项和默认做法。
- [cases/README](cases/README.md)：真人成片记录格式。
- [作者原文存档](../references/author-cinedance-v442.md)。

## 调整记录
**R1a（第一版，2026-10-08）**
- JIN 回复"a 请你放那边 然后 审查"：作者规则全部放进本仓库，通用仓库不改。
- 新增：入口 SKILL.md；T1–T8 共 20 张卡（R01–R20）；作者原文存档；本目录的三个文件和 cases/README。
- 不含 cinematic-prompt-toolkit；不含 Chibi 内容；通用仓库与 `chibi-` 仓库未改。
