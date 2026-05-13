<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/棱镜分析-Prism%20Analysis-8b5e3c?style=for-the-badge&labelColor=1a1a1a">
    <img src="https://img.shields.io/badge/棱镜分析-Prism%20Analysis-8b5e3c?style=for-the-badge&labelColor=f7f5f0" alt="棱镜分析">
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT">
  <img src="https://img.shields.io/github/last-commit/zhudali956-dotcom/prism-analysis-skill" alt="Last Commit">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-8b5e3c" alt="Claude Code Skill">
</p>

<p align="center">
  四维解构分析框架 —— <b>起源 → 分野 → 格局 → 推演</b><br>
  把深度分析做成可复用的技能。
</p>

---

## 什么是棱镜分析？

🔭 **棱镜分析（Prism Analysis）** 是一个面向 Claude Code 的结构化分析技能。它像一枚棱镜，把研究对象拆解为四个维度，穿透表层信息抵达底层结构。

每一次分析都是一次**四维解构**：

| 维度 | 核心追问 |
|------|---------|
| 🌱 **起源** | 它是怎么来的？关键节点在哪？ |
| 🔀 **分野** | 在哪些岔路口做出了关键选择？竞品的选择有何不同？ |
| 🗺️ **格局** | 当前位势如何？竞争格局是什么样的？ |
| 🚀 **推演** | 未来可能走向何方？多种场景的概率与条件？ |

## 特色

- **四轮搜索** — 扫描 → 深挖 → 验证 → 补漏，级联递进
- **CRAAP 可信度评估** — 每个关键事实标注 A/B/C/D 四级可信度
- **反事实推演** — 在每个岔路口追问"如果当时选了另一条路？"
- **MD + HTML 双输出** — 排版精美的分析报告，可直接分享
- **中文原生** — 全流程中文，分析对象不限

## 安装

在 Claude Code 中，输入：

```
帮我安装这个 skill：https://github.com/zhudali956-dotcom/prism-analysis-skill
```

或手动在项目 `CLAUDE.md` 中添加：

```markdown
## Skills

- [棱镜分析](https://raw.githubusercontent.com/zhudali956-dotcom/prism-analysis-skill/main/SKILL.md) — 四维解构分析框架
```

## 使用

安装后，在对话中输入：

```
使用棱镜分析：<分析对象>
```

例如：

```
使用棱镜分析：GLP-1 药物竞争格局
使用棱镜分析：中国创新药出海策略
使用棱镜分析：SGLT2i 跨界现象
```

分析会自动运行，最终交付 MD + HTML 双格式报告。

## 技能目录

```
├── SKILL.md                 # 技能主文件（框架定义）
├── CLAUDE.md                # 安装指引
├── agents/
│   └── 搜索代理.md           # 四轮搜索代理定义
├── references/
│   └── schema.json          # 参考 schema
└── scripts/
    └── md_to_pdf.py         # MD 转 PDF 脚本
```

## 输出样例

| 报告 | 字数 |
|------|------|
| 心衰治疗 — 棱镜分析报告 | ~19,500 字（HTML） |
| Cursor 产品 — 棱镜分析报告 | ~15,300 字（MD） |
| MCP 协议 — 棱镜分析报告 | ~11,000 字（MD） |

> 更多示例见 `examples/` 目录。

---

<p align="center">
  用棱镜透视本质。<br>
  如果这个技能对你有帮助，请给它一个 ⭐️
</p>

<p align="center">
  <b>zzzzzy</b> · 棱镜分析
</p>
