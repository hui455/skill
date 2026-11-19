# skill

个人自定义 Skills 集合。每个目录是一项可独立调用的 skill，按任务选用。

## 当前收录 · UI 设计

| Skill | 用途 | 典型场景 |
| --- | --- | --- |
| [ui-reference-analysis](ui-reference-analysis/SKILL.md) | 参考页面拆解 | 拆解竞品、找成熟案例 |
| [ui-concept-brief](ui-concept-brief/SKILL.md) | 视觉初稿提示 | 多方向视觉初稿、生图提示词 |
| [ui-component-spec](ui-component-spec/SKILL.md) | 公共组件规范 | 语义色、按钮/输入框/弹窗规范 |
| [ui-state-spec](ui-state-spec/SKILL.md) | 页面与数据状态规范 | 加载、空状态、分页失败、重试 |
| [ui-flow-review](ui-flow-review/SKILL.md) | 已有流程走查 | 原型缺页、断点、返回与恢复 |

## 使用方式

把需要的完整目录复制到客户端的 skills 目录，然后按名称调用。不同客户端的目录和调用方式不同，下表仅供参考，以各客户端官方文档为准：

| 客户端 | 项目级目录 | 调用示例 |
| --- | --- | --- |
| Codex 等支持 `.agents` 的客户端 | `.agents/skills/` | `$ui-state-spec 审查搜索页` |
| Claude Code | `.claude/skills/` | `/ui-state-spec 审查搜索页` |

不支持 Agent Skills 的客户端，也可以直接读取对应的 SKILL.md 作为规范提示。

例如：`$ui-state-spec 审查搜索页，重点看筛选无结果和下一页加载失败。`
