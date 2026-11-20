# Book Relay｜书籍精读接力仓库

## 仓库定位

本仓库用于长期书籍阅读、精读成果归档和云端 Codex 接力。**Obsidian + 坚果云仍是主工作区，GitHub 只承担中转、版本追溯和任务交接，不取代个人知识库。**

- Obsidian：日常阅读、编辑、双链和知识管理。
- 坚果云：本地知识库的多设备同步。
- GitHub：保存阶段性 Markdown 成果、模板、索引、进度和交接规范。
- 云端 Codex：拉取仓库、按规范执行任务、更新进度并提交成果。

## 当前项目：《毛泽东选集》精读

- 阅读底本：《毛泽东选集》，人民出版社1991年第二版，四卷本。
- 当前仓库已归档编号覆盖：**第01—124篇**。
- 当前下一项：**第125篇《新解放区农村工作的策略问题》**。具体任务状态以 [唯一进度文件](work/maoxuan_project_progress.md) 为准。
- 编号覆盖表示对应文件已归档，不代表所有篇目都完成了同一轮质量返修；不要仅凭目录数量推断完成状态。
- 第14篇有一个同内容的主模板副本；第99篇版本A是已完成验收的正式稿，版本B保留为补充参考稿，两份原文均保留。

## 导航入口

- [《毛泽东选集》四卷总索引](books/maoxuan/README.md)
  - [第一卷｜第01—34篇](books/maoxuan/volume_01/README.md)
  - [第二卷｜第35—55篇](books/maoxuan/volume_02/README.md)
  - [第三卷｜第56—87篇](books/maoxuan/volume_03/README.md)
  - [第四卷｜第88—124篇](books/maoxuan/volume_04/README.md)
- [工作区说明](work/README.md)
- [当前精读进度](work/maoxuan_project_progress.md)
- [主精读模板](work/14_template_practice_on_the_relation_between_knowledge_and_action.md)
- [云端 Codex 工作规范](AGENTS.md)
- [来源与材料边界](sources/README.md)
- [初始迁移记录说明](logs/README.md)

## 目录职责

- `work/`：保留编号笔记原路径、项目进度、检查脚本和历史参考副本。为保护 Obsidian 相对链接，未经检查不要随意移动或重命名笔记。
- `books/maoxuan/`：只放四卷导航索引，不复制笔记正文。
- `sources/`：记录底本、外部来源及未上传材料的边界。
- `logs/`：记录初始迁移清单和仓库整理说明。

## 接力规则

1. 云端 Codex 每次开始前先读取 `AGENTS.md` 和 `work/maoxuan_project_progress.md`。
2. 每次只推进一个明确篇目；完成后同步更新唯一进度文件。
3. 一批任务完成并检查后再提交 GitHub，不做实时双向同步。
4. 本地与云端不要同时修改同一批文件。
5. 仓库保持 Private，只使用 `main` 分支；禁止 force push，不新增自动同步工作流。
6. 不上传整本电子书、扫描件、密钥、访问令牌或私人配置。
