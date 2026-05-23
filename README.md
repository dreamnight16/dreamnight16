# 梦夜十六 · DreamNight

**code for life, build for fun.**

---

## 项目生态 / Project Ecosystem

```mermaid
flowchart LR
    subgraph AI["AI 伴侣"]
        CE[companion-engine] --> YM[Yumema]
        CE --> VP[V-Partner]
    end

    subgraph Content["内容与抓取"]
        SU[chinese-scraper-utils] --> CR[ComiRadar]
        SU --> WH[weekly-hotspot]
        CR --> MB[myBlog]
        WH --> MB
    end

    subgraph Learn["学习与工具"]
        DC[DreamCode]
        YN[Yanmo]
    end

    style CE fill:#4a6fa5,color:#fff
    style YM fill:#4a6fa5,color:#fff
    style VP fill:#4a6fa5,color:#fff
    style SU fill:#6b8e23,color:#fff
    style CR fill:#6b8e23,color:#fff
    style WH fill:#6b8e23,color:#fff
    style MB fill:#6b8e23,color:#fff
    style DC fill:#b5651d,color:#fff
    style YN fill:#b5651d,color:#fff
```

### AI 伴侣 / AI Companion

| Project | Description | Package |
|---------|-------------|---------|
| [companion-engine](https://github.com/sixtdreanight/companion-engine) | 核心引擎，驱动所有 AI 伴侣应用 / Core engine for AI companion apps | [![npm](https://img.shields.io/npm/v/@sixtdreamnight/companion-engine)](https://www.npmjs.com/package/@sixtdreamnight/companion-engine) |
| [Yumema](https://github.com/sixtdreanight/Yumema) | Electron 桌面应用，基于 companion-engine / Electron desktop app | |
| [V-Partner](https://github.com/sixtdreanight/V-Partner) | CLI + QQ 机器人，基于 companion-engine / CLI & QQ bot | |

### 内容与抓取 / Content & Scraping

| Project | Description | Package |
|---------|-------------|---------|
| [chinese-scraper-utils](https://github.com/sixtdreanight/chinese-scraper-utils) | 通用爬虫工具库 / Shared scraping utilities | [![PyPI](https://img.shields.io/pypi/v/chinese-scraper-utils)](https://pypi.org/project/chinese-scraper-utils/) |
| [ComiRadar](https://github.com/sixtdreanight/ComiRadar) | 动漫事件雷达，驱动博客 events 页面 / Anime event radar | |
| [weekly-hotspot](https://github.com/sixtdreanight/weekly-hotspot) | 每周热点深度分析，驱动博客 weekly 页面 / Weekly hot topics | |
| [myBlog](https://github.com/sixtdreanight/myBlog) | 个人博客 (Astro + React) / Personal blog | |

### 学习与工具 / Learning & Tools

| Project | Description |
|---------|-------------|
| [DreamCode](https://github.com/sixtdreanight/DreamCode) | 交互式编程入门课，让编程充满乐趣 / Interactive vibe coding course |
| [Yanmo](https://github.com/sixtdreanight/Yanmo) | 学术研究助手 (研墨) / Academic research assistant |

---

## GitHub 统计 / Stats

![DreamNight's GitHub stats](https://github-readme-stats.vercel.app/api?username=sixtdreanight&show_icons=true&theme=graywhite&hide_border=true&locale=cn)

---

## 链接 / Links

- **博客 / Blog**: [dreamnight.net.cn](https://dreamnight.net.cn)
