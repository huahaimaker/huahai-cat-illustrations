# Huahai Cat Illustrations

用“花海猫”个人 IP 为中文文章生成 16:9 白底手绘正文配图的 Agent Skill。

它会先理解文章中的认知锚点，再为每张图设计一个由花海猫亲自推动的物理隐喻。角色身份由内置三视图约束，避免生成时变成普通白猫、改变服装或带入设定图背景。

## 能做什么

- 分析文章并输出 1–9 张配图 shot list。
- 直接生成花海猫正文配图，不把多张图拼在一起。
- 用角色三视图保持尖耳、蓝眼、绿色夹克、卡其工装裤、斜挎包与卷尾等身份锚点。
- 修正角色漂移、错字、多余肢体和参考图污染。
- 为 Markdown / Obsidian 文章保存图片并插入相对链接。

## 视觉语言

- 16:9 横版，纯白或近纯白背景。
- 彩色角色搭配轻手绘线稿和大量留白。
- 奶白、森林绿、卡其、深蓝、暖橙的克制配色。
- 一张图只表达一个判断、动作、状态或隐喻。
- 不是 PPT 信息图、角色海报、商业 3D 或儿童绘本。

## 安装

使用通用 skills 安装器：

```bash
npx skills add huahaimaker/huahai-cat-illustrations
```

或手动克隆到 Codex skills 目录：

```bash
git clone https://github.com/huahaimaker/huahai-cat-illustrations.git \
  ~/.codex/skills/huahai-cat-illustrations
```

## 使用

```text
Use $huahai-cat-illustrations 为这篇中文文章设计并生成 4 张花海猫正文配图。
```

只做规划：

```text
Use $huahai-cat-illustrations 先不要生图，分析这篇文章值得配置哪些图，输出 5 张左右的 shot list。
```

## 目录结构

```text
.
├── SKILL.md
├── agents/openai.yaml
├── assets/huahai-cat-character-sheet.png
└── references/
    ├── character-ip.md
    ├── composition-patterns.md
    ├── prompt-template.md
    ├── qa-checklist.md
    └── visual-dna.md
```

## 许可与署名

Skill 指令与文档采用 MIT License。花海猫角色设定图不包含在 MIT 授权范围内，具体见 [ASSET-LICENSE.md](ASSET-LICENSE.md)。

文章配图工作流改编自 Ian 的 [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations)，原项目采用 MIT License；完整署名与上游许可见 [NOTICE.md](NOTICE.md) 和 [LICENSE-IAN](LICENSE-IAN)。
