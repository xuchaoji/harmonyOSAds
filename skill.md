# HarmonyOS Ads Kit (广告服务) 开发指南

## 描述

本 Skill 包含华为鸿蒙（HarmonyOS）Ads Kit（广告服务）的完整开发文档，涵盖流量变现服务、广告形式（横幅、原生、激励、插屏、开屏、贴片）、OAID（开放匿名设备标识符）、实时竞价、常见问题等所有核心内容。

## 触发条件

当用户需要以下帮助时，自动加载本 Skill：
- 鸿蒙/HarmonyOS 广告接入相关的问题
- Ads Kit（广告服务）的 API 使用
- 流量变现服务开发
- 各种广告形式的实现（横幅广告、原生广告、激励广告、插屏广告、开屏广告、贴片广告）
- 实时竞价（RTB）集成
- OAID 获取与使用
- 广告相关错误排查
- Web 组件广告过滤

## 文档索引

本 Skill 包含 **32 篇**鸿蒙广告相关文档，分为开发指南（19篇）和 API 参考（13篇）：

- 开发指南: `reference/*.md`（19篇）
- API 参考: `reference/api/*.md`（13篇）

### Ads Kit（广告服务）核心文档

| 文档ID | 标题 | 说明 |
| -------- | ------ | ------ |
| `ads-introduction` | Ads Kit简介 | 整体介绍、流量变现服务、OAID服务、场景介绍、约束和限制 |
| `ads-kit-glossary` | Ads Kit术语 | 广告相关的专业术语解释 |
| `ads-kit-guide` | Ads Kit（广告服务） | 功能列表与开发索引 |
| `ads-publisher-service-dev` | 流量变现服务开发 | 开发概述与所有广告形式汇总 |

### 广告形式开发指南

| 文档ID | 标题 | 说明 |
| -------- | ------ | ------ |
| `ads-publisher-service-dev-overview` | 流量变现服务开发概述 | 开发前的准备工作和概述 |
| `ads-publisher-service-banner` | 横幅广告 | Banner广告的接入与开发 |
| `ads-publisher-service-native` | 原生广告 | 原生广告的接入与开发 |
| `ads-publisher-service-reward` | 激励广告 | 激励视频广告的接入与开发 |
| `ads-publisher-service-interstitial` | 插屏广告 | 插屏广告的接入与开发 |
| `ads-publisher-service-splash` | 开屏广告 | 开屏广告的接入与开发 |
| `ads-publisher-service-roll` | 贴片广告 | 贴片广告的接入与开发 |
| `ads-real-time-bidding` | 实时竞价 | 实时竞价的集成说明 |

### 常见问题

| 文档ID | 标题 | 说明 |
| -------- | ------ | ------ |
| `ads-publisher-service-faq` | 流量变现服务常见问题 | FAQ总览 |
| `ads-publisher-service-faq-4` | 展示广告时显示白屏 | 白屏问题排查 |
| `ads-publisher-service-faq-6` | 鲸鸿动能媒体服务平台打开受限 | 平台受限问题 |
| `ads-publisher-service-faq-7` | PC设备请求或展示广告时返回了801错误码 | 801错误码排查 |

### 相关文档

| 文档ID | 标题 | 说明 |
| -------- | ------ | ------ |
| `description-of-personal-data` | 鲸鸿动能Ads Kit个人数据处理说明 | 个人数据处理与隐私合规 |
| `ad-redirection` | 广告跳转 | 应用间广告跳转实现 |
| `web-adsblock` | 使用Web组件的广告过滤功能 | Web组件中的广告过滤 |

## 使用方式

参考文档位于: `/mnt/d/aiCodeing/adsSkill/skills/harmonyos-ads/reference/`

1. 当用户提问时，根据问题内容找到相关的文档
2. 使用 `read` 工具读取对应的 `/mnt/d/aiCodeing/adsSkill/skills/harmonyos-ads/reference/{文档ID}.md` 文件
3. 解析文档中的代码示例和 API 说明，帮用户解决问题

