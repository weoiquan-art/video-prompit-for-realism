# T6 光线、风格、声音
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R14 光线按场景类型选｜作者原则[LIGHTING RULES]**
写法："Choose lighting from the scene type." "Do not apply one universal formula to every prompt." 作者按场景类型给的方向：
- 战场、神话式对峙：逆光、轮廓边缘光、低调曝光、深阴影。
- 街头混乱、车辆场景：太阳方向或街灯光源、车流阴影、薄雾（haze）、活的城市反光（live urban reflections）。
- 亲密室内戏：有动机的窗光或实景灯、眼睛可读、柔和的低调阴影。
- 夜景外景、社会写实：有动机的实景灯、湿地反弹光、脸可读、真正的负填充（true negative fill：用吸光物让暗部真的暗下去）、受控的黑暗。
- 恐怖变形：材质的湿润、变形可读、落地的阴影。
总要防：平的正面光；泛泛的美颜补光；影棚主光感；表演重要时脸被压成看不清；夜景里漏进日光。
"Lighting must say where the light comes from and what it does to faces, eyes, surfaces and depth."
避免：一套光线公式套所有提示词；只写"电影感灯光"而不说光从哪来、对脸和表面做了什么。
注意：作者的分类来自英文真人电影语境；不在分类里的场景（白天办公室、自然光户外等）按同一原则写——来源、对脸和表面的作用。这一句是整理者的推论，不是作者原文。

**R15 声音与对白｜作者原则[AUDIO RULES]**
写法："Only include dialogue if the user specifies dialogue." 有对白时：用确切的台词；用户给了时序就保留；不即兴加词；不加额外的说话人（no extra voices）；除非要求，不加字幕；除非要求，不加音乐；一次只有一个人说话，除非明确写了重叠。
声音要支撑镜头节奏：雨、织物、呼吸、远处车流、俱乐部低频、引擎、冲击、蒸汽、脚步、静默。"Do not add narration."
避免：自己加台词、旁白、字幕、音乐；两个人同时说话而没有写明重叠。
注意：与通用仓库"声音与对白挂在动作或时间点上"同向；通用仓库的台词符号写法（如 {台词}）见其 T4，本仓库不复制。

**R16 风格与质量锁（静态与慢镜头）｜作者原则[STYLE RULES；QUALITY RULES：still or slow dramatic shots]**
写法：
- "Style should support the shot's job, not overpower it." 风格块紧凑、可观察：写实程度；电影传统或类型质感；色彩关系；有无颗粒；对比；表面行为；需要时的年代美术。
- "Do not stack too many director names or vague prestige words." 用户给了具体风格就保留；没给就按场景推一个务实的电影风格："If the user provides a specific style, preserve it. If the user does not, infer a practical cinematic style from the scene."
- 质量锁："Quality locks should prevent likely generation failure without fighting motion." 静态或慢速戏剧镜头的作者写法：
```text
Sharp clarity, stable picture, natural colours, readable faces, controlled highlights, no ghosting, no flicker.
```
  动作镜头的质量锁见 R13；"Do not use “no blur” as a universal suffix."
避免：堆导演名和空泛的名牌词；风格压过镜头任务；把"无模糊"当通用后缀。
注意：是否把这句质量锁整句写进复制区，见入口"待 JIN 定"第 7 项（默认不再另加，因为 JIN 的【全局限制】已承担同类作用）。
