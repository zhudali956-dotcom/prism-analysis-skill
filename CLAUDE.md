# 棱镜分析（Prism Analysis）

四维解构分析框架：**起源 → 分野 → 格局 → 推演**

## 安装方式

### 方式一：CLAUDE.md 引用（推荐）

在项目根目录的 `CLAUDE.md` 中加入：

```markdown
## Skills

- [棱镜分析](https://raw.githubusercontent.com/zhudali956-dotcom/prism-analysis-skill/main/SKILL.md) — 四维解构分析框架
```

### 方式二：本地文件

克隆仓库到本地：

```bash
git clone https://github.com/zhudali956-dotcom/prism-analysis-skill.git
```

然后在 Claude Code 中通过 `/skill` 命令引用 `SKILL.md` 路径。

## 使用方法

在对话中输入：

```
使用棱镜分析：<分析对象>
```

框架会自动执行四轮搜索，按起源→分野→格局→推演四维解构分析对象，输出 MD + HTML 格式报告。

## 输出格式

- Markdown 报告（.md）
- HTML 报告（.html，含样式，移动端适配）
- 可选：Word 文档（.docx）

## 框架结构

| 维度 | 核心问题 |
|------|---------|
| 起源 | 时间线叙事，关键节点 |
| 分野 | 时间与竞品融合的决策岔路口 |
| 格局 | 竞品位势图 + 商业模式拆解 |
| 推演 | 多场景推演 + 概率判断 |

## 来源评估

信息可信度采用 CRAAP 五维评分：
- **[A级]** 官方/学术 — 顶刊论文、官方指南、政府报告
- **[B级]** 权威媒体 — 专业媒体、权威数据库
- **[C级]** 行业分析 — 行业报告、付费数据摘要
- **[D级]** 社区讨论 — 仅用于口碑/体验信息
