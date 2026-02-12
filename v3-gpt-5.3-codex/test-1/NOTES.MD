## 1. 项目上下文
- 品牌/产品：野生咖啡（新锐精品手冲咖啡豆）
- 行业：食品饮料 / 咖啡零售（DTC 优先）
- 营销目标（品/效/销）：
  - 品：Q2 新品上市 3 个月内建立品牌认知
  - 效：建立“风味教育 + 冲煮仪式感”内容心智
  - 销：获得 5,000+ 首单用户
- 投放周期：2026-04-01 至 2026-06-30（Q2）
- 预算：80 万元
- 目标受众：25-35 岁，一二线城市咖啡爱好者

## 2. 分析问题与范围界定
- 核心问题：在预算 80 万约束下，如何同时达成“新品认知”与“5000+ 首单”双目标。
- 纳入范围：
  - 目标人群触媒行为（短视频、内容社区、微信生态）
  - 平台商业化与流量趋势（腾讯、快手、B站）
  - 咖啡赛道竞争强度（瑞幸公开财报）
  - 小红书食品饮料/餐饮服务行业成本效率基准（内部数据）
- 不纳入范围：
  - 线下门店联动费用与分销渠道返利
  - 直播间搭建、人力与供应链履约成本拆分
  - 长周期品牌资产研究（>12 个月）
- 关键业务假设（用于估算，非实测）：
  - 客单价（AOV）：150 元
  - 毛利率：55%
  - 90 天复购因子：保守 0.7 / 基准 0.8 / 乐观 0.9

## 3. Evidence Ledger

| ID | 来源标题 | 类型 | URL/路径 | 发布日期 | 访问日期 | 时效标记 | 可信度 |
|---|---|---|---|---|---|---|---|
| S1 | 小红书行业投放数据（食品饮料/餐饮服务） | 内部数据资产 | `.agents/skills/media-planning/xiaohongshu_ad_data.json` | 未标注 | 2026-02-12 | 未知 | medium |
| S2 | Tencent Quarterly Results 页面（含 2025Q1-Q3） | 官方投资者页面 | https://www.tencent.com/en-us/investors/quarter-result.html | 页面持续更新 | 2026-02-12 | <=12m | high |
| S3 | Tencent Announces 2025 Third Quarter Results | 官方财报 PDF | https://static.www.tencent.com/uploads/2025/11/13/a33b6f19738615834787623f17d20ba3.pdf | 2025-11-13 | 2026-02-12 | <=12m | high |
| S4 | Kuaishou Technology Announces Second Quarter and Interim 2025 Unaudited Financial Results | 官方 IR | https://ir.kuaishou.com/news-releases/news-release-details/kuaishou-technology-announces-second-quarter-and-interim-2025/ | 2025-08-21 | 2026-02-12 | <=12m | high |
| S5 | Bilibili Inc. Announces Third Quarter 2025 Financial Results | 公司新闻稿（GlobeNewswire 分发） | https://www.globenewswire.com/news-release/2025/11/13/3187072/0/en/Bilibili-Inc-Announces-Third-Quarter-2025-Financial-Results.html | 2025-11-13 | 2026-02-12 | <=12m | high |
| S6 | 第56次《中国互联网络发展状况统计报告》发布 | 官方机构公告（CNNIC） | https://www.cnnic.net/n4/2025/0721/c326-11327.html | 2025-07-21 | 2026-02-12 | <=12m | high |
| S7 | Luckin Coffee Announces Second Quarter 2025 Financial Results | 官方 IR | https://investor.lkcoffee.com/news-releases/news-release-details/luckin-coffee-announces-second-quarter-2025-financial-results | 2025-07-30 | 2026-02-12 | <=12m | high |
| S8 | 中国数字媒介渠道基准数据参考 | 内部参考文档 | `.agents/skills/media-planning/channel-benchmarks.md` | 未标注 | 2026-02-12 | 未知 | medium |

## 4. 推理链（结论 -> 证据 -> 推导）

