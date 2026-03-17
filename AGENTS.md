# Agent Code Navigation

这个页面把 Lakr233 的公开仓库按 **“Agent 可以抄哪些代码”** 的角度整理出来，只收录 **MIT 和宽松许可证** 的项目，方便直接挑仓库、挑模块、挑许可证。

- 已收录：**94** 个 permissive-license 仓库
- 已排除：**29** 个仓库（GPL / AGPL / LGPL / 无明确许可证）
- 使用方式：先看「建议抄的部分」，再点进仓库抄对应模块；复制时保留 LICENSE / NOTICE，并再次确认第三方依赖、素材、商标和线上服务条款。
- 许可口径：本页把 `MIT`, `Apache-2.0`, `BSD`, `Unlicense`, `WTFPL` 等视为宽松许可证；`GPL / AGPL / LGPL / NOASSERTION` 一律不放进可抄导航。

## Legend

- `App`：适合抄完整产品结构、模块拆分、交互流
- `Library`：适合抄可复用 API、UI 组件、模块边界
- `Tooling`：适合抄 CLI、服务接口、自动化流程、外部系统集成
- `System`：适合抄底层解析、协议桥接、设备交互、逆向工具链

## Coverage Summary

- **App** × 32
- **Library** × 26
- **Tooling** × 22
- **System** × 14
- **Apache-2.0** × 1
- **BSD-3-Clause** × 2
- **MIT** × 81
- **Unlicense** × 5
- **WTFPL** × 5

## Copy-Friendly Repositories

