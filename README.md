# Personal Android Browser Prompt

## 核心理念

过去，人们拿到一台新设备后会先安装一个通用浏览器；现在，人们可以用一句话让 Code X、Codex 或其他 Agent 生成一个写着自己名字、带着自己图标、按照自己偏好构建的私人定制安卓浏览器 APK。

## Core Idea

In the past, people installed a generic browser on a new device; now, people can use one sentence to ask Code X, Codex, or another agent to generate a personal Android browser APK with their own name, icon, and preferred experience.

## 用法

1. 复制下面的一句话提示词。
2. 把 `【你的名字】` 替换成你的名字、昵称或品牌名。
3. 把 `【图标描述】` 替换成你想要的图标风格。
4. 粘贴到 Code X、Codex 或其他支持代码生成的 Agent 中。
5. 让 Agent 生成完整项目并构建 Android APK。

## Usage

1. Copy the one-sentence prompt below.
2. Replace `【你的名字】` with your name, nickname, or brand.
3. Replace `【图标描述】` with your desired icon style.
4. Paste it into Code X, Codex, or another coding agent.
5. Ask the agent to generate the complete project and build an Android APK.

## 一句话提示词 / One-Sentence Prompt

请创建一个名为【你的名字】Browser 的私人定制安卓浏览器 APK，使用 React Native 或原生 Android 均可，应用只呈现一个完整浏览器体验，顶部是安全区下方的地址栏、加号新建页签按钮、显示当前页签数量的按钮，地址栏支持输入网址或搜索词并自动规范化，横向页签条展示所有页签且可点击切换，页签数量按钮打开页签列表，列表支持点击切换、关闭页签、拖动排序并在拖动时让当前行浮起跟随手指移动、靠近边缘自动滚动、松手后落回列表，主区域使用 Android WebView 加载网页并支持 JavaScript、DOM Storage、Cookie、多窗口链接自动新建页签、HTTPS 证书异常时弹出风险提示并允许用户继续一次或信任站点后继续，底部工具栏只放浏览器控制按钮：后退、前进、刷新或停止、关闭当前页签、更多菜单，更多菜单包含收藏当前页、收藏夹、清除浏览数据，收藏夹支持持久化、打开收藏到新页签、删除收藏，浏览器状态支持持久化恢复包括页签、当前页签、标题和 URL，界面要安静、紧凑、适合长期使用，按钮使用清晰图标，文字不溢出，适配安卓手机安全区和小屏幕，请使用 Apache 2.0 开源许可，如果模型支持图像生成请先根据【图标描述】生成一个有设计感的高质量应用图标，要求现代、辨识度高、适合 Android launcher、前景主体清晰、背景简洁、有层次和光影、不要使用受版权保护的品牌标识，如果不支持图像生成则用矢量 drawable 或 SVG 代码绘制一个风格一致的图标，并输出可直接构建 release APK 的完整项目、依赖安装命令、构建命令和 APK 产物路径。

## License

Apache License 2.0.
