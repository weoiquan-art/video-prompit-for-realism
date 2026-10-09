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

**R15 声音与对白｜作者原则[AUDIO RULES]；豆包官方[prompt.md：特殊符号规则]**
写法："Only include dialogue if the user specifies dialogue." 有对白时：用确切的台词；用户给了时序就保留；不即兴加词；不加额外的说话人（no extra voices）；除非要求，不加字幕；除非要求，不加音乐；一次只有一个人说话，除非明确写了重叠。
声音要支撑镜头节奏：雨、织物、呼吸、远处车流、俱乐部低频、引擎、冲击、蒸汽、脚步、静默。"Do not add narration."
避免：自己加台词、旁白、字幕、音乐；两个人同时说话而没有写明重叠。
标注符号（豆包官方写法，不是作者原话；JIN 2026-10-09 同意加入，2.5 上没测过）：音乐写在 `()` 里，音效写在 `<>` 里，台词写在 `{}` 里，旁白写在 `『』` 里，字幕写在 `【】` 里。豆包原文的例子：`(背景中播放着快节奏的摇滚乐)`、`<远处传来狗叫声>`、`{你好，世界}`、`『旁白：三年前的那个雨夜，一切都改变了。』`、`【第一章：启程】`。台词不是中文或英文时注明语种（豆包原文：用日语说道`{こんにちは}`）。
符号只是标注写法，不改变上面的规则：没要求台词、音乐、旁白、字幕的，仍一概不加；音效是镜头自带的声音（见上），可以直接用 `<>` 写。
注意：台词照 JIN 给的原文，不改写（作者："use exact line text"）。
- 整理者核对：`【】` 同时是 R04 中文块名（如【声音】）的括号。字幕只在 JIN 明确要字幕时才写，写成【声音】块里单独的"字幕："一行；块名独占一行当标题，不放字幕内容。
- 豆包的符号面向它自己的工具；在 LibTV 上是否同样有效，没有核对。

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
注意：JIN 2026-10-09 定：质量锁跟作者，静态或慢镜在【质量】块写这一句，中文写法见 R04（入口"JIN 的决定"第 7 项）。
