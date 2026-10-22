# tech-book-writer-skills

`tech-book-writer` 是一个 Codex skill，用于撰写和修改中文后端架构文章。它参考《亿级流量系统架构设计与实战》的知识组织与讲解方法，帮助规划章节、解释概念、梳理技术推导并检查行文。生成的内容应是原创内容，不复述原书。

## 安装

将本仓库克隆到 Codex 的 skills 目录，并把目录命名为 `tech-book-writer`。默认位置是 `~/.codex/skills/tech-book-writer`；如果设置了 `CODEX_HOME`，则使用 `$CODEX_HOME/skills/tech-book-writer`。

## 使用

在 Codex 中指定 skill，并给出主题、读者基础和希望的详略程度。例如：

> $tech-book-writer 面向只听过 Kubernetes 名称的读者，写一篇从基本概念讲到典型工作流程的技术文章。请分章，首次出现的术语要解释清楚。

也可以用它修改现有稿件：

> $tech-book-writer 请检查这篇文章的章节顺序、段落衔接和术语解释，并直接修改正文。

普通写作可以直接使用仓库中的 [SKILL.md](SKILL.md) 和 [references](references)。只有需要重新分析参考书或更新写作档案时，才需要另行提供 PDF。
