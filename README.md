# skill

五个按需使用的 UI 设计规范。设计顺序由使用者决定，每项都可独立加载。

| Skill | 用途 |
| --- | --- |
| [ui-reference-analysis](ui-reference-analysis/SKILL.md) | 参考页面拆解 |
| [ui-concept-brief](ui-concept-brief/SKILL.md) | 视觉初稿提示 |
| [ui-component-spec](ui-component-spec/SKILL.md) | 公共组件规范 |
| [ui-state-spec](ui-state-spec/SKILL.md) | 页面与数据状态规范 |
| [ui-flow-review](ui-flow-review/SKILL.md) | 已有流程走查 |

使用时复制需要的完整目录到项目的 `.agents/skills/`，再在支持 Agent Skills 的客户端按名称调用。也可以单独读取对应的 SKILL.md 作为规范提示。

例如：`$ui-state-spec 审查搜索页，重点看筛选无结果和下一页加载失败。`
