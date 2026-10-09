# video-prompit-for-realism｜真人／写实视频提示词

给 Seedance（豆包、LibTV）写真人、写实风格视频提示词的 Skill 仓库。只管真人和写实；Q 版、Chibi、动画、漫剧不在这里。

## 现状（2026-10-09，第三版）
- 内容是作者 Skill（higgsfield-seedance-prompt-builder，CINEDANCE v4.4.2）的全部章节，整理成 20 张主题卡（R01–R20）、14 条每次必读和 12 项自检。JIN 2026-10-08："虽然仅真人 但它也是视频提示词的正确指示"（说的是整份文件，没有逐条审）。
- 作者做法与 JIN 原有做法冲突的 7 处，JIN 2026-10-09 定了怎么处理，见入口"JIN 的决定"：结构照作者的 14 块和原顺序，复制区写中文。
- 规则标签是"作者原则"（入口第 1、2 条是 JIN 的规则）。复盘、失败、成片记录等经验不放这里，归 video-exp；从经验提炼出的约束，JIN 同意后才写进卡。
- 第三版加入豆包官方 Skill（doubao-creative-drama）里写视频提示词的部分：R21（关键帧锚点、对应表、多人称呼、不用 `--`）和 R15 的标注符号，标签"豆包官方"。它的剧本、分镜、资产、选帧在短剧筹备 Skill（weoiquan-art/short-drama-prep）；原文存 video-exp。
- 不含 cinematic-prompt-toolkit：它是短剧开拍前的流程，另放"短剧筹备" Skill。

## 目录
- [SKILL.md](SKILL.md)：入口——流程、核心原则、每次必读 14 条、主题索引、自检、JIN 的决定、修改治理
- [topics/](topics/)：T1–T8，R01–R20 二十张作者卡，加 R21（豆包官方）
- [references/](references/author-cinedance-v442.md)：作者原文逐字存档（只读，不加载）
- [evidence/](evidence/README.md)：标签与来源边界、逐章去向、JIN 的决定与原话

## 与其他仓库
- 经验（复盘、失败、成片记录）：weoiquan-art/video-exp-（私有）
- 通用视频提示词 Skill：[weoiquan-art/-prompit-for-ai-video-generator](https://github.com/weoiquan-art/-prompit-for-ai-video-generator)（本仓库写提示词时不读它的规则，也不修改它；需要平台事实时看它的版本备注）。它里面的 skills/practical-case-skills/cinedance-v4 是早期 CINEDANCE V4 的整理分支，与本仓库部分重叠，关系见 evidence/README
- Q 版 Chibi 角色与声音：weoiquan-art/chibi-（有自己的流程，不动）
- Sera Canon：weoiquan-art/sera-universal；故事开发：JIN-Story-Development
