# Agent Code Navigation

This page curates Lakr233's public repositories from the perspective of **what an agent can safely study or reuse**. It only includes projects under **MIT and other permissive licenses**, so it is easy to pick repositories, modules, and licenses at a glance.

- Included: **94** repositories with permissive licenses
- Scope: `MIT`, `Apache-2.0`, `BSD`, `Unlicense`, `WTFPL`, and similar permissive licenses
- Usage: start with the “What to copy” column, then open the repository and study the matching module or pattern
- Reminder: keep the original `LICENSE` / `NOTICE`, and double-check third-party dependencies, assets, trademarks, and service terms before reusing code

## Legend

- `App`: complete product architecture, module splits, and interaction flows
- `Library`: reusable APIs, UI components, and module boundaries
- `Tooling`: CLIs, service interfaces, automation flows, and external integrations
- `System`: low-level parsing, protocol bridges, device interaction, and reverse-engineering toolchains

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

| Repo | Type | License | Lang | What to copy | Description |
| --- | --- | --- | --- | --- | --- |
| [ActionBee](https://github.com/Lakr233/ActionBee) | `Tooling` | `MIT` | `Swift` | Trigger design, clipboard automation, and action orchestration. | A programmable pasteboard action trigger |
| [ActivateMac](https://github.com/Lakr233/ActivateMac) | `App` | `MIT` | `Objective-C` | Full product structure, module boundaries, and interaction flow. | Show MS Windows style activation dialog on my screen. |
| [Aibmoe](https://github.com/Lakr233/Aibmoe) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | Use Swift to pack ambiguous image that display differently on Apple and Other devices. |
| [AirDropDyldCache](https://github.com/Lakr233/AirDropDyldCache) | `System` | `MIT` | `Swift` | Low-level format parsing, reverse-engineering tooling, and CLI bridging. | — |
| [AlertController](https://github.com/Lakr233/AlertController) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Simple AlertViewController |
| [AppleMobileDeviceLibrary](https://github.com/Lakr233/AppleMobileDeviceLibrary) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | Repo to store binary targets |
| [ApplePackage](https://github.com/Lakr233/ApplePackage) | `Tooling` | `MIT` | `Swift` | CLI/service interfaces, automation flows, and integration patterns. | ipatool rewrite in library and cli using Swift |
| [AppleSiliconUIKitPatch](https://github.com/Lakr233/AppleSiliconUIKitPatch) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | Script to patch iOS app so we can later use it on Apple Silicon devices. |
| [ASMultiAppsRiverView](https://github.com/Lakr233/ASMultiAppsRiverView) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | App Store Like Multi App River View |
| [Asspp](https://github.com/Lakr233/Asspp) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | The App Store for your multi-account eco system. |
| [AssppWeb](https://github.com/Lakr233/AssppWeb) | `App` | `MIT` | `TypeScript` | Full product structure, module boundaries, and interaction flow. | — |
| [AudioEditorKit](https://github.com/Lakr233/AudioEditorKit) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Simplified audio editing library for Swift + UIKit. |
| [AuxiliaryExecute](https://github.com/Lakr233/AuxiliaryExecute) | `Tooling` | `MIT` | `Swift` | System command wrappers, process management, and environment passing. | A Swift wrapper for system shell over posix_spawn with search path and env support. |
| [Axchange](https://github.com/Lakr233/Axchange) | `System` | `MIT` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | Android file transfer via ADB |
| [BlossomColorPicker](https://github.com/Lakr233/BlossomColorPicker) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | — |
| [BootableBackupOSX](https://github.com/Lakr233/BootableBackupOSX) | `Tooling` | `Unlicense` | `Shell` | Backup/restore flows, task orchestration, and failure handling. | A script to backup all your macOS files using rsync. |
| [BQBClassifier](https://github.com/Lakr233/BQBClassifier) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A machine learning based emoji image classifier |
| [BreakGlass](https://github.com/Lakr233/BreakGlass) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |
| [CameraTools](https://github.com/Lakr233/CameraTools) | `System` | `MIT` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | EXIF Tool Kit |
| [ChatBot-TGLM6B](https://github.com/Lakr233/ChatBot-TGLM6B) | `Tooling` | `WTFPL` | `Python` | Chat UI, message models, and conversation-layer abstractions. | ChatGLM-6B Bot for Telegram |
| [ChatClientKit](https://github.com/Lakr233/ChatClientKit) | `Library` | `MIT` | `Swift` | Chat UI, message models, and conversation-layer abstractions. | — |
| [ChidoriMenu](https://github.com/Lakr233/ChidoriMenu) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Drop in replacement for _presentMenuAtLocation: |
| [code-clarity](https://github.com/Lakr233/code-clarity) | `Tooling` | `MIT` | `—` | Agent skill structure, prompt organization, and code readability rules. | Claude Code skill for readable code — naming, early return, abstraction levels, and class design. Swift-primary. |
| [CodeEditorUI](https://github.com/Lakr233/CodeEditorUI) | `Library` | `Unlicense` | `TypeScript` | Reusable API design, UI components, and module boundaries. | CodeMirror Binding to Apple UI Frameworks (UIKit, AppKit, SwiftUI) |
| [Colorful](https://github.com/Lakr233/Colorful) | `Library` | `MIT` | `Swift` | Color systems, gradient rendering, and animated backgrounds. | A SwiftUI implementation of AppleCard's animated colorful blur background. |
| [ColorfulX](https://github.com/Lakr233/ColorfulX) | `Library` | `MIT` | `Swift` | Color systems, gradient rendering, and animated backgrounds. | ColorfulX is a high-performance library designed for creating vibrant & animated mesh gradient views. |
| [ColorVector](https://github.com/Lakr233/ColorVector) | `Library` | `MIT` | `Swift` | Core algorithms, API design, and responsibility boundaries. | Color with its space, in Swift. |
| [ComputerUse](https://github.com/Lakr233/ComputerUse) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |
| [ConfigurableKit](https://github.com/Lakr233/ConfigurableKit) | `Library` | `MIT` | `Swift` | Settings-page modeling, form abstractions, and configurable UIKit patterns. | Set up settings pages like a charm with UIKit. |
| [CoreExtendedNFC](https://github.com/Lakr233/CoreExtendedNFC) | `System` | `MIT` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | Swift Package porting libnfc protocol-layer logic to iOS via CoreNFC |
| [CreemKit](https://github.com/Lakr233/CreemKit) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | — |
| [CreemProxy](https://github.com/Lakr233/CreemProxy) | `Tooling` | `MIT` | `Go` | Proxy boundaries, auth isolation, and upstream API wrapping. | A proxy designed for Creem users to securely delegate requests to the Creem API. |
| [CydiaRepoSync](https://github.com/Lakr233/CydiaRepoSync) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |
| [Dealer](https://github.com/Lakr233/Dealer) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | Simple web search with multiple source. |
| [Dog](https://github.com/Lakr233/Dog) | `Library` | `MIT` | `Swift` | Logging models, persistence strategies, and debugging interfaces. | A lightweight persist logging system. |
| [DpkgVersion](https://github.com/Lakr233/DpkgVersion) | `App` | `MIT` | `Swift` | Core algorithms, API design, and responsibility boundaries. | Swift implementation of robust dpkg semi-semantic version management. |
| [DYLDExtractor](https://github.com/Lakr233/DYLDExtractor) | `System` | `MIT` | `Swift` | Low-level format parsing, reverse-engineering tooling, and CLI bridging. | Packed tool for extracting frameworks and libraries from iOS dyld shared cache. |
| [esp32-nfc-display](https://github.com/Lakr233/esp32-nfc-display) | `System` | `MIT` | `C` | Protocol bridges, low-level parsing, and device interaction. | Simple app to display nfc card info. |
| [Evil.Objective-C](https://github.com/Lakr233/Evil.Objective-C) | `App` | `WTFPL` | `Objective-C` | Full product structure, module boundaries, and interaction flow. | Use with caution |
| [Firework](https://github.com/Lakr233/Firework) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A firework box app. |
| [FishUpgrade](https://github.com/Lakr233/FishUpgrade) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A macOS slacking simulator. |
| [Fix-GPS](https://github.com/Lakr233/Fix-GPS) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | Reads location data from lifetime tracks and writes it into photos. |
| [FixTim](https://github.com/Lakr233/FixTim) | `App` | `MIT` | `Swift` | Runtime patching, compatibility layers, and macOS workaround patterns. | Fix every runtime bug on macOS. |
| [FluidInterpolation](https://github.com/Lakr233/FluidInterpolation) | `Library` | `MIT` | `Swift` | Core algorithms, API design, and responsibility boundaries. | — |
| [GGLyn](https://github.com/Lakr233/GGLyn) | `System` | `Unlicense` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | An HTTP-to-BLE bridge for the Dingdang Classmate D1X thermal printer. |
| [GitLab-License-Generator](https://github.com/Lakr233/GitLab-License-Generator) | `Tooling` | `WTFPL` | `Ruby` | CLI/service interfaces, automation flows, and integration patterns. | Generate GitLab License For Self-Hosted/Private Instances |
| [Halloween24](https://github.com/Lakr233/Halloween24) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |
| [iLrcOverlay](https://github.com/Lakr233/iLrcOverlay) | `Library` | `MIT` | `Objective-C` | Reusable API design, UI components, and module boundaries. | — |
| [IOKit-Headers](https://github.com/Lakr233/IOKit-Headers) | `System` | `MIT` | `C` | Protocol bridges, low-level parsing, and device interaction. | — |
| [iOSreExtension](https://github.com/Lakr233/iOSreExtension) | `Tooling` | `Apache-2.0` | `TypeScript` | CLI/service interfaces, automation flows, and integration patterns. | A fast and elegant extension for VSCode used for iOSre projects. |
| [iphone-mcp](https://github.com/Lakr233/iphone-mcp) | `Tooling` | `MIT` | `Python` | MCP interface design, tool exposure, and automation workflows. | A Model Context Protocol (MCP) server for automating iPhone tasks with Appium. Supports app control, UI interactions, and screenshot capture via streamable HTTP. |
| [Iridium](https://github.com/Lakr233/Iridium) | `System` | `MIT` | `Swift` | Low-level format parsing, reverse-engineering tooling, and CLI bridging. | An iOS app decrypter, full static using fouldecrypt. |
| [iVariant](https://github.com/Lakr233/iVariant) | `System` | `MIT` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | Read iOS device model/variants from Xcode. |
| [LanguageModelChatUI](https://github.com/Lakr233/LanguageModelChatUI) | `Library` | `MIT` | `Swift` | Chat UI, message models, and conversation-layer abstractions. | — |
| [libcapstone-spm](https://github.com/Lakr233/libcapstone-spm) | `System` | `BSD-3-Clause` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | Swift Package Manager support for Capstone disassembly engine |
| [libghostty-spm](https://github.com/Lakr233/libghostty-spm) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | — |
| [libimg4-spm](https://github.com/Lakr233/libimg4-spm) | `System` | `MIT` | `Swift` | Low-level format parsing, reverse-engineering tooling, and CLI bridging. | Swift Package Manager wrapper for img4tool (Apple IMG4/IM4P firmware container parser) |
| [libssh2-spm](https://github.com/Lakr233/libssh2-spm) | `System` | `MIT` | `Swift` | Protocol bridges, low-level parsing, and device interaction. | Swift package for libssh2, automatically tracked on release tags. |
| [libzip-spm](https://github.com/Lakr233/libzip-spm) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | — |
| [ListViewKit](https://github.com/Lakr233/ListViewKit) | `Library` | `MIT` | `Swift` | Data-driven lists, refresh strategies, and scrolling performance. | An UITableView replacement that won't create glitches when changing data. Requires iOS 13.0+. |
| [Litext](https://github.com/Lakr233/Litext) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | A tiny rich-text supporting library for Apple platform. |
| [markdown_core](https://github.com/Lakr233/markdown_core) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Swift package to wrap around rust package markdown |
| [mobilePillowTalkLite](https://github.com/Lakr233/mobilePillowTalkLite) | `App` | `BSD-3-Clause` | `Swift` | Full product structure, module boundaries, and interaction flow. | An iOS & SwiftUI server monitor tool for linux based machines using remote proc file system with script execution. |
| [MobileTransfer](https://github.com/Lakr233/MobileTransfer) | `App` | `MIT` | `Swift` | Backup/restore flows, task orchestration, and failure handling. | Backup & restore iOS devices with advanced settings. |
| [MoneyProgress](https://github.com/Lakr233/MoneyProgress) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A progress bar for getting through the workday. |
| [MSDisplayLink](https://github.com/Lakr233/MSDisplayLink) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | The missing DisplayLink object for Apple platforms. |
| [myyearwithgit](https://github.com/Lakr233/myyearwithgit) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A year-end report for code repositories. |
| [NaiveboomDockerComposed](https://github.com/Lakr233/NaiveboomDockerComposed) | `Tooling` | `MIT` | `JavaScript` | CLI/service interfaces, automation flows, and integration patterns. | docker-compose capability layer for naive boom~ |
| [NotchDrop](https://github.com/Lakr233/NotchDrop) | `App` | `MIT` | `Swift` | Notch-area UI, drag-and-drop entry points, and temporary file flows. | Use your MacBook's notch like Dynamic Island for temporary storing files and AirDrop |
| [NotchNotification](https://github.com/Lakr233/NotchNotification) | `App` | `MIT` | `Swift` | Notch-area UI, drag-and-drop entry points, and notification presentation. | Display Notification Inside Mac's Notch. |
| [notion-mcp-proxy](https://github.com/Lakr233/notion-mcp-proxy) | `Tooling` | `MIT` | `Python` | MCP interface design, tool exposure, and automation workflows. | move bearer token to local clients |
| [openssl-spm](https://github.com/Lakr233/openssl-spm) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | Swift Package for OpenSSL with prebuilt XCFramework |
| [PhotopeaElectronApp](https://github.com/Lakr233/PhotopeaElectronApp) | `Tooling` | `WTFPL` | `JavaScript` | CLI/service interfaces, automation flows, and integration patterns. | — |
| [Privacy-Insight](https://github.com/Lakr233/Privacy-Insight) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | Read iOS 15 privacy insight '.ndjson' file into your human brain. |
| [pwgen](https://github.com/Lakr233/pwgen) | `Tooling` | `MIT` | `Swift` | CLI/service interfaces, automation flows, and integration patterns. | Simple command line to generate random password. |
| [RainbowFart](https://github.com/Lakr233/RainbowFart) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | An offline compliment machine with attention sensing. |
| [Remove-All-Your-Stars](https://github.com/Lakr233/Remove-All-Your-Stars) | `Tooling` | `WTFPL` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | Remove all your star from GitHub |
| [SafariYYDS](https://github.com/Lakr233/SafariYYDS) | `App` | `Unlicense` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |
| [Saily](https://github.com/Lakr233/Saily) | `App` | `Unlicense` | `Objective-C` | Full product structure, module boundaries, and interaction flow. | Modern. Fast. Beautiful. |
| [ScrubberKit](https://github.com/Lakr233/ScrubberKit) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | — |
| [Sentry](https://github.com/Lakr233/Sentry) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A powerful macOS security monitoring application that detects unauthorized access attempts and records video evidence for you. |
| [SkyLightWindow](https://github.com/Lakr233/SkyLightWindow) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Display your UI on lock screen. |
| [SleepHoldService](https://github.com/Lakr233/SleepHoldService) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | A lightweight macOS service that prevents system sleep when the lid is closed. |
| [SpeedBall](https://github.com/Lakr233/SpeedBall) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | Bring back the old 90's floating speed ball to your Mac with a somehow modern design. |
| [SpringInterpolation](https://github.com/Lakr233/SpringInterpolation) | `Library` | `MIT` | `Swift` | Core algorithms, API design, and responsibility boundaries. | Spring Interpolation for you to create animation |
| [swift-trustcache](https://github.com/Lakr233/swift-trustcache) | `System` | `MIT` | `Swift` | Low-level format parsing, reverse-engineering tooling, and CLI bridging. | Pure Swift library for creating and parsing Apple trust caches (v1) |
| [SwiftThrottle](https://github.com/Lakr233/SwiftThrottle) | `Library` | `MIT` | `Swift` | Core algorithms, API design, and responsibility boundaries. | A simple throttle written in Swift. |
| [TextExpress2-CheatBRT](https://github.com/Lakr233/TextExpress2-CheatBRT) | `App` | `MIT` | `Python` | Full product structure, module boundaries, and interaction flow. | A cheat for you to play Text Express 2, using brute force or search word with giving conditions. |
| [TreeNewBee](https://github.com/Lakr233/TreeNewBee) | `App` | `MIT` | `LLVM` | Full product structure, module boundaries, and interaction flow. | Tree New Bee. |
| [unJailbreakBash](https://github.com/Lakr233/unJailbreakBash) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | a script to unjailbreak, update from Electra |
| [vphone-cli](https://github.com/Lakr233/vphone-cli) | `Tooling` | `MIT` | `Swift` | CLI/service interfaces, automation flows, and integration patterns. | — |
| [wcdb-spm-prebuilt](https://github.com/Lakr233/wcdb-spm-prebuilt) | `Tooling` | `MIT` | `Shell` | CLI/service interfaces, automation flows, and integration patterns. | — |
| [WindowAnimation](https://github.com/Lakr233/WindowAnimation) | `Library` | `MIT` | `Swift` | Reusable API design, UI components, and module boundaries. | Provide animation when animating SwiftUI windows on macOS. |
| [X2D-GPS-Companion](https://github.com/Lakr233/X2D-GPS-Companion) | `App` | `MIT` | `Swift` | Full product structure, module boundaries, and interaction flow. | — |

## Practical Copy Rules

1. You can directly study and reuse project structure, reusable components, algorithms, CLI flows, and system-bridge ideas.
2. Before copying, verify third-party dependency licenses, branding assets, screenshots, icons, API keys, and private endpoints.
3. Keep any required `LICENSE`, `NOTICE`, and attribution text from the original repository.
4. If a repository does not have a clear license, treat it as inspiration only and do not copy the implementation.
