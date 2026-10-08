# T5 表演、物理、运动质感
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R11 角色行为系统与景别决定表演颗粒度｜作者原则[CHARACTER ACTING RULES]**
写法：
- "Acting prompts should give a playable behavior system, not a list of random tics." 每个角色定义：情绪状态；此刻想要什么；在藏什么；主导的身体节奏；2–4 个贴合这一拍的可见习惯；这一镜里什么在变。
- 听者要用有动机的微反应保持"活着"，不是随机乱动："Listeners must stay alive with motivated micro-reactions, but never random fidgeting." 作者的好例与弱例：
```text
Oli carries the reaction: bravado dimmed, shoulders dropping into a flicker of childlike slouch, a slow nostril flare swallowed back, eyes on Cal then dropping in a blink.
```
```text
Oli constantly fidgets, cracks knuckles, breathes, smirks, gestures, shifts, stares and paces.
```
- 景别决定写到哪一层。广角里把反应写成身体可读的动作："If a character is in a wide shot, write reactions as body-readable actions:" 后接列表：weight shift（重心转移）；head drop（头低下）；shoulders collapse（肩膀塌下）；hand jab（手指戳点）；step back（后退一步）；turn away（转开）；freeze（僵住）；glasses push（推眼镜）。
- 近景或中近景才写微表演："If a character is in close-up or medium close-up, microacting can include:" 后接列表：eye wetness（眼湿）；blink timing（眨眼时机）；jaw tension（下颌紧张）；throat swallow（吞咽）；lip compression（嘴唇压紧）；breath through nose（鼻息）；gaze loss and recovery（视线失落与恢复）。
- "Do not demand close-up microacting from tiny figures in a wide general plan."
避免：给远处小人物写眼神嘴角；用一串随机小动作（搓手、抖腿、踱步）代替有动机的反应；所有角色套同一组表情。
注意：与 R08 配合——表演镜头用 47°–84°；空间镜头用 84°–107°，反应写成肢体可读的动作，不要求微表情。

**R12 物理：质量（mass）、接触、重力、加速度、恢复｜作者原则[PHYSICS RULES]**
写法："Every movement must have mass, contact, gravity, acceleration and recovery." 要描述的维度：重心转移；脚的接触；摩擦；惯性；衣料滞后；头发滞后；物体阻力；液体行为；冲击的因果；环境的持续性（environmental persistence）。
- 动作戏：预备（anticipation）→ 加速 → 冲击 → 跟随 → 反冲 → 稳定落定。
- 对白戏：呼吸、姿态、手的位置、织物、雨、身体静止、路面震动、椅子吱嘎、与地面接触。
- 车辆：轮胎接地、悬挂、引擎震动、车身侧倾、湿地反光、车灯溢光。
- "Do not let style override physics."
避免：让风格压过物理；只写结果不写受力和恢复。
注意：与通用仓库的"动作有过程""接触与持有闭合"同向；本卡不复制通用仓库的卡。

**R13 180° 快门运动模糊与动作质量锁｜作者原则[180-DEGREE SHUTTER / MOTION BLUR RULE；QUALITY RULES：action；COMMON FAILURE FIXES：If action stutters or FPS drops]**
写法：用户要自然运动、FPS 稳定或动作清晰时用。"Do not write “no blur” for moving action. That can make motion strobe, judder, or look like dropped frames."
- 通用：
```text
Natural 180-degree shutter motion cadence: moving hands, heads, cloth and camera motion carry realistic cinematic motion blur during fast movement, while faces and the main action remain readable at the hold points. No smeared ghost trails, no frame-blending, no stutter, no frozen-sharp strobing.
```
- 静态对白：
```text
Stable natural motion cadence with very subtle motion blur only on small head turns and hand gestures; held faces remain sharp and readable.
```
- 打斗、追逐：
```text
Natural 180-degree shutter action cadence: fast strikes and evasions have brief directional motion blur, then resolve into sharp readable impact poses. No slow-motion, no ghosting, no duplicated limbs, no frame-skipping stutter.
```
- 动作镜头的质量锁（作者）：
```text
Sharp readable impact poses with natural cinematic motion blur during fast movement; stable temporal cadence, no ghosting, no duplicated limbs, no frame-skipping stutter.
```
  "Do not use “no blur” as a universal suffix."
- 动作卡顿或掉帧时（作者的修法）：用自然 180° 快门运动节奏、稳定时间节奏、可读的冲击停顿；去掉过多的速度线、混乱镜头和"no blur"。
避免：把"无模糊"当通用后缀；用堆速度线和混乱镜头去补动感。
注意：
- 作者把"180° 快门自然模糊"也列在 R09 的时间／运动类手法里，但本卡的用法是按需：用户要自然运动、帧率稳定或动作清晰时用，不是每个镜头都要加的装饰（整理者归纳）。
- 整理者核对：这些句子本身带 "no ghosting""no stutter" 这类否定短语，是作者自己的写法；是否改写成纯正向，见入口"待 JIN 定"第 4 项。
- JIN 的槽位模板头部有【全局限制】"全程无超帧"，含义与作者的 "no frame-skipping stutter" 接近，但"超帧"的确切意思未核实；先不改。入口"待 JIN 定"第 7 项处理两者并存。
