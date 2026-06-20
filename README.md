# Personal Android Browser

## 核心理念

以前，人们拿到一台新设备，会先下载一个通用浏览器；现在，人们可以把自己的名字、自己的图标、自己的习惯交给 Codex 或其他 agent，用一句话生成一个专属于自己的安卓浏览器 APK。

This repository is a tiny prompt artifact for a simple idea: the next browser on a new device does not have to be downloaded, it can be generated from one sentence with your name, your icon, and your own Android browsing experience.

## 用法

1. 复制下面的“一句话提示词”。
2. 把 `{你的名字}` 改成你的名字，把 `{你的图标描述}` 改成你想要的应用图标描述。
3. 粘贴给 Codex 或其他能创建 Android / React Native / Expo 项目的 agent。
4. 要求 agent 直接生成并打包 Android APK。

## Usage

1. Copy the one-sentence prompt below.
2. Replace `{your name}` with your name and `{your icon description}` with the icon you want.
3. Paste it into Codex or another agent that can build Android / React Native / Expo apps.
4. Ask the agent to generate and package the Android APK.

## 一句话提示词 / One-Sentence Prompt

请为我创建一个私人定制的安卓浏览器 APK，应用名称使用 `{你的名字}` 的专属浏览器 / `{your name}` Browser，应用图标根据 `{你的图标描述}` 生成，如果当前模型或工具支持生图就优先生成 bitmap 图标并适配 Android 图标尺寸，如果不支持生图就 fallback 到 SVG 或 Android vector drawable 绘制图标，使用 React Native 或 Expo 并包含 checked-in Android project，首屏就是浏览器而不是 landing page，不要做底部多页切换区域，浏览器体验要包含顶部安全区下的地址栏、输入 URL 或搜索词、加号新建页签、显示当前页签数量的方形按钮、横向滚动页签条、页签列表弹窗、点击页签切换、页签列表中可关闭页签、页签列表中允许通过拖动把手调整顺序且拖动时行应临时脱离列表连续跟随手指移动并在松手后回到列表、WebView 浏览网页、支持 JavaScript、DOM storage、第三方 Cookie、多窗口请求打开为新页签、后退、前进、刷新和停止加载按钮、更多菜单、收藏当前页、收藏夹、从收藏夹新建页签打开、删除收藏、清除浏览器数据、空白页提示、加载状态、HTTPS 证书异常时弹出风险提示并允许用户取消、继续一次、或信任该站点后继续，视觉风格要像一个安静实用的移动端浏览器而不是营销页面，控件使用清晰的图标按钮，地址栏和页签区域留白紧凑且上下平衡，所有浏览器状态包括页签、当前页签和收藏都要持久化，最终请运行类型检查并打包 release APK。

## License

Apache License 2.0, see `LICENSE`.
