# 项目大纲 Skill

这是一个面向 Codex 的个人 skill：在项目启动时建立简洁的大纲，并在后续实质性工作中持续对照，帮助项目遵循已确认的目标、范围、核心方案和关键参数。

## 功能

- 项目开始时查看现有说明，创建或沿用项目根目录的 `PROJECT_OUTLINE.md`。
- 记录核心方向、范围边界、已确认的框架与方案、重要参数和成功标准；不确定的信息标为“待确认”。
- 推进项目时读取大纲。新信息与已确认内容冲突时，先指出差异并询问是否修订；确认后再更新。
- 大纲过长时合并重复内容，并移除已确认无用或明确被取代的条目，不顺带删除其他项目资料。

## 使用

把 `project-outline/` 文件夹放入 Codex 的个人 skills 目录（通常是 `~/.codex/skills/`）。在 Codex 中可用 `$project-outline` 显式调用；也可以让 Codex 根据 skill 名称和描述自动判断是否使用。自动调用不是后台持续运行，想确保本次项目任务使用它时，请显式调用。

## 文件

- `project-outline/SKILL.md`：skill 指令
- `project-outline/agents/openai.yaml`：Codex 界面信息
