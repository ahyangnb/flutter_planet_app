[![GitHub stars](https://img.shields.io/github/stars/ahyangnb/flutter_planet_app)](https://github.com/ahyangnb/flutter_planet_app/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ahyangnb/flutter_planet_app)](https://github.com/ahyangnb/flutter_planet_app/network)
[![GitHub issues](https://img.shields.io/github/issues/ahyangnb/flutter_planet_app)](https://github.com/ahyangnb/flutter_planet_app/issues)

> 如果产生其他依赖无法编译的问题，可以尝试将`pubspec.yaml`中的`dependencies`中的所有依赖的"^"去掉或者插件版本号改为any，重新编译尝试。
> 还是出错的话在项目主目录执行`flutter clean`再重新运行。
> 如果出现插件版本不适配记得看`pubspec.yaml`文件介绍的插件flutter版本是否与自己本地Flutter适配。

# log

* 2020.10.10 创建；

# 介绍
flutter星球，仿网易星球app开源项目。

# 效果图
等待更新

# 第三方框架
等待整理

# 使用教程

*  使用命令（拉取项目）：$ git clone https://github.com/ahyangnb/flutter_planet_app.git
*  然后命令（获取依赖）：$ flutter packages get  (IOS执行IOS部分再执行下一步)
*  最后命令（运行）：$ flutter run

IOS
*  进入项目IOS目录：$ cd ios/
*  更新Pod（非必须）：$ pod update
*  安装Pod：$ pod install

如果出现`(Connection refused - connect(2) for "raw.githubusercontent.com" port 443)`，则表示还没设置国内源，
或者尝试下翻墙。

# 我的Flutter环境
```
q1deMacBook-Pro:~ q1$ flutter doctor -v
[✓] Flutter (Channel stable, 1.20.2, on Mac OS X 10.14.5 18F2059, locale
    zh-Hans-CN)
    • Flutter version 1.20.2 at /Users/q1/flutter
    • Framework revision bbfbf1770c (12 days ago), 2020-08-13 08:33:09 -0700
    • Engine revision 9d5b21729f
    • Dart version 2.9.1
    • Pub download mirror https://pub.flutter-io.cn
    • Flutter download mirror https://storage.flutter-io.cn

[✓] Android toolchain - develop for Android devices (Android SDK version 29.0.3)
    • Android SDK at /Users/q1/Library/Android/sdk
    • Platform android-29, build-tools 29.0.3
    • ANDROID_HOME = /Users/q1/Library/Android/sdk
    • Java binary at: /Applications/Android
      Studio.app/Contents/jre/jdk/Contents/Home/bin/java
    • Java version OpenJDK Runtime Environment (build
      1.8.0_242-release-1644-b3-6222593)
    • All Android licenses accepted.

[✓] Xcode - develop for iOS and macOS (Xcode 11.3)
    • Xcode at /Applications/Xcode.app/Contents/Developer
    • Xcode 11.3, Build version 11C29
    • CocoaPods version 1.8.4

[✓] Android Studio (version 4.0)
    • Android Studio at /Applications/Android Studio.app/Contents
    • Flutter plugin version 48.1.2
    • Dart plugin version 193.7361
    • Java version OpenJDK Runtime Environment (build
      1.8.0_242-release-1644-b3-6222593)

[✓] VS Code (version 1.47.3)
    • VS Code at /Applications/Visual Studio Code.app/Contents
    • Flutter extension version 3.12.2


[✓] Connected device (1 available)
    • sdk gphone x86 arm (mobile) • emulator-5554 • android-x86 • Android 11
      (API 30) (emulator)

• No issues found!
```

# Flutter微信群

<img src="assets/git/left_group.png" height="200" width="210" style="zoom:30%;" />

[上图无法显示点我](http://www.flutterj.com/left_group.png)

Flutter教程网：www.flutterj.com

Flutter交流QQ群：[874592746](https://jq.qq.com/?_wv=1027&k=5coTYqE)

# 公众号
<img src="http://www.flutterj.com/public.jpg" height="200" width="200" style="zoom:30%;" />

关注公众号“`Flutter前线`”，各种Flutter项目实战经验技巧，干活知识，Flutter面试题答案，等你来领取。

### LICENSE
```
flutter_planet_app is licensed under the
Apache License 2.0

A permissive license whose main conditions require preservation of copyright and license notices.
Contributors provide an express grant of patent rights.
Licensed works, modifications, and larger works may be distributed under different terms and without source code.
```