### 文档分类与路由

- **概述/入门** → `ads-introduction.md`, `ads-kit-guide.md`
- **术语查询** → `ads-kit-glossary.md`
- **横幅广告** → `ads-publisher-service-banner.md`
- **原生广告** → `ads-publisher-service-native.md`
- **激励广告** → `ads-publisher-service-reward.md`
- **插屏广告** → `ads-publisher-service-interstitial.md`
- **开屏广告** → `ads-publisher-service-splash.md`
- **贴片广告** → `ads-publisher-service-roll.md`
- **实时竞价/RTB** → `ads-real-time-bidding.md`
- **错误排查** → `ads-publisher-service-faq*.md`
- **隐私合规** → `description-of-personal-data.md`
- **Web广告过滤** → `web-adsblock.md`
- **广告跳转** → `ad-redirection.md`
- **核心API/所有接口** → `api/js-apis-advertising.md`（广告服务框架全部API）
- **广告对象类型** → `api/js-apis-advertisement.md`
- **AutoAdComponent组件** → `api/js-apis-autoadcomponent.md`
- **AdComponent组件** → `api/js-apis-adcomponent.md`
- **广告扩展服务** → `api/js-apis-adsserviceextensionability.md`
- **OAID标识符** → `api/js-apis-oaid.md`
- **广告错误码** → `api/errorcode-ads.md`, `api/errorcode-oaid.md`

### API 参考文档

| 文档ID | 标题 | 说明 |
| -------- | ------ | ------ |
| `api/js-apis-advertising` | @ohos.advertising (广告服务框架) | 核心API：导入模块、showAd、loadAd、AdRequestParams、AdOptions、AdDisplayOptions、AdLoadListener、AdInteractionListener、错误码等全部接口 |
| `api/js-apis-advertisement` | advertisement (广告内容) | 广告对象类型定义 |
| `api/js-apis-autoadcomponent` | @ohos.advertising.AutoAdComponent | 轮播广告展示组件属性与方法 |
| `api/js-apis-adcomponent` | @ohos.advertising.AdComponent | 广告展示组件属性与方法 |
| `api/js-apis-adsserviceextensionability` | @ohos.advertising.AdsServiceExtensionAbility | 广告扩展服务能力 |
| `api/js-apis-oaid` | @ohos.identifier.oaid (OAID) | 开放匿名设备标识符获取API |
| `api/ads-api` | Ads Kit API 总览 | API列表与导航 |
| `api/ads-arkts` | ArkTS API 目录 | ArkTS API索引 |
| `api/ads-advert` | advertisement 目录 | advertisement子模块导航 |
| `api/ads-comp` | ArkTS组件 目录 | 广告组件导航 |
| `api/errorcode-ads` | 广告服务框架错误码 | 21800001-21800004等错误码详解 |
| `api/errorcode-oaid` | OAID错误码 | 17300001, 17300002等错误码详解 |
| `api/ads-arkts-errcode` | 错误码 目录 | 错误码导航 |

## 关键API速查

### 广告类型枚举
- 横幅广告 (Banner)
- 原生广告 (Native)
- 激励广告 (Rewarded)
- 插屏广告 (Interstitial)
- 开屏广告 (Splash)
- 贴片广告 (Roll)

### 广告请求核心流程
1. 创建广告请求参数 (AdRequestParams)
2. 获取广告提供者 (AdProvider)
3. 加载广告 (LoadAd)
4. 展示广告 (ShowAd)
5. 处理回调 (AdLoadListener, AdDisplayListener)

### 常用错误码
- 200: 成功
- 401: 鉴权失败
- 801: 请求超时
- 1200: 广告请求参数错误

### 权限要求
- `ohos.permission.INTERNET` - 网络访问权限
- `ohos.permission.APP_TRACKING_CONSENT` - 个性化推荐权限
