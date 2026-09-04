# Seamless 下载与更新

Seamless 是本地优先的清单应用，支持清单管理、AI 助手、插件和局域网同步。
此仓库提供编译后的应用、更新说明和更新源；不包含应用源码。

[查看所有版本](https://github.com/sd0116baka/Seamless-releases/releases)

- 正式版：经过正式发布的版本。
- Nightly：每日测试版本，在 Releases 中标记为 Pre-release。
- Windows：首次运行 `Seamless-windows-setup.exe`，以后在应用内更新。
- macOS：解压 `Seamless-macos.zip` 并移到应用程序目录。
- Android：安装 `Seamless-android.apk`，以后应用内下载并确认系统安装请求。

在侧边栏“应用更新”中选择通道。通道切换重启后生效，不自动降级。
各版本附有 `SHA256SUMS.txt`。桌面更新包还会由原生更新器验证签名。

首次迁移提醒：旧 Android 测试包的签名可能与新版本不同，无法直接覆盖安装。
请先通过节点同步保留并确认数据可恢复，不要直接卸载有数据的旧版本。
macOS 当前尚未进行 Apple Developer ID 公证，首次安装可能需要系统确认。
