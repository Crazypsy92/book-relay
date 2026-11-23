# Book Archive｜长期书籍资料库

## 仓库定位

本仓库用于长期保存书籍资料、精读笔记、来源索引和阅读进度。**GitHub 是长期归档副本，不是任务完成后清空的临时中转目录。**

- Obsidian + 坚果云：日常阅读、编辑、双链和个人知识管理。
- GitHub：长期保存已经归档的书籍资料、Markdown 笔记、索引、来源记录和进度；项目阶段结束后继续保留。
- Codex：按仓库规范继续精读、核对、整理和提交。

除用户明确要求外，不因项目结束、任务完成或目录整理而删除已有书籍资料和有效笔记。

## 当前项目：《毛泽东选集》精读

- 阅读底本：《毛泽东选集》，人民出版社1991年第二版，四卷本。
- 当前已归档编号：**第001—157篇，已完成**；第157篇《唯心历史观的破产》（1949年9月16日，第四卷第1509—1517页）为人民出版社1991年第二版目录所列卷末篇。
- 归档数量只表示文件已保存，不代表每篇都完成了同一轮质量返修；具体状态以 [唯一进度文件](work/maoxuan_project_progress.md) 为准。
- 正式篇目文件统一使用三位数字前缀，并直接存放在对应卷目录：`books/maoxuan/volume_01/` 至 `volume_04/`；每卷内部按编号自然排序。
- 第99篇正式稿列入第四卷编号篇目；补充参考稿单独归档在 [`references/099_supplementary_reference.md`](books/maoxuan/volume_04/references/099_supplementary_reference.md)，不计入篇目数量。

## 跨文体经典精读

- 阅读方法与体裁路由遵循现有 [`unified-content-notes` Skill](https://github.com/Crazypsy92/unified-content-notes)：分别识别处理动作、文本结构和文体视角，按需复用模块，不另建统一模板。
- 已结项作品：马克思《路易·波拿巴的雾月十八日》；[阅读导览](books/marx/eighteenth_brumaire/README.md)、[精读主笔记](books/marx/eighteenth_brumaire/reading_notes.md)。两轮阅读与全书综合分析完成后停止推进，历史记录保留在唯一进度文件。
- 已结项作品：毛泽东《寻乌调查》，社会调查报告；[阅读导览与九单元路线](books/maozedong/xunwu_investigation/README.md)、[精读主笔记](books/maozedong/xunwu_investigation/reading_notes.md)、[唯一进度文件](work/classics_reading_progress.md)。九个单元、全书综合与格式 / 链接验收已完成；阅读依据为共产党员网公开转录，1993年纸本仍待校。原接力任务已停用；原每小时 / Asia/Shanghai 计划参数保留但不再自动执行。
- 已按用户要求将《寻乌调查》正式笔记调整为读者视角；后续精读以具体文本和阅读过程为主线，第一人称适量自然使用，避免第三人称会议纪要腔，也避免机械堆叠“我读到 / 我认为”。小说笔记优先参考用户认可的《文城》连续场景叙事节奏。
- **读者视角返修已完成，原文事实核验进行中：**鲁迅《呐喊》《彷徨》《故事新编》33篇合订本中，《阿Q正传》专题保持不变，其余32篇完成叙述深化；现有 **18/32篇**已对照可访问原文核对并修订，本轮新增《幸福的家庭》《肥皂》《长明灯》，另14篇待核验。已补正早期笔记对场景、人物行动、关键对话和结尾的遗漏或过度概括。核验规范见 [unified-content-notes Skill](https://github.com/Crazypsy92/unified-content-notes)。[唯一正式正文](books/luxun/lu_xun_novels_integrated.md)；[阅读进度](work/classics_reading_progress.md)。当前核对不等于不同纸本 / 初刊版本逐字校勘，原接力任务继续暂停。
- 已结项作品均遵循来源边界：不上传整本原著，不将一个版本的页码移植到另一版本；当前状态只以唯一进度文件为准。

## 导航入口

- [鲁迅三部小说集合订本｜呐喊·彷徨·故事新编（含阿Q专题深读）](books/luxun/lu_xun_novels_integrated.md)

- [《毛泽东选集》四卷总索引](books/maoxuan/README.md)
  - [第一卷｜已归档第001—015篇](books/maoxuan/volume_01/README.md)
  - [第二卷｜已归档第016—055篇](books/maoxuan/volume_02/README.md)
  - [第三卷｜已归档第056—087篇](books/maoxuan/volume_03/README.md)
  - [第四卷｜已归档第088—157篇（全卷完成）](books/maoxuan/volume_04/README.md)
- [工作区说明](work/README.md)
- [当前精读进度](work/maoxuan_project_progress.md)
- [跨文体经典精读进度](work/classics_reading_progress.md)
- [云端 Codex 工作规范](AGENTS.md)
- [来源与材料边界](sources/README.md)
- [初始迁移记录说明](logs/README.md)

## 目录职责

- `work/`：项目进度、跨文体阅读进度与方法记录，以及质量检查脚本；正式精读笔记统一归档在 `books/`。
- `books/maoxuan/`：按人民出版社1991年第二版实际卷次保存正式精读笔记，并维护四卷索引。
- `books/marx/`：经典作品的阅读导览、正式精读主笔记、章节结构和分段计划。
- `books/luxun/`：鲁迅三部小说集合订本；单篇专题深化优先融合进已有合订本，避免重复正文。
- `sources/`：记录底本、外部来源及未上传材料的边界。
- `logs/`：保留初始迁移清单和历史整理记录。

## 接力与归档规则

1. 毛选任务开始前读取 `AGENTS.md`、四卷总索引、对应卷索引和 `work/maoxuan_project_progress.md`；跨文体任务读取其独立进度文件。
2. 每次只推进一个明确篇目；完成后更新唯一进度文件和对应卷索引。
3. 一批任务完成并检查后再提交 GitHub，不做实时双向同步。
4. 本地与云端不要同时修改同一批文件。
5. 仓库保持 Private，只使用 `main` 分支；禁止 force push，不新增自动同步工作流。
6. 不上传密钥、访问令牌、私人配置或未经授权的整本电子书/扫描件。
7. 已归档资料长期保留；只有用户明确授权时才删除文件。
