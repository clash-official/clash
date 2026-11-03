<div align="center">
  <a href="https://github.com/clash-official/clash" title="Clash 官方渠道核对清单">
<img width="150" height="150" alt="Clash" src="https://github.com/user-attachments/assets/388727d7-80ff-4a24-8456-a52ce7b61bad" />

  </a>
  <h1>Clash 官方渠道核对清单 (2026年11月更新)</h1>
  <p>
    <b>发布页、Releases 与停更备份对照，减少下错源</b>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Update-2026.11-brightgreen.svg" alt="Update">
    <img src="https://img.shields.io/badge/Platform-Win%20%7C%20Mac%20%7C%20iOS%20%7C%20Android%20%7C%20Linux-blue.svg" alt="Platform">
    <img src="https://img.shields.io/badge/Ecosystem-Clash%20%7C%20Mihomo%20%7C%20Sing--box%20%7C%20Xray-orange.svg" alt="Ecosystem">
  </p>
</div>

如果你觉得这个项目对你有帮助，欢迎点右上角的**Star**⭐ 支持一下！

[代理雷达](https://github.com/guiforcores/dailileida)：每日追踪 mihomo、sing-box、Xray、V2Ray、Clash 及自研内核的代理客户端：开源项目看 GitHub Star，商店应用看美区 App Store / Google Play 评分数。

**本页导航：** [官方核对清单](#官方核对清单) · [发布渠道卡片](#发布渠道卡片) · [渠道对照](#渠道对照一眼看) · [停更与备份](#停更与备份渠道) · [订阅说明](#订阅与节点说明) · [FAQ](#faq) · [免责](#免责声明)

---

## 定位：官网向「发布渠道」索引

本仓库按 **Clash 官方渠道核对清单** 整理：**先核对渠道是否官方，再按发布渠道取包**。这里不做平台选型排行，也不做 Wiki 词条长文；目标是让你在下载前完成一套固定检查，并落到各项目的 **GitHub Releases**（或明确标注的备份仓）。

标题里的 `YYYY年M月更新` 与绿色 `Update-YYYY.MM` 徽章表示**本页维护月份**，不等于某一客户端发版日；二者由例行任务同步，请勿改乱格式。

---

## 官方核对清单

按顺序做完再点 Assets，可大幅降低装到仿冒包、停更旧包或错误架构包的概率。

### 1. 确认组织与仓库名

打开链接后先看地址栏：`https://github.com/<组织>/<仓库>`。组织名、仓库名应与下方「发布渠道卡片」一致。名称相近、多一个连字符、或突然跳到陌生域名的页面，一律当作未核验渠道。

### 2. 确认是 Releases，而不是 Issues / Wiki 附件

正式安装包应在该仓库的 **Releases** 页（URL 通常以 `/releases` 结尾）。Issues 评论、Discussions 附件、第三方网盘分享**不在本页背书范围内**。

### 3. 优先 Latest 正式版

默认选标注 **Latest** 的正式发布。Pre-release / nightly 仅在你明确需要尝鲜、并愿意自行承担兼容风险时使用。

### 4. 按 OS + CPU 选 Assets

同一 Release 常有多份构建：Windows x64 / arm64、macOS Apple Silicon / Intel、Linux AppImage / deb / rpm、Android apk 等。看文件名后缀与架构标记，**不要**凭「第一个文件」随便下。

### 5. 有校验信息就核对

若 Release 正文提供 SHA / 校验和，下载后本地核对再安装。Windows SmartScreen、macOS「无法验证开发者」提示时，先回到同一 Release 页确认包名与体积，再决定是否放行。

---

## 发布渠道卡片

以下每张卡片 = **一条发布渠道**：主链指向官方 GitHub Releases；说明只写渠道用途，不写逐步安装教程。卡片顺序按「常见桌面 → 跨端 → 移动 → 补充」排列，**不是**推荐榜。

### 渠道 A · Clash Verge Rev

| 项 | 内容 |
|:---|:-----|
| 发布页 | [clash-verge-rev/clash-verge-rev/releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| 覆盖面 | Windows / macOS / Linux |
| 渠道备注 | 活跃桌面维护分支之一；按 1–5 核对后取包 |

### 渠道 B · Clash Party

| 项 | 内容 |
|:---|:-----|
| 发布页 | [mihomo-party-org/clash-party/releases](https://github.com/mihomo-party-org/clash-party/releases) |
| 覆盖面 | Windows / macOS / Linux |
| 渠道备注 | Mihomo Party 系桌面客户端发布源 |

### 渠道 C · ClashX Meta

| 项 | 内容 |
|:---|:-----|
| 发布页 | [MetaCubeX/ClashX.Meta/releases](https://github.com/MetaCubeX/ClashX.Meta/releases) |
| 覆盖面 | macOS |
| 渠道备注 | Meta 系 macOS 客户端；注意与已停更的经典 ClashX 备份仓区分 |

### 渠道 D · FlClash

| 项 | 内容 |
|:---|:-----|
| 发布页 | [chen08209/FlClash/releases](https://github.com/chen08209/FlClash/releases) |
| 覆盖面 | Windows / macOS / Linux / Android |
| 渠道备注 | 同一发布页含多端构建；选 Assets 时务必对系统 |

### 渠道 E · Clash Mi

| 项 | 内容 |
|:---|:-----|
| 发布页 | [KaringX/clashmi/releases](https://github.com/KaringX/clashmi/releases) |
| 覆盖面 | Windows / macOS / Linux / iOS / Android |
| 渠道备注 | 跨端统一时常用；iOS 安装渠道以该仓库官方说明 / 商店为准，本页不索引不明 IPA |

### 渠道 F · Clash Meta for Android

| 项 | 内容 |
|:---|:-----|
| 发布页 | [MetaCubeX/ClashMetaForAndroid/releases](https://github.com/MetaCubeX/ClashMetaForAndroid/releases) |
| 覆盖面 | Android |
| 渠道备注 | Android 常见维护项；勿与下方「Clash for Android」停更备份混淆 |

### 渠道 G · Hiddify

| 项 | 内容 |
|:---|:-----|
| 发布页 | [hiddify/hiddify-app/releases](https://github.com/hiddify/hiddify-app/releases) |
| 覆盖面 | Windows / macOS / Linux / iOS / Android |
| 渠道备注 | 跨栈多端；配置模型可能与纯 Clash YAML 不完全对应，导入前读该仓说明 |

### 渠道 H · Clash Nyanpasu

| 项 | 内容 |
|:---|:-----|
| 发布页 | [LibNyanpasu/clash-nyanpasu/releases](https://github.com/LibNyanpasu/clash-nyanpasu/releases) |
| 覆盖面 | Windows / macOS / Linux |
| 渠道备注 | 桌面 GUI 补充渠道 |

### 渠道 I · 补充发布源

| 项目 | 发布页 | 覆盖面 |
|:-----|:-------|:-------|
| Bettbox | [appshubcc/Bettbox/releases](https://github.com/appshubcc/Bettbox/releases) | 桌面向补充 |
| Sparkle | [xishang0128/sparkle/releases](https://github.com/xishang0128/sparkle/releases) | 桌面向补充 |
| ClashBox | [xiaobaigroup/ClashBox/releases](https://github.com/xiaobaigroup/ClashBox/releases) | Android 补充 |

OpenWRT / 软路由一般不走上述桌面 GUI 的同一套 Assets；请查对应固件插件源或 mihomo 相关文档，并与手机/电脑配置分开备份。

---

## 渠道对照（一眼看）

用「你已决定要什么形态」反查卡片，而不是先填一张平台推荐表。

| 你需要的形态 | 先看这些渠道 |
|:-------------|:-------------|
| 只要桌面 GUI | A Verge Rev · B Party · H Nyanpasu · I Bettbox / Sparkle |
| 只要 macOS 专用入口 | C ClashX Meta（并可用 A / B 作对照） |
| 只要 Android 维护项 | F Clash Meta for Android · D FlClash · I ClashBox |
| 希望少换工具、多端共用 | E Clash Mi · G Hiddify · D FlClash |
| iOS | E / G 的官方说明或商店；**不要**从本页以外来路下 IPA |
| 热度旁证（非下载源） | [代理雷达](https://github.com/guiforcores/dailileida) |

---

## 停更与备份渠道

下列链接仅供**历史对照 / 归档查阅**，**不建议**作为日常主用发布渠道。若你仍打开它们，请同样执行 1–5，并优先迁回上方维护中渠道。

| 历史名称 | 备份 / 原仓库 | 迁移提示 |
|:---------|:--------------|:---------|
| Clash for Windows | [clash-latest/Clash-for-Windows](https://github.com/clash-latest/Clash-for-Windows) | 改看渠道 A / B / D 等桌面维护项 |
| ClashX | [clash-latest/ClashX](https://github.com/clash-latest/ClashX) | 改看渠道 C 或 A / B |
| Clash for Android | [clash-latest/Clash-for-Android](https://github.com/clash-latest/Clash-for-Android) | 改看渠道 F |
| Clash Verge（原版） | [zzzgydi/clash-verge/releases](https://github.com/zzzgydi/clash-verge/releases) | 日常改看渠道 A（Verge Rev） |
| ClashN | [2dust/clashN/releases](https://github.com/2dust/clashN/releases) | 归档对照 |

---

## 订阅与节点说明

- 本仓库**不托管、不生成、不代发**订阅或节点。  
- 客户端只是发布渠道；订阅由你自行准备，并遵守当地法律法规与服务条款。  
- 若需要节点相关的兄弟整理，可另见 [clash-latest/ClashNode](https://github.com/clash-latest/ClashNode)（内容与可用性以该仓为准，本页不作担保）。

导入订阅后：先测延迟，再开启系统代理或 TUN；避免多个同类工具同时抢系统代理。

---

## FAQ

**Q：本页和「按平台选型」类长文有什么不同？**  
A：本页是 **官网向发布渠道索引**：先跑核对清单，再按渠道卡片取 GitHub Releases；不做「某系统唯一推荐」排行。

**Q：为什么卡片里没有教程站外链？**  
A：安装细节以各仓库 README / Issues 为准，避免外链失效或与官方说明冲突。需要热度对照时用 [代理雷达](https://github.com/guiforcores/dailileida)。

**Q：Clash、Mihomo、Clash Meta 是不是同一个发布渠道？**  
A：不是。口语里常统称「Clash」；多数仍在维护的 GUI 使用 Mihomo 等兼容内核。以具体仓库 README 的内核说明为准。

**Q：可以只下停更备份仓吗？**  
A：可以查阅，但日常请改用维护中渠道卡片。备份仓可能缺少安全修复与新协议支持。

**Q：标题月份和 Update 徽章谁改？**  
A：例行任务自动更新 `YYYY年M月更新` 与 `Update-YYYY.MM`。人工改文案时请保留这两种字面格式。

**Q：Release 页 404 怎么办？**  
A：以 GitHub 上该组织当前页面为准；本页链接可能滞后，请回到卡片中的组织名重新搜索仓库。

---

## 免责声明

1. 本页仅为开源客户端 **发布渠道与核对步骤** 的索引，不提供绕过审查、侵犯版权或从事违法活动的服务或操作指南。  
2. 请遵守你所在地区的法律法规及服务条款；使用第三方客户端、订阅或节点的风险与后果由使用者自行承担。  
3. 第三方仓库的可用性、版本号与 Assets 列表随时变化；本仓库不对具体二进制做担保，也不镜像安装包。  
4. 日期徽章仅表示本页维护周期，不代表任一上游项目的发版日。

---

<sub>Clash 官方渠道核对清单 · 发布渠道索引 · 2026年11月更新 · 不镜像安装包</sub>
