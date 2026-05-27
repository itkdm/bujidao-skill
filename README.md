# Bujidao Skill

[English](./README.en.md)

一个面向个人效率与项目开发的可复用 AI Agent Skill、Prompt 与 Workflow 精选仓库。

## 简介

`Bujidao Skill` 用来收集那些真正可复用、可迁移、可组合的 AI Agent Skill。

## Why This Repo

很多 AI Agent 的能力最后都会沉淀成一类稳定模式，例如：

- 特定任务的提示词结构
- 一套可重复执行的分析步骤
- 某类项目常见的工作流约定
- 针对特定场景的产出模板

这个仓库的目标，就是把这些模式整理成可直接复用的 skill，而不是把它们零散地留在聊天记录、临时笔记或单个项目里。

## Who It Is For

这个仓库适合以下使用场景：

- 为个人项目积累可复用的 Agent 能力
- 为团队沉淀统一的工作方式和提示模板
- 为不同代码仓库复用同一批高质量 skill
- 持续整理那些已经验证有效的 AI 工作流

## Design Principles

- 简单优先：先保证易读、易找、易维护
- 以 skill 为中心：一个目录聚焦一个能力
- 可复用优先：尽量提炼跨项目可迁移的内容
- 渐进演进：先收集，再逐步形成更稳定的规范

## 仓库结构

仓库采用扁平结构：

```text
bujidao-skill/
  skill-a/
  skill-b/
  skill-c/
  README.md
  README.en.md
  LICENSE
```

每个根目录下的 skill 文件夹都应包含该 skill 所需的内容；如果适用，建议使用 `SKILL.md` 作为主要入口文件。

## License

本项目基于 [MIT License](./LICENSE) 开源。
