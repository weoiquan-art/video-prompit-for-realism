# T1 设计：先判可行、一镜一个任务、世界地图、成稿结构
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R01 先判可行与让步顺序｜作者原则[THE MAIN CHANGE IN V4.4；FEASIBILITY VETO RULES]**
写法：动笔前先判断这一镜按要求真的能成吗。"Do not merely describe a bad or overloaded shot more precisely."（不要只把一个糟糕或超载的镜头描述得更精确。）需求自相矛盾时："If the user's request contains an internal conflict, preserve the core creative intent and correct the least important parameter."
作者的三个例子：①又要极端超广角的空间交代、又要微小的表演 → 先定这一镜主要是空间镜还是表演镜；②小房间里没有可能的机位距离，却要长焦人像 → 选一个可行的视场，保住情绪结果；③一个广角镜里同时要很多道具、演员、可读文字、精确台词、复杂调度、细微反应 → 减少次要细节，或拆成两次生成。
否决条件（作者原列 11 项）：极端广角加细微面部表演；很小的角色加精确口型；不同景深层面可读物件太多；机位距离不可能；第一帧要动作却空镜开场；镜头越轴又要保持屏幕方向；对白场景配狂乱运镜；精确地理加过度风格抽象；连续镜头里大事太多；夜景配日光语言；快动作写"无模糊"。
让步顺序（作者 6 步）：1 保核心情绪与叙事意图；2 保参考身份；3 保必要站位；4 保台词；5 按需调光学、机位距离、景别、次要细节；6 去掉非必要的风格或物件要求。要保住的是 1–4；5 和 6 是可以调整的。
本 Skill 的处理（非作者原文）：作者是静默修正，终稿里只给改好的版本（"silently fix the conflict"）；本 Skill 改为——改了视场、机位、景别或次要细节，在复制区外写一行"已调整：…"（本 Skill 新增），不悄悄改；牵涉人物、顺序、结局、台词、JIN 点名的道具，先问 JIN（入口第 1 条管人物、顺序、结局；台词和 JIN 点名的道具是本 Skill 在这里加的）；审查与分析时直接说出冲突（与作者一致）。
避免：保留注定失败的设计、只把它写得更精确；为通过清单而保住冲突的设计。
注意：5 和 6 谁先让，作者没有写明（原文只说改"最不重要的参数"），按镜头任务判断。用户点名的创意手法不在可以去掉的范围内（R09："The Feasibility Veto may reshape a creative device, but must not erase it."）。

**R02 每镜八问与一镜一个主要任务｜作者原则[IDENTITY；CORE PRINCIPLE；OPERATING LOOP：Choose the shot intent、Apply the density law]**
写法：
- 立场：作者要的不是漂亮的描述，而是"首次认真尝试就尽量能成"的、对生成安全的镜头；最高优先级是用户想要的结果，不是形式上满足规则；提示词是否成功，只看视频模型能否在物理、空间、电影语言和时间上理解要生成什么。原文："Your job is not to write beautiful descriptions. Your job is to design generation-safe cinematic shots that work as often as possible on the first serious attempt."
- 核心判断："Seedance follows clear physical, spatial, and cinematic logic better than abstract prose or overloaded control language."
- 每个认真的镜头先答八问：①谁或什么可见？②正在发生的"唯一的主要事件"是什么？③每个人在物理空间的哪里？④摄影机的物理位置和戏剧任务是什么？⑤什么光学自然匹配这个镜头的内容？⑥第一帧必须看到什么？⑦有没有必须保留的创意摄影或风格手法？⑧模型可以放心忽略什么？答不干净："If a prompt cannot answer these cleanly, rewrite the design before writing the final prompt."
- 每镜一个主要任务（作者列 11 种，选一个）：表演；空间与连续性锁定；冲击、暴力、破坏；悬念、恐惧；美感与氛围；物件细节；运动、追逐；变形、身体恐怖；对白覆盖；收尾钩子；创意摄影或风格手法。它决定光学、构图、细节密度和运镜："Do not let secondary details overpower the primary job."
- 密度法则：一镜 = 一个主要想法、一个主要动作、一个相机策略、一个主要情绪效果。"If the shot needs multiple big events, split it into timed beats or separate generation blocks." 必须连续的话："keep the camera and action simpler."
避免：次要细节压过主要任务；一镜里同时塞几件大事；答不出八问就硬写。
注意：JIN 的核心原则（入口）与此同向：模型不会脑补，要把看不见的变成看得见的。"一个主要动作"怎么读（整理者推论，不是作者原文）：指同一镜里同时发生的事；作者允许把多件事拆成带时间的节拍（"timed beats"），所以按时间排开的阶段不算"同时发生"；但连续镜头仍要保持相机和动作简单，连续镜头里大事太多仍触发 R01 的否决条件。

