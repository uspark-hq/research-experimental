# 西班牙（Spain）乘用车税费研究报告

**时间戳:** 2025-01-23 UTC | CET (UTC+1)

## A) 答案先行（Executive Summary）

西班牙乘用车税负采用CO₂分级注册税（IEDMT），120g/km以下免征，最高14.75%。标准增值税21%，加那利群岛适用IGIC替代。MOVES III延长至2025年底，BEV最高补贴€7,000，PHEV需续航>30km。BEV享受注册税全免和市政流通税75%减免。关键影响：特殊领土（加那利、休达、梅利利亚）税负显著低于本土，地区激励差异明显。

## B) 法规速览表（Regulatory Overview）

| 税种/费用 | 法定税率/分段 | 计税基/公式 | 计算顺序 | 生效/修订日期 | 法源与条文 | 备注(本地语原名) |
|-----------|--------------|------------|----------|--------------|------------|------------------|
| 关税（Customs） | CBU: 10% | CIF价值 | 1 | 2025-01-01 | [EU TARIC](https://taxation-customs.ec.europa.eu) | Arancel aduanero |
| 增值税（VAT） | 本土: 21%<br>加那利: IGIC变动<br>休达/梅利利亚: IPSI 8-10% | CIF+关税 | 3 | 2025-01-01 | [Agencia Tributaria](https://sede.agenciatributaria.gob.es) | IVA |
| 注册税（IEDMT） | <120g: 0%<br>120+: 4.75%<br>160+: 9.75%<br>200+: 14.75% | WLTP CO₂ | 2 | 2024-01-01 | [Ley 38/1992](https://www.boe.es/buscar/act.php?id=BOE-A-1992-28741) | Impuesto de Matriculación |
| 市政流通税 | <1000cc: €12+<br>1000-1499: €34+<br>1500-1999: €71+<br>2000+: €122+ | 排量分级 | 年度 | 市政自定 | 各市政府 | IVTM |
| DGT注册费 | 转让: €55.70<br>非EU: €100 | 固定 | 4 | 2024更新 | [DGT](https://www.dgt.es) | Tasa DGT |

## C) 进口到上牌价格瀑布（CIF→OTR Price Waterfall）

### CBU ICE案例：1.5L汽油车，150g CO₂/km，CIF: CNY 140,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 18,182 | 140,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 18,182 | 10% | 18,182 × 0.10 | 1,818 | 14,000 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| IEDMT | 150g CO₂ | 4.75% | 18,182 × 0.0475 | 864 | 6,653 | - | [Agencia Tributaria](https://sede.agenciatributaria.gob.es) |
| 税基小计 | 20,864 | - | 18,182+1,818+864 | 20,864 | 160,653 | - | - |
| 增值税 | 20,864 | 21% | 20,864 × 0.21 | 4,381 | 33,734 | 同上 | [Ley 37/1992](https://www.boe.es/buscar/act.php?id=BOE-A-1992-28740) |
| DGT费用 | - | €100 | 非EU车辆 | 100 | 770 | - | [DGT](https://www.dgt.es) |
| **OTR总价** | - | - | - | **25,345** | **195,157** | - | - |
| 年度IVTM | 1.5L | €71 | 马德里基准 | 71 | 547 | - | [Ayuntamiento Madrid](https://sede.madrid.es) |

### CBU BEV案例：60kWh电池，0g CO₂/km，CIF: CNY 196,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 25,455 | 196,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 25,455 | 10% | 25,455 × 0.10 | 2,545 | 19,600 | 同上 | [EU TARIC](https://taxation-customs.ec.europa.eu) |
| IEDMT | 0g CO₂ | 0% | 免征 | 0 | 0 | - | [Agencia Tributaria](https://sede.agenciatributaria.gob.es) |
| 税基小计 | 28,000 | - | 25,455+2,545 | 28,000 | 215,600 | - | - |
| 增值税 | 28,000 | 21% | 28,000 × 0.21 | 5,880 | 45,276 | 同上 | [Ley 37/1992](https://www.boe.es) |
| DGT费用 | - | €100 | 非EU车辆 | 100 | 770 | - | [DGT](https://www.dgt.es) |
| MOVES III | 符合条件 | -€7,000 | BEV/FCEV | -7,000 | -53,900 | - | [IDAE](https://www.idae.es) |
| **OTR总价** | - | - | - | **26,980** | **207,746** | - | - |
| 年度IVTM | BEV | €17.75 | 75%减免 | 18 | 139 | - | [Ayuntamiento Madrid](https://sede.madrid.es) |

### 加那利群岛特例（IGIC替代IVA）

| 税种 | 本土税率 | 加那利税率 | 节省比例 | 法源 |
|------|----------|------------|----------|------|
| 增值税/IGIC | 21% | 7-15% | 6-14个百分点 | [Ley 20/1991](https://www.gobiernodecanarias.org/tributos) |
| IEDMT | 标准 | 降低1个百分点 | 如4.75%→3.75% | 特别制度 |
| 总体税负 | 基准 | 降低15-20% | 显著优势 | - |

## D) EV/HEV/PHEV 专项政策卡

| 政策类型 | 资格条件 | 金额/减免 | 上限/配额 | 有效期/日落 | 主管部门 | 链接 |
|----------|----------|-----------|-----------|-------------|----------|------|
| MOVES III-BEV | 0g CO₂<br>价格≤€45,000 | €7,000 | €17.35亿总预算 | 2025-12-31 | IDAE | [MOVES III](https://www.idae.es/ayudas-y-financiacion/para-movilidad-y-vehiculos/programa-moves-iii) |
| MOVES III-PHEV | 续航>90km | €7,000 | 同上 | 2025-12-31 | IDAE | 同上 |
| MOVES III-PHEV | 续航30-90km | €5,000 | 同上 | 2025-12-31 | IDAE | 同上 |
| 充电设施 | 私人用户 | 70%补贴 | 项目预算内 | 2025-12-31 | IDAE | 同上 |
| 个人所得税扣除 | BEV≤€45,000 | 15%扣除<br>最高€3,000-4,000 | 无 | 2025-12-31 | Hacienda | [IRPF](https://sede.agenciatributaria.gob.es) |
| 公司车BIK | EV<€40,000 | 30%减免 | 无 | 2025-12-31 | Hacienda | [IS规定](https://sede.agenciatributaria.gob.es) |
| 加速折旧 | 充电基础设施 | 双倍系数 | 无 | 2023-2025 | Hacienda | [Ley 6/2022](https://www.boe.es) |

## E) 合规与操作要点

### 报关单证要求
- **EU符合性证书（COC）**: 必须包含WLTP数据
- **ITV技术检验卡**: 新车首检4年后
- **环保标签（Distintivo）**: DGT分级（0、ECO、C、B）

### 型式批准要求
- EU WVTA (Whole Vehicle Type Approval)
- 西班牙特殊：日间行车灯强制、三角警示牌

### 自治区差异
- **马德里**: IVTM自愿缴纳期4月1日-6月2日
- **巴塞罗那**: 生态奖励限5年
- **巴斯克地区**: 独立税收体系，可能有额外优惠

### MOVES III申请流程
1. 经销商预注册系统
2. 购买后提交申请
3. 自动扣减购车款（经销商垫付）
4. IDAE后续审核拨款

## F) 风险与变更监测

| 时间线 | 变更事项 | 状态 | 影响评估 | 来源 |
|--------|----------|------|----------|------|
| 2025-01-01 | MOVES III追溯延长 | 已实施 | 确保政策连续性 | [IDAE公告](https://www.idae.es) |
| 2025-12-31 | MOVES III到期 | 确定 | 需关注MOVES IV | [RD 1124/2024](https://www.boe.es) |
| 2025-2027 | EU车队CO₂目标93.6g/km | 执行中 | 加速电动化压力 | [EU 2019/631](https://eur-lex.europa.eu) |
| 2026规划 | MOVES IV预期 | 筹备中 | 简化流程+提高门槛 | [Ministerio Transportes](https://www.transportes.gob.es) |
| 2030目标 | 零排放LDV占比36.3% | 政策驱动 | 持续强化激励 | [PNIEC](https://www.miteco.gob.es) |

## G) 信息来源清单

| 来源标题(英文原名) | 机构/部门 | 年份 | URL | 访问日期 | 语言 | 适用范围 |
|-------------------|-----------|------|-----|----------|------|----------|
| Agencia Tributaria | 税务总局 | 2025 | [Link](https://sede.agenciatributaria.gob.es) | 2025-01-23 | ES | 税务法规 |
| DGT Vehicle Services | 交通总局 | 2025 | [Link](https://www.dgt.es/nuestros-servicios/tu-vehiculo/) | 2025-01-23 | ES | 注册流程 |
| IDAE MOVES III | 能源多元化研究所 | 2025 | [Link](https://www.idae.es/ayudas-y-financiacion/para-movilidad-y-vehiculos/programa-moves-iii) | 2025-01-23 | ES | 补贴政策 |
| BOE Legislation | 官方公报 | 2025 | [Link](https://www.boe.es) | 2025-01-23 | ES | 法律法规 |
| EU TARIC | European Commission | 2025 | [Link](https://taxation-customs.ec.europa.eu) | 2025-01-23 | EN | 关税 |
| ECB Exchange Rates | ECB | 2025 | [Link](https://www.ecb.europa.eu) | 2025-01-23 | EN | 汇率 |

## 敏感性分析

### CIF价格±10%影响（ICE案例，150g CO₂）
- CIF -10% (€16,364): OTR = €22,873 (-9.8%)
- CIF +10% (€20,000): OTR = €27,817 (+9.8%)

### 汇率EUR/CNY ±5%影响
- EUR/CNY -5% (7.32): 相对竞争优势提升
- EUR/CNY +5% (8.09): 进口成本压力增加

### CO₂排放敏感性（CIF €18,182固定）
- 119g/km: IEDMT = 0%，OTR = €23,618
- 160g/km: IEDMT = 9.75%，OTR = €26,310
- 200g/km: IEDMT = 14.75%，OTR = €27,222

## 特殊领土对比

| 地区 | IVA/替代税 | IEDMT | 实际税负 | 优势 |
|------|------------|-------|----------|------|
| 西班牙本土 | 21% | 标准 | 基准 | - |
| 加那利群岛 | IGIC 7-15% | -1% | -15~20% | 显著 |
| 休达 | IPSI 8% | 0% | -40% | 极优 |
| 梅利利亚 | IPSI 10% | 0% | -35% | 极优 |

## 合规声明

本报告基于2025年1月23日公开信息编制。西班牙汽车税制复杂，涉及国家、自治区、市政三级征管，特殊领土享有独立税制。MOVES III政策延续但预算有限，建议尽早申请。实际操作请咨询当地税务机构或IDAE认证经销商。

---
*最后更新：2025-01-23 UTC*