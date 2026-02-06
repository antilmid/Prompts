[English Version](./README.en.md) | [中文版本](./README.md)

---

# Prompts

这里收集了一些可复用的「提示词 / Prompt」模板，面向日常研发工作场景（如 Git 分支命名、TypeScript 类型声明生成等）。每个 Prompt 都尽量做到开箱即用：直接复制到对话的系统/角色设定里即可使用。

## 目录结构

- `branch-named/`
  - `index.md`：中文版本 Prompt（分支命名）
  - `index-en.md`：英文版本 Prompt（内容可能仍约束“用中文输出”，以文件内规则为准）
- `ts-type-declaration/`
  - `index.md`：中文版本 Prompt（TS 类型声明）
  - `index-en.md`：英文版本 Prompt（内容可能仍约束“用中文输出”，以文件内规则为准）

## 使用方式

1. 进入对应目录，打开 `index.md`（或 `index-en.md`）。
2. 将全文复制到你使用的 AI 工具的「系统提示词 / 角色设定 / 指令」区域。
3. 按 Prompt 的“任务/输出要求”直接输入你的需求文本即可。


## 维护约定（建议）

- 每个 Prompt 尽量自包含：包含角色、任务、输出限制/示例。
- 输出规则写清楚并可验证：例如“只输出分支名”“只输出代码”等。
- 中英文版本保持语义一致：如需强制中文输出，以 Prompt 内规则为准。