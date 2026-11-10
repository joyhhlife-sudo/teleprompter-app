# VoiceCue：前后双摄八大场景 × 中文与英文 Image 2 提示词

**更新日期：2026-11-10。** App：随声提词器 / VoiceCue: Teleprompter；Bundle ID：com.xtools.voicecue；Team ID：RYYV52Z7L3。

## 素材包与如何使用

Mac 根目录：`/Users/app/01-xcode/06_提词器/VoiceCue_Marketing_2026-11-10/`

本轮新增 8 大场景 × 中英文各一张：**16 张 1206 × 2622 PNG 合成宣传示意图**，另有对应的 16 篇 TXT 中英文配音稿。示意图由摄影素材与排版程序合成，不是实拍双摄画面。

选择一个场景、选择一种语言，在 ChatGPT Image 2 中同时上传：① `website/assets/icon.png` 真实 App 图标；② `screenshots/{语言}/VoiceCue_{语言}_practice.png` 已有的真实 iOS 提词界面；③ `scenarios/{语言}/VoiceCue_{语言}_{序号}_{场景}.png` 场景构图参考。**必须把中文和英文截图分开输入**；不要直接用中文 UI 加英文广告标题。

### 统一母提示词 — 中文

> 为 iPhone App Store 设计一张精致、自然的 **1206×2622** 像素竖版宣传图片。产品是「随声提词器」，中文副标题「开口即跟随，轻松拍口播。」画面展示兼容设备的前摄+后摄模式，前摄为自然光下的讲解者，后摄为用户指定场景主体。模拟苹果原生 App 的实际使用氛围，背景采用暖白、雾蓝、适量暖杏色；手机屏幕采用提供的真实中文 App 截图作为不可随意改动的 UI 依据。允许优化摄影场景、人物、排版和设备外形，禁止幻想系统按钮、伪造实际录制效果、引入未开发功能，避免过分 AI 发光与文字乱码。正式替换为真机双摄画面前，请保留「宣传场景示意」标注。

### Shared master prompt — English

> Design a polished 1206×2622 iPhone App Store portrait for **VoiceCue: Teleprompter** with subtitle **Speak Naturally, Record Easily**. The front camera frames a natural, approachable on-camera host; the rear camera frames the subject of this scene. Use the uploaded GENUINE English-language VoiceCue UI as the source of truth for all controls and text. Light mist-blue, warm ivory, restrained apricot accents, natural photographic lighting, clear large typography. The scene mockup is a composition reference, not a real dual-camera capture. Do not invent app features or corrupt UI; preserve an “Illustrative concept” notice until replaced with real footage.

## App Store 每个语言 10 张主图（建议排序）

| 序号 | 中文主题 | English | 本地素材 |
|---|---|---|---|
| 01 | 智能语音跟读 | Voice-following | AppStore_10/{lang}/01_voice_follow.png |
| 02 | 稿件库 | Script library | AppStore_10/{lang}/02_script_library.png |
| 03 | 文稿编辑 | Script editor | AppStore_10/{lang}/03_script_editor.png |
| 04 | 设置和提词样式 | Settings | AppStore_10/{lang}/04_app_settings.png |
| 05 | Pro 功能 | Pro features | AppStore_10/{lang}/05_pro_features.png |
| 06 | 独立提词练习 | Practice | AppStore_10/{lang}/06_practice_mode.png |
| 7 | 前后双摄 · 美食探店 | Food Stories, Two Views | AppStore_10/{lang}/7_food_review.png |
| 8 | 前后双摄 · 旅行风景 | Share the View and You | AppStore_10/{lang}/8_landscape_story.png |
| 9 | 前后双摄 · 摊位介绍 | Bring Your Stall to Life | AppStore_10/{lang}/9_street_stall.png |
| 10 | 前后双摄 · 商品讲解 | Show Every Product Detail | AppStore_10/{lang}/10_product_demo.png |

**第 11–14 场景为备用图，不计入每语言的正式十张**，按中国区/海外用户定位可替换前十张中的较弱卖点。英文版与中文版独立交付。

## 八类场景：逐张中英文生图提示词

