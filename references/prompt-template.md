# 生图与改图提示词模板

## 工具调用要求

每张图单独调用当前环境可用的图像生成或编辑工具。

必须实际附带 `../assets/devon-cat-character-sheet.png` 作为身份主参考。再根据 [character-library.md](character-library.md) 选择至多一张场景副参考；复合场景只有在确有必要时才使用两张副参考。

不要只在文字中提到文件。不要默认把六张角色图一次全部传入。

批量任务先为每张图指定一套完整造型。身份主参考控制脸、耳、眼、毛色、比例和单尾；副参考可以明确覆盖签名服装。除非用户要求统一制服，一组 3 张以上不要全部使用绿色棒球夹克。

## 通用参考说明

把下面这段放在生成提示词前部：

```text
Reference hierarchy:
- The attached three-view Devon Cat sheet is the canonical identity reference. It controls species, face, proportions, cream-white fur, oversized ears with pale-pink inner ears, deep-blue eyes, small pink nose, and one curled cream tail.
- The attached context sheet, if present, is secondary. Use only the requested pose, expression, approved outfit, or prop from it.
- Ignore and do not reproduce any orange background, FRONT/SIDE/BACK labels, three-view lineup, eight-character grid, two-row layout, equal spacing, white sprite-sheet composition, unrelated pose, unrelated outfit, or decorative icon from the references.
- Show one Devon Cat unless the user explicitly requests multiple characters or a character sheet.
```

## 正文配图模板

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

{通用参考说明}

Outfit mode:
{signature outfit / approved contextual outfit from the selected secondary reference}

Character behavior:
Devon Cat is a curious, capable content explorer and builder. The character must perform the action that makes the concept work, not pose beside a finished diagram. Cute and friendly, but not babyish, not a sticker, not a mascot poster.

Theme:
{正文配图主题}

Core idea:
{唯一核心意思}

Visual metaphor:
{为当前内容新设计的物理隐喻}

Composition:
{德文猫的位置、动作、情绪、主要物件、信息如何变化}

Chinese handwritten labels:
{3–6 个短标注}

Visual DNA:
Pure or near-pure white background. Clean hand-drawn line art with slight natural wobble. Lots of empty space. Keep the Devon Cat in its approved restrained colors. Use forest green for primary structure, warm orange for the key action or path, deep blue for secondary system notes, and warning red only when necessary. The whole subject occupies about 40%–65% of the canvas.

Constraints:
One image explains one concept. No top-left type title. No PPT infographic, formal flowchart, course slide, dense UI, photorealism, glossy 3D, anime comic page, children's picture-book scene, or commercial mascot poster. Do not add extra tails, ears, limbs, bags, or characters. Do not turn the character into another animal or a human child in a costume. Do not copy old Xiaohei compositions or copy a pose-sheet panel literally. Invent a fresh metaphor for this content.
```

## 小红书 3:4 封面模板

```text
Create one finished Xiaohongshu cover illustration in an exact 3:4 portrait composition, designed for 1080 × 1440 px.

{通用参考说明}

Cover family:
{judgment / emotional resonance / tutorial steps}

Exact Chinese title:
“{8–18 个汉字，逐字渲染}”

Required complete outfit from the selected context reference:
{明确写出整套服装；如需变化，补充 No varsity jacket}

Character action:
{德文猫亲自完成能证明标题的动作}

Layout:
Large title in the upper area, normally 2–4 lines. Character and core prop occupy the lower half. Keep at least 8% safe margin on every edge. Keep the title, Devon Cat face, and key prop readable inside the centered square region. Strong phone-feed hierarchy and clean negative space.

Supporting labels:
{0–3 个短标签；逐字列出；没有就写 none}

Typography:
Bold, highly legible Chinese display lettering with slight hand-drawn warmth. Render only the exact title and requested labels. No English subtitle, author, platform logo, watermark, or extra headline.

Visual style:
Premium clean hand-drawn editorial illustration with subtle paper texture. Use the Devon Cat palette plus at most two contextual accent colors. Cute and intelligent, not babyish. No PPT, dense infographic, UI, glossy 3D, or sprite-sheet layout.
```

## 公众号正文配图模板

```text
Create one finished WeChat Official Account article body illustration in a wide 16:9 horizontal composition, designed for 1080 × 608 px.

{通用参考说明}

Core idea:
{正文里的唯一认知关系}

Required complete outfit from the selected context reference:
{学习 / 情绪 / 生活 / 运动中的一套完整造型}

Character action and physical relationship:
{德文猫如何让输入、变化或结果发生}

Composition:
Keep all important content inside the central 82% width and central 75% height. Devon Cat occupies about 20%–35% of the canvas. Leave at least 30% calm white space. No top-left type title, poster headline, paragraph, border, or course-slide layout.

