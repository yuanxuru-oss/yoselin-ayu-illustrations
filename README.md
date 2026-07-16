# 阿鱼魔法设计正文配图

为中文文章和内容文档生成阿鱼正文配图的 Codex Skill。它把一个观点、流程、状态或隐喻，转成一张白底、彩铅手绘、带一点星月魔法的设计解释图。

固定主角是阿鱼：蓝紫小企鹅小巫师、粉腮、黄色小椭圆鼻子、无嘴巴、软塌宽帽沿的星月巫师帽，以及横向游动的灰蓝小鱼搭档。阿鱼是一位正在解决问题的魔法设计师：用鱼棒绘制虚线、整理卡片、修补断点、压缩想法或搭建信任桥。

## 视觉方向

- 干净白底与大片留白，黑色不规则铅笔线、彩铅颗粒和轻微试画痕。
- 清透蓝紫、暖白、粉、黄色星月，搭配少量蓝橙红中文批注。
- 小星、月亮、蓝紫虚线与光点只围绕动作出现，不画完整场景或重特效。
- 不做羊毛毡、3D、写实、游戏场景、PPT、通用儿童插画或光滑矢量风。

## 样例

最终 8 张视觉样例位于 `yoselin-ayu-illustrations/assets/examples/`：

```text
01-two-breakpoints.png
02-sorting-by-purpose.png
03-one-source-many-forms.png
04-handoff-path.png
05-idea-well.png
06-idea-press.png
07-content-fermentation.png
08-trust-bridge.png
```

生成时上传 `yoselin-ayu-illustrations/assets/ayu-penguin-reference.png`，并将上述样例作为画风与角色动作参考。

## 安装

将 `yoselin-ayu-illustrations/` 复制到 `${CODEX_HOME:-$HOME/.codex}/skills/`。

## 使用

```text
Use $yoselin-ayu-illustrations 为这篇中文文章设计并生成 4 张阿鱼魔法设计正文配图。使用白底彩铅手绘、黄色小鼻子无嘴、参考图同款宽帽沿星月帽、鱼棒和灰蓝小鱼搭档。
```

也可以先做配图策略：

```text
Use $yoselin-ayu-illustrations 先不要生图。请为下面文章输出 5 张阿鱼配图 shot list，每张写清阿鱼的设计动作、小鱼的协作动作和一个轻量魔法结果。
```

## 版权与致谢

本仓库保留原始项目的 LICENSE 与 NOTICE。阿鱼角色形象、品牌设定及新增内容归 Yoselin 所有。