### 7. 前后双摄 · 美食探店 / Food Stories, Two Views

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_7_food_review.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_7_food_review.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_7_food_review.txt` / `demo_scripts/en/scene_7_food_review.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 food。

**中文标题**：前后双摄 · 美食探店
**中文副标题**：自己出镜讲解，后摄展示眼前的美味
**高亮朗读台词**：今天带你尝尝这碗热腾腾的拉面。
**后续朗读台词**：先看汤底，再试试面条的口感。

**Image 2 中文单图提示词（复制）：**

```text
设计第 7 张「前后双摄 · 美食探店」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 food 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 美食探店」，副标题「自己出镜讲解，后摄展示眼前的美味」。底部黑色提词栏高亮文字必须是「今天带你尝尝这碗热腾腾的拉面。」，下一行文字必须是「先看汤底，再试试面条的口感。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Food Stories, Two Views
**English subtitle:** Show your face and the food in one story.
**Active voice-follow line:** Let's explore this bowl of ramen.
**Next spoken line:** First the broth, then the noodles.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 7, concept "Food Stories, Two Views" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and food in the rear view; use a picture-in-picture composition. Headline: "Food Stories, Two Views". Supporting copy: "Show your face and the food in one story.". Voice-follow highlighted words: "Let's explore this bowl of ramen.". Upcoming words: "First the broth, then the noodles.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 今天带你尝尝这碗热腾腾的拉面。先看看汤底，香气非常浓郁；再试试面条，口感筋道。边讲自己的体验，边给大家看看这碗美食的细节。

**Complete English narration:**

> Let's explore this bowl of ramen. First, look at the rich broth. Now let's try the noodles and see how they taste. I can share my reaction while showing the food up close.

---

### 8. 前后双摄 · 旅行风景 / Share the View and You

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_8_landscape_story.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_8_landscape_story.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_8_landscape_story.txt` / `demo_scripts/en/scene_8_landscape_story.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 scenery。

**中文标题**：前后双摄 · 旅行风景
**中文副标题**：一边说旅途感受，一边记录沿途景色
**高亮朗读台词**：前方就是今天最期待的山谷。
**后续朗读台词**：此刻的光和风，都值得慢慢分享。

**Image 2 中文单图提示词（复制）：**

```text
设计第 8 张「前后双摄 · 旅行风景」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 scenery 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 旅行风景」，副标题「一边说旅途感受，一边记录沿途景色」。底部黑色提词栏高亮文字必须是「前方就是今天最期待的山谷。」，下一行文字必须是「此刻的光和风，都值得慢慢分享。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Share the View and You
**English subtitle:** Tell the story while showing the scenery.
**Active voice-follow line:** This is the valley we came to see.
**Next spoken line:** The light and breeze feel incredible.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 8, concept "Share the View and You" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and scenery in the rear view; use a picture-in-picture composition. Headline: "Share the View and You". Supporting copy: "Tell the story while showing the scenery.". Voice-follow highlighted words: "This is the valley we came to see.". Upcoming words: "The light and breeze feel incredible.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 前方就是今天最期待的山谷。远处的山脉层层叠叠，阳光洒在草地上。现在我想把眼前的风景，连同此刻的感受，一起分享给你。

**Complete English narration:**

> This is the valley we came to see. The distant mountains stretch across the horizon, and the afternoon light turns the grass golden. Let me show you the view and tell you how it feels.

---

### 9. 前后双摄 · 摊位介绍 / Bring Your Stall to Life

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_9_street_stall.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_9_street_stall.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_9_street_stall.txt` / `demo_scripts/en/scene_9_street_stall.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 stall。

**中文标题**：前后双摄 · 摊位介绍
**中文副标题**：摊主出镜招呼，后摄展示摊位和食材
**高亮朗读台词**：欢迎来到我们的小摊，今天有现做小吃。
**后续朗读台词**：来看看刚刚准备好的食材。

**Image 2 中文单图提示词（复制）：**