Exact Chinese labels:
{0–3 个，每个 2–6 个字；逐字列出}

Typography:
Only the requested short labels. No other text, English, author, or watermark.

Visual style:
Premium clean hand-drawn Chinese editorial illustration on pure or near-pure white paper. Fine slightly wobbly linework, restrained Devon Cat colors, and one warm-orange action path. Not a formal flowchart, UI, PPT, commercial poster, or glossy 3D.
```

## 公众号 2.35:1 头图模板

```text
Create one WeChat Official Account lead cover in an exact 2.35:1 horizontal composition, designed for 900 × 383 px.

Keep the Devon Cat face, title keyword, and essential brand recognition inside the centered 383 × 383 px safe region. Use the left and right wings only for crop-safe background, atmosphere, or secondary paths. Do not stretch a 16:9 body illustration.

Exact title:
“{最多 12 个汉字，通常不超过两行}”
```

## 单角色 IP 素材模板

```text
Generate one standalone full-body Devon Cat IP character asset on a pure white background, default 4:5 portrait.

{通用参考说明}

Purpose:
{头像 / 社交互动 / CTA / 表情 / 动作素材 / 其他}

Pose and expression:
{一个清楚动作 + 一个主要情绪}

Approved outfit:
{签名造型或角色库中的一套完整造型}

Composition:
One character only, fully visible from ears to shoes unless a 1:1 head-and-shoulders portrait is requested. Keep a clean silhouette and comfortable white margin. No caption, no environment, no grid, no other poses. Include only the small symbol or prop explicitly requested.
```

## 场景素材模板

```text
Generate one clean Devon Cat scene illustration.

{通用参考说明}

Scene category:
{seasonal lifestyle / work-study / emotion / sports-entertainment}

Situation:
{具体情境}

Character action and emotion:
{动作与情绪}

Approved outfit and prop:
{从副参考图选择的一套造型与必要道具}

Keep one focal action, one character, a pure or near-pure white background, restrained props, and generous negative space. Do not reproduce the reference grid or add unrelated outfits and icons.
```

## 批量动作或表情

默认逐张生成：

```text
Create {数量} separate Devon Cat character assets, one generation and one file per pose. Keep identity and outfit consistent across the set. Vary only the requested pose and expression. Do not combine them into a contact sheet or grid.

Pose list:
{动作与情绪列表}
```

平台批量案例还要先写造型分配：

```text
Outfit rotation plan:
1. {主题} — {副参考} — {完整造型}
2. {主题} — {副参考} — {完整造型}
3. {主题} — {副参考} — {完整造型}

Keep the same Devon Cat identity across the set, but do not reuse the same signature outfit for every image. Vary outfit, pose, expression, and prop according to the content.
```

只有用户明确要求合集图时：

```text
Create one clean character reference sheet containing exactly {数量} Devon Cat poses in a clearly separated grid. Keep the same identity, scale, line style, and chosen outfit across all cells. Do not introduce extra poses, captions, or unrelated props.
```

## 修正角色漂移

```text
Edit the image while preserving the core composition and concept. Correct the Devon Cat identity using the attached canonical three-view sheet: cream-white fur, oversized upright ears with pale-pink inner ears, deep-blue eyes, small pink nose, large-head small-body proportions, and exactly one curled cream tail.

Preserve the current outfit only if it matches the signature outfit, the selected approved context sheet, or the user's explicit request. Remove species drift, wrong eye color, mixed outfits, extra limbs, extra tails, duplicate bags, grid artifacts, character-sheet labels, or unrelated reference icons. Do not import the orange background, three-view layout, or eight-character grid.
```

## 更换为已确认造型

```text
Edit only the Devon Cat outfit and necessary context prop using the attached approved context sheet. Keep the same character identity, face, body proportions, action, composition, background, and aspect ratio. Use one complete outfit from the reference; do not mix clothing pieces from multiple examples or add unrelated icons and poses.
```

## 去掉标题或错字

```text
Edit the provided illustration. Remove only the handwritten text “{要删除的文字}” and its underline or arrow if specified. Fill the area with the same clean white background. Preserve the Devon Cat, all other labels, actions, objects, line style, composition, aspect ratio, and image quality. Do not add new text or objects.
```

## 从旧角色图重新设计

```text
Redesign this illustration around the same core idea, using the attached canonical Devon Cat sheet and the selected context sheet as identity and pose references. Replace the old actor with Devon Cat and adapt the action so the cat genuinely drives the concept. Do not trace, recolor, or paste the new character over the old one. If the old composition depends on another character's specific metaphor, invent a new physical metaphor while preserving the intended meaning. Keep a clean white-background hand-drawn illustration style.
```
