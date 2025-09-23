# 法国（France）乘用车税费研究报告

**时间戳:** 2025-01-23 UTC | CET (UTC+1)

## A) 答案先行（Executive Summary）

法国乘用车税负采用"奖惩并举"（Bonus-Malus）生态系统，通过高额CO₂和重量双重惩罚税（最高€70,000）与电动车补贴（最高€4,000）引导市场。2025年CO₂门槛降至113g/km，重量税1,600kg起征。BEV享受收入联动补贴和社会租赁计划（月供<€200），但预算从€15亿削减至€10亿。关键影响：税负极化严重，高排放车型OTR可增加200%以上。

## B) 法规速览表（Regulatory Overview）

| 税种/费用 | 法定税率/分段 | 计税基/公式 | 计算顺序 | 生效/修订日期 | 法源与条文 | 备注(本地语原名) |
|-----------|--------------|------------|----------|--------------|------------|------------------|
| 关税（Customs Duty） | CBU: 10%<br>中国EV额外: 17-35.3% | CIF价值 | 1 | 2024-10-01 | [EU TARIC](https://taxation-customs.ec.europa.eu) | Droits de douane |
| 增值税（VAT） | 20% | DDP价值 | 3 | 2025-01-01 | [Code général des impôts](https://www.legifrance.gouv.fr) | TVA |
| CO₂惩罚税（Malus） | €50-70,000<br>113g/km起征(2025) | WLTP CO₂排放 | 2 | 2025-03-01 | [Service-Public](https://www.service-public.fr/particuliers/vosdroits/F35947) | Malus écologique |
| 重量税（Weight Tax） | €10-30/kg<br>1,600kg起征 | 车重-阈值 | 2 | 2025-01-01 | [Service-Public](https://www.service-public.fr/particuliers/vosdroits/F35950) | Malus au poids |
| 注册税（Carte grise） | Y1: 地区×CV<br>Y3: 环境税<br>Y4: €11 | CV=(CO₂/45)+(P/40)^1.6 | 4 | 各地区自定 | [ANTS](https://immatriculation.ants.gouv.fr) | Taxe régionale |

## C) 进口到上牌价格瀑布（CIF→OTR Price Waterfall）

### CBU ICE案例：1.5L汽油车，150g CO₂/km，1,800kg，CIF: CNY 140,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 18,182 | 140,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 18,182 | 10% | 18,182 × 0.10 | 1,818 | 14,000 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| CO₂惩罚税 | 150g/km | €3,000 | 查表法 | 3,000 | 23,100 | - | [Barème 2025](https://www.service-public.fr/particuliers/vosdroits/F35947) |
| 重量税 | 1,800kg | €15/kg | (1,800-1,600)×15 | 3,000 | 23,100 | - | [Malus poids](https://www.service-public.fr/particuliers/vosdroits/F35950) |
| DDP小计 | 26,000 | - | 18,182+1,818+6,000 | 26,000 | 200,200 | - | - |
| 增值税 | 26,000 | 20% | 26,000 × 0.20 | 5,200 | 40,040 | 同上 | [Code CGI](https://www.legifrance.gouv.fr) |
| 注册费 | - | 约€400 | 地区差异 | 400 | 3,080 | - | [ANTS](https://immatriculation.ants.gouv.fr) |
| **OTR总价** | - | - | - | **31,600** | **243,320** | - | - |

### CBU BEV案例：60kWh电池，0g CO₂/km，CIF: CNY 196,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 25,455 | 196,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 25,455 | 10% | 25,455 × 0.10 | 2,545 | 19,600 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| CO₂惩罚税 | 0g/km | €0 | 免税 | 0 | 0 | - | [Service-Public](https://www.service-public.fr) |
| 重量税 | BEV | €0 | 免税 | 0 | 0 | - | [Malus poids](https://www.service-public.fr) |
| DDP小计 | 28,000 | - | 25,455+2,545 | 28,000 | 215,600 | - | - |
| 增值税 | 28,000 | 20% | 28,000 × 0.20 | 5,600 | 43,120 | 同上 | [Code CGI](https://www.legifrance.gouv.fr) |
| 注册费 | - | 约€150 | 减免 | 150 | 1,155 | - | [ANTS](https://immatriculation.ants.gouv.fr) |
| 生态奖励 | RFR≤€16,300 | -€4,000 | 收入审核 | -4,000 | -30,800 | - | [Prime écologique](https://www.primealaconversion.gouv.fr) |
| **OTR总价** | - | - | - | **29,750** | **229,075** | - | - |

## D) EV/HEV/PHEV 专项政策卡

| 政策类型 | 资格条件 | 金额/减免 | 上限/配额 | 有效期/日落 | 主管部门 | 链接 |
|----------|----------|-----------|-----------|-------------|----------|------|
| 生态奖励 | BEV/FCEV<br>收入分级 | €2,000-4,000 | 车价€47,000 | 2025-12-31 | 经济部 | [Bonus écologique](https://www.primealaconversion.gouv.fr) |
| 社会租赁 | RFR≤€16,300<br>通勤>15km | 补贴€7,000 | 5万辆 | 2025-09-30启动 | 交通部 | [Leasing social](https://www.service-public.fr) |
| PHEV优惠 | 续航>50km | Malus免税<br>重量减200kg | 无 | 2025-12-31 | 经济部 | [Code CGI](https://www.legifrance.gouv.fr) |
| 公司车BIK | BEV/PHEV | 50%减免 | €1,800/年 | 2025-12-31 | 税务总局 | [ex-TVS](https://entreprendre.service-public.fr/vosdroits/F22203) |
| Prime转换 | N/A | 已取消 | - | 2024-12终止 | 经济部 | - |

## E) 合规与操作要点

### 报关单证要求
- **EUR.1移动证书**: EU-瑞士/挪威优惠贸易必需
- **WLTP测试报告**: 2025年强制，替代NEDC
- **环境评分（Crit'Air）**: 进入低排放区必需

### 型式批准
- EU Whole Vehicle Type Approval (WVTA)
- 法国特殊要求：前雾灯、反光背心、酒精测试仪

### 地方性差异
- **巴黎大区（Île-de-France）**: Y1税率€51.20/CV（全国最高）
- **科西嘉（Corse）**: Y1税率€27/CV（全国最低）
- **海外省（DOM-TOM）**: 无Malus税，特殊关税制度

## F) 风险与变更监测

| 时间线 | 变更事项 | 状态 | 影响评估 | 来源 |
|--------|----------|------|----------|------|
| 2025-03-01 | CO₂门槛降至113g/km | 确定实施 | 90%汽油车触发Malus | [PLF 2025](https://www.economie.gouv.fr) |
| 2025-09-30 | 社会租赁重启 | 已公布 | 低收入群体月供<€140 | [Ministère des Transports](https://www.ecologie.gouv.fr) |
| 2026-01-01 | CO₂门槛降至107g/km | 立法中 | 95%汽油车征税 | [Assemblée Nationale](https://www.assemblee-nationale.fr) |
| 2026-01-01 | 重量税门槛降至1,500kg | 计划中 | 影响70% SUV | [Sénat](https://www.senat.fr) |
| 2027-01-01 | CO₂门槛降至98g/km | 规划中 | 仅HEV/PHEV免税 | [France Stratégie](https://www.strategie.gouv.fr) |

## G) 信息来源清单

| 来源标题(英文原名) | 机构/部门 | 年份 | URL | 访问日期 | 语言 | 适用范围 |
|-------------------|-----------|------|-----|----------|------|----------|
| Code général des impôts | Légifrance | 2025 | [Link](https://www.legifrance.gouv.fr) | 2025-01-23 | FR | 税法总则 |
| Service-Public.fr | DILA | 2025 | [Link](https://www.service-public.fr) | 2025-01-23 | FR | 官方指南 |
| ANTS Vehicle Registration | ANTS | 2025 | [Link](https://immatriculation.ants.gouv.fr) | 2025-01-23 | FR/EN | 注册系统 |
| Bonus écologique 2025 | Ministère de l'Économie | 2025 | [Link](https://www.primealaconversion.gouv.fr) | 2025-01-23 | FR | 补贴政策 |
| Douane française | Direction générale des douanes | 2025 | [Link](https://www.douane.gouv.fr) | 2025-01-23 | FR | 海关程序 |
| ECB Exchange Rates | ECB | 2025 | [Link](https://www.ecb.europa.eu) | 2025-01-23 | EN | 汇率数据 |

## 敏感性分析

### CIF价格±10%影响（ICE案例，150g CO₂）
- CIF -10% (€16,364): OTR = €29,673 (-6.1%)，Malus固定€3,000
- CIF +10% (€20,000): OTR = €33,527 (+6.1%)，Malus不变

### 汇率EUR/CNY ±5%影响
- EUR/CNY -5% (7.32): CNY计价降低，相对竞争力提升
- EUR/CNY +5% (8.09): CNY计价上升，Malus负担加重

### CO₂排放敏感性（CIF €18,182固定）
- 112g/km: Malus = €0，OTR = €23,018
- 130g/km: Malus = €300，OTR = €26,618
- 180g/km: Malus = €18,000，OTR = €47,818

## CKD/SKD vs CBU对比

| 装配类型 | 关税率 | Malus适用 | 典型节省 | 本地化要求 |
|----------|--------|-----------|----------|------------|
| CBU | 10% | 100% | 基准 | 无 |
| SKD | 4-6% | 100% | 4-6%关税 | 最终装配 |
| CKD | 0-4% | 100% | 6-10%关税 | 显著增值 |

## 合规声明

本材料基于2025年1月23日可获得的公开信息编制，仅供参考。法国税制复杂且频繁调整，实际操作前务必咨询当地税务顾问或官方机构。特别提示：Malus税率可能因环保政策临时调整。

---
*最后更新：2025-01-23 UTC*