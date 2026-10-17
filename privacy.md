# SnapSort Privacy Policy / 隐私政策

**Effective date / 生效日期: October 7, 2026**

Pathvana LLC ("we", "us") built SnapSort as an on-first-principles private app: your screenshots are processed **on your device** by default. This policy explains exactly what happens to your data.

Pathvana LLC（"我们"）开发的 SnapSort 默认在**你的设备上**处理截图。本政策说明你的数据的实际去向。

## What stays on your device / 哪些数据只留在你的设备上

- SnapSort reads only the photos you authorize (full or limited access) and only processes assets the system marks as screenshots. It never modifies or deletes photos in your library.
- OCR (text recognition) runs locally using Apple's Vision framework. Titles, summaries, tags, notes, and recognized text are stored in a file inside the app's private container on your device.
- Three sample entries shown on first launch are bundled content, not your data.
- SnapSort contains **no analytics, no advertising, no trackers, and no third-party SDKs**. We collect nothing.

- SnapSort 仅读取你授权范围内的照片，且只处理系统标记为截图的照片，绝不修改或删除你相册中的照片。
- 文字识别（OCR）通过 Apple Vision 框架在本地完成。标题、摘要、标签、备注和识别文字保存在设备上 App 的私有目录中。
- 首次启动显示的三条示例为内置内容，不是你的数据。
- SnapSort **不含分析、广告、追踪或任何第三方 SDK**，我们不收集任何数据。

## What you can optionally send / 你可以选择发送的内容

All of the following are **off by default** and require your explicit action and consent:

- **Cloud AI organization (OpenAI / Anthropic).** If you enable this and provide your own API key, SnapSort sends the recognized text of a screenshot (up to 16,000 characters) to the provider you choose so it can generate a summary, topic, and tags. If you additionally enable image recognition, SnapSort sends a compressed copy of the screenshot (JPEG, max ~4 MB). These requests go directly from your device to the provider and are governed by that provider's privacy policy. We never see your API key, your content, or the results.
- **Notion export.** Only when you tap "Save to Notion" and confirm, SnapSort sends the exported text of that single entry to Notion's API using the integration token you configured.

以下功能**默认全部关闭**，需要你明确开启并授权：

- **云端 AI 整理（OpenAI / Anthropic）。** 开启并填入你自己的 API 密钥后，SnapSort 会把单张截图的识别文字（最多 16,000 字）发送给你选择的服务商，用于生成摘要、主题和标签；若额外开启图片识别，还会发送压缩后的截图（JPEG，最大约 4 MB）。请求从你的设备直接发往服务商，并受该服务商隐私政策约束。我们无法看到你的密钥、内容或结果。
- **Notion 导出。** 仅当你点击"保存到 Notion"并确认时，SnapSort 才会把该条内容的导出文字通过你配置的集成 token 发送到 Notion API。

## Credentials / 密钥

API keys and Notion tokens you enter are stored in the iOS Keychain on your device (`WhenUnlockedThisDeviceOnly`) and are transmitted only to the service they belong to — never to us.

你填写的 API 密钥和 Notion token 保存在设备钥匙串中（仅本机、解锁时可用），只发送给对应的服务商，不会发送给我们。

## Deleting your data / 删除你的数据

Delete the SnapSort app to remove all locally stored libraries and notes. Keys you saved are removed with the app's Keychain data. Content already sent to a cloud provider or to Notion is governed by those services.

删除 SnapSort 即可移除本地保存的全部资料和备注；钥匙串中的密钥随之删除。已发送给云服务商或 Notion 的内容由对应服务管理。

## Children / 儿童

SnapSort is not directed at children under 13 and we do not knowingly collect any personal information.

SnapSort 不面向 13 岁以下儿童，我们不会有意收集任何儿童个人信息。

## Changes / 政策变更

We will update this page if the app's data practices change, and revise the effective date above.

如应用的数据处理方式发生变化，我们会更新本页并修改生效日期。

## Contact / 联系

Pathvana LLC — [blurjp@gmail.com](mailto:blurjp@gmail.com)

## App Store Privacy Nutrition Label summary / App Store 隐私标签摘要

**Data Not Collected:** SnapSort does not collect any data from you. Optional content you explicitly send to third-party services you configure (OpenAI, Anthropic, Notion) is sent directly from your device to those services under your own accounts.

**不收集数据：** SnapSort 不收集你的任何数据。你主动配置并选择发送给第三方服务（OpenAI、Anthropic、Notion）的内容，由你的设备在你自己的账户下直接发送给对应服务。
