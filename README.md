# Windows Software

我的 Windows 软件清单。换机重装照着装，附每项的去留理由。

> Windows 11

## 系统增强

| 软件                                                            | 用途                              | 备注                               |
| ------------------------------------------------------------- | ------------------------------- | -------------------------------- |
| [Twinkle Tray](https://github.com/xanderfrangos/twinkle-tray) | 托盘调显示器亮度，支持 DDC/CI 外接屏          | 1.17.2，托盘滚轮，步进 2%                |
| [Volume²](https://github.com/irzyxa/Volume2)                  | 滚轮/热键调音量，可换肤 OSD                | 26.1.0.471，皮肤 Windows 11 v3 Dark |
| [Windhawk](https://windhawk.net)                              | 系统 UI 模组平台，hook 注入 explorer.exe | 1.7.3，见下方 mod 列表                 |
| [NetTime](https://timensecure.com/nettime)                    | NTP 网络校时                        | 解决系统时间漂移                         |

### Windhawk mods

| Mod                             | 用途                          | 配置                     |
| ------------------------------- | --------------------------- | ---------------------- |
| Taskbar Clock Customization     | 任务栏时钟改格式，可加天气/网速/CPU/GPU/内存 | 三行：时间/日期/星期，显示秒，180×60 |
| Taskbar tray system icon tweaks | 隐藏托盘系统图标，调「显示桌面」按钮宽度        | 隐藏音量图标，按钮宽 12px        |

## 文件与搜索

| 软件                                      | 用途            | 备注                 |
| --------------------------------------- | ------------- | ------------------ |
| [Everything](https://www.voidtools.com) | 极速文件名搜索       | 1.4.1.1024，NTFS 索引 |
| [7-Zip](https://www.7-zip.org)          | 压缩解压          | 26.06              |
| [ImageGlass](https://imageglass.org)    | 轻量看图，替代照片查看器  | 9.4.1              |
| [PixPin](https://pixpinapp.com)         | 截图、贴图、OCR、长截图 | 3.6.6              |

## 媒体

| 软件                                      | 用途            | 备注       |
| --------------------------------------- | ------------- | -------- |
| [PotPlayer](https://potplayer.daum.net) | 本地视频播放器，格式支持全 | 24.12.16 |
| [OBS Studio](https://obsproject.com)    | 录屏、直播推流       | 32.1.2   |
| [calibre](https://calibre-ebook.com)    | 电子书管理与格式转换    | 9.5.0    |

## 写作与知识

| 软件                               | 用途                      | 备注         |
| -------------------------------- | ----------------------- | ---------- |
| [Obsidian](https://obsidian.md)  | 本地 Markdown 笔记库         | 1.14.5     |
| [Typora](https://typora.io)      | Markdown 编辑器，所见即所得      | 1.0.4      |
| [Xmind](https://xmind.app)       | 思维导图                    | 26.5       |
| [Zotero](https://www.zotero.org) | 文献管理、引用插入               | 8.0.4      |
| [Pandoc](https://pandoc.org)     | 文档格式互转（md/docx/pdf/tex） | 3.9        |
| Microsoft Office 2019            | 办公套件                    | 16.0.19127 |
| WPS Office                       | 办公套件（与 Office 并存）       | 12.1.0     |

## 开发

| 软件                                                     | 用途                                | 备注            |
| ------------------------------------------------------ | --------------------------------- | ------------- |
| [VS Code](https://code.visualstudio.com)               | 主力编辑器                             | 1.143.1       |
| [IntelliJ IDEA](https://www.jetbrains.com/idea/)       | Java IDE                          | 2021.3.3      |
| [PyCharm](https://www.jetbrains.com/pycharm/)          | Python IDE                        | 2025.3.1      |
| [CLion](https://www.jetbrains.com/clion/)              | C/C++ IDE                         | 2026.2.4      |
| [Android Studio](https://developer.android.com/studio) | Android 开发                        | —             |
| [Git](https://git-scm.com)                             | 版本控制                              | 2.54.0        |
| [Node.js](https://nodejs.org)                          | JS 运行时                            | 24.18.0       |
| [Python](https://www.python.org)                       | 3.10.4                            | 另有 Java 8 JDK |
| [Qoder CN](https://qoder.com)                          | AI 编程 IDE                         | 0.5.1         |
| [CC Switch](https://github.com/farion1231/cc-switch)   | 一键切换 Claude Code / Codex 的 API 配置 | 3.19.2        |
| DeepSeek Harness                                       | DeepSeek 相关工具                     | 0.2.1-rc.5    |
| [SQLite Expert](https://www.sqliteexpert.com)          | SQLite 数据库管理                      | 5.4.34        |

## 网络

| 软件                                                                | 用途             | 备注           |
| ----------------------------------------------------------------- | -------------- | ------------ |
| [Clash Verge](https://github.com/clash-verge-rev/clash-verge-rev) | Clash 客户端，规则分流 | 2.4.7        |
| [v2rayN](https://github.com/2dust/v2rayN)                         | V2Ray/Xray 客户端 | 与 Clash 功能重叠 |

## 协作与通讯

微信 · QQ · 飞书 · 钉钉 · 腾讯会议 · 元宝 · 豆包 · 千问

## 网盘

阿里云盘 · 百度网盘 · 夸克网盘

## 其他

MuMu 模拟器 · DOSBox · 迅雷 · 同花顺 · 通达信 · 腾讯桌面整理 · 搜狗输入法 · WorkBuddy

---

## 备注

- **重叠项**：T-Clock Redux 与 Windhawk 的 Taskbar Clock Customization 都在改任务栏时钟，同时启用可能互相覆盖。
- **重叠项**：Clash Verge 与 v2rayN 都会接管系统代理，建议只留一个常驻。
- **重复安装**：同花顺存在 9.60.81 与 9.60.90 两个版本。
- **并存**：Office 2019 与 WPS 同时安装，注意文件关联归属。