```text
设计第 9 张「前后双摄 · 摊位介绍」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 stall 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 摊位介绍」，副标题「摊主出镜招呼，后摄展示摊位和食材」。底部黑色提词栏高亮文字必须是「欢迎来到我们的小摊，今天有现做小吃。」，下一行文字必须是「来看看刚刚准备好的食材。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Bring Your Stall to Life
**English subtitle:** Meet the maker and see what is on offer.
**Active voice-follow line:** Welcome to our little food stall!
**Next spoken line:** Let me show you today's fresh picks.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 9, concept "Bring Your Stall to Life" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and stall in the rear view; use a picture-in-picture composition. Headline: "Bring Your Stall to Life". Supporting copy: "Meet the maker and see what is on offer.". Voice-follow highlighted words: "Welcome to our little food stall!". Upcoming words: "Let me show you today's fresh picks.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 欢迎来到我们的小摊！今天准备了几样现做的小吃。你可以先看看这些食材和做法，再跟着我一起挑选今天最值得尝试的口味。

**Complete English narration:**

> Welcome to our little food stall! Today we have a few freshly made treats. Take a closer look at the ingredients, and let me help you choose what to try first.

---

### 10. 前后双摄 · 商品讲解 / Show Every Product Detail

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_10_product_demo.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_10_product_demo.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_10_product_demo.txt` / `demo_scripts/en/scene_10_product_demo.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 product。

**中文标题**：前后双摄 · 商品讲解
**中文副标题**：前摄讲卖点，后摄清楚展示产品细节
**高亮朗读台词**：这款手表吸引我的是简洁的设计。
**后续朗读台词**：先看表盘，再聊聊佩戴体验。

**Image 2 中文单图提示词（复制）：**

```text
设计第 10 张「前后双摄 · 商品讲解」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 product 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 商品讲解」，副标题「前摄讲卖点，后摄清楚展示产品细节」。底部黑色提词栏高亮文字必须是「这款手表吸引我的是简洁的设计。」，下一行文字必须是「先看表盘，再聊聊佩戴体验。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Show Every Product Detail
**English subtitle:** Talk naturally and show the finer details.
**Active voice-follow line:** I love this watch's clean design.
**Next spoken line:** Let's look at the dial and the strap.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 10, concept "Show Every Product Detail" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and product in the rear view; use a picture-in-picture composition. Headline: "Show Every Product Detail". Supporting copy: "Talk naturally and show the finer details.". Voice-follow highlighted words: "I love this watch's clean design.". Upcoming words: "Let's look at the dial and the strap.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 这款手表吸引我的是简洁的设计。先看它的表盘，刻度清晰，整体非常利落。再看看表带与佩戴体验，适合哪些日常场合。

**Complete English narration:**

> I love this watch's clean design. Let's start with the dial and its easy-to-read details. Then we can look at the strap and talk about how it feels to wear.

---

### 11. 前后双摄 · 亲子记录 / Little Moments, Big Memories

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_11_family_moments.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_11_family_moments.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_11_family_moments.txt` / `demo_scripts/en/scene_11_family_moments.txt`
**镜头布局**：左右分屏 / side-by-side split。前摄人物 presenter；后摄主体 family。

**中文标题**：前后双摄 · 亲子记录
**中文副标题**：记录亲子互动，也留下你的讲述和笑容
**高亮朗读台词**：今天和孩子一起记录一段小小的回忆。
**后续朗读台词**：看看他们的笑容，多么自然。

**Image 2 中文单图提示词（复制）：**

```text
设计第 11 张「前后双摄 · 亲子记录」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 family 主题。采用左右分屏。顶部主标题「前后双摄 · 亲子记录」，副标题「记录亲子互动，也留下你的讲述和笑容」。底部黑色提词栏高亮文字必须是「今天和孩子一起记录一段小小的回忆。」，下一行文字必须是「看看他们的笑容，多么自然。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Little Moments, Big Memories
**English subtitle:** Capture family time and your own reactions.
**Active voice-follow line:** Today is a little family adventure.
**Next spoken line:** It's these smiles we'll remember.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 11, concept "Little Moments, Big Memories" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and family in the rear view; use a side-by-side split composition. Headline: "Little Moments, Big Memories". Supporting copy: "Capture family time and your own reactions.". Voice-follow highlighted words: "Today is a little family adventure.". Upcoming words: "It's these smiles we'll remember.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 今天和孩子一起记录一段小小的回忆。我们走到户外，看看周围的风景，一起发现好玩的细节。最值得珍藏的，不一定是大场面，而是这些自然的笑容。

