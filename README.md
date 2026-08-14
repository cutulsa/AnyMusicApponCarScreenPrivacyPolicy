[README.md](https://github.com/user-attachments/files/31051175/README.md)
# Privacy Policy — Car Screen

*[中文版见下](#car-screen-隐私权政策)*

**Last updated: 2026-08-13**

**Car Screen does not collect, store, or share any personal data.**

## What this app does

Car Screen reads the media session that is already active on your phone and mirrors the
track title, artist and album art to the Android Auto screen. It forwards the playback
controls you press in the car back to the app that is actually playing. It plays no audio
of its own.

## No data collection

This app collects no data of any kind. Nothing is sent anywhere, because the app has no
network capability at all: it does not request the `INTERNET` permission, contains no
networking code, and includes no third-party analytics, advertising or crash-reporting
components.

## Notification access

Android only allows an app holding notification access to read what is currently playing.
Car Screen uses that permission solely as the credential for reading playback information.
The service behind it implements no notification callbacks at all: it never reads, parses,
stores or transmits notification content. You can revoke this permission at any time in
Android's Settings.

## What is stored on your device

Two things, both in the app's private storage, neither ever leaving the device:

- your preferences: which source you pinned, which sources you blocked, the title-cleanup
  switch, and how often each source was selected;
- a cache of album artwork taken from the currently playing app, kept so the car screen can
  show artwork without delay.

Uninstalling the app removes both permanently.

## Exporting diagnostics

The app has an optional *Export diagnostics* button. It builds a text report of the app's
own settings and status, the media sessions currently present on the phone (app package
names, playback state and the track title being shown), and the app's own recent log lines.
The report never contains notification content, account information or location.

**The app does not send this report anywhere.** It is handed to Android's share sheet, and
you alone decide whether to share it and with whom. If you never press the button, no report
is ever created.

## Permissions

The app declares no runtime or dangerous permissions. The only entry in its permission list
is an internal, self-signed permission automatically added by the Android support libraries;
it grants no capability outside the app itself.

## Children

This app is not directed at children and collects no data from anyone.

## Changes

Any change to this policy will be published at this same address with an updated date.

## Contact

louisliu0896@gmail.com

---

# Car Screen 隐私权政策

**最后更新：2026-08-13**

**Car Screen 不收集、不存储、不共享任何个人数据。**

## 本应用做什么

Car Screen 读取手机上当前已经活跃的媒体会话，把曲名、歌手和专辑封面镜像到 Android Auto
屏幕，并把你在车机上按下的播放控制转发回真正在播放的那个应用。本应用自己不播放任何音频。

## 不收集任何数据

本应用不收集任何形式的数据。也不存在把数据发出去的可能——它完全没有联网能力：不申请
`INTERNET` 权限、不含任何网络代码、不含任何第三方分析、广告或崩溃上报组件。

## 关于通知访问权限

Android 只允许持有通知访问权限的应用读取当前播放信息。Car Screen 仅把该权限用作读取播放
信息的凭据。承载该权限的服务没有实现任何通知回调：它从不读取、解析、存储或传输任何通知内容。
你可以随时在系统设置中收回该权限。

## 设备上保存了什么

两类，都在应用私有存储中，都不会离开你的设备：

- 你的偏好设置：置顶了哪个音源、屏蔽了哪些音源、标题清洗开关，以及各音源被选中过的次数；
- 一份专辑封面缓存，取自当前正在播放的应用，用于让车机即时显示封面。

卸载应用会永久删除以上全部内容。

## 关于导出诊断信息

应用里有一个可选的「导出诊断信息」按钮。它会生成一份文本报告，内容包括：本应用自己的设置与
状态、手机上当前存在的媒体会话（应用包名、播放状态、正在显示的曲目名），以及本应用自己的近期
日志。报告中不含通知内容、不含账号信息、不含位置。

**本应用不会把这份报告发送到任何地方。** 它只是交给 Android 的系统分享面板，是否分享、
分享给谁完全由你决定。如果你从不按这个按钮，报告就永远不会被生成。

## 权限

本应用未声明任何运行时权限或危险权限。权限列表中唯一的一条是 Android 支持库自动加入的内部
自签名权限，它不授予本应用之外的任何能力。

## 儿童

本应用不面向儿童，也不从任何人处收集数据。

## 变更

本政策的任何变更都会发布在同一地址，并更新日期。

## 联系方式

louisliu0896@gmail.com
