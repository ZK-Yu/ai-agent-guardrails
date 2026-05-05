# AI Agent Guidelines

这个仓库用于集中存放给 AI Agents 使用的行为约束、编写准则和可复用模板。

## 目录

- `Karpathy-Inspired/AGENTS.md`
  - 原版参考文件，保持不改。
- `yzk-guideline-cn/AGENTS_ori_cn.md`
  - 我们维护的中文原始基线文件。
- `yzk-guideline-en/AGENTS_ori_en.md`
  - 与中文基线对应的英文原始文件。
- `yzk-guideline-cn/CLAUDE_ori_cn.md`
  - 中文版 Claude 对应原始文件。
- `yzk-guideline-en/CLAUDE_ori_en.md`
  - 英文版 Claude 对应原始文件。

## 命名约定

- `AGENTS_ori_cn.md` / `AGENTS_ori_en.md`
  - 表示原始基线文件，作为后续扩展的起点。
- `AGENTS_<project>_cn.md` / `AGENTS_<project>_en.md`
  - 表示针对具体项目或场景做过定制的版本，例如 `AGENTS_python_cn.md`。
- 修改顺序
  - 优先修改 `yzk-guideline-cn` 下面的中文文件。
  - 中文版本确认后，再同步修改 `yzk-guideline-en` 下面对应的英文文件。

## 使用方式

新项目可以直接从 `AGENTS_ori_*` 开始，复制后再按项目需要派生出自己的版本。

如果后续某个项目需要更具体的约束，可以在这个仓库中继续新增类似 `AGENTS_python_cn.md`、`AGENTS_python_en.md` 这样的文件，保留原始基线文件不变，方便持续迭代和对照。
