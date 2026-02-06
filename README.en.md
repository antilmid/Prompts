[English Version](./README.en.md) | [中文版本](./README.md)

---

# Prompts
This repository collects reusable **Prompt templates** tailored for daily R&D workflows (e.g., Git branch naming, TypeScript type declaration generation). All prompts are designed to be **out-of-the-box**: simply copy the content to the system/role setting section of your chat interface and start using it immediately.

## Directory Structure
- `branch-named/`
  - `index.md`: Chinese version of the prompt (for branch naming)
  - `index-en.md`: English version of the prompt (output may still be restricted to Chinese, subject to the rules specified in the file)
- `ts-type-declaration/`
  - `index.md`: Chinese version of the prompt (for TS type declaration)
  - `index-en.md`: English version of the prompt (output may still be restricted to Chinese, subject to the rules specified in the file)

## Usage Instructions
1. Navigate to the corresponding directory and open `index.md` (or `index-en.md`).
2. Copy the entire content to the **System Prompt / Role Setting / Instruction** section of your AI tool.
3. Enter your requirement text directly in accordance with the prompt's **task/output requirements**.

## Maintenance Conventions (Recommendations)
- Make each prompt as **self-contained** as possible: include the role definition, task description, and output constraints/examples.
- Define clear and verifiable output rules: e.g., "Output only the branch name", "Output code only", etc.
- Keep the Chinese and English versions **semantically consistent**: if forced Chinese output is required, follow the rules specified in the prompt itself.