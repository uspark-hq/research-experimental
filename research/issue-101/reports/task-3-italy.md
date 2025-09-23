# 意大利（Italy）乘用车税费研究报告

**时间戳:** 2025-01-23 UTC | CET (UTC+1)

## A) 答案先行（Executive Summary）

意大利乘用车税负以22%增值税（IVA）为主体，配合省级转录税（IPT）和豪车附加税（Superbollo）。2024年Ecobonus预算€9.5亿，BEV最高补贴€11,000（含报废），但2025年国家级激励已终止，仅剩地方补贴。BEV享受5年免征流通税（Bollo），之后减征75%。关键影响：从中央激励转向地方差异化政策，北部地区（南蒂罗尔、瓦莱达奥斯塔）维持高额补贴。

## B) 法规速览表（Regulatory Overview）

| 税种/费用 | 法定税率/分段 | 计税基/公式 | 计算顺序 | 生效/修订日期 | 法源与条文 | 备注(本地语原名) |
|-----------|--------------|------------|----------|--------------|------------|------------------|
| 关税（Customs） | CBU: 10%<br>中国EV: +20.7-35.3% | CIF价值 | 1 | 2024-10-01 | [EU TARIC](https://taxation-customs.ec.europa.eu) | Dazio doganale |
| 增值税（VAT） | 22% | CIF + 关税 | 2 | 2025-01-01 | [Agenzia Entrate](https://www.agenziaentrate.gov.it) | IVA |
| 省转录税（IPT） | 各省自定<br>BEV常减免 | 功率/排量 | 3 | 省级调整 | [ACI](https://www.aci.it) | Imposta Provinciale di Trascrizione |
| 印花税 | €32-48 | 固定 | 4 | 2024-01-01 | [Bollo Auto](https://www.aci.it/i-servizi/guide-utili/guida-al-bollo-auto.html) | Imposta di bollo |
| 豪车税 | €20/kW | >185kW部分 | 年度 | 2011起 | [L.214/2011](https://www.gazzettaufficiale.it) | Superbollo |
| 流通税 | 按kW分段 | 前100kW基准费率 | 年度 | 地区自定 | 各大区法规 | Bollo auto |

## C) 进口到上牌价格瀑布（CIF→OTR Price Waterfall）

### CBU ICE案例：1.5L汽油车，110kW，CIF: CNY 140,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 18,182 | 140,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 18,182 | 10% | 18,182 × 0.10 | 1,818 | 14,000 | 同上 | [ADM](https://www.adm.gov.it) |
| 税基小计 | 20,000 | - | 18,182 + 1,818 | 20,000 | 154,000 | - | - |
| 增值税 | 20,000 | 22% | 20,000 × 0.22 | 4,400 | 33,880 | 同上 | [Agenzia Entrate](https://www.agenziaentrate.gov.it) |
| IPT | 110kW | €300(估) | 省级差异 | 300 | 2,310 | - | [ACI](https://www.aci.it) |
| 注册费 | - | €400(估) | 含印花税等 | 400 | 3,080 | - | [PRA](https://www.aci.it/i-servizi/servizi-online/pra.html) |
| **OTR总价** | - | - | - | **25,100** | **193,270** | - | - |
| 年度流通税 | 110kW | €250(估) | 地区差异 | 250 | 1,925 | - | 各大区 |

### CBU BEV案例：60kWh电池，150kW，CIF: CNY 196,000

| 步骤 | 基数(Base) | 税率/规则 | 计算式 | 金额(EUR) | 金额(CNY) | FX来源与日期 | 来源链接 |
|------|------------|----------|--------|-----------|-----------|--------------|----------|
| CIF价值 | - | - | - | 25,455 | 196,000 | ECB 2025-01-22: 1 EUR = 7.70 CNY | [ECB](https://www.ecb.europa.eu) |
| 关税 | 25,455 | 10% | 25,455 × 0.10 | 2,545 | 19,600 | 同上 | [ADM](https://www.adm.gov.it) |
| 税基小计 | 28,000 | - | 25,455 + 2,545 | 28,000 | 215,600 | - | - |
| 增值税 | 28,000 | 22% | 28,000 × 0.22 | 6,160 | 47,432 | 同上 | [Agenzia Entrate](https://www.agenziaentrate.gov.it) |
| IPT | BEV | €0-100 | 多省免征 | 50 | 385 | - | [ACI](https://www.aci.it) |
| 注册费 | - | €200(估) | BEV优惠 | 200 | 1,540 | - | [PRA](https://www.aci.it) |
| 2024激励 | 无报废 | -€6,000 | 若符合条件 | -6,000 | -46,200 | - | [Invitalia](https://ecobonus.mise.gov.it) |
| **OTR总价** | - | - | - | **28,410** | **218,757** | - | - |
| 年度流通税 | BEV | €0 | 5年免征 | 0 | 0 | - | 各大区 |

*注：2025年无国家级Ecobonus，上述€6,000激励仅为2024年参考*

## D) EV/HEV/PHEV 专项政策卡

| 政策类型 | 资格条件 | 金额/减免 | 上限/配额 | 有效期/日落 | 主管部门 | 链接 |
|----------|----------|-----------|-----------|-------------|----------|------|
| 2024 Ecobonus-BEV | 0-20g CO₂<br>价格≤€35,000+IVA | €6,000-11,000 | €2.4亿 | 2024-12-31止 | MIMIT/Invitalia | [Ecobonus](https://ecobonus.mise.gov.it) |
| 2024 Ecobonus-PHEV | 21-60g CO₂<br>价格≤€45,000+IVA | €4,000-8,000 | €1.5亿 | 2024-12-31止 | MIMIT/Invitalia | [Ecobonus](https://ecobonus.mise.gov.it) |
| 流通税免征 | BEV/FCEV | 5年100%<br>后续75%减免 | 无限制 | 永久政策 | 各大区 | [ACI Bollo](https://www.aci.it) |
| 南蒂罗尔补贴 | BEV<€60,000 | €2,000-4,000 | 地方预算 | 2025持续 | 博尔扎诺省 | [Provincia BZ](https://www.provincia.bz.it) |
| 瓦莱达奥斯塔 | BEV<€60,000 | €9,000-12,700 | 地方预算 | 2025持续 | Aosta大区 | [Regione VDA](https://www.regione.vda.it) |
| 公司车BIK | BEV/PHEV | 10%/20%应税 | 无 | 2025-12-31 | 财政部 | [MEF](https://www.mef.gov.it) |

## E) 合规与操作要点

### 报关单证要求
- **符合性证书（COC）**: 必须翻译为意大利语
- **WVTA型式认证**: EU Whole Vehicle Type Approval强制
- **原产地证明**: 享受FTA优惠必需

### 进口港口选择
- **利沃诺（Livorno）**: 汽车进口主港，高速直连内陆
- **热那亚（Genova）**: 最大港口，铁路网发达
- **巴勒莫（Palermo）**: 西西里直达，班次有限

### 地方性差异
- **伦巴第大区**: BEV流通税永久免征（5年后）
- **皮埃蒙特大区**: BEV流通税永久免征
- **拉齐奥大区**: 标准5年免征+75%减免

### ACI系统操作
- **PRA登记**: 购买后60天内完成"Passaggio di Proprietà"
- **在线缴费**: Bollonet系统支持在线支付Bollo
- **Superbollo计算器**: [ACI在线工具](https://www.aci.it/i-servizi/servizi-online/bollo-auto.html)

## F) 风险与变更监测

| 时间线 | 变更事项 | 状态 | 影响评估 | 来源 |
|--------|----------|------|----------|------|
| 2024-06-03 | Ecobonus启动 | 已耗尽 | BEV基金3天售罄 | [Invitalia](https://ecobonus.mise.gov.it) |
| 2025-01-01 | 国家激励终止 | 已确认 | OTR增加€6,000-11,000 | [MIMIT](https://www.mimit.gov.it) |
| 2025全年 | 地方激励持续 | 执行中 | 南北差异扩大 | 各大区 |
| 2025-01-01 | 公司车IVA扣除降至40% | 已实施 | 企业成本增加 | [Agenzia Entrate](https://www.agenziaentrate.gov.it) |
| 2026规划 | 新激励方案 | 讨论中 | 可能恢复中央补贴 | [Parlamento](https://www.parlamento.it) |

## G) 信息来源清单

| 来源标题(英文原名) | 机构/部门 | 年份 | URL | 访问日期 | 语言 | 适用范围 |
|-------------------|-----------|------|-----|----------|------|----------|
| Agenzia delle Entrate | 税务局 | 2025 | [Link](https://www.agenziaentrate.gov.it) | 2025-01-23 | IT | IVA/税务 |
| ACI Bollo Auto Guide | ACI | 2025 | [Link](https://www.aci.it/i-servizi/guide-utili/guida-al-bollo-auto.html) | 2025-01-23 | IT | 流通税 |
| Agenzia Dogane e Monopoli | ADM | 2025 | [Link](https://www.adm.gov.it) | 2025-01-23 | IT | 海关 |
| Ecobonus Platform | Invitalia | 2024 | [Link](https://ecobonus.mise.gov.it) | 2025-01-23 | IT | 激励政策 |
| EU TARIC Database | European Commission | 2025 | [Link](https://taxation-customs.ec.europa.eu) | 2025-01-23 | EN | 关税 |
| Gazzetta Ufficiale | 官方公报 | 2025 | [Link](https://www.gazzettaufficiale.it) | 2025-01-23 | IT | 法律法规 |

## 敏感性分析

### CIF价格±10%影响（ICE案例）
- CIF -10% (€16,364): OTR = €22,664 (-9.7%)
- CIF +10% (€20,000): OTR = €27,536 (+9.7%)

### 汇率EUR/CNY ±5%影响
- EUR/CNY -5% (7.32): 降低人民币计价成本
- EUR/CNY +5% (8.09): 增加人民币计价成本

### 功率对Superbollo影响（>185kW）
- 200kW: 额外€300/年 (15kW × €20)
- 250kW: 额外€1,300/年 (65kW × €20)
- 300kW: 额外€2,300/年 (115kW × €20)

## IPT省级差异示例

| 省份 | ICE费率 | BEV政策 | 特殊规定 |
|------|---------|----------|----------|
| 米兰（Milano） | 标准 | 全免 | - |
| 罗马（Roma） | 标准 | 减免50% | - |
| 那不勒斯（Napoli） | 降低20% | 全免 | 促进南部登记 |
| 博尔扎诺（Bolzano） | 标准 | 全免 | 额外地方补贴 |

## 合规声明

本报告基于2025年1月23日公开信息。意大利税制具有显著地区差异，2025年国家级激励已终止但地方政策延续。实际操作需咨询ACI地方办事处或专业顾问。特别提醒：进口认证程序复杂，建议预留充足时间。

---
*最后更新：2025-01-23 UTC*