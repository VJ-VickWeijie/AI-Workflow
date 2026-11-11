# 上游 Skills

四个模块来自 GitHub Awesome Copilot，锁定到同一上游提交 `eaaffd5d020b756a2777a4b1b161d2bdc126d9a0`。按项目和阶段选择；IdeaLab 的权限和审批规则约束这些模块的输出与执行。

| Skill | 适用场景 | 上游文件 blob |
| --- | --- | --- |
| [ai-team-orchestration](https://github.com/github/awesome-copilot/blob/eaaffd5d020b756a2777a4b1b161d2bdc126d9a0/skills/ai-team-orchestration/SKILL.md) | M1 组队与方案讨论 | `bdbf711aece38d17671a190abbbc7d0ba924ad85` |
| [prd](https://github.com/github/awesome-copilot/blob/eaaffd5d020b756a2777a4b1b161d2bdc126d9a0/skills/prd/SKILL.md) | M0/M2 软件产品需求 | `b19e77a252c14eed2b8fd1b506aa100fa2010fb3` |
| [create-specification](https://github.com/github/awesome-copilot/blob/eaaffd5d020b756a2777a4b1b161d2bdc126d9a0/skills/create-specification/SKILL.md) | M2 详细技术规格 | `89d998c7af65ed9b7bd06548a9a0ecc969174cbb` |
| [create-implementation-plan](https://github.com/github/awesome-copilot/blob/eaaffd5d020b756a2777a4b1b161d2bdc126d9a0/skills/create-implementation-plan/SKILL.md) | M3 技术实施计划 | `4540a479c34d298d5f7e78f24d0806652411fcf8` |

已读取并核对四个固定版本入口。组队模块包含四个 references 文档，并引用同提交下的 ai-team-producer、ai-team-dev、ai-team-qa 角色定义。迁移时应保留 references，并将 Copilot 角色映射到环境实际支持的执行上下文；合并行为须遵守项目审批。实施计划模板涉及 POSIX 命令，应按执行环境检查适用性。上游许可见[固定版本 LICENSE](https://github.com/github/awesome-copilot/blob/eaaffd5d020b756a2777a4b1b161d2bdc126d9a0/LICENSE)。

本仓库采用固定链接集成。平台安装、自动发现和实际 Skill 调用需分别验证。
