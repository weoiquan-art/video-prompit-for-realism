# video-prompit-for-realism｜真人／写实视频提示词

给 Seedance（豆包、LibTV）写真人、写实风格视频提示词的 Skill 仓库。只管真人和写实；Q 版、Chibi、动画、漫剧不在这里。

## 现状（2026-10-08，第一版）
- 内容是作者 Skill（higgsfield-seedance-prompt-builder，CINEDANCE v4.4.2）的全部章节（个别处按 JIN 的格式调整，见 evidence/classification），整理成 20 张主题卡（R01–R20）、14 条每次必读和 12 项自检。JIN 2026-10-08："虽然仅真人 但它也是视频提示词的正确指示"（说的是整份文件，没有逐条审）。
- 规则标签是"作者原则"（入口第 1、2 条是 JIN 的规则）：我们还没有自己的真人成片验证，所以不分把握等级。验证记录写在 evidence/cases/。
- 不含 cinematic-prompt-toolkit（短片全流程策划模板库）。

## 目录
- [SKILL.md](SKILL.md)：入口——流程、核心原则、每次必读 14 条、主题索引、自检、待 JIN 定、修改治理
- [topics/](topics/)：T1–T8，R01–R20 二十张卡
- [references/](references/author-cinedance-v442.md)：作者原文逐字存档（只读，不加载）
- [evidence/](evidence/README.md)：标签与来源边界、逐项分类、待 JIN 定的事项、真人成片记录格式

## 与其他仓库
- 通用提示词经验与槽位模板：[weoiquan-art/-prompit-for-ai-video-generator](https://github.com/weoiquan-art/-prompit-for-ai-video-generator)（本仓库不复制，也不修改它）。它里面的 skills/practical-case-skills/cinedance-v4 是早期 CINEDANCE V4 的整理分支，与本仓库部分重叠，关系见 evidence/README
- Q 版 Chibi 角色与声音：weoiquan-art/chibi-（有自己的流程，不动）
- Sera Canon：weoiquan-art/sera-universal；故事开发：JIN-Story-Development
