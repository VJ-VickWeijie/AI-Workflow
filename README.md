# AI-Workflow V1.1

为 [IdeaLab](https://github.com/VJ-VickWeijie/IdeaLab) 提供通用多角色协作规范。IdeaLab 保存业务资料与审批记录，AI-Workflow 独立维护流程版本。项目以完整 Git 提交 SHA 固定所用版本。

V1.1 已合并至主分支，正式版本提交为 `939ec44036d89cd91622ab96b938be9f02479026`。项目升级时记录新 SHA 并检查兼容性。进行中的项目继续遵循其已批准的固定版本，除非项目所有者批准升级。

按顺序读取 IdeaLab 根 README 与 AGENTS、目标项目资料、项目固定的本仓库版本，然后恢复里程碑与授权。新会话、交接或新主要里程碑应重新核对。

- [七阶段执行协议](workflows/LIFECYCLE.md)
- [组队与辩论](agents/TEAM.md)
- [模型选择规则](policies/MODEL_SELECTION.md)
- [审批、质量与回退](policies/GATES.md)
- [上游 Skills 与使用边界](skills/README.md)
- [里程碑与交接模板](templates/MILESTONE.md)
- [Work / Codex 启动与交接](adapters/WORK_CODEX.md)
- [试运行用例](tests/BOOTSTRAP.md)

规范定义了显式启动、按授权自治和证据记录。自动发现、自动审批门禁、跨环境调度及每个工具中按角色切换模型的能力仍需在对应环境分别验证。