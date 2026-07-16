---
name: yoselin-ayu-illustrations
description: 为中文文章、帖子、博客、Notion 文档、方法论、流程、状态、隐喻或观点生成阿鱼风格正文配图。用于用户要求文章插图、配图建议、shot list、白底手绘、企鹅小巫师、小鱼搭档、极简解释图或改图；默认使用阿鱼小企鹅 IP、清透蓝紫与白纸手绘正文配图风格。
---

# 阿鱼魔法游乐园正文配图

将文章里的关键判断、流程、结构或状态，变成一张有故事的 16:9 横版配图。每张图只讲一个认知点，优先画成阿鱼小企鹅在岛上认真完成一件魔法小事，而不是正式的信息图或通用卡通。

## 先读参考

- `references/style-dna.md`：白底手绘正文配图的颜色、线条、留白与禁忌。
- `references/ayu-penguin-ip.md`：阿鱼小企鹅的固定外形与二维手绘转译规则；每次生图必读。
- `references/composition-patterns.md`：文章结构如何转成小岛魔法场景。
- `references/prompt-template.md`：单张生成与编辑提示词。
- `references/qa-checklist.md`：生成后检查。
- `assets/ayu-penguin-reference.png`：固定角色视觉参照；生成时应作为角色参考图。

## 工作流

1. 阅读正文，优先找认知锚点：转折、分流、闭环、对比、卡点、路径、成长或收集。
2. 用户只要策略时，输出 4-8 张 shot list：段落位置、核心意思、构图类型、阿鱼动作、场景元素、短标注词。
3. 用户要求生成时，每张图单独生成。让阿鱼承担核心动作，必要时让小鱼搭档协作；不要把多张图拼成一张。
4. 每次生图先读 `references/ayu-penguin-ip.md`，再使用 `references/prompt-template.md`；将参考头像作为角色识别参考，而非材质或场景风格参考。
5. 根据 `references/qa-checklist.md` 检查。生成结果应保存到 `assets/<article-slug>-illustrations/`，用 `01-topic-name.png` 命名，不覆盖已有文件。

## 硬规则

- 阿鱼小企鹅必须出现在画面并参与核心动作，不能只是角落贴纸。
- 不得生成小黑、黑色实心怪物、白点眼小人、黑白手绘线稿或 Ian 旧视觉。
- 不做 PPT、流程图、商业 KV、儿童海报、通用 AI 插画或密集说明图。
- 每张图使用一个新隐喻，不复刻旧案例构图。
- 中文标注保持短小；文字越少越稳定。
