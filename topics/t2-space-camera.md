# T2 空间与相机：第一帧与站位、机位翻译、运镜
条目：编号 名称｜来源标签[作者 Skill 章节]；写法；避免（由上文规则推出的提醒，不是作者原话）；注意。标签与编号索引见 [evidence/README](../evidence/README.md)。英文原话逐字取自 [作者原文存档](../references/author-cinedance-v442.md)；中文是概括与翻译，不是作者原文。

**R05 第一帧与空间站位｜作者原则[FIRST FRAME RULES；SPATIAL BLOCKING RULES]**
写法：
- 第一帧："Avoid empty openings unless explicitly requested." 角色、道具、载具、怪物、武器、关键地标，只要重要，第一帧就已在正确的世界位置可见（"If characters, props, vehicles, monsters, weapons, or key landmarks matter, they must already be visible in the first frame in their correct world positions."）。多镜序列里每一段都要写第一帧站位："For multi-shot sequences, every segment must include first-frame blocking." 第一帧用物理、可见的语言，作者例：
```text
First frame: @CAL is already foreground-left with his back shoulder cutting into frame; @OLI stands center mid-depth facing screen-left; @HORACE stands right of him, also facing screen-left; the Morris is parked behind them on the right against the bins.
```
- 站位：物理地理优先于数字坐标。总要定义：身体朝向；视线方向；屏幕方向；主体之间的距离；到地标的距离；机位侧；动作线（轴线）；景深层；与地面、墙、物件、车辆、武器、家具的接触。
- 朝向与视线分开写："Body orientation and gaze direction are separate." 作者例：
```text
Oli’s torso stays angled toward Cal on screen-left, but his eyes drop to the wet cobbles after Cal mentions Maya.
```
- 动作戏跨镜锁定屏幕左右关系："For action scenes, lock the screen-left / screen-right relationship across cuts." 对白戏保持视线，不越轴："For dialogue scenes, preserve eyelines and do not cross the line unless the user explicitly wants a disorienting flip."
避免：空镜开场却要动作；把身体朝向和视线当成同一件事。
注意：作者例里的 @标签是作者所用平台的参考引用写法；豆包、LibTV 用图号，写成"名字（对应图片N）"，见 R17。

**R06 机位写成物理位置｜作者原则[SHOT ANGLE AND VIEWPOINT SOLVER]**
写法：把角度词翻译成摄影机的物理位置。每个机位回答六问：①机位高度；②机位在哪一侧；③机位距离；④瞄准方向；⑤滚转／倾斜；⑥哪个前景物或身体部位锚定画面。"Do not rely on “high angle,” “low angle,” “side angle,” or “Dutch angle” alone."
作者的五个常用翻译（原文；括号为内容提示）：
- 地面侧向超广（贴地、近地面、斜向上看人）：
```text
Camera placed on the wet floor at the left kerb, about 0.15-0.30 m above the ground, looking sideways across the alley and slightly upward at the characters in mid-depth.
```
- 低侧角（低位、侧墙、近景墙角大）：
```text
Camera low on the side wall of the alley, about 0.5 m above the cobbles, looking across the lane at the group, with the near wall edge large in foreground.
```
- 高位倾斜反打（肩后上方、俯看、滚转、不越轴）：
```text
Camera above and behind Cal’s left shoulder, looking down toward Oli and Horace, with a 10-15° roll to the right. Cal’s shoulder remains dark foreground-left; the camera does not cross the action line.
```
- 过肩（甲的肩作遮挡锚点，乙是主要可读的脸）：
```text
Camera physically behind Character A’s shoulder, looking toward Character B. Character A occupies foreground edge as an occluding anchor, while Character B is the main readable face.
```
- 荷兰角（只滚转，不换侧、不是鱼眼）：
```text
The camera is rolled 10-20° on its optical axis while its physical position and action-line side stay unchanged. The cant affects frame tilt only; it does not mean fisheye, barrel distortion, or a changed world layout.
```
"Do not use Dutch angle to explain spatial flipping. Dutch angle is roll, not a camera-side change."
避免：只写"高角度""低角度"而不写高度、侧别、距离；用荷兰角解释左右翻转。
注意：整理者核对：作者对滚转度数有三处说法——高位倾斜反打 10–15°、荷兰角翻译 10–20°、R10 里 8–15°（风格化紧张）与 15–25°（激进失衡）；写荷兰角时按 R10 的两档选，不当精确规格。

**R07 运镜要有任务，且物理上做得到｜作者原则[CAMERA RULES]**
写法："Camera instructions must be physically possible inside the location." 先查五件事：房间或小巷有足够的机位距离吗？所要求的镜头能给出所要求的主体大小吗？机位高度与所述角度一致吗？机位这一侧能保住动作线吗？运动会不会和调度打架？
运动要有戏剧任务（作者对应）：固定（locked-off）＝必然、压迫、观察；手持落稳（handheld settle）＝真人在场、紧张、社会写实；缓慢推进＝内在压力或领悟；跟拍＝与运动动作相连；甩镜／甩切（whip pan / whip cut）＝暴烈的转场或注意力突然转移；低角度＝来自下方的体量感（mass）、威胁、脆弱；高角度＝压迫、暴露、崩塌、监视。
"Do not add camera movement just to make the prompt cinematic." "If the performance matters, keep the camera calmer." "If the action impact matters, let the camera react physically but not become chaotic."
避免：为"电影感"加运镜；对白或细腻表演配狂乱运镜；运镜和站位打架。
