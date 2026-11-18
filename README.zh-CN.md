# AI 原生设计

[English](README.md) · [简体中文](README.zh-CN.md)

一套可复用的智能体技能：建立丰富上下文，探索真正不同的结构，制作功能原型，用动效引导注意力，并通过可观察的任务验证设计。

**以消除不确定性衡量进展，而不是以生成方案的数量衡量进展。**

## 选择语言版本

| 版本 | 技能目录 | 调用方式 |
|---|---|---|
| English | [ai-native-design](ai-native-design/SKILL.md) | `$ai-native-design` |
| 简体中文 | [ai-native-design-zh](ai-native-design-zh/SKILL.md) | `$ai-native-design-zh` |

两个版本包含对应的技能指令、动效指南、工作表和完整示例。建议选择一个版本安装，避免自动触发范围重叠。

## 安装到 Codex

克隆仓库，再将所选版本复制到技能目录。以下使用默认位置；如果设置了自定义 Codex 主目录，请改用 `$CODEX_HOME/skills`。

```sh
git clone https://github.com/imdoinggreat/ai-native-design-skill.git
cd ai-native-design-skill
mkdir -p ~/.codex/skills
```

中文版：

```sh
test ! -e ~/.codex/skills/ai-native-design-zh && cp -R ai-native-design-zh ~/.codex/skills/
```

英文版：

```sh
test ! -e ~/.codex/skills/ai-native-design && cp -R ai-native-design ~/.codex/skills/
```

若目标目录已存在，先检查内容再决定是否替换。安装后开启一个新的 Codex 对话来加载技能。

## 使用示例

```text
使用 $ai-native-design-zh 检查这个作品集的代码和参考资料。
先探索实质不同的导航模型，再比较视觉变体。
推荐一个方向；如果已有实施授权，就制作功能原型。
定义可观察的访客任务，并明确标注尚未验证的假设。
```

动效任务：

```text
使用 $ai-native-design-zh 为导出 CSV 功能设计一个 20 秒分镜。
明确焦点、阅读停留、过渡目的、空间连续性，以及减少动态效果的版本。
可以使用示意数据，但不要编造效果或性能承诺。
```

## 技能会产出什么

- 项目简报：参考、反向参考、限制与已有决策。
- 结构方案：假设、任务路径、可能的失败及取舍。
- 在任务要求下，产出选定方向的视觉变体和功能原型。
- 基于任务的验证计划，明确区分真实证据与假设。
- 可复用原则，并与项目审美偏好分别记录。

小修改按小任务处理，不会要求每次界面调整都重新设计。没有强制的框架、外部服务或可执行依赖。

## 来源与验证

本技能改编自用户提供的一篇关于 AI 辅助设计访谈的反思，将其中方法整理为可执行流程；不是访谈逐字稿，也不代表受访者背书。仓库未包含访谈引语及个人上下文。原始访谈链接未提供，因此不声称已独立核实其中的故事。

验证范围与限制见[评估记录](evaluations/README.md)。
