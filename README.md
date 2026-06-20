# Personal Android Browser Prompt

## 核心理念

过去，人们拿到一台新设备后会先安装 Chrome；现在，人们可以用一句话让 codex、cursor、claude 或其他 agent 生成一个写着自己名字、带着自己图标、按照自己偏好构建的私人定制安卓浏览器 APK。

## Core Idea

In the past, people installed Chrome on a new device; now, people can use one sentence to ask codex, cursor, claude, or another agent to generate a personal Android browser APK with their own name, icon, and preferred experience.

## 用法

1. 复制下面的一句话提示词，括号说明只要都用逗号连接，也是一句话。
2. 把 `【我的浏览器】` 替换成你的浏览器名称。
3. 把 `【图标主题】` 替换成你想要的图标主题。
4. 粘贴到 codex、cursor、claude 或其他支持代码生成的 agent 中。
5. 让 agent 生成完整项目并构建 Android APK。

## Usage

1. Copy the one-sentence prompt below, the parenthetical notes still count as one sentence when everything is joined with commas.
2. Replace `【我的浏览器】` with your browser name.
3. Replace `【图标主题】` with your desired icon theme.
4. Paste it into codex, cursor, claude, or another coding agent.
5. Ask the agent to generate the complete project and build an Android APK.

## 一句话提示词 / One-Sentence Prompt

请创建一个名为【我的浏览器】Browser 的私人定制安卓浏览器 APK，技术栈固定使用 React Native、Expo、react-native-webview、checked-in Android project 和 Android release APK 构建流程，应用只呈现一个完整浏览器体验，顶部是安全区下方的地址栏、加号新建页签按钮、显示当前页签数量的按钮，地址栏支持输入网址或搜索词并自动规范化，横向页签条展示所有页签且可点击切换，页签数量按钮打开页签列表，列表支持点击切换、关闭页签、拖动排序并在拖动时让当前行浮起跟随手指移动、靠近边缘自动滚动、松手后落回列表，主区域使用 Android WebView 加载网页并支持 JavaScript、DOM Storage、Cookie、多窗口链接自动新建页签且要防止重复打开，通过 network_security_config 同时信任系统 CA 和用户安装 CA，切换页签时保留各页签 WebView 和浏览状态，后台页签不卸载不重载、JS timer 按浏览器策略节流、音视频暂停，切回时尽量原状态恢复，HTTPS 证书异常时要通过原生 WebViewClient 补丁或等效方式弹出风险提示并允许用户继续一次或信任站点后继续，信任站点后继续保存的证书例外必须可以在应用内手动清理，底部工具栏只放浏览器控制按钮包括后退、前进、刷新或停止、关闭当前页签、更多菜单，更多菜单包含收藏当前页、收藏夹、清除浏览数据、清除已信任证书例外，清除已信任证书例外要撤销所有通过信任站点后继续保存的证书例外且不清除 Cookie、缓存、浏览器页签、API Key 或其他浏览数据，收藏夹支持持久化、打开收藏到新页签、删除收藏，浏览器状态支持持久化恢复包括页签、当前页签、标题、URL 和收藏，界面要安静、紧凑、适合长期使用，按钮使用清晰图标，文字不溢出，适配安卓手机安全区和小屏幕，请使用 Apache 2.0 开源许可，如果模型支持图像生成请先根据【图标主题】生成一个有设计感的应用图标，如果不支持图像生成则用矢量 drawable 或 SVG 代码绘制一个风格一致的图标，执行时不要把需要确认当作默认行为，除非继续执行会造成不可逆风险、需要账号密钥登录态验证码隐私信息、需要管理员权限、构建受本机环境权限网络限制、同类修复连续失败两次或单个命令超过十分钟无进展，否则直接安装依赖、修类型错误、修构建配置、运行类型检查和 Android 构建，缺 JDK 或 Android SDK 时允许在项目本地临时安装且不污染系统环境，构建成功后验证 APK 路径、包名、应用名、签名状态和文件大小，并输出可直接构建 release APK 的完整项目、依赖安装命令、类型检查命令、构建命令和 APK 产物路径。

## License

Apache License 2.0.
