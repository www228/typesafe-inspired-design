# TypeSafe 风格设计

这是一个用于网站和应用界面设计的 Codex Skill。它参考 [TypeSafe AI 官网](https://typesafe.ai/)的视觉语言，帮助你在自己的产品中运用鲜明的大字排版、浅色画布、粉色重点、方正的桌面窗口元素和技术图示。

Skill 的显示名称是 **TypeSafe 风格设计**。目录与调用标识保留为 `typesafe-inspired-design`，因此可以用 `$typesafe-inspired-design` 明确调用。

## 安装

把仓库克隆到 Codex 的个人 Skills 目录。Windows PowerShell：

```powershell
git clone https://github.com/www228/typesafe-inspired-design.git "$env:USERPROFILE\.codex\skills\typesafe-inspired-design"
```

macOS 或 Linux：

```bash
git clone https://github.com/www228/typesafe-inspired-design.git ~/.codex/skills/typesafe-inspired-design
```

如果已有同名 Skill，先检查本地改动，再决定如何更新，避免覆盖自己的修改。

## 适合什么时候用

- 为新网站、落地页或应用界面确定技术感较强的视觉方向。
- 改造已有界面的排版、色彩、信息层级与展示模块。
- 设计开发者工具、技术产品介绍、数据看板或产品演示页面。

它会根据产品受众和原有设计系统取舍元素。营销页面可以更鲜明；日常使用的应用界面会保留清晰、稳定的导航、表单和数据呈现。

## 核心设计语言

| 元素 | 用法 |
| --- | --- |
| 字体层级 | 大号无衬线标题与小号等宽标签形成对比；正文仍需易读。 |
| 颜色 | 浅色背景、深色文字、少量暖粉色重点；绿或青色仅用于有意义的数据或状态。 |
| 形状 | 方正面板、细边线、网格、窗口标题栏；遵循项目原有的组件约定。 |
| 内容 | 用真实流程、代码、图表或产品预览支撑主张。 |
| 动效 | 让动效解释状态变化，并照顾减少动态效果的用户设置。 |

Skill 不会要求照搬 TypeSafe 的品牌标志、文案、指标、插图或页面结构，也不规定固定的字体和像素值。

## 调用示例

> 用 `$typesafe-inspired-design` 为我的开发者工具首页设计首屏。保留现有品牌色和导航，重点优化标题层级与产品演示区。

> 用 `$typesafe-inspired-design` 调整这个管理后台的空状态和数据概览。保持表单、表格交互不变，让视觉更接近 TypeSafe 官网的技术编辑风格。

## 文件

- [SKILL.md](SKILL.md)：Codex 实际执行的设计指导。
- [agents/openai.yaml](agents/openai.yaml)：在 Codex 中显示的中文名称与简介。

## 参考范围

本 Skill 于 2026-09-23 根据官网可读取的内容和页面结构，以及[第三方视觉拆解](https://www.pixloop.ai/design-md/typesafe-ai)编写。当时浏览器无法完成官网的实时渲染，因此文档没有把具体字体、尺寸或动画行为当作已核实的规范。需要高度还原当前官网时，应重新查看实时页面。