**Complete English narration:**

> Today is a little family adventure. We're spending time outside and noticing the small things together. The sweetest memories are often the moments we didn't plan.

---

### 12. 前后双摄 · 教育讲解 / Teach and Demonstrate

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_12_education_lessons.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_12_education_lessons.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_12_education_lessons.txt` / `demo_scripts/en/scene_12_education_lessons.txt`
**镜头布局**：左右分屏 / side-by-side split。前摄人物 teacher；后摄主体 education。

**中文标题**：前后双摄 · 教育讲解
**中文副标题**：讲知识，也让学生看清实例与过程
**高亮朗读台词**：今天我们用一个例子理解新知识。
**后续朗读台词**：先观察现象，再一起分析原因。

**Image 2 中文单图提示词（复制）：**

```text
设计第 12 张「前后双摄 · 教育讲解」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 education 主题。采用左右分屏。顶部主标题「前后双摄 · 教育讲解」，副标题「讲知识，也让学生看清实例与过程」。底部黑色提词栏高亮文字必须是「今天我们用一个例子理解新知识。」，下一行文字必须是「先观察现象，再一起分析原因。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Teach and Demonstrate
**English subtitle:** Explain an idea while showing examples.
**Active voice-follow line:** Let's learn through a simple example.
**Next spoken line:** Observe first, then explain why.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 12, concept "Teach and Demonstrate" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and education in the rear view; use a side-by-side split composition. Headline: "Teach and Demonstrate". Supporting copy: "Explain an idea while showing examples.". Voice-follow highlighted words: "Let's learn through a simple example.". Upcoming words: "Observe first, then explain why.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 今天我们用一个简单的例子来理解新知识。请先观察画面中的现象，想一想它为什么会出现。接下来我们分步骤分析，再用自己的话解释一遍。

**Complete English narration:**

> Let's learn through a simple example. First, observe what's happening on screen and think about why it works. Next, we'll go through the steps and explain the idea in our own words.

---

### 13. 前后双摄 · 实地讲解 / Guide the Story On Location

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_13_guided_explanation.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_13_guided_explanation.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_13_guided_explanation.txt` / `demo_scripts/en/scene_13_guided_explanation.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 travel。

**中文标题**：前后双摄 · 实地讲解
**中文副标题**：前摄解说，后摄带观众看现场细节
**高亮朗读台词**：这里最吸引我的是独特的自然地貌。
**后续朗读台词**：我们从地形和光线慢慢看起。

**Image 2 中文单图提示词（复制）：**

