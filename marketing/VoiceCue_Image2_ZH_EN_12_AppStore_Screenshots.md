# VoiceCue / 随声提词器 — Image 2 官方商店截图与首屏生图提示词

**版本**：2026-11-10 · v2.0（中文 + English，分语言真实截图输入）
**iOS Bundle ID**：`com.xtools.voicecue` · **Team**：`RYYV52Z7L3`
**App 中文名**：随声提词器；**中文副标题**：开口即跟随，轻松拍口播。
**English App Name**：VoiceCue: Teleprompter；**English subtitle**：Speak Naturally, Record Easily

## 0. 先看这个：素材的位置与性质

Mac 工作目录：`/Users/app/01-xcode/06_提词器/VoiceCue_Marketing_2026-11-10/`

| 类型 | 中文 / English | 属性 |
|---|---|---|
| App 真截图 | `screenshots/zh-Hans/*.png` | iOS 模拟器内的真实 SwiftUI 页面，简体中文 |
| Real App screenshots | `screenshots/en/*.png` | Real SwiftUI screens running in the English iOS simulator |
| 双语排版草稿 | `mockups/zh-Hans/*.png` | Swift 绘制宣传构图预览，不是商店审核最终稿 |
| Bilingual layout drafts | `mockups/en/*.png` | Swift-rendered marketing compositions; not the final screenshots |
| 网页引用图 | `website/assets/screen-library-{en,zh}.png`, `screen-prompt-{en,zh}.png` | 网站首页按语言切换 |
| App icon | `website/assets/icon.png` | 已有图标，不要重新发明/改造 |

**图像生成建议**：一次生成一张、一个语言的截图，中文与英文分别独立绘制。将该语言的真实 App 截图（不是另一种语言的）作为 **图像参考输入**，再将 App icon 作为第二张参考输入。如果设计工具不能确保屏幕 UI 中的每个字准确，**先只生带设备框的背景版**，再用原始截图直接作为未改像素的屏幕图层合成，以保证产品真实性。

**声明**：模拟器无法验证真实摄像头画面。双摄/前摄/后摄可展示摄像头模式的 UI 示意，但不能把 AI 生成的人物画面冒充实际 App 拍摄结果；正式 App Store 发布前须用真机可用模式替换。

## 1. 统一视觉规范（每张图片都附上）

- 比例 1206 × 2622 像素，竖版，sRGB，不透明 PNG；仅需另做适配其他 App Store 设备规格的输出。
- 自然、轻盈、有质感的 Apple 风格，使用浅雾蓝、暖白、少量柔和桃橙色；功能截图可采用深夜黑与温暖黄色提词高亮。配色贴近原 App（橙色 UI）与已经确定的蓝色图标，不要整页荧光蓝。
- 大标题和副标题清楚，标题安全边距上下至少 120 px、左右至少 88 px。手机硬件边框自然、比例准确，不遮挡核心 UI。
- 不添加任何没有真实实现的菜单、付费权益、神奇的 AI 写稿、眼神矫正、人像合成、云同步、在线直播等功能。
- 请保留 App 真实 UI 的精确排版，尤其是黑色提词背景、黄色强调文字、拍摄按钮、前后摄切换、Pro 状态、稿件列表。
- 不要破坏中文笔画；英语拼写规范；不要混合中文 UI 与英文标题、英文 UI 与中文标题。
- 禁止过度渐变、强发光、玻璃质感泛滥、浮空粒子、随机英文、假按钮、生成式杂乱图标。
- **输出两套**：每个序号 `ZH_01.png` 和 `EN_01.png`，直到 06，总共 12 张。

## 2. 全局主提示词（每次复制并配合下方单图提示词使用）

**中文主提示词：**

设计 iPhone App Store 竖向功能展示图，尺寸 1206×2622 像素。产品：随声提词器（VoiceCue: Teleprompter）；核心定位：开口即跟随，轻松拍口播。使用真实、朴素而专业的 iOS 应用广告视觉。淡雾蓝、暖白、极少量橙色，严谨对齐与精细留白。手机屏幕内容必须遵守上传的简体中文真实 App 截图，不改动 UI、语句、操作按钮和文字。标题采用大号易读中文字，画面清晰有说服力，不要 AI 绘画感、不要虚假功能。若无法逐像素重现屏幕，单独生成无屏幕文字的背景与设备框，保留屏幕区域方便贴入真实截图。

**English master prompt:**

Create a premium, understated iPhone App Store portrait screenshot, 1206×2622 pixels, for “VoiceCue: Teleprompter”. Brand line: “Speak Naturally, Record Easily”. Design language: modern native iOS, soft mist blue, warm white, restrained apricot-orange accents, elegant typography, generous whitespace, realistic iPhone proportions. **Use the supplied English screenshot as the literal screen UI reference**; do not translate it back to Chinese or invent buttons/text. Show authentic speech-following/teleprompter controls. No futuristic neon, generic AI glow, hallucinated features, fake reviews, or illegible lettering. If exact UI reproduction is not possible, keep the device screen area ready for the original screenshot to be composited pixel-for-pixel.

