# T7 参考：角色参考、场景参考、关键帧
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R17 参考只用当前有效的，并分清它管什么、不管什么｜作者原则[REFERENCE RULES；LOCATION RULES]**
写法：
- 只用用户提供的有效参考："Use only active references provided by the user." 提示词里每个参考标签都必须在"有效参考"里："Every @tag in the final prompt must exist in ACTIVE REFERENCES." 没有过期的、没用的、上一场景的、杜撰的标签。豆包、LibTV 用图号：每个图号都必须是当前有效的，且与正文一致（作者的 @tag 对应我们的"名字（对应图片N）"）。
- 角色参考的描述要紧凑，作者列六项："Character reference descriptions should be compact:" 后接列表：identity（身份）；current visible state（当前可见状态）；wardrobe if needed（需要时的服装）；action-critical anchors（对动作关键的锚点）；“100% matches the reference”（与参考 100% 一致）；what to ignore from the reference（参考里要忽略的部分）。"Do not over-describe a character if the reference already controls identity."
- 授权的真人演员：作者允许写想要的角色表演与肢体表演，但要绑定到所提供的参考和用户授权的选角语境（原文："keep it tied to the supplied reference and user’s authorized casting context"）。
- 场景参考：总要分清它管什么、不管什么："Always separate what a location reference controls from what it does not control." 可以管：几何；材质；布局；地标位置；氛围；实景光源。不自动管："A location reference does not automatically control:" 后接列表：camera angle；framing；story identity；added props；added people；shot order。
- 不从泛泛的场景杜撰故事身份："Do not invent story identity from a generic location." 作者例：参考是后巷，就不要改叫孤儿院、医院、学校、警察局或俱乐部，除非用户明说。
避免：过期或杜撰的图号；参考已经锁定身份还大段重复描述；让场景参考顺带决定机位、构图和剧情。

**R21 从镜头表和关键帧写：锚点声明、对应表、多人称呼｜豆包官方[prompt.md：生成门禁、输入引用规则、多主体场景定义规则、特殊符号规则；storyboard.md：连续性规则]**
来源：豆包官方 Skill（doubao-creative-drama）。下面是整理者的提炼，不是原文；原文存档在 video-exp 的 sources/doubao-creative-drama/。作者 CINEDANCE 没有这些条目。
写法：
- 关键帧当参考：每张关键帧图写明它在时间轴上的身份——首帧（0 秒开场和它一致）、X–Y 秒中段锚点（画面要经过这个状态）、尾帧（结尾落到这个状态），并写它对应哪一镜、为什么选它（短剧筹备 D08 的命中标准）。只有一张时默认当首帧；它对应的镜头不在开头，就写成那个时间点的中段锚点。接上一段时，上一段的尾帧标"承接参考"，不当本段首帧。
- 图里已有的画面不在正文重复：关键帧已经管构图、服装、材质、光向、道具位置；正文写运镜、动作、剧情推进、声音；要守的连续性（脸、道具尺寸、锁扣位置）写成一句正向约束。与 R17"参考已管身份就别过度描述"同向。
- 有关键帧时，默认不再传场景资产图，免得两份参考打架；只有关键帧只有一张、空间交代不全，或 JIN 要求时才补传，并写明原因。
- 从短剧筹备的镜头表写时：复制区外先列一张对应表——镜头编号 → 提示词时间段 → 用哪张关键帧；每个时间段都对得回镜头表；相邻、连续的镜头可以合并，但保留因果；不加镜头表里没有的剧情、人物、道具、动作结果（同必读第 1 条"不改故事"）。缺镜头原文或时间戳断开时，先回短剧筹备补。
- 多人：开头逐个定义（如"图片1 中的高个男人是警察；图片2 中的矮个男人是小偷"），给每人一个稳定称呼；之后全程用同一称呼，不换成代词或别称，动作句不省主语；多人同时出现逐个写名字，不写"三个人""众人"。与作者 R04 的好例 "Exactly three named characters appear in the alley: @CAL, @OLI and @HORACE." 同向。
- 提示词里不用 `--`：豆包原文说它后面的内容可能被截掉、不被执行。
避免：关键帧不标时间身份；正文把关键帧里的服装、光向、构图再描述一遍；为了合并镜头改掉因果；用"他""众人"指代。
注意：
- 本 Skill 的处理（非豆包原文）：图里已有的画面不重复，不包括站位和朝向——第一帧谁在哪、朝哪、动作从哪起，仍按 R05 写（整理者调和）。
- 不收：豆包要求视频提示词开头放全局风格词（与"JIN 的决定"第 2 项冲突，照作者顺序）；末尾必加"禁止生成字幕、文字、LOGO、水印"（JIN 2026-10-09：像是针对 Seedance 2.0，2.5 应该不需要）；15 秒片段、画幅限制、一次 2 个视频（JIN：束缚）。音乐、音效、台词、旁白、字幕的标注符号 JIN 同意加入，写在 R15。
- 豆包的写法面向它自己的工具（图生视频、`@图片N` 引用）；在 LibTV 上是否同样有效，没有核对。