### C1 目标拆解：先种草建认知，再在中后段强承接首单
- 结论：采用“认知 40% + 转化 45% + 复购承接 15%”的目标结构，避免一开始过度追求 CPA 导致内容资产不足。
- 证据：`[S2][S3][S4][S5][S6]`
- 推导：
  - 腾讯/快手/B站均显示广告商业化仍在增长，Q2-Q3 流量供给与广告位效率并未恶化到无法做品牌投放。[S3][S4][S5]
  - CNNIC 显示网民规模与移动互联网使用仍高位，短视频与内容消费是主流触达入口，适合“教育型内容先行”。[S6]
- 数据类型：参考
- confidence：high

### C2 人群策略：以“风味认知型兴趣人群”作为种子，再扩圈到效率人群
- 结论：核心人群先锁定“手冲/精品咖啡内容消费者”，通过内容互动行为做 lookalike 扩量。
- 证据：`[S1][S6][S8]`
- 推导：
  - 小红书食品饮料、餐饮服务行业在 CTR/CPM 指标上具备可操作空间，适合以内容兴趣做冷启动筛选。[S1]
  - 以内容互动为早期优化目标，可比直接冲购买更稳定，适配新品教育期。[S8]
- 数据类型：参考 + 估算
- confidence：medium

### C3 渠道组合：小红书+抖音+微信为主，B站做深内容，快手小规模测试
- 结论：预算建议为小红书 40%、抖音 25%、微信生态 20%、B站 10%、快手 5%。
- 证据：`[S1][S2][S3][S4][S5][S8]`
- 推导：
  - 小红书对“风味教育+决策前搜索”有优势，内部数据支持食品饮料/餐饮服务成本可控。[S1]
  - 微信生态具备内容分发与小程序承接闭环，适合承担复购经营入口。[S2][S3]
  - B站用户深度消费内容能力强，适合冲煮教程、产地故事等“长内容种草”。[S5]
  - 快手流量规模强，但与一二线精品手冲人群匹配度不确定，先做 5% 测试控制风险。[S4][S6]
- 数据类型：参考 + 估算
- confidence：medium

### C4 预算分配模型：基准情景可达 6,165 首单，覆盖 5,000 目标
- 结论：在 80 万预算下，基准情景预计首单约 6,165，CPA 约 130 元。
- 证据：`[S1][S8]`
- 推导（统一口径估算）：
  - 公式：
    - 曝光量 = 预算 ÷ CPM × 1000
    - 点击量 = 曝光量 × CTR
    - 转化量 = 点击量 × CVR
    - CPA = 预算 ÷ 转化量
  - 基准参数（估算）：
    - 小红书：32 万；CPM 45；CTR 1.8%；CVR 2.2%
    - 抖音：20 万；CPM 38；CTR 1.6%；CVR 1.8%
    - 微信：16 万；CPM 55；CTR 1.4%；CVR 3.0%
    - B站：8 万；CPM 45；CTR 1.2%；CVR 1.6%
    - 快手：4 万；CPM 32；CTR 1.8%；CVR 1.2%
  - 结果（基准）：
    - 预计曝光：约 1,854 万
    - 预计点击：约 33.4 万
    - 预计首单：约 6,165
    - 预计 CPA：约 129.8 元
- 数据类型：估算
- confidence：medium

### C5 投放节奏：2周预热 + 6周放量 + 4周收口复购
- 结论：Q2 采用“预热-放量-收口”三段节奏，618 前后集中预算冲刺转化。
- 证据：`[S2][S3][S6][S7]`
- 推导：
  - 平台广告生态稳定增长，说明中期放量仍有支撑。[S3][S4][S5]
  - 赛道竞争强度高（瑞幸营收与开店高增），必须在节点期快速抢心智并承接交易。[S7]
- 数据类型：参考
- confidence：medium

## 5. 结论卡片（含 confidence）
- 卡片 1：渠道预算结构
  - 小红书 40% / 抖音 25% / 微信 20% / B站 10% / 快手 5%
  - confidence：medium

- 卡片 2：首单目标可达性（估算）
  - 保守 4,900；基准 6,165；乐观 7,320
  - 对应 CPA：163 / 130 / 109
  - confidence：medium

- 卡片 3：ROI 约束
  - 首单毛利 ROI：0.51 / 0.64 / 0.75（保守/基准/乐观）
  - 90 天 ROI（含复购）：0.86 / 1.14 / 1.43
  - 结论：若仅看首单，ROI 难达 1；必须依赖复购运营
  - confidence：low（复购因子待实测）

