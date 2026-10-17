# Refina 隐私政策 / Privacy Policy

**最后更新：2026-10-17** · 适用版本 v2.1.0 起

Refina 由 **Hanyu Filming Studio**（SSM 202103146940 / CA0324496-P，独资企业，马来西亚吉隆坡）开发并提供。
联系方式：filmingalliancemy@gmail.com

---

## 一句话版本

**你的影片、照片、音频永远不会离开你的电脑，连文件名都不会。**
我们只知道你按过哪些功能、哪一步出错、你的电脑是什么规格。

---

## 1. 我们收集什么

| 资料 | 为什么 |
| --- | --- |
| 你的 Google 邮箱 | 识别账号、同步成就、你要删资料时能找到你 |
| 功能使用次数（例如「跑过 3 次照片」「用过精细去噪」） | 知道哪些功能有人用、哪些可以砍掉 |
| 任务失败时**卡在哪一步**（例如「影片 · 放大 · 失败」） | 修 bug |
| 电脑规格：macOS 版本、芯片型号、内存大小 | 知道什么配置容易出问题 |
| App 版本号 | 知道 bug 出在哪一版 |
| 你**主动点「报 bug」**送出的内容 | 处理你报的问题 |
| 你同意本条款的版本号 | 证明取得过同意 |

## 2. 我们不收集什么

- **你的素材文件本身**。所有处理（AI 放大、补帧、去噪、修脸、上色、去背、人声分离）**全部在你自己的 Mac 上完成**，不经过任何服务器。
- **你的文件名**。失败记录只保留步骤名称，文件名在上传前就被剥掉了。
- 你的通讯录、位置、浏览记录、其他 App 的资料。这些我们碰都不碰。
- 密码。登录走 Google 官方流程，我们拿到的只有一个授权令牌，看不到你的密码。

## 3. 资料存在哪里

存在 **Google Firebase (Cloud Firestore)**，由 Google 运营，服务器位于马来西亚境外。
这表示你的邮箱和使用统计会被**传输到马来西亚以外**并储存在当地。使用 Refina 即表示你知悉并同意这项跨境传输。

登录令牌只存在**你自己电脑上**的
`~/Library/Application Support/Refina/`，权限 600（只有你的账号读得到），不会上传。

## 4. 我们怎么用这些资料

**只用来改进 Refina 本身**：看哪些功能常用、bug 集中在哪、什么配置容易出问题。

我们**不会**：
- 卖给任何人
- 交给第三方做营销
- 投放广告
- 拿你的作品做任何用途（我们根本拿不到）

## 5. 第三方

| 服务 | 用途 | 它会拿到什么 |
| --- | --- | --- |
| Google 登录 (OAuth) | 验证身份 | 你授权时 Google 自己知道的那些 |
| Google Firebase | 存成就和统计 | 本页第 1 节列出的内容 |
| GitHub | 下载 App 和检查更新 | 你的 IP（GitHub 的常规日志） |
| Hugging Face | 首次使用某些功能时下载 AI 模型 | 你的 IP |

App 内**没有**任何广告 SDK、第三方分析工具或追踪器。

## 6. 保留多久

账号还在就一直保留。你要求删除时我们会删掉。

## 7. 你的权利

你可以要求：**查看**我们存了你哪些资料、**更正**、**删除**、**撤回同意**。

寄信到 **filmingalliancemy@gmail.com**，我们会在**合理时间内**处理（通常几天）。
删除账号后，你电脑上的 App 仍可继续使用，只是成就不再同步。

你也可以随时自己删掉本机资料：直接删除
`~/Library/Application Support/Refina/` 这个文件夹。

## 8. 儿童

Refina 不是给儿童设计的，我们不会刻意收集 13 岁以下儿童的资料。

## 9. Cookie

Refina 是 macOS 原生应用程序，**不使用 cookie**。

## 10. 改动

本政策如有改动，会更新本页顶部的日期，重大改动会在 App 内重新请求同意。

---

# English

**Last updated: 2026-10-17** · Applies from v2.1.0

Refina is made by **Hanyu Filming Studio** (SSM 202103146940 / CA0324496-P, sole proprietorship, Kuala Lumpur, Malaysia).
Contact: filmingalliancemy@gmail.com

**In one line: your video, photos and audio never leave your computer, not even their file names.**

**What we collect:** your Google email (to identify your account and sync achievements), which features you use and how often, the step a job failed at (step names only), your machine specs (macOS version, chip, memory), the app version, bug reports you choose to send, and the version of these terms you accepted.

**What we never collect:** your media files (all processing runs locally on your Mac), your file names (stripped before upload), your contacts, location or browsing history, or your password (login goes through Google's own flow).

**Where it is stored:** Google Firebase (Cloud Firestore), on servers outside Malaysia. Using Refina means you consent to that cross-border transfer. Your login token stays on your own machine at `~/Library/Application Support/Refina/` with 0600 permissions and is never uploaded.

**How we use it:** only to improve Refina. Never sold, never shared for marketing, no ads, and we never touch your work because we never receive it.

**Third parties:** Google Sign-In (identity), Google Firebase (storage), GitHub (downloads and update checks, sees your IP), Hugging Face (first-time AI model downloads, sees your IP). There are no ad SDKs, analytics tools or trackers in the app.

**Your rights:** request access, correction, deletion, or withdraw consent by emailing filmingalliancemy@gmail.com. You can also delete local data yourself by removing `~/Library/Application Support/Refina/`.

**Cookies:** none. Refina is a native macOS app.