## 3. 六张图 — 中文与英文两套提示词

### 01 — 语音智能跟读 / Speech-following（首图，最重要）

**输入**：
- 中文：`screenshots/zh-Hans/VoiceCue_zh-Hans_practice.png`
- English: `screenshots/en/VoiceCue_en_practice.png`
- App icon：`website/assets/icon.png`

**中文图标题**：开口即跟随
**中文副标题**：文字跟着你的声音走
**中文单图提示词**：以上传的中文独立提词真实截图为主要画面，保留黑色底色、黄色高亮文字和“智能跟读”控制条。单台大号 iPhone 居中偏下，上方白蓝留白区域放主副标题。可以在手机外围放极少量柔和声波曲线，表达自然跟读，但禁止在屏幕中额外绘制不存在的识别动画。让观众第一眼明白这是会随朗读调整进度的智能提词器。

**English title**: Your Words. Your Pace.
**English subtitle**: The script follows your voice.
**English single-image prompt**: Feature the attached genuine **English** standalone teleprompter screen, retaining its English menu labels, black prompt background, and yellow reading highlight. A single large iPhone dominates the lower portion of the visual, with clean blue-white upper copy area. Restrained, subtle waveform strokes can sit **outside** the screen. Focus on natural speech-guided scrolling, not made-up AI transcription controls.

### 02 — 稿件库 / Script Library

**输入**：`screenshots/zh-Hans/VoiceCue_zh-Hans_library.png` / `screenshots/en/VoiceCue_en_library.png`

**中文图标题**：稿件整理，一目了然
**中文副标题**：写稿、导入、编辑，随时开拍
**中文提示词**：真实中文稿件库界面完整可辨，显示多条适合口播的内容卡片，轻微透视的手机直立展示；上半部清晰大字、下半部完整真实屏幕；简洁自然的暖白背景与浅杏色边角，突出稿件卡片和新增按钮。不添加“AI 自动写稿”。

**English title**: Every Script, Ready to Go.
**English subtitle**: Create, import, and organize with ease.
**English prompt**: Use the real English Scripts page with English script titles and descriptions. Warm white editorial background, straight-on phone, airy layout, readable type. Highlight the script library, import, and plus buttons without adding fictional capabilities.

### 03 — 拍摄模式 / Flexible Camera Modes

**输入**：中文 `screenshots/zh-Hans/VoiceCue_zh-Hans_editor.png`、`screenshots/zh-Hans/VoiceCue_zh-Hans_practice.png`；英文对应 `screenshots/en/VoiceCue_en_editor.png`、`screenshots/en/VoiceCue_en_practice.png`。**更理想的最终输入是支持 MultiCam 的 iPhone 真机拍摄页面截图，当前暂缺。**

**中文标题**：前摄、后摄、双摄
**中文副标题**：镜头随你选择，提词始终在线
**中文提示词**：表现三种模式的视觉差异：一个正面自拍口播视角、一个后摄展示视角、一个前后双摄的双画面构图；用优雅的三分屏或主辅两画面构图，边框和控件一律以真实截图为准，不要伪造手机真实录制效果。该图标注为宣传概念，未取得真机结果前不能作为“已验证录像成果”。

**English title**: One App. More Ways to Film.
**English subtitle**: Front, rear, and supported dual-camera modes.
**English prompt**: A polished editorial composition suggesting front, rear, and simultaneous dual-camera modes on supported hardware. Use supplied English UI assets for real buttons and labels; keep any conceptual camera content **clearly illustrative**, not a falsely claimed real recording. Do not invent an impossible triple-lens recording feature.

### 04 — 稿件编辑 / Script Editing

**输入**：`screenshots/zh-Hans/VoiceCue_zh-Hans_editor.png` / `screenshots/en/VoiceCue_en_editor.png`

**中文标题**：灵感写下来，表达更流畅
**中文副标题**：编辑自己的内容，准备每次开口
**中文提示词**：主视角展示中文稿件编辑器，强调真实编辑标题与正文、清晰文字、留白舒适。允许少量纸张、笔记、咖啡等生活方式摆件，但不喧宾夺主，避免散落文字。

**English title**: Write It. Say It.
**English subtitle**: Edit scripts for every story.
**English prompt**: Show the real English script editor with readable English text and familiar native iOS typography. Calm creative workspace, minimal props, clean product focus, no invented generative writing tools.

### 05 — 自定义设置与 Pro / Customize & Pro

