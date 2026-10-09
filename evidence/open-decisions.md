# JIN 的决定：作者做法与 JIN 原有做法冲突的 7 处

> 状态：2026-10-09 JIN 回复后定下，JIN 随时可改；入口"JIN 的决定"是这里的缩略。每项列：作者怎么说；JIN 原来怎么做；决定与 JIN 原话。

**1 静默修正 vs 不改故事**
- 作者：发现冲突就静默修正，终稿只给改好的版本；修正时先保核心情绪与叙事意图、参考身份、必要站位、台词，再调光学、机位距离、景别、次要细节，最后去掉非必要的风格或物件要求（THE MAIN CHANGE IN V4.4；FEASIBILITY VETO RULES）。
- JIN 原来：通用仓库入口第 1 条"不改故事：已确认事实照用，假设可撤回，改变角色、顺序、结局的先问"。
- 两边都不改故事；差别只在技术调整改完说不说。
- 决定：沿用 JIN 的规则。技术调整照作者做，在复制区外写一行"已调整"（本 Skill 新增）；牵涉人物、顺序、结局、台词的先问（台词是本 Skill 加的）。JIN 2026-10-09 问"我的做法不改故事是什么意思"，听完解释答"不改故事 没关系"。

**2 风格段放在哪**
- 作者：14 块里 STYLE 排第 12，在 ACTION TIMING（第 8）之后；"Critical spatial information comes before style."（FINAL PROMPT ARCHITECTURE；OPERATING LOOP）
- JIN 原来：核心原则"我们需要在动作 秒针之前加一堆风格提示词"。
- 决定：照作者顺序，风格块在动作时间轴之后。核心原则原文不改，这一点在本 Skill 先不照做。JIN 2026-10-09："关于我的风格词站 提示词前面 目前先不用遵守 作者这么做肯定有原因目前我们还未尝试"。

**3 度数还是毫米**
- 作者：视场角度数是主要数值语言；毫米只在用户提到、或有助于说明意图时作括注；避免 "16mm, 24mm, anamorphic Cooke, f/2.8, ISO 800." 这类写法，除非用户明确要胶片技术语言（OPTICS RULES）。
- JIN 原来：槽位模板【镜头】写毫米，如"50mm"。
- 决定：跟作者。JIN 2026-10-09："作者skill 是使用什么度数还是毫米 都跟着作者"。

**4 否定块**
- 作者：不单独写否定块，重要的禁止项写成正向约束放进相关段落（FINAL PROMPT ARCHITECTURE）；作者自己的质量锁句里仍有 "no ghosting"、"no flicker"。
- JIN 原来：槽位模板有【全局限制】和每段"限制条件"。
- 决定：跟作者，随第 6 项（用作者的结构）一起定。

**5 输出语言**
- 作者："Final Seedance/Higgsfield prompts are normally written in clean cinematic English."（IDENTITY）；cinematic-prompt-toolkit 也默认终稿写英文。
- JIN 原来：豆包、LibTV 上写中文提示词。
- 已知（2026-10-06 的跨来源调查，官方文档多为摘要）：中文、英文都支持（建议中文不超过 500 字、英文不超过 1000 词）；没有可靠来源说哪种效果更好；官方要求每句台词只用一种语言。
- 决定：写中文。块名和作者定句（锁定句、质量锁、急变焦）用整理者的中文译法（R04）；台词照 JIN 给的原文。中英效果差别没测过。JIN 2026-10-09："输出语言可以保留中文？ 因为我看了作者画布也是使用的中文"。

**6 模板**
- 作者：给的是 14 块的成稿结构（SCENE CONTEXT 到 POSITIVE CONSTRAINTS），没有填好的完整范例（FINAL PROMPT ARCHITECTURE）。
- JIN 原来：通用仓库的槽位模板。
- 决定：用作者的 14 块、照作者顺序，块名写中文（R04）。

**7 镜头锁定与质量锁**
- 作者：镜头锁定写 "84° diagonal field of view, classic wide rectilinear character. Lens locked for the whole shot."；急变焦镜头改写 "Lens/FOV change is limited to the single timed crash zoom; no other lens drift."；质量锁静态或慢镜写 "Sharp clarity, stable picture, natural colours, readable faces, controlled highlights, no ghosting, no flicker."，动作镜头写 R13 那句；"Do not use “no blur” as a universal suffix."（OPTICS RULES；Crash zoom；QUALITY RULES）
- JIN 原来：槽位模板头部【镜头】一行与【全局限制】。
- 决定：跟作者，写成中文（R04）。JIN 2026-10-09："镜头也是 锁不锁跟着作者"；质量锁和镜头锁定是同一项，一并跟作者。
