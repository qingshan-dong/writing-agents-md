# writing-agents-md

把 AGENTS.md 写成**短入口**：每类任务都要用的才留在主文件，其余按情境下沉，每个约定只有一个来源。

一个帮你新建、审阅、修改常驻 Agent 规则文件的 skill，适用于 AGENTS.md、CLAUDE.md、GEMINI.md、Cursor rules 等同类文件。

## 它做什么

六步流程：提重点 → 找冲突 → 归类下沉 → 标删除 → 出稿与走读 → 交付。三种模式：

| 模式 | 适用 | 交付 |
| --- | --- | --- |
| 新建 | 还没有规则文件 | 候选稿 |
| 审阅 | 只要意见 | 问题与建议，不改文件 |
| 修改 | 按授权动手 | 改动（你通过 diff 审阅） |

配套文章：《如何写好一个 AGENTS.md》—— https://mintpick.app/posts/writing-agents-md

## 安装

**方式一：skills CLI（推荐）**

```bash
npx skills add qingshan-dong/writing-agents-md
```

**方式二：zip 直链安装**

```bash
npx skills add https://mintpick.app/downloads/writing-agents-md.zip
```

**方式三：手动**

下载 zip 解压，把 `writing-agents-md` 文件夹放进你的 Agent 工具的 skills 目录；或直接 clone 本仓库使用。

## 使用

安装后，在 Agent 工具里点名即可，例如：「用 writing-agents-md 审阅我的 AGENTS.md」「用 writing-agents-md 帮我从零写一份」。

## 安全

纯 Markdown，无脚本、无可执行代码，不联网、不收集任何数据。安装前可直接通读 `SKILL.md` 全文核对。

## 版本

见 [CHANGELOG.md](CHANGELOG.md)。