**输入**：`screenshots/zh-Hans/VoiceCue_zh-Hans_settings.png` + `screenshots/zh-Hans/VoiceCue_zh-Hans_pro.png` / English equivalents。

**中文标题**：提词方式，由你掌控
**中文副标题**：字号、样式与专业版功能
**中文提示词**：双层设备构图，用真实设置页为主、真实专业版界面为辅；突出实际出现的提词显示选项和购买入口。不添加“终身免费”“无限云空间”等并不存在或未经审查的卖点。

**English title**: Make It Yours.
**English subtitle**: Personalize your prompt and explore Pro.
**English prompt**: Two carefully balanced devices showing authentic **English** Settings and Pro screens. Premium but restrained warm-blue/ivory palette. Do not invent subscription prices, entitlements, or unlimited features.

### 06 — 独立提词 / Practice Anywhere

**输入**：`screenshots/zh-Hans/VoiceCue_zh-Hans_practice.png` / `screenshots/en/VoiceCue_en_practice.png`

**中文标题**：不拍摄，也能从容练习
**中文副标题**：独立提词，让每次表达更自信
**中文提示词**：画面安静而专注，深色提词屏放大文字区域，顶部明确展示真实智能跟读与匀速滚动方式。背景使用干净室内创作场景，不渲染任何超出实际系统的跨 App 悬浮保证。

**English title**: Practice with Confidence.
**English subtitle**: Rehearse first. Record when ready.
**English prompt**: A calm practice moment centered around the authentic English standalone teleprompter. Preserve English “Voice Follow” and scrolling controls, black UI and yellow focus text; no invented overlays or fake live-streaming integrations.

## 4. 欢迎首屏 / Onboarding（独立于六张商店图）

**中文标题**：随声提词器
**中文副标题**：开口即跟随，轻松拍口播。
**English title**：VoiceCue: Teleprompter
**English subtitle**：Speak Naturally, Record Easily

**提示词**：设计 App 首次启动欢迎页而非 App Store 海报。沿用真实 VoiceCue 图标，淡雾蓝和暖白背景，中央在提词行、声音节奏、单/双摄三种功能之间建立轻量视觉关联。底部预留“开始使用 / Get Started”标准按钮空间。勿在屏幕中添加不可点击的假系统交互。请分别用简体中文/英文成套生成，须与现有 App 的配色、圆角尺度和 iOS 系统原生控件一致。

## 5. 配套的示例口播稿（适合导入 App、重新截图）

**中文四篇（建议标题）**：口播开场 · 自信表达 / 知识分享 · 三个表达技巧 / 旅行日记 · 海边的一天 / 30 秒产品介绍。

**English four scripts**: Creator Intro · Welcome / Three Tips for Better Videos / Travel Diary · By the Sea / 30-Second Product Introduction.

**中文核心示例**：镜头已经准备好了。现在，请看着镜头，像和朋友聊天一样，自然地说出你的故事。稿件会跟着你的朗读前进，让你把注意力留给表达。

**English core sample**：Your camera is ready. Look into the lens and speak as naturally as you would to a friend. Let the words move with your voice, so you can focus on telling your story.

已准备好的中英文模拟器截图中包含宣传示例稿件；其内容属于测试演示数据，不触及个人隐私。

## 6. 生图流程与成品验收

1. 在 ChatGPT Image 2 中上传 `网站图标` + 对应语言的 `真实截图`，先选一张图做视觉基线，再制作其余五张。切换语言时**更换真实截图文件**，不能仅改标题。
2. 输入“全局主提示词”+ 对应单图提示词（中文/英文二选一），并引用上一张已通过的风格效果作为风格样本。
3. 导出 `ZH_01...ZH_06` 和 `EN_01...EN_06`，共 12 张无透明 PNG，1206×2622。
4. 检查标题、文字拼写、截图语言、状态栏、按钮、图标、比例、边距，排除缺字、重影、UI 幻觉、错位、黑色相机预览。
5. **真正上架**：优先采用截图底图 + 未修改过的实际 App 屏幕合成；涉及双摄实拍的图需另行真实设备验证。

## 7. 网站与 App 地址（独立仓库，不再依赖 dualcapture-privacy）

- 独立仓库：https://github.com/joyhhlife-sudo/teleprompter-app
- 官网：https://joyhhlife-sudo.github.io/teleprompter-app/
- 隐私：https://joyhhlife-sudo.github.io/teleprompter-app/privacy.html
- 使用条款：https://joyhhlife-sudo.github.io/teleprompter-app/terms.html
- 支持：https://joyhhlife-sudo.github.io/teleprompter-app/support.html

**备注**：旧文档中的 `/voicecue-privacy/` 是过时草案地址；以已建成的 `/teleprompter-app/` 为准。