**R03 动笔前先画世界地图｜作者原则[OPERATING LOOP：Build the world map]**
写法：写风格之前先定八件事（作者："Before writing style, define:"）：谁在哪；谁朝着谁；摄影机物理上站在哪；摄影机留在动作线的哪一侧；前景、中景、背景各是什么；哪些地标锚定空间；第 0 帧（首帧）能看到什么；什么能动、什么必须固定。
屏幕坐标只在能提升控制时用：X 轴 0% 最左、50% 居中、100% 最右；Y 轴 0% 最上、50% 居中、100% 最下。"Physical relationship language must come before coordinates."
作者的好例（先物理关系，后坐标）：
```text
The three men stand tight together in the mid-depth of the alley, just out from the left brick back door. Cal is left of the cluster nearest the red lamp, Oli is center, Horace is right, all within 1-1.5 m of each other. On screen: Cal x ~46%, Oli x ~53%, Horace x ~60%.
```
坏例（只有坐标）：`Cal x 46%, Oli x 53%, Horace x 60%.`
中文写法示意（意译，非作者原文）：三个人在小巷中景站得很近，离左边砖墙后门不远；甲在人群左侧、最靠近红灯，乙居中，丙在右侧，三人彼此都在 1–1.5 米以内；画面上甲约 46%、乙约 53%、丙约 60%。
避免：只有坐标没有物理关系；每镜重新发明地理。
注意：这是写前的准备，不是提示词里的段落顺序。作者的成稿结构把地图和第一帧排在风格之前；本 Skill 的全局顺序仍按 JIN 的核心原则，把风格段放在时间轴之前（见 R04 与入口）。

**R04 提取当前镜头、成稿结构与正向约束｜作者原则[OPERATING LOOP：Diagnose the shot、Write the final prompt；OUTPUT BEHAVIOR；FINAL PROMPT ARCHITECTURE]**
写法：
- 作者的工作顺序（"Always work in this order."）：提取当前镜头 → 定主要任务（R02）→ 应用密度法则（R02）→ 画世界地图（R03）→ 选可行的光学（R08）→ 写终稿。
- 提取当前镜头或当前序列时，只提取这一镜，列出：出场角色；有效参考；场景；道具与载具；第一帧可见内容；主要动作；对白与声音；机位侧与角度；屏幕方向；身体朝向与视线；身体接触点；光源；终帧或切点。删掉过期上下文：没用的角色、旧参考标签、上一场景的措辞、场景编号，以及这一镜里看不见也听不见的物件。
- 写成短、具体、可见的句子，并把这些分开写：主体动作、相机动作、环境动作、情绪表演、光学、光线、声音。"Critical spatial information comes before style." "Critical camera information comes before mood." "Critical dialogue timing comes before voice style."
- 作者的终稿结构（14 块，英文系统提示的场景）：SCENE CONTEXT；ACTIVE REFERENCES；LOCATION MAP；FIRST FRAME AND SPATIAL BLOCKING；FORMAT MODE；OPTICS；CAMERA；ACTION TIMING；PHYSICS；LIGHTING；AUDIO；STYLE；QUALITY；POSITIVE CONSTRAINTS。OUTPUT SETTINGS 只在用户要求、或平台界面不管这些设置时才写。
- 正向约束："Do not include a separate NEGATIVE CONSTRAINTS block unless the user explicitly asks." "If a prohibition is important, integrate it as a positive constraint inside the relevant section." 好例："Exactly three named characters appear in the alley: @CAL, @OLI and @HORACE." 弱例："No extra people."
- 交付行为：要提示词就给干净的终稿；用户说 final 或 copy-paste 时只输出干净终稿；要分析、审查、测试、系统工作就简明实用地说；不展示内部草稿、审计表、隐藏推理、失败笔记、修正循环，除非明确要求。长提示词、修订、失败的生成用"文件优先"：保留强的段落、只补弱的段落、留一份能用的提示词作真源、需要时再另编干净终稿。
本 Skill 的处理（非作者原文）：
- 全局顺序：JIN 的核心原则要求风格段放在秒针（时间轴）之前，沿用 JIN 的槽位格式；"空间先于风格""相机先于情绪"只用在每个镜头行内部的写法顺序。
- 整理者核对：内容性的禁止项仍应改写成正向（作者的弱例就是 "No extra people."）。作者自己的质量锁句里有 "no ghosting"、"no flicker" 这类否定词（见 R13、R16），那是作者的惯用写法，不能推广成"可以堆否定词"。JIN 的【全局限制】与每段"限制条件"是 JIN 自己的格式，不算作者说的"隐藏的否定块"（R19）。是否改成纯正向写法，见入口"待 JIN 定"第 4 项。
- "复述＋已调整"写在复制区外，复制区只放干净提示词。复制区干净与作者一致；区外加这些说明是本 Skill 的偏离（作者不展示修正过程，也不留"已调整"）。
- 槽位字段 → 读哪张卡（本 Skill 的建议）：【摄影机+胶片/质感】【真人专属补充】→ R16、R14；【镜头】→ R08；【全局限制】与每段"限制条件"→ 本卡的正向约束、R13、R16；【人物/物品设定】与"出镜人物"→ R17；"运镜"→ R07、R09、R10；"景别"→ R08、R11；"地点/场景""主体""画面位置"→ R03、R05；"台词"→ R15；"表情"→ R11；"画面动作"→ R12、R13。
- 作者结构里的 FORMAT MODE 一块，v4.4.2 原文没有展开；通用仓库的早期分支（skills/practical-case-skills/cinedance-v4）§7 写过：先决定单一连续镜头还是受控多镜头序列，默认不让模型自己发明随机切镜。可作参考。
- 分辨率、画幅、帧率若由平台界面控制，可以省略（R19 不扣分项）；JIN 的槽位模板头部自带这些字段，保留或省略由 JIN 指定。
避免：把旧镜头的角色、图号、道具带进新镜头；用"不要…"堆一串禁止项代替把想要的结果写出来。
