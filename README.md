# HarmonyOS Ads Kit Skill

华为鸿蒙（HarmonyOS）Ads Kit（广告服务）开发文档 Skill，为 AI 编程助手提供完整的广告接入参考资料。

## 简介

本 Skill 收录了华为开发者官方文档中关于 Ads Kit 的全部核心内容，涵盖：

- **6 种广告形式**：横幅 (Banner)、原生 (Native)、激励 (Rewarded)、插屏 (Interstitial)、开屏 (Splash)、贴片 (Roll)
- **实时竞价 (RTB)** 集成
- **OAID**（开放匿名设备标识符）获取
- **Web 组件广告过滤**
- **常见问题排查**（白屏、801 错误码等）
- **完整 API 参考**（13 篇接口文档）

文档来源：[华为开发者文档 - Ads Kit](reference/ads-introduction.md)

## 目录结构

```
harmonyos-ads/
├── skill.md                  # Skill 定义与索引（触发条件、文档路由）
├── reference/                # 开发指南（19 篇）
│   ├── ads-introduction.md           # Ads Kit 简介
│   ├── ads-kit-glossary.md           # 术语表
│   ├── ads-kit-guide.md              # 功能索引
│   ├── ads-publisher-service-*.md    # 各广告形式开发指南
│   ├── ads-real-time-bidding.md      # 实时竞价
│   ├── web-adsblock.md               # Web 组件广告过滤
│   └── api/                          # API 参考（13 篇）
│       ├── js-apis-advertising.md    # 广告服务框架（核心 API）
│       ├── js-apis-advertisement.md  # 广告对象类型
│       ├── js-apis-oaid.md           # OAID 获取
│       └── ...                       # 其他组件与错误码
```

## 使用方式

作为 AI 编程助手的 Skill，在对话中提及鸿蒙广告开发相关问题时自动加载。文档索引和路由规则见 `skill.md`。

## 文档说明

- 文档版本 V215 / V66（2026-06-08 更新）
- 共 32 篇 markdown 文档
- 包含完整的代码示例（ArkTS / Java）
- 接口说明均含参数表、返回值、错误码

## License

文档内容版权归华为所有，详见[华为开发者文档](reference/ads-introduction.md)。