```text
设计第 13 张「前后双摄 · 实地讲解」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 travel 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 实地讲解」，副标题「前摄解说，后摄带观众看现场细节」。底部黑色提词栏高亮文字必须是「这里最吸引我的是独特的自然地貌。」，下一行文字必须是「我们从地形和光线慢慢看起。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** Guide the Story On Location
**English subtitle:** Explain what matters and show the scene.
**Active voice-follow line:** What makes this place so special?
**Next spoken line:** Let's look at the land and the light.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 13, concept "Guide the Story On Location" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and travel in the rear view; use a picture-in-picture composition. Headline: "Guide the Story On Location". Supporting copy: "Explain what matters and show the scene.". Voice-follow highlighted words: "What makes this place so special?". Upcoming words: "Let's look at the land and the light.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 这里最吸引我的是独特的自然地貌。你看，岩石和地形经过长时间变化，形成了很有层次的景观。我们一边走，一边观察它们的形状与颜色。

**Complete English narration:**

> What makes this place so special? Look at the shape of the landscape and the colors of the rock. Let's explore it together, one detail at a time.

---

### 14. 前后双摄 · 门店推广 / A Story from Your Shop

**本地中文示意图**：`scenarios/zh-Hans/VoiceCue_zh-Hans_14_small_business.png`
**English visual mockup**: `scenarios/en/VoiceCue_en_14_small_business.png`
**对应 TXT**：`demo_scripts/zh-Hans/scene_14_small_business.txt` / `demo_scripts/en/scene_14_small_business.txt`
**镜头布局**：右上角前摄画中画 / picture-in-picture。前摄人物 presenter；后摄主体 cafe。

**中文标题**：前后双摄 · 门店推广
**中文副标题**：店主亲自讲解，后摄展示店内氛围
**高亮朗读台词**：欢迎来到我们的街角咖啡馆。
**后续朗读台词**：这杯拿铁，是今天的小小推荐。

**Image 2 中文单图提示词（复制）：**

```text
设计第 14 张「前后双摄 · 门店推广」的随声提词器 App Store 竖版截图。保留我上传的真实中文版提词器界面结构，以相同语言的场景示意图作为摄影和版式参考。前置镜头是自然讲述的真人，后置镜头展示 cafe 主题。采用右上角前摄画中画。顶部主标题「前后双摄 · 门店推广」，副标题「店主亲自讲解，后摄展示店内氛围」。底部黑色提词栏高亮文字必须是「欢迎来到我们的街角咖啡馆。」，下一行文字必须是「这杯拿铁，是今天的小小推荐。」。素材自然无 AI 味，白蓝浅色品牌背景，真实设备比例，UI 以源截图为准；不可将普通合成摄影谎称为实际双摄录制。1206×2622，中文排版必须准确。
```

**English headline:** A Story from Your Shop
**English subtitle:** Introduce your shop while showing the space.
**Active voice-follow line:** Welcome to our neighborhood café.
**Next spoken line:** Here's today's favorite coffee.

**Image 2 English prompt (copy):**

```text
Create English App Store screenshot 14, concept "A Story from Your Shop" for VoiceCue. Use the uploaded original ENGLISH UI screenshot and the matching English scene mockup. Show the on-camera narrator in the front camera view and cafe in the rear view; use a picture-in-picture composition. Headline: "A Story from Your Shop". Supporting copy: "Introduce your shop while showing the space.". Voice-follow highlighted words: "Welcome to our neighborhood café.". Upcoming words: "Here's today's favorite coffee.". Natural daylight, editorial photography, understated warm-white and mist-blue branding, correct 1206x2622 portrait. Do not translate the original UI to Chinese and do not fabricate app controls, features or recording provenance. Mark as an illustrative mockup until authentic dual-camera footage is provided.
```

**完整中文讲解稿：**

> 欢迎来到我们的街角咖啡馆。今天想给大家介绍一款刚刚做好的拿铁。你可以看看咖啡的颜色、奶泡的细腻程度，再听我聊聊这杯咖啡的风味。

**Complete English narration:**

> Welcome to our neighborhood café. Today I'd love to show you a freshly prepared latte. Take a look at the creamy texture, and let me tell you what makes this one special.

---

## 多场景素材来源与合规说明

演示场景使用 Unsplash 图片 CDN 的公开摄影素材组合。网页展示时标注「场景合成示意 / Illustrative mockup」，并不能代表同一时间同一设备的真实双摄结果。正式商业发布应核对图片的版权授权及人物肖像许可。参考来源：

- presenter — https://images.unsplash.com/photo-1544005313-94ddf0286df2
- food — https://images.unsplash.com/photo-1569718212165-3a8278d5f624
- scenery — https://images.unsplash.com/photo-1500534623283-312aade485b7
- stall — https://images.unsplash.com/photo-1652690528633-a0d1902ecf63
- product — https://images.unsplash.com/photo-1523275335684-37898b6baf30
- family — https://images.unsplash.com/photo-1476703993599-0035a21b17a9
- education — https://images.unsplash.com/photo-1503676260728-1c00da094a0b
- teacher — https://images.unsplash.com/photo-1573496359142-b8d87734a5a2
- travel — https://images.unsplash.com/photo-1533105079780-92b9be482077
- cafe — https://images.unsplash.com/photo-1517248135467-4c7edcad34c4

## 发布路径

- 独立仓库：https://github.com/joyhhlife-sudo/teleprompter-app
- 产品网页：https://joyhhlife-sudo.github.io/teleprompter-app/
- 中文：scenarios/zh-Hans/、AppStore_10/zh-Hans/
- 英文：scenarios/en/、AppStore_10/en/
- 讲解稿：demo_scripts/zh-Hans/、demo_scripts/en/
- 本 Markdown 可直接上传给 ChatGPT Image 2 使用。
