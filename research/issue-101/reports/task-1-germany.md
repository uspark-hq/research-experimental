# 德国（Germany）乘用车税费研究报告

**时间戳:** 2025-01-23 UTC | CET (UTC+1)

## A) 答案先行（Executive Summary）

德国乘用车税负体系以19%增值税（Mehrwertsteuer）为基础，配合基于CO₂排放的年度车辆税（Kfz-Steuer）。2024年起终止了电动车购置补贴（Umweltbonus），转向公司车税收优惠。BEV享受至2030年免车辆税，但2026年后新注册BEV将立即按50%税率征收。关键影响：电动车政策从直接补贴转向税收激励，重点支持商用车队电气化。

## B) 法规速览表（Regulatory Overview）

| 税种/费用 | 法定税率/分段 | 计税基/公式 | 计算顺序 | 生效/修订日期 | 法源与条文 | 备注(本地语原名) |
|-----------|--------------|------------|----------|--------------|------------|------------------|
| 关税（Customs Duty） | CBU: 10%<br>CKD/SKD: 降低税率 | CIF价值 | 1 | 2025-01-01 | [EU TARIC](https://taxation-customs.ec.europa.eu/customs/calculation-customs-duties/customs-tariff/eu-customs-tariff-taric_en) | Zollsatz |
| 增值税（VAT） | 19% | CIF + 关税 | 2 | 2025-01-01 | [BMF](https://www.bundesfinanzministerium.de) | Mehrwertsteuer/MwSt |
| 车辆税（Vehicle Tax） | 汽油: €2/100cc<br>柴油: €9.50/100cc<br>CO₂: €0-4/g | 排量 + CO₂排放 | 年度缴纳 | 2024-01-01 | [Kfz-Steuer法](https://www.bundesfinanzministerium.de/Web/DE/Service/Apps_Rechner/KfzRechner/KfzRechner.html) | Kfz-Steuer |
| BEV税收优惠 | 免税至2030年 | N/A | N/A | 2025-12-31前注册 | [KraftStG §3d](https://www.gesetze-im-internet.de/kraftstg/) | Steuerbefreiung |

## C) 进口到上牌价格瀑布（CIF→OTR Price Waterfall）

### CBU ICE案例：1.5L汽油车，130g CO₂/km，CIF: CNY 140,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 18,182 | 140,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/eurofxref-graph-cny.en.html) |
| 关税 | 18,182 | 10% | 18,182 × 0.10 | 1,818 | 14,000 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| 小计 | 20,000 | - | 18,182 + 1,818 | 20,000 | 154,000 | 同上 | - |
| 增值税 | 20,000 | 19% | 20,000 × 0.19 | 3,800 | 29,260 | 同上 | [BMF](https://www.bundesfinanzministerium.de) |
| **OTR总价** | - | - | - | **23,800** | **183,260** | - | - |
| 年度车辆税 | - | - | (1500/100)×2 + (130-95)×2 | 100 | 770 | 同上 | [Kfz计算器](https://www.bundesfinanzministerium.de/Web/DE/Service/Apps_Rechner/KfzRechner/KfzRechner.html) |

### CBU BEV案例：60kWh电池，CIF: CNY 196,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 25,455 | 196,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 25,455 | 10% | 25,455 × 0.10 | 2,545 | 19,600 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| 小计 | 28,000 | - | 25,455 + 2,545 | 28,000 | 215,600 | 同上 | - |
| 增值税 | 28,000 | 19% | 28,000 × 0.19 | 5,320 | 40,964 | 同上 | [BMF](https://www.bundesfinanzministerium.de) |
| **OTR总价** | - | - | - | **33,320** | **256,564** | - | - |
| 年度车辆税 | - | - | 2025年注册：免税至2030年 | 0 | 0 | - | [KraftStG](https://www.gesetze-im-internet.de/kraftstg/) |

## D) EV/HEV/PHEV 专项政策卡

| 政策类型 | 资格条件 | 金额/减免 | 上限/配额 | 有效期/日落 | 主管部门 | 链接 |
|----------|----------|-----------|-----------|-------------|----------|------|
| BEV车辆税免税 | 2025-12-31前注册 | 100%免税 | 无上限 | 至2030-12-31 | BMF | [KraftStG §3d](https://www.gesetze-im-internet.de/kraftstg/) |
| 公司车BIK优惠 | BEV价格≤€95,000 | 0.25%月率 | €95,000 | 延长至2030 | BMF | [EStG §8](https://www.gesetze-im-internet.de/estg/) |
| PHEV BIK优惠 | 电动续航≥80km或CO₂≤50g/km | 0.5%月率 | 无 | 2025-12-31 | BMF | [EStG §8](https://www.gesetze-im-internet.de/estg/) |
| 特别折旧 | 商用电动车 | 首年40% | 无 | 2024-07至2028-12 | BMF | [AfA表](https://www.bundesfinanzministerium.de) |
| Umweltbonus | N/A | 已终止 | - | 2023-12-17终止 | BAFA | [BAFA公告](https://www.bafa.de) |

## E) 合规与操作要点

### 报关单证要求
- **原产地证明（Certificate of Origin）**: EU内贸易需Movement Certificate EUR.1
- **车辆一致性证书（COC）**: 必须符合EU Type Approval
- **发票**: 需包含VIN、HS Code、WLTP排放数据

### 型式批准
- Euro 6e-TEMP标准（2025年强制执行）
- WLTP测试程序取代NEDC
- RDE (Real Driving Emissions)合规性测试

### 地方性差异
- 各州（Bundesland）注册费用略有差异：€20-80
- 环保贴纸（Umweltplakette）: €6-20（进入低排放区必需）
- H牌照（30年以上经典车）: 固定年税€191.73

## F) 风险与变更监测

| 时间线 | 变更事项 | 状态 | 影响评估 | 来源 |
|--------|----------|------|----------|------|
| 2024-01-01 | Umweltbonus终止 | 已实施 | BEV购置成本增加€4,500-6,000 | [BAFA](https://www.bafa.de) |
| 2025-01-01 | 公司车BEV门槛提高至€95,000 | 已实施 | 扩大优惠覆盖范围 | [BMF公告](https://www.bundesfinanzministerium.de) |
| 2025-12-31 | 低排放车辆优惠（€30/年）终止 | 待实施 | 小幅增加持有成本 | [KraftStG](https://www.gesetze-im-internet.de/kraftstg/) |
| 2026-01-01 | 新注册BEV立即征收50%车辆税 | 立法中 | BEV年税约€100-200 | [联邦议会草案](https://www.bundestag.de) |
| 2030-12-31 | 2025年前注册BEV免税期结束 | 已确定 | 转为50%征收 | [KraftStG §3d](https://www.gesetze-im-internet.de/kraftstg/) |

## G) 信息来源清单

| 来源标题(英文原名) | 机构/部门 | 年份 | URL | 访问日期 | 语言 | 适用范围 |
|-------------------|-----------|------|-----|----------|------|----------|
| Kraftfahrzeugsteuergesetz (KraftStG) | Bundesgesetzblatt | 2024 | [Link](https://www.gesetze-im-internet.de/kraftstg/) | 2025-01-23 | DE | 车辆税法 |
| EU TARIC Database | European Commission | 2025 | [Link](https://taxation-customs.ec.europa.eu) | 2025-01-23 | EN | 关税税率 |
| Kfz-Steuer-Rechner | BMF | 2025 | [Link](https://www.bundesfinanzministerium.de/Web/DE/Service/Apps_Rechner/KfzRechner/KfzRechner.html) | 2025-01-23 | DE | 税额计算 |
| BAFA Elektromobilität | BAFA | 2024 | [Link](https://www.bafa.de) | 2025-01-23 | DE | 补贴政策 |
| ECB Exchange Rates | ECB | 2025 | [Link](https://www.ecb.europa.eu) | 2025-01-23 | EN | 汇率数据 |
| Zoll Import Guide | German Customs | 2025 | [Link](https://www.zoll.de) | 2025-01-23 | DE/EN | 进口程序 |

## 敏感性分析

### CIF价格±10%影响（ICE案例）
- CIF -10% (€16,364): OTR = €21,420 (-10%)
- CIF +10% (€20,000): OTR = €26,180 (+10%)

### 汇率EUR/CNY ±5%影响
- EUR/CNY -5% (7.32): CNY计价OTR降低5%
- EUR/CNY +5% (8.09): CNY计价OTR增加5%

## 合规声明

本材料仅为一般信息与计算示例，不构成法律或税务建议。实际税负可能因个案情况、政策更新或地方规定而异。建议在实际操作前咨询专业税务顾问或相关政府部门。

---
*最后更新：2025-01-23 UTC*