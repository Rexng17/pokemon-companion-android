# 试用版隐私说明 / Trial privacy notice

适用版本：0.7.1。更新日期：2026-11-06。

## 中文

本说明对应「弱点图鉴 / TypeDex」GitHub 试用包，维护与反馈入口为 [Rexng17/pokemon-companion-android](https://github.com/Rexng17/pokemon-companion-android/issues)。使用 App 无需注册账号。

### 截图与本地数据

只有点击识别并经 Android 系统授权后，App 才截取一次画面。截图仅在本机内存中处理，不持久保存、不上传。手动导入的图片同样在本机识别；App 不删除用户选择的原始图片。

收藏、选中的宝可梦、语言、浮窗位置与大小等偏好保存在应用私有存储。App 没有自建用户账号、云同步或独立用户行为统计服务。可在 Android 设置中清除应用数据或卸载 App，清除本地收藏、设置及统计缓存；已向第三方发出的网络请求不因此撤回。

### 联网功能

- **热门招式**：向 `championsbattledata.com` 请求所查看宝可梦的标识及双打统计，不发送截图。服务方可接收到 IP 地址及常规请求信息。结果在本机缓存，正常情况下 24 小时内复用，过期清理时最多保留 7 天和 64 条；离线图鉴和本地识别不依赖此服务。
- **广告**：0.7.1 不包含 Google 广告或同意管理 SDK，不初始化、不请求、不展示广告。热门招式查询仍需要上述网络请求；本版本没有为使用统计添加埋点。
- **下载与反馈**：GitHub 管理下载页面和公开 Issues，适用 [GitHub 隐私声明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。App 本身不要求 GitHub 登录，也没有自动上传问题报告。

### 权限与反馈

悬浮权限用于在其他 App 上方显示工具；屏幕捕获授权用于本次识别；前台服务和通知用于保持已开启的悬浮窗、执行单次捕获并提供关闭入口。可以关闭浮窗或在系统设置撤销相关权限，继续使用手动图鉴。

反馈时不要提交账号密码、设备唯一标识或含个人信息的完整屏幕截图。Issues 是公开的；只需提供型号、Android 版本、App 版本和复现步骤。后续若变更联网用途或接入正式广告，将同步更新说明。

## English

This notice covers TypeDex trial version 0.7.1, dated 2026-11-06. The project’s maintenance and feedback channel is [Rexng17/pokemon-companion-android](https://github.com/Rexng17/pokemon-companion-android/issues). No app account is required.

### Screen capture and local storage

The app captures a single frame only after you tap Scan and authorize capture through Android. Frames are processed in memory on the device, without being saved or uploaded. Imported images are also recognized locally; the app does not delete the original image you selected.

Favorites, the selected Pokémon, language and overlay layout preferences are stored in app-private storage. The app has no developer-operated accounts, cloud sync or separate usage analytics service. Clearing app data or uninstalling removes local preferences, favorites and cached statistics. This does not retract network requests already received by third parties.

### Network access

- **Popular moves:** requests to `championsbattledata.com` include the selected Pokémon identifier and doubles statistics parameters, never a screenshot. The service may receive your IP address and ordinary request metadata. Cached data is normally reused for 24 hours and pruned to at most seven days and 64 entries. Offline lookups and local recognition do not require this service.
- **Ads:** version 0.7.1 includes neither Google’s advertising SDK nor its consent SDK. It does not initialize, request or show ads. Popular move lookups still make the network requests described above; no usage analytics have been added.
- **Downloads and feedback:** GitHub hosts downloads and public Issues under its [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The app does not require GitHub sign-in and does not automatically upload bug reports.

### Permissions and contact

Overlay permission displays the tool above other apps. Android screen-capture consent enables the current scan. Foreground services and notifications support the enabled overlay and single-frame capture, with stop controls. Closing the overlay or revoking permissions still allows manual reference lookups.

Issues are public. Please provide only the phone model, Android version, app version and steps needed to reproduce a problem. Do not submit passwords, unique device identifiers or screenshots containing personal information. This notice will be updated if network purposes change or production advertising is introduced.
