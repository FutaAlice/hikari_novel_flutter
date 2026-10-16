### ⚠️2026.10.16 更新说明: 模拟 Chrome 浏览器 TLS, 绕过 Cloudflare 403
### ⚠️本仓库维护者只修 bug。要在这里做新功能，先开 [Issue](https://github.com/FutaAlice/hikari_novel_flutter/issues/new?template=feature.yml) 商量方向和范围。单纯请求新功能，请到 [15dd](https://github.com/15dd/hikari_novel_flutter/issues) 仓库。
### ⚠️自0.2.0版本开始，本软件开始转为使用网页源，放弃了mewx源
### ⚠️原作者不希望分享编译产物。编译出来只供自己使用，不要到处分享。网站做反扒会让 App 体验变差。奥さん、你也不想翻页等两秒还要输验证码吧？

<hr>

# Hikari Novel

使用Flutter构建的第三方轻小说文库客户端

<div>
  <img alt="GitHub Release" src="https://img.shields.io/github/v/release/FutaAlice/hikari_novel_flutter?style=for-the-badge&color=%23408A23">
  <img alt="License" src="https://img.shields.io/badge/License-MIT-Green?style=for-the-badge&color=rgb(164%2C25%2C49)">
</div>


## ✨ 功能
- Material Design 3风格
- 支持深浅模式切换
- 适配平板
- 支持章节缓存
- 支持查看评论与回复
- 阅读进度保存


## 📱 支持平台

| 平台     | 系统版本 | 测试日期    | 提交/版本号 |
|----------|-------- |------------|------------|
| Android  | 13      | 2026.10.13 | 0.6.0      |
| iOS      | N/A     |            |            |

其他版本请开 Issue，选择「[兼容性测试](https://github.com/FutaAlice/hikari_novel_flutter/issues/new?template=compat.yml)」。

填写平台、系统版本、机型、App 版本或 commit，并附上系统版本截图。

登录页、最近更新、评论区(含一条3天内的评论) 的截图。

测试日期以 Issue 创建日期为准。

## 🖼️ 软件截图
- 手机
<div align="center">
  <img src="./readme/1.jpg" width="30%"></img> <img src="./readme/2.jpg" width="30%"></img> <img src="./readme/3.jpg" width="30%">
</div>

- 平板
<div align="center">
  <img src="./readme/1_tablet.png" width="80%"></img> <img src="./readme/2_tablet.png" width="80%"></img>
</div>


## ⛓️ 分支介绍

- `master` 主分支, 发布版本用.
- `dev` 开发分支, 开发用.
- `main` / `develop` 保留, 用于从 [15dd](https://github.com/15dd/hikari_novel_flutter) 源仓库同步

新功能请开 Issue，选择「[新功能](https://github.com/FutaAlice/hikari_novel_flutter/issues/new?template=feature.yml)」。

从 15dd 或其他经过广泛测试的 fork 合并已有功能，选择「[合并已有功能](https://github.com/FutaAlice/hikari_novel_flutter/issues/new?template=port.yml)」。

维护者同意后再从 `dev` 拉分支，PR 合并回 `dev`。


## 📦 安装
- 本项目不提供安装包，请参考下方 `编译` 板块自行编译使用


## 💻 编译
- ##### 我的开发环境
  ```
  [√] Flutter (Channel stable, 3.47.4, on Microsoft Windows [版本 10.0.26200.9457], locale zh-CN) [251ms]
      • Flutter version 3.47.4 on channel stable at C:\SDK\flutter
      • Upstream repository https://github.com/flutter/flutter.git
      • Framework revision 9584c6713b (9 days ago), 2026-09-10 15:25:10 -0700
      • Engine revision 06a2e2a110
      • Dart version 3.13.3
      • DevTools version 2.60.0
      • Pub download mirror https://pub.flutter-io.cn
      • Flutter download mirror https://storage.flutter-io.cn
      • Feature flags: enable-web, enable-linux-desktop, enable-macos-desktop, enable-windows-desktop, enable-android,
        enable-ios, cli-animations, enable-native-assets, enable-record-use, enable-swift-package-manager,
        omit-legacy-version-file, enable-lldb-debugging, enable-uiscene-migration
  
  [√] Windows Version (Windows 11 or higher, 25H2, 2009) [959ms]
  
  [√] Android toolchain - develop for Android devices (Android SDK version 36.0.0) [1,750ms]
      • Android SDK at C:\SDK\android
      • Emulator version unknown
      • Platform android-36, build-tools 36.0.0
      • ANDROID_HOME = C:\SDK\android
      • Java binary at: C:\Program Files\Microsoft\jdk-17.0.20.101-hotspot\bin\java
        This JDK is specified by the JAVA_HOME environment variable.
        To manually set the JDK path, use: `flutter config --jdk-dir="path/to/jdk"`.
      • Java version OpenJDK Runtime Environment Microsoft-14940689 (build 17.0.20.1+1-LTS)
      • All Android licenses accepted.
  ```
- ##### 编译
  1. 克隆此仓库
  2. 安装flutter，参考 [flutter.dev](https://flutter.dev/docs/get-started/install)
  3. 准备 Rust 网络层的编译工具。Android 见 [DEVELOPMENT.android.md](./readme/DEVELOPMENT.android.md)，iOS 见 [DEVELOPMENT.ios.md](./readme/DEVELOPMENT.ios.md)
  4. 编译出对应平台的安装包，如 `flutter build apk`


## 🧑‍💻 交流
&nbsp;&nbsp;<a href="https://t.me/+CUSABNkX5U83NGNl"><img alt="Static Badge" src="https://img.shields.io/badge/Telegram-加入群组-blue?style=for-the-badge&logo=telegram"></a>


## 📣 声明
- 本项目是个人为了兴趣以及学习移动端开发而开发的，仅用于学习和测试
- 本项目所用API均从轻小说文库官方网站收集，不提供任何破解内容
- 本项目是个人项目，与轻小说文库官方无关，请注意辨别


## 📖 参考
- [flutter_dmzj](https://github.com/xiaoyaocz/flutter_dmzj)
- [venera](https://github.com/venera-app/venera)
- [mihon](https://github.com/mihonapp/mihon)
- [mikan_flutter](https://github.com/iota9star/mikan_flutter)
- [pilipala](https://github.com/guozhigq/pilipala)
- [PiliPalaX](https://github.com/orz12/PiliPalaX)
- [PiliPlus](https://github.com/bggRGjQaUbCoE/PiliPlus)
- AI


## ⭐ 星标数趋势
[![RepoStars](https://repostars.dev/api/embed?repo=15dd%2Fhikari_novel_flutter&theme=dark)](https://repostars.dev/?repos=15dd%2Fhikari_novel_flutter&theme=dark)