# T8 审查：常见失败的修法、审查口径、终检清单
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R18 常见失败的修法｜作者原则[COMMON FAILURE FIXES]**
写法：作者列了 7 种情形，各有修法：
1. 镜头必须是广角连续性锁定："Reduce microacting and use large body-readable reactions." 用 84° 或 107°；除非镜头真的关于空间畸变或极端环境，不用 120°。
2. 镜头必须是表演拍："Use 47° to 84°." 机位要近到眼、唇、下颌、喉咙读得出；降低对背景可读性的要求。
3. 镜头总是左右翻转：物理地写明机位在哪一侧，在第一帧和正向约束里各重复一次世界排布顺序（谁在左谁在右、地标在哪一侧）；不要每段都过度重复（"Do not over-repeat it in every section."）。
4. 机位角度失败：重写成物理位置——机位高度；墙、侧面或车辆位置；瞄准方向；滚转；前景锚点（见 R06）。
5. 镜头（焦段）失败：重写内容，让内容自然需要那个镜头；"Do not rely on FOV number alone."（见 R08）
6. 演员发僵：加与台词相连的、有动机的听者反应，不是不停乱动（见 R11）。
7. 动作卡顿或 FPS 掉：用自然 180° 快门运动节奏、稳定时间节奏、可读的冲击停顿；去掉过多的速度线、混乱镜头和"no blur"（见 R13）。
避免：一出问题就整段重写；只改数字不改内容。
注意：作者在终检里的做法是 "patch the relevant section only"——只补出问题的那一段（见 R20），与通用仓库的"排查一次只改一层"同向。

**R19 审查口径：不扣分与应扣分｜作者原则[AUDITOR COMPATIBILITY]**
写法：作者写给"独立审查者"（cinedance-auditor，我们没有这个 Skill）的口径，这里只取口径。
不应扣分（6 项）：没有单独的否定约束块；因为平台界面已管理而省略输出设置；简单特写里没有百分比坐标；在不适合的地方没用极端逆光；靠参考图而写得简短的角色描述；把做不到的视场要求换成可行的镜头设计。
应扣分（11 项）：过期的参考；杜撰的地点；多出来的角色；错误的第一帧；不可能的机位；镜头（视场）与内容不匹配；视线或身体朝向不清；复杂场景里空间交代薄弱；没要求的对白、音乐、字幕；用户没要求却藏了一个否定块；形式合规但保住了一个糟糕的镜头设计。
原文英文（逐项）：
- should not punish: no separate NEGATIVE CONSTRAINTS block; omitted OUTPUT SETTINGS because UI handles them; no percentage coordinates in a simple close-up; no extreme backlight where it does not fit; compact character descriptions relying on references; replacing an impossible requested FOV with a feasible shot design.
- should punish: stale references; invented locations; extra characters; wrong first frame; impossible camera placement; lens/content mismatch; unclear gaze/body orientation; weak geography in complex scenes; unwanted dialogue/music/subtitles; hidden negative block when user did not ask; formal compliance that preserves a bad shot design.
避免：为满足清单而加约束；用清单代替对镜头设计本身的判断（"formal compliance that preserves a bad shot design" 本身要扣分）。
注意：
- 本 Skill 的处理（非作者原文）：JIN 的槽位模板里【全局限制】和每段"限制条件"是 JIN 自己的格式，不算"藏起来的否定块"；"没有单独的否定块"在 JIN 的格式里不适用，是否改变见入口"待 JIN 定"第 4 项。
- 通用仓库的审查口径（成片复查、生成前预检）在其 T8，本仓库不复制。

**R20 终检清单（作者 16 项）与入口自检的对应｜作者原则[FINAL SELF-CHECK BEFORE OUTPUT]**
写法：作者要求输出前默默检查这 16 项（译）：
1. 这一镜有一个主导任务吗？
2. 选的视场与内容匹配吗？
3. 机位物理上可行吗？
4. 第一帧有人有物且正确吗？
5. 所有参考标签都有效且必要吗？
6. 场景参考的管辖范围写对了吗？
7. 身体朝向和视线方向清楚吗？
8. 需要时动作线保住了吗？
9. 台词确切且有限吗？
10. 演员"活着"但没有乱动吗？
11. 物理与接触落地了吗？
12. 光线适合场景吗？
13. 提示词里没有过期的上下文吗？
14. 明确要求的创意摄影／风格手法保住了吗？
15. 用户没要求时，没有自己发明创意手法吗？
16. 没有为了满足清单而加内容吗？
需要修就只补相关段落："If a fix is needed, patch the relevant section only."
入口自检 12 项的对应（本 Skill 的合并，非作者原文）：入口 1＝JIN 的"删抽象词再读"；入口 2＝作者 1 与 R01；入口 3＝作者 2、3；入口 4＝作者 4；入口 5＝作者 5、6；入口 6＝作者 7、8；入口 7＝作者 9；入口 8＝作者 10 与 R11；入口 9＝作者 11 与 R13；入口 10＝作者 12；入口 11＝作者 14、15；入口 12＝作者 13、16 与通用的"没加剧情、人物、对白、能力"。作者 16 项全部覆盖。
避免：把清单当成要填满的表格；检查通过了但镜头设计本身不可行。