| Repo | Type | License | Lang | 建议抄的部分 | 仓库说明 |
| --- | --- | --- | --- | --- | --- |
| [ActionBee](https://github.com/Lakr233/ActionBee) | `Tooling` | `MIT` | `Swift` | 触发器设计、剪贴板自动化、动作编排 | A programmable pasteboard action trigger |
| [ActivateMac](https://github.com/Lakr233/ActivateMac) | `App` | `MIT` | `Objective-C` | 完整产品架构、模块拆分、交互流 | Show MS Windows style activation dialog on my screen. |
| [Aibmoe](https://github.com/Lakr233/Aibmoe) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | Use Swift to pack ambiguous image that display differently on Apple and Other devices. |
| [AirDropDyldCache](https://github.com/Lakr233/AirDropDyldCache) | `System` | `MIT` | `Swift` | 底层格式解析、逆向工具封装、命令行桥接 | — |
| [AlertController](https://github.com/Lakr233/AlertController) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Simple AlertViewController |
| [AppleMobileDeviceLibrary](https://github.com/Lakr233/AppleMobileDeviceLibrary) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | Repo to store binary targets |
| [ApplePackage](https://github.com/Lakr233/ApplePackage) | `Tooling` | `MIT` | `Swift` | CLI / 服务接口 / 自动化流程 / 集成方式 | ipatool rewrite in library and cli using Swift |
| [AppleSiliconUIKitPatch](https://github.com/Lakr233/AppleSiliconUIKitPatch) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | Script to patch iOS app so we can later use it on Apple Silicon devices. |
| [ASMultiAppsRiverView](https://github.com/Lakr233/ASMultiAppsRiverView) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | App Store Like Multi App River View |
| [Asspp](https://github.com/Lakr233/Asspp) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | The App Store for your multi-account eco system. |
| [AssppWeb](https://github.com/Lakr233/AssppWeb) | `App` | `MIT` | `TypeScript` | 完整产品架构、模块拆分、交互流 | — |
| [AudioEditorKit](https://github.com/Lakr233/AudioEditorKit) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Simplified audio editing library for Swift + UIKit. |
| [AuxiliaryExecute](https://github.com/Lakr233/AuxiliaryExecute) | `Tooling` | `MIT` | `Swift` | 系统命令封装、进程管理、环境变量传递 | A Swift wrapper for system shell over posix_spawn with search path and env support. |
| [Axchange](https://github.com/Lakr233/Axchange) | `System` | `MIT` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | Android file transfer via ADB |
| [BlossomColorPicker](https://github.com/Lakr233/BlossomColorPicker) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | — |
| [BootableBackupOSX](https://github.com/Lakr233/BootableBackupOSX) | `Tooling` | `Unlicense` | `Shell` | 备份/恢复流程、任务编排、异常处理 | A script to backup all your macOS files using rsync. |
| [BQBClassifier](https://github.com/Lakr233/BQBClassifier) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | A machine learning based emoji image classifier |
| [BreakGlass](https://github.com/Lakr233/BreakGlass) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | — |
| [CameraTools](https://github.com/Lakr233/CameraTools) | `System` | `MIT` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | EXIF Tool Kit |
| [ChatBot-TGLM6B](https://github.com/Lakr233/ChatBot-TGLM6B) | `Tooling` | `WTFPL` | `Python` | 聊天 UI、消息模型、会话层抽象 | ChatGLM-6B Bot for Telegram |
| [ChatClientKit](https://github.com/Lakr233/ChatClientKit) | `Library` | `MIT` | `Swift` | 聊天 UI、消息模型、会话层抽象 | — |
| [ChidoriMenu](https://github.com/Lakr233/ChidoriMenu) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Drop in replacement for _presentMenuAtLocation: |
| [code-clarity](https://github.com/Lakr233/code-clarity) | `Tooling` | `MIT` | `—` | Agent 技能结构、提示词组织、代码可读性规范 | Claude Code skill for readable code — naming, early return, abstraction levels, and class design. Swift-primary. |
| [CodeEditorUI](https://github.com/Lakr233/CodeEditorUI) | `Library` | `Unlicense` | `TypeScript` | 可复用 API / UI 组件 / 模块边界 | CodeMirror Binding to Apple UI Frameworks (UIKit, AppKit, SwiftUI) |
| [Colorful](https://github.com/Lakr233/Colorful) | `Library` | `MIT` | `Swift` | 颜色系统、渐变渲染、动画背景 | A SwiftUI implementation of AppleCard's animated colorful blur background. |
| [ColorfulX](https://github.com/Lakr233/ColorfulX) | `Library` | `MIT` | `Swift` | 颜色系统、渐变渲染、动画背景 | ColorfulX is a high-performance library designed for creating vibrant & animated mesh gradient views. |
| [ColorVector](https://github.com/Lakr233/ColorVector) | `Library` | `MIT` | `Swift` | 基础算法/API 设计、职责边界 | Color with its space, in Swift. |
| [ComputerUse](https://github.com/Lakr233/ComputerUse) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | — |
| [ConfigurableKit](https://github.com/Lakr233/ConfigurableKit) | `Library` | `MIT` | `Swift` | 设置页建模、表单项抽象、UIKit 配置化 | Set up settings pages like a charm with UIKit. |
| [CoreExtendedNFC](https://github.com/Lakr233/CoreExtendedNFC) | `System` | `MIT` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | Swift Package porting libnfc protocol-layer logic to iOS via CoreNFC |
| [CreemKit](https://github.com/Lakr233/CreemKit) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | — |
| [CreemProxy](https://github.com/Lakr233/CreemProxy) | `Tooling` | `MIT` | `Go` | 代理边界、鉴权隔离、上游 API 封装 | A proxy designed for Creem users to securely delegate requests to the Creem API. |
| [CydiaRepoSync](https://github.com/Lakr233/CydiaRepoSync) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | — |
| [Dealer](https://github.com/Lakr233/Dealer) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | Simple web search with multiple source. |
| [Dog](https://github.com/Lakr233/Dog) | `Library` | `MIT` | `Swift` | 日志模型、持久化策略、调试接口 | A lightweight persist logging system. |
| [DpkgVersion](https://github.com/Lakr233/DpkgVersion) | `App` | `MIT` | `Swift` | 基础算法/API 设计、职责边界 | Swift implementation of robust dpkg semi-semantic version management. |
| [DYLDExtractor](https://github.com/Lakr233/DYLDExtractor) | `System` | `MIT` | `Swift` | 底层格式解析、逆向工具封装、命令行桥接 | Packed tool for extracting frameworks and libraries from iOS dyld shared cache. |
| [esp32-nfc-display](https://github.com/Lakr233/esp32-nfc-display) | `System` | `MIT` | `C` | 设备协议桥接、近场通信/蓝牙交互 | Simple app to display nfc card info. |
| [Evil.Objective-C](https://github.com/Lakr233/Evil.Objective-C) | `App` | `WTFPL` | `Objective-C` | 完整产品架构、模块拆分、交互流 | Use with caution |
| [Firework](https://github.com/Lakr233/Firework) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | 烟花箱！ |
| [FishUpgrade](https://github.com/Lakr233/FishUpgrade) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | macOS 摸鱼模拟器 |
| [Fix-GPS](https://github.com/Lakr233/Fix-GPS) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | 从一生足迹中读取位置数据并写入图片 |
| [FixTim](https://github.com/Lakr233/FixTim) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | Fix every runtime bug on macOS. |
| [FluidInterpolation](https://github.com/Lakr233/FluidInterpolation) | `Library` | `MIT` | `Swift` | 基础算法/API 设计、职责边界 | — |
| [GGLyn](https://github.com/Lakr233/GGLyn) | `System` | `Unlicense` | `Swift` | 设备协议桥接、近场通信/蓝牙交互 | 叮当同学 D1X 热敏打印机 HTTP -> BLE 桥 |
| [GitLab-License-Generator](https://github.com/Lakr233/GitLab-License-Generator) | `Tooling` | `WTFPL` | `Ruby` | CLI / 服务接口 / 自动化流程 / 集成方式 | Generate GitLab License For Self-Hosted/Private Instances |
| [Halloween24](https://github.com/Lakr233/Halloween24) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | — |
| [iLrcOverlay](https://github.com/Lakr233/iLrcOverlay) | `Library` | `MIT` | `Objective-C` | 可复用 API / UI 组件 / 模块边界 | — |
| [IOKit-Headers](https://github.com/Lakr233/IOKit-Headers) | `System` | `MIT` | `C` | 协议桥接 / 底层解析 / 设备交互 | — |
| [iOSreExtension](https://github.com/Lakr233/iOSreExtension) | `Tooling` | `Apache-2.0` | `TypeScript` | CLI / 服务接口 / 自动化流程 / 集成方式 | A fast and elegant extension for VSCode used for iOSre projects. |
| [iphone-mcp](https://github.com/Lakr233/iphone-mcp) | `Tooling` | `MIT` | `Python` | MCP 接口设计、工具暴露、自动化工作流 | A Model Context Protocol (MCP) server for automating iPhone tasks with Appium. Supports app control, UI interactions, and screenshot capture via streamable HTTP. |
| [Iridium](https://github.com/Lakr233/Iridium) | `System` | `MIT` | `Swift` | 底层格式解析、逆向工具封装、命令行桥接 | An iOS app decrypter, full static using fouldecrypt. |
| [iVariant](https://github.com/Lakr233/iVariant) | `System` | `MIT` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | Read iOS device model/variants from Xcode. |
| [LanguageModelChatUI](https://github.com/Lakr233/LanguageModelChatUI) | `Library` | `MIT` | `Swift` | 聊天 UI、消息模型、会话层抽象 | — |
| [libcapstone-spm](https://github.com/Lakr233/libcapstone-spm) | `System` | `BSD-3-Clause` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | Swift Package Manager support for Capstone disassembly engine |
| [libghostty-spm](https://github.com/Lakr233/libghostty-spm) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | — |
| [libimg4-spm](https://github.com/Lakr233/libimg4-spm) | `System` | `MIT` | `Swift` | 底层格式解析、逆向工具封装、命令行桥接 | Swift Package Manager wrapper for img4tool (Apple IMG4/IM4P firmware container parser) |
| [libssh2-spm](https://github.com/Lakr233/libssh2-spm) | `System` | `MIT` | `Swift` | 协议桥接 / 底层解析 / 设备交互 | Swift package for libssh2, automatically tracked on release tags. |
| [libzip-spm](https://github.com/Lakr233/libzip-spm) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | — |
| [ListViewKit](https://github.com/Lakr233/ListViewKit) | `Library` | `MIT` | `Swift` | 数据驱动列表、刷新策略、滚动性能 | An UITableView replacement that won't create glitches when changing data. Requires iOS 13.0+. |
| [Litext](https://github.com/Lakr233/Litext) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | A tiny rich-text supporting library for Apple platform. |
| [markdown_core](https://github.com/Lakr233/markdown_core) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Swift package to wrap around rust package markdown |
| [mobilePillowTalkLite](https://github.com/Lakr233/mobilePillowTalkLite) | `App` | `BSD-3-Clause` | `Swift` | 完整产品架构、模块拆分、交互流 | An iOS & SwiftUI server monitor tool for linux based machines using remote proc file system with script execution. |
| [MobileTransfer](https://github.com/Lakr233/MobileTransfer) | `App` | `MIT` | `Swift` | 备份/恢复流程、任务编排、异常处理 | Backup & restore iOS devices with advanced settings. |
| [MoneyProgress](https://github.com/Lakr233/MoneyProgress) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | 借一个上班的进度条。 |
| [MSDisplayLink](https://github.com/Lakr233/MSDisplayLink) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | The missing DisplayLink object for Apple platforms. |
| [myyearwithgit](https://github.com/Lakr233/myyearwithgit) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | 代码仓库年终总结报告。 |
| [NaiveboomDockerComposed](https://github.com/Lakr233/NaiveboomDockerComposed) | `Tooling` | `MIT` | `JavaScript` | CLI / 服务接口 / 自动化流程 / 集成方式 | docker-compose capability layer for naive boom~ |
| [NotchDrop](https://github.com/Lakr233/NotchDrop) | `App` | `MIT` | `Swift` | 刘海区 UI、拖放入口、通知呈现 | Use your MacBook's notch like Dynamic Island for temporary storing files and AirDrop |
| [NotchNotification](https://github.com/Lakr233/NotchNotification) | `App` | `MIT` | `Swift` | 刘海区 UI、拖放入口、通知呈现 | Display Notification Inside Mac's Notch. |
| [notion-mcp-proxy](https://github.com/Lakr233/notion-mcp-proxy) | `Tooling` | `MIT` | `Python` | MCP 接口设计、工具暴露、自动化工作流 | move bearer token to local clients |
| [openssl-spm](https://github.com/Lakr233/openssl-spm) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | Swift Package for OpenSSL with prebuilt XCFramework |
| [PhotopeaElectronApp](https://github.com/Lakr233/PhotopeaElectronApp) | `Tooling` | `WTFPL` | `JavaScript` | CLI / 服务接口 / 自动化流程 / 集成方式 | — |
| [Privacy-Insight](https://github.com/Lakr233/Privacy-Insight) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | Read iOS 15 privacy insight '.ndjson' file into your human brain. |
| [pwgen](https://github.com/Lakr233/pwgen) | `Tooling` | `MIT` | `Swift` | CLI / 服务接口 / 自动化流程 / 集成方式 | Simple command line to generate random password. |
| [RainbowFart](https://github.com/Lakr233/RainbowFart) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | 全自动夸夸机，配备先进的注意力感知功能，人工智能且离线。 |
| [Remove-All-Your-Stars](https://github.com/Lakr233/Remove-All-Your-Stars) | `Tooling` | `WTFPL` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | Remove all your star from GitHub |
| [SafariYYDS](https://github.com/Lakr233/SafariYYDS) | `App` | `Unlicense` | `Swift` | 完整产品架构、模块拆分、交互流 | — |
| [Saily](https://github.com/Lakr233/Saily) | `App` | `Unlicense` | `Objective-C` | 完整产品架构、模块拆分、交互流 | Modern. Fast. Beautiful. |
| [ScrubberKit](https://github.com/Lakr233/ScrubberKit) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | — |
| [Sentry](https://github.com/Lakr233/Sentry) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | A powerful macOS security monitoring application that detects unauthorized access attempts and records video evidence for you. |
| [SkyLightWindow](https://github.com/Lakr233/SkyLightWindow) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Display your UI on lock screen. |
| [SleepHoldService](https://github.com/Lakr233/SleepHoldService) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | A lightweight macOS service that prevents system sleep when the lid is closed. |
| [SpeedBall](https://github.com/Lakr233/SpeedBall) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | Bring back the old 90's floating speed ball to your Mac with some how morden design. |
| [SpringInterpolation](https://github.com/Lakr233/SpringInterpolation) | `Library` | `MIT` | `Swift` | 基础算法/API 设计、职责边界 | Spring Interpolation for you to create animation |
| [swift-trustcache](https://github.com/Lakr233/swift-trustcache) | `System` | `MIT` | `Swift` | 底层格式解析、逆向工具封装、命令行桥接 | Pure Swift library for creating and parsing Apple trust caches (v1) |
| [SwiftThrottle](https://github.com/Lakr233/SwiftThrottle) | `Library` | `MIT` | `Swift` | 基础算法/API 设计、职责边界 | A simple throttle written in Swift. |
| [TextExpress2-CheatBRT](https://github.com/Lakr233/TextExpress2-CheatBRT) | `App` | `MIT` | `Python` | 完整产品架构、模块拆分、交互流 | A cheat for you to play Text Express 2, using brute force or search word with giving conditions. |
| [TreeNewBee](https://github.com/Lakr233/TreeNewBee) | `App` | `MIT` | `LLVM` | 完整产品架构、模块拆分、交互流 | 树新风 |
| [unJailbreakBash](https://github.com/Lakr233/unJailbreakBash) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | a script to unjailbreak, update from Electra |
| [vphone-cli](https://github.com/Lakr233/vphone-cli) | `Tooling` | `MIT` | `Swift` | CLI / 服务接口 / 自动化流程 / 集成方式 | — |
| [wcdb-spm-prebuilt](https://github.com/Lakr233/wcdb-spm-prebuilt) | `Tooling` | `MIT` | `Shell` | CLI / 服务接口 / 自动化流程 / 集成方式 | — |
| [WindowAnimation](https://github.com/Lakr233/WindowAnimation) | `Library` | `MIT` | `Swift` | 可复用 API / UI 组件 / 模块边界 | Provide animation when animating SwiftUI windows on macOS. |
| [X2D-GPS-Companion](https://github.com/Lakr233/X2D-GPS-Companion) | `App` | `MIT` | `Swift` | 完整产品架构、模块拆分、交互流 | — |

## Excluded for License Reasons

下面这些仓库暂时不放进 Agent 导航：要么是 GPL / AGPL / LGPL，要么是 GitHub 上没有明确许可证声明。

| Repo | License | Why excluded |
| --- | --- | --- |
| [FlowDown](https://github.com/Lakr233/FlowDown) | `AGPL-3.0` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [hitokoto_mcp](https://github.com/Lakr233/hitokoto_mcp) | `AGPL-3.0` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [iQemu-iPsw-iPreparer](https://github.com/Lakr233/iQemu-iPsw-iPreparer) | `AGPL-3.0` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [BBackupp](https://github.com/Lakr233/BBackupp) | `GPL-3.0` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [SwiftCourse](https://github.com/Lakr233/SwiftCourse) | `GPL-3.0` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [AppleMobileDevice](https://github.com/Lakr233/AppleMobileDevice) | `LGPL-2.1` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [AppleWebLogin](https://github.com/Lakr233/AppleWebLogin) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [backup-xiaolian](https://github.com/Lakr233/backup-xiaolian) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [BuildThatADB](https://github.com/Lakr233/BuildThatADB) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [Decrypter](https://github.com/Lakr233/Decrypter) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [GetThemAll](https://github.com/Lakr233/GetThemAll) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [KeyboardLocationReader](https://github.com/Lakr233/KeyboardLocationReader) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [Kimis](https://github.com/Lakr233/Kimis) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [Lakr-s-License](https://github.com/Lakr233/Lakr-s-License) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [Lakr233](https://github.com/Lakr233/Lakr233) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [libkeystone-spm](https://github.com/Lakr233/libkeystone-spm) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [MAGPIE](https://github.com/Lakr233/MAGPIE) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [makeCommandLineToolAvailableForiOS](https://github.com/Lakr233/makeCommandLineToolAvailableForiOS) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [MarkdownView](https://github.com/Lakr233/MarkdownView) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [NSRemoteShell](https://github.com/Lakr233/NSRemoteShell) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [Rayon](https://github.com/Lakr233/Rayon) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [RunestoneEditor](https://github.com/Lakr233/RunestoneEditor) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [SGRenet](https://github.com/Lakr233/SGRenet) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [spotify-api](https://github.com/Lakr233/spotify-api) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [tart-yolo-claude](https://github.com/Lakr233/tart-yolo-claude) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [UIEffectKit](https://github.com/Lakr233/UIEffectKit) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [vphone-cli-storage](https://github.com/Lakr233/vphone-cli-storage) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [WhisperKit](https://github.com/Lakr233/WhisperKit) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |
| [XTerminalUI](https://github.com/Lakr233/XTerminalUI) | `NOASSERTION` | Copyleft or unknown license; keep out of copy-friendly navigation |

## Practical Copy Rules

1. **可以直接抄**：工程结构、可复用组件、算法实现、命令行流程、系统桥接思路。
2. **抄之前先确认**：第三方依赖的子许可证、品牌素材、截图、图标、线上 API Key、私有 endpoint。
3. **抄完要保留**：原仓库要求的 LICENSE / NOTICE / attribution。
4. **遇到无 License 仓库不要抄代码**：只能看思路，不能默认复制实现。
