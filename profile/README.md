[![DOORS 中文维基](assets/logo.png)](https://zh.doorsgame.wiki/wiki/DOORS_Wiki)

**DOORS 中文维基**是面向中文玩家的 DOORS 资料站点。我们整理游戏条目，校订译名与数据，并维护与站点相关的工具项目。

## 001 · 正门

| 入口 | 用途 |
| --- | --- |
| **[进入中文维基](https://zh.doorsgame.wiki/wiki/DOORS_Wiki)** | 查阅条目、实体、机制、物品与版本资料 |
| **[开始贡献](https://zh.doorsgame.wiki/wiki/Help:%E5%BC%80%E5%A7%8B%E8%B4%A1%E7%8C%AE)** | 了解编辑方式与贡献流程 |
| **[Wiki 规则](https://zh.doorsgame.wiki/wiki/DOORS_Wiki:Rules)** | 阅读站点方针与协作规范 |

## 002 · 社群

| 平台 | 用途 | 入口 |
| --- | --- | --- |
| **QQ 交流群** | 日常交流、编辑协作与视频计划讨论 | **[加入](https://qm.qq.com/q/JVUedAJkoE)** |
| **Discord** | 跨平台即时交流 | **[加入](https://discord.gg/SpKAgJDuVn)** |
| **哔哩哔哩** | 条目视频化计划与官方投稿 | **[关注](https://space.bilibili.com/3706993330096130)** |
| **X（原 Twitter）** | 关注站点动态 | **[关注](https://x.com/DoorsWikiZH)** |

## 003 · 项目档案

### syncbot

> 将英文 DOORS Wiki 的模板与模块，以及腾讯文档中的成就文本和物品译名，同步到中文维基，并支持反向回写。

| 项目 | 内容 |
| --- | --- |
| 类型 | Wiki 数据同步工具 |
| 技术栈 | Python · pywikibot · Grist · systemd |
| 同步频率 | 成就常驻同步；物品译名每 5 分钟；腾讯文档至 Grist 每 30 分钟 |
| 冲突处理 | 对比 Wiki 与表格保存的状态哈希；两端同时变更且不一致时停止覆盖，交由人工处理 |
| 安全 | 仓库不包含账号、令牌或环境密钥 |
| 许可 | CC BY-SA 4.0 |
| 源码 | **[DOORS-Chinese-Wiki/syncbot](https://github.com/DOORS-Chinese-Wiki/syncbot)** |

**同步路径**

```text
腾讯文档 ──→ Grist ↔ 中文维基    成就文本 / 物品译名
英文 DOORS Wiki ──→ 中文维基      模板 / 模块 / 重定向
```

---

*主视觉素材来自 [DOORS 中文维基](https://zh.doorsgame.wiki/wiki/DOORS_Wiki) 与 [DOORS 官方维基](https://doorsgame.wiki/wiki/DOORS_Wiki)。站点内容除另有声明外，依 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 授权。*
