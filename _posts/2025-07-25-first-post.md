---
title: "信息获取方法-RSS"
date: 2025-07-25
categories: [工具]
tags: [RSS, 工具]
author: "Dan"
toc: true
toc_label: "文章目录"
toc_icon: "bars"
---

RSS是我这些年来一直使用的重要信息获取途径。RSS是一项历史悠久的技术，其核心原理是将网站或博客的内容以标准化格式提供一个可访问的接口。这项技术让互联网信息获取变得更加简单高效，但由于不符合当前应用数据隔离的商业趋势，逐渐被大型厂商所抛弃。

我初次接触RSS技术是通过V2EX和少数派这两个平台。在这里，我对RSS有了初步了解，并开始尝试各种相关服务和应用程序。

经过多年的使用，我积累了一些实用经验，在此做个简单总结。

RSS订阅服务主要分为两大类别：一类是云端订阅服务，如inoreader、feedly等；另一类是本地客户端应用，如NetNewsWire和Reeder等。下面将分别详细介绍。

### 云端服务

在云端服务方面，我测试过以下几个主要平台：

**Inoreader** 是我使用体验较好的服务之一。界面设计美观，免费版本支持150个订阅源。虽然macOS没有原生客户端，但iOS和Android都有官方应用。其web端的订阅源发现功能特别实用，同一网站的多个RSS源会被整理展示，还能看到每个源的订阅人数，这对判断源的质量很有帮助。最大的优势是免费版本的订阅数量限制相对宽松。

**Feedly** 的使用频率不高，免费版仅支持100个订阅源。应用界面过于简洁，缺乏吸引力，用户体验一般。

**Feedbin** 采用简单直接的付费模式，只提供30天免费试用，之后必须付费使用。由于成本考虑，我没有深度使用。

**NewsBlur** 界面简洁清爽，但移动应用显得过时，设计风格偏向old school。免费版最多支持64个订阅源，限制较为严格。

**FreshRSS** 是自建解决方案，需要自己管理服务器和存储资源，维护成本较高，最终放弃使用。

**Feeder** 是最近发现的新选择，提供实用的Chrome插件可以直接预览RSS源，免费版支持200个订阅源，限制相对宽松。不过主流RSS客户端的集成支持还不够完善。

### 客户端

在客户端应用方面，我体验过以下几款主要产品：

**NetNewsWire** 是最值得推荐的RSS客户端，完全免费且开源，体现了优秀的软件哲学。从界面设计到开发者博客，都令人印象深刻。在苹果生态系统中表现出色，几乎无可挑剔。使用中遇到的主要问题是iCloud同步在新设备上速度较慢，这可能是iCloud本身的限制。另外，当NetNewsWire连接Inoreader账号时，只能获取近期更新，较久远的历史文章无法显示。

**Reeder** 的定价相对较高，macOS和iOS版本需要分别购买，总计约15美元。虽然界面设计确实精美，但我并未发现明显的杀手级功能。目前Reeder有两个版本：Reeder Classic采用传统的买断制，提供基础的阅读体验；新版Reeder则采用订阅制，集成了RSS源搜索等高级功能。

**Feeeed** 是近期出现的新兴应用，直接基于iCloud同步，无需依赖第三方云服务。订阅操作便捷，界面展示美观，还集成了AI功能。但存在一个明显缺陷：不支持搜索功能。

**Folo** 由RSShub作者开发，号称是下一代的信息浏览器。结合了区块链技术，虽然我也不知道具体原理。在macOS平台表现出色，基于iCloud同步。其最大亮点是直接集成RSShub进行订阅源发现，还提供翻译和AI功能，而且还免费。不过目前稳定性仍有待提升，macOS版本相对完善，而移动端应用连横屏适配都尚未完成。

### 我的推荐

我自己的RSS工具总是在切换。目前主要使用NetNewsWire作为主力客户端，通过iCloud进行数据同步，这样可以完整保留所有订阅源的历史文章记录。同时配合Folo来发现新的订阅源，其集成的RSShub搜索功能非常实用。此外，保留Inoreader作为备用方案，确保在需要时有替代选择。这套组合既保证了阅读体验，又兼顾了订阅管理的便利性。


