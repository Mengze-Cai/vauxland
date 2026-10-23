# Vauxland

每日 AI 与开源项目雷达 · Daily AI & Open-Source Radar

**先看懂一个项目能做什么，再决定是否值得打开。**

AI 产品和开源项目更新很快，真正费时间的不是找到链接，而是判断：它解决什么问题、适不适合自己、是否值得继续研究。

Vauxland 把每日项目信号整理为中文用途说明，配合历史日报、搜索收藏、情报来源与评测导航，帮助你从“发现一个名字”走到“理解它的价值”。以 AI 为主，也保留部分相关开发工具与开源生态项目。

[访问网站](https://www.vauxland.com/) · [浏览全部项目](https://www.vauxland.com/discover?ds=all) · [完整使用指南](USAGE.md) · [反馈问题](https://github.com/Mengze-Cai/vauxland/issues)

> 这是网站介绍、使用说明和公开反馈仓库，不是网站源码仓库。直接访问网站即可使用，无需克隆、安装或部署；浏览和本机收藏不需要注册账号。

## 第一次来，建议这样用

1. **看看最近有什么值得关注。** 打开[首页](https://www.vauxland.com/)，先看当前日报日期，再读项目的中文介绍和关注理由。
2. **带着问题找工具。** 到[完整项目库](https://www.vauxland.com/discover?ds=all)，搜索“智能体”“视频”“推理”等用途，配合分类、项目类型和“只看 AI 项目”缩小范围。
3. **看懂之后，再去原站。** 打开项目详情，核对官网、GitHub、许可证与数据日期；有可靠资料时，还能看到官方 README 的入门说明。
4. **把值得研究的留下。** 点击心形收藏，在[我的收藏](https://www.vauxland.com/saved)集中回看，并通过导出／导入文件迁移清单。

想回看某一天？点击首页日期或发现页的“浏览范围”，打开日历，选择有数据的已发布日期；想持续跟进，可以[订阅日报 RSS](https://www.vauxland.com/feeds/daily.xml)。具体操作见[完整使用指南](USAGE.md)。

## 网站可以帮你做什么

| 页面 | 适合解决的问题 | 主要功能 |
| --- | --- | --- |
| [首页与日报](https://www.vauxland.com/) | 最近有什么值得打开？ | 最新已发布一期、本期概览、焦点项目与最多 5 条额外项目导读；日历可回看历史。 |
| [发现](https://www.vauxland.com/discover) | 有没有适合我用途的项目？ | 查看单期完整榜单或累计项目库，组合关键词、分类、项目类型、AI 筛选与排序，分批加载结果。 |
| 项目详情（从卡片进入） | 它到底做什么，下一步去哪里？ | 中文用途、关注理由、资料与官方链接；有可靠依据时展示 README 入门说明，并标明检查日期。 |
| [来源](https://www.vauxland.com/sources) | 应该去哪里继续查资料？ | 先看核心入口，再按全部分类浏览产品、模型、论文、社区等网站；说明各站用途与访问方式。 |
| [评测](https://www.vauxland.com/benchmarks) | 选模型或 Agent，应该看什么榜？ | 核心评测入口、能力分类与搜索；展开查看主要指标、适用范围、方法和局限。 |
| [收藏](https://www.vauxland.com/saved) | 如何保存和整理研究清单？ | 当前浏览器收藏、清单内搜索、JSON 导出与合并导入。 |
| [功能说明](https://www.vauxland.com/features) | 数据从哪来，功能有哪些边界？ | 网站工作流，以及日期、热度、搜索范围和收藏机制说明。 |

## 四件最容易误解的事

**归档不再限于最近 30 天。** 每日快照长期保存，公开日历可选择自 **2026 年 9 月 22 日**起全部已有的已发布日报。起始日之前、缺期、未发布及未来日期置灰；长期保存不等于每天都有一期。“全部项目”则汇总累计收录且仍公开可见的资料，并非把同一项目每天重复列出。

**发现页默认日报，首页搜索默认全库。** 直接进入发现页、未输入搜索词时，默认最新已发布日报；从首页发起搜索、未指定日期时搜索全库。选定日期后，关键词只筛选该期。想扩大范围，切换“浏览范围 → 全部项目”。

**Stars 是热度信号，不是产品评分。** “当日新增”来自采集时 GitHub Trending 的标注；“较上次入榜”是与上次可用记录的累计差值，可能跨多天；“累计 Stars”是采集时总量。三者不能混为同一天增长，也不是实时数据。

**来源与评测是导航，不是已经打通的数据库。** 收录一个网站不表示已接入它的数据、已关联每天的项目，或 Vauxland 自行复测过它的成绩。API／RSS 标签描述原站的访问方式，不代表本站接入状态。

首页只展示精选导读，不等于当天只收录了这几个项目。通过“查看本期完整榜单”进入发现页，即可浏览该期完整已发布列表；日报还有独立的 `/daily/YYYYMMDD` 链接，便于收藏和分享。

## 内容如何产生

公开项目信号 → 补全仓库资料 → AI 辅助整理中文说明 → 人工对照审核 → 发布带日期的日报。

项目资料主要来自 GitHub Trending、已配置的订阅来源与项目公开文档。自动化负责准备资料和待审核文案，审核与发布仍由管理员决定。因此首页展示的是**最新已发布一期**，不承诺每天固定时刻更新，也不把未发布的日期显示为已有日报。

中文说明用于帮助理解，不等于逐项实测、安全审计或购买建议。开始使用前，请回到项目原站核对最新状态、运行环境、许可证、模型／API 费用和部署成本。

## 订阅日报 RSS

把下面的地址添加到 Inoreader 或其他支持 RSS 的阅读器：

**[Vauxland Daily RSS](https://www.vauxland.com/feeds/daily.xml)**

订阅提供最近 20 期已发布日报的项目名称、中文用途与带日期的链接；历史完整归档仍以网站日历为准。RSS 跟随发布更新，不是实时 Stars 接口，也不会包含未审核草稿。若某期没有发布，不会用空白记录冒充新一期。

## 收藏与隐私

- 收藏保存在当前设备、当前浏览器，不会因为登录 GitHub 或其他账号就自动跨设备同步。
- 换浏览器、使用无痕模式或清除站点数据前，请先导出收藏 JSON；在另一浏览器导入会合并清单，不覆盖原有记录。
- 收藏会保留关联的日报日期；如果对应快照不可用，页面会提示并尝试显示仍可见的最新资料。导出文件是清单备份，不包含网页全文或完整历史数据。
- GitHub Issues 是公开空间。反馈时请勿提交 API Key、密码、Token、个人联系方式或未经脱敏的后台截图。

## 反馈与推荐

欢迎[提交 Issue](https://github.com/Mengze-Cai/vauxland/issues/new)，报告错误、推荐项目或讨论功能。为便于核对，请提供：

1. 页面／项目链接，以及对应的日报日期（如有）。
2. 你做了什么、实际看到什么、期望是什么。
3. 如涉及介绍或数据错误，附上支持更正的官方资料链接；截图请先脱敏。

推荐项目时，补充官网或 GitHub 地址、主要用途和推荐理由即可。推荐不等于保证收录，也请勿在 Issue 中粘贴第三方受版权保护的全文。

如果网站帮你发现了有价值的项目，欢迎 Star 本介绍仓库，或把 [Vauxland](https://www.vauxland.com/) 分享给同样关注 AI 的朋友。

## English overview

Vauxland is an AI-first discovery website for products and open-source projects. It combines Chinese-language explanations, published daily editions, a long-term calendar archive of available editions from September 22, 2026, searchable project profiles, device-local bookmarks, daily RSS, and curated information-source and benchmark directories.

Visit [vauxland.com](https://www.vauxland.com/) to use the product. No installation is required. The directories link to external resources; they do not imply full data integration or independent benchmark replication. Bookmark lists stay in your current browser and can be exported and imported.

This repository is a **product introduction, user guide, and public feedback hub**. It does not distribute the website source code, credentials, production data, or deployment configuration.

---

说明更新：2026-10-23。功能与可用数据以[在线网站](https://www.vauxland.com/)为准。
