# qclaw-skill-creator 技能创建工具（中文版）

创建新 OpenClaw 技能的指南和工具包。实现 Anthropic 4 条硬约束并提供工程模板。

🌐 **语言**: [English](README.md) | **简体中文**（当前）

## 描述

为 OpenClaw 框架提供创建新技能的方法论和模板。

### 核心特性

- **Anthropic 4 条硬约束**：描述作为路由、references 分层、缺口驱动、确定性步骤用脚本
- **技能模板**：标准化的 SKILL.md / references / scripts 结构
- **审计协议**：评估现有技能的工具
- **自我学习**：从技能使用反馈中迭代改进
- **工程模板**：Python 脚本、文档模板

### 适用场景

- 创建自定义 OpenClaw 技能
- 评估现有技能的质量
- 标准化技能设计流程
- 推广团队内部的最佳实践

## 安装

将整个 qclaw-skill-creator/ 目录复制到 OpenClaw 技能目录（通常是 ~/.openclaw-skills/qclaw-skill-creator/）。

## 目录结构

\qclaw-skill-creator/
├── SKILL.md          # 技能主定义（先读这个）
├── references/       # 参考文档
├── scripts/          # 可执行工具
├── _knowledge/       # 知识库
└── _meta.json        # 技能元数据
\
## 许可证

MIT — 详见 [LICENSE](LICENSE)

---

## 🙋 致中国用户

本仓库同时提供英文和简体中文文档。如果你发现任何翻译问题，欢迎提 Issue 或 PR。
