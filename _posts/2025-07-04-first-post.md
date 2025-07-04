---
title: "CursorUIViewService (not responding) 问题解决"
date: 2025-07-04
categories: [技术]
tags: [macOS, Cursor, 问题解决]
---

我一直在使用一台搭载M2芯片的MacBook Air作为办公和开发的主力设备。在使用苹果设备时，我习惯性地跟随最新的稳定版系统进行升级。在我看来，使用苹果设备实际上是在体验一套软硬件深度融合的解决方案。如果因为担心系统升级而错过新特性，未免有些因噎废食。如果系统升级后出现卡顿问题，我认为更合适的做法是更换新设备。当然，这种做法也存在一定风险，比如系统升级后某些老软件可能不兼容，或者部分老硬件可能不再支持。

最近升级到最新的macOS Sequoia后，我发现经常出现"CursorUIViewService (not responding)"的问题。根据查阅的资料，这个问题很可能与macOS Sonoma中新增的"Text Insertion Point (Cursor) / Caps-lock Indicator"特性有关。

经过一个月的测试验证，在关闭这个特性后，我的MacBook Air上再也没有出现过这个问题。

关闭方法如下：
```bash
sudo defaults write /Library/Preferences/FeatureFlags/Domain/UIKit.plist redesigned_text_cursor -dict-add Enabled -bool NO
```

结束。