## 6. 结构化输出（给 report.html 使用）

### Executive Summary
- 80 万预算建议采取“内容教育优先 + 中后段转化收口”的叙事路径，主阵地为小红书、抖音、微信生态。[S1][S2][S3][S6]
- 基准测算可实现 6,165 首单（CPA 129.8 元），满足 5,000+ 目标；但即时首单毛利 ROI 预计约 0.64。[S1][S8]
- 项目关键成功因素是 90 天复购经营，而非单次首单转化；微信小程序应承担复购中枢。[S2][S3]

### Strategy & Budget
- 目标拆解：认知（内容）-> 转化（搜索/信息流）-> 复购（私域）
- 渠道建议：
  - 小红书（风味教育+搜索承接）40%
  - 抖音（短视频扩量+节点放量）25%
  - 微信生态（视频号+小程序承接）20%
  - B站（深内容背书）10%
  - 快手（成本测试）5%
- 节奏建议：预热 25% / 放量 35% / 收口 40%

### Outcome Projection
- 保守：4,900 首单，CPA 163，90天 ROI 0.86
- 基准：6,165 首单，CPA 130，90天 ROI 1.14
- 乐观：7,320 首单，CPA 109，90天 ROI 1.43

### Risk Mitigation
- 风险 1：大盘竞价波动导致 CPM 抬升
  - 应对：设置 CPM 上限和自动降档规则
- 风险 2：素材疲劳导致 CTR 下滑
  - 应对：每周素材刷新，保留 20% 测试预算
- 风险 3：复购不及预期导致 ROI 不达标
  - 应对：第 4 周上线会员补货机制，建立 30/60/90 天 cohort 看板

## 7. 数据缺口与待验证事项
- Gap 1：`xiaohongshu_ad_data.json` 无明确采集时间与样本口径。
  - 影响：实际竞价与估算可能偏离。
  - 建议：投放前向平台/代理补充近 90 天同类目实盘数据。
- Gap 2：缺少“精品手冲咖啡豆 DTC”公开复购基准。
  - 影响：ROI 预测不确定性高。
  - 建议：首月建立 cohort 复购追踪并每两周复盘。
- Gap 3：竞品素材频次与卖点迭代缺少系统监控。
  - 影响：创意更新节奏可能滞后。
  - 建议：建立周度竞品素材监测（主题/形式/互动率）。

## 8. Source Index
- [S1] 小红书行业投放数据（食品饮料/餐饮服务），`.agents/skills/media-planning/xiaohongshu_ad_data.json`（accessed: 2026-02-12）
- [S2] Investors - Tencent Quarterly Results, https://www.tencent.com/en-us/investors/quarter-result.html（accessed: 2026-02-12）
- [S3] Tencent Announces 2025 Third Quarter Results (PDF), https://static.www.tencent.com/uploads/2025/11/13/a33b6f19738615834787623f17d20ba3.pdf（published: 2025-11-13, accessed: 2026-02-12）
- [S4] Kuaishou Technology Announces Second Quarter and Interim 2025 Unaudited Financial Results, https://ir.kuaishou.com/news-releases/news-release-details/kuaishou-technology-announces-second-quarter-and-interim-2025/（published: 2025-08-21, accessed: 2026-02-12）
- [S5] Bilibili Inc. Announces Third Quarter 2025 Financial Results, https://www.globenewswire.com/news-release/2025/11/13/3187072/0/en/Bilibili-Inc-Announces-Third-Quarter-2025-Financial-Results.html（published: 2025-11-13, accessed: 2026-02-12）
- [S6] 第56次《中国互联网络发展状况统计报告》发布, https://www.cnnic.net/n4/2025/0721/c326-11327.html（published: 2025-07-21, accessed: 2026-02-12）
- [S7] Luckin Coffee Announces Second Quarter 2025 Financial Results, https://investor.lkcoffee.com/news-releases/news-release-details/luckin-coffee-announces-second-quarter-2025-financial-results（published: 2025-07-30, accessed: 2026-02-12）
- [S8] 中国数字媒介渠道基准数据参考, `.agents/skills/media-planning/channel-benchmarks.md`（accessed: 2026-02-12）
