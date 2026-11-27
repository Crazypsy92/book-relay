# 转录处理记录

这里保存 B 站转录从原始 ASR 到校订阅读版、候选检查和 Obsidian 整理的过程记录。它们用于追溯处理过程，不是推荐的日常阅读入口。

## 文件说明

| 文件 | 用途 | 使用时注意 |
|---|---|---|
| [转录处理状态.json](转录处理状态.json) | 9 条视频的来源、BV 号、处理状态、模型与转录文件映射 | 9 条均记录为 COMPLETED；仅表示转录文件已归档 |
| [03_候选问题清单.json](03_候选问题清单.json) | 第 03 期 13 个重复片段候选及文本位置核对 | 13/13 候选已与原始转录逐字符对齐；音频仍未核验，不能自动删除 |
| [03_校订稿_未人工核音.md](03_校订稿_未人工核音.md) | 第 03 期校订阅读稿 | 未进行人工核听，不能称为逐字核对稿 |
| [03_校订差异记录.json](03_校订差异记录.json) | 校订过程中保留的候选标记和差异信息 | 用于追溯处理动作 |
| [03_Obsidian整理版.md](03_Obsidian整理版.md) | 第 03 期观点摘要与 Obsidian 阅读版 | 其中引用的原始转录已改为链接到本专区归档 |
| [03_转录加工试验记录.md](03_转录加工试验记录.md) | 九篇视频在 Social2MD ASR 加工队列中的历史状态 | 队列状态不代表人工核音或观点分析完成度 |

## 重要边界

- 原始转录在上一级[视频转录](../视频转录/README.md)目录，作为原始材料保留。
- 处理记录不替代游戏原作，也不代表视频讲者的所有说法都已独立核验。
- 第 03 期原始 ASR 文件与“视频转录”目录中的第 08 篇内容相同，因此只保留一份，避免重复占用空间。
- 原仓库的转录检查点 ZIP 是 9 篇独立 Markdown 的打包副本，不重复保存。
- 原始阅读索引已由[游戏专区总入口](../../README.md)取代；原有 24 篇分析稿按主题融合进六份中文主文档，没有逐篇丢弃。

## 24 篇分析稿迁移映射

下表列出原分析目录中的 24 篇分析稿及其归并位置。目标文档中的内容以主题融合，不保证仍保持原文件的章节边界。

| 原分析稿文件名 | 归并后的主文档 |
|---|---|
| cyberpunk_worldbuilding_01_arasaka_rise_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_worldbuilding_02_usa_fragmentation_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_worldbuilding_03_idealist_tragedy_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_worldbuilding_04_corporate_war_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_worldbuilding_05_ordinary_life_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_ultimate_analysis_01_worldbuilding_analysis.md | [01 世界观与历史](../../资料/01_世界观与历史.md) |
| cyberpunk_ultimate_analysis_02_development_and_story_analysis.md | [02 游戏本体剧情与结局](../../资料/02_游戏本体剧情与结局.md) |
| cyberpunk_ultimate_analysis_03_cdpr_and_endings_analysis.md | [02 游戏本体剧情与结局](../../资料/02_游戏本体剧情与结局.md) |
| cyberpunk_ultimate_analysis_04_phantom_liberty_analysis.md | [03 往日之影剧情与结局](../../资料/03_往日之影剧情与结局.md) |
| cyberpunk_2077_character_dossiers.md | [04 人物志](../../资料/04_人物志.md) |
| cyberpunk_2077_supporting_character_dossiers.md | [04 人物志](../../资料/04_人物志.md) |
| cyberpunk_phantom_liberty_character_dossiers.md | [04 人物志](../../资料/04_人物志.md) |
| cyberpunk_edgerunners_anime_analysis.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_episode_analysis.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_character_analysis.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_lore_and_society.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_production_and_music.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_cross_season_comparison.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_s2_episode_themes_extended.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_02_deep_analysis.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_franchise_connections.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_edgerunners_madness_research.md | [05 边缘行者动画与衍生作品](../../资料/05_边缘行者动画与衍生作品.md) |
| cyberpunk_series_consistency_audit.md | [06 术语表与资料校对](../../资料/06_术语表与资料校对.md) |
| cyberpunk_terminology_corrections.md | [06 术语表与资料校对](../../资料/06_术语表与资料校对.md) |

## 迁移核对规则

- 9 篇原始转录以来源 SHA-256 与迁移后的文件逐篇对应；原始状态清单中的 BV 号、标题、来源链接、ASR 模型和哈希均保留。
- 24 篇分析稿的原文件名均可在对应主文档的来源/迁移记录中找到；内容按六个主题整合。
- 原阅读索引改为中文专题 README；ZIP 与重复的第 03 期原始 ASR 副本不重复保存。
- 迁移没有将未人工核听的 ASR 转录标记为正式字幕，也没有把视频观点自动升级为官方设定。
