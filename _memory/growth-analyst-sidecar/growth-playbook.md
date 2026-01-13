# Growth Playbook

> Base de connaissances pour Pixel Metrics.
> Benchmarks SaaS, formules, templates dashboards, et best practices.

---

## Benchmarks SaaS par Stade

### Pre-PMF (0-$10K MRR)

| Métrique | Acceptable | Bon | Excellent |
|----------|------------|-----|-----------|
| Monthly Churn | <15% | <10% | <7% |
| Activation Rate | >20% | >30% | >40% |
| NPS | >0 | >20 | >40 |
| Time to Value | <7 jours | <3 jours | <1 jour |
| DAU/MAU | >10% | >15% | >20% |

**North Star Focus:** Product-Market Fit signals (retention, engagement)
**KPIs Secondaires:** Activation rate, Time to value, User feedback score

### PMF ($10K-$100K MRR)

| Métrique | Acceptable | Bon | Excellent |
|----------|------------|-----|-----------|
| Monthly Churn | <8% | <5% | <3% |
| Net Revenue Retention | >90% | >100% | >110% |
| CAC Payback | <18 mois | <12 mois | <6 mois |
| LTV/CAC | >2x | >3x | >5x |
| Activation Rate | >30% | >40% | >50% |

**North Star Focus:** Revenue growth + retention balance
**KPIs Secondaires:** MRR growth, Expansion revenue, Churn cohorts

### Scale ($100K+ MRR)

| Métrique | Acceptable | Bon | Excellent |
|----------|------------|-----|-----------|
| Annual Churn | <10% | <7% | <5% |
| Net Revenue Retention | >100% | >110% | >120% |
| CAC Payback | <12 mois | <9 mois | <6 mois |
| LTV/CAC | >3x | >4x | >6x |
| Rule of 40 | >30% | >40% | >50% |

**North Star Focus:** Efficient growth (Rule of 40)
**KPIs Secondaires:** NRR, CAC efficiency, Channel mix

---

## Formules Essentielles

### Revenue Metrics

```
MRR = Σ (Monthly recurring revenue from all customers)

ARR = MRR × 12

Net MRR Change = New MRR + Expansion MRR - Churned MRR - Contraction MRR

MRR Growth Rate = (MRR_current - MRR_previous) / MRR_previous × 100
```

### Retention Metrics

```
Monthly Churn Rate = (Customers lost this month / Customers at start of month) × 100

Revenue Churn = (MRR lost this month / MRR at start of month) × 100

Net Revenue Retention (NRR) = ((MRR_start + Expansion - Contraction - Churn) / MRR_start) × 100

Gross Revenue Retention (GRR) = ((MRR_start - Contraction - Churn) / MRR_start) × 100
```

### Unit Economics

```
Customer Acquisition Cost (CAC) = Total Sales & Marketing Spend / New Customers Acquired

Lifetime Value (LTV) = ARPU × Gross Margin % × (1 / Monthly Churn Rate)

LTV/CAC Ratio = LTV / CAC

CAC Payback (months) = CAC / (ARPU × Gross Margin %)

Magic Number = (QoQ ARR Growth) / (Previous Quarter S&M Spend)
```

### Engagement Metrics

```
DAU/MAU = Daily Active Users / Monthly Active Users

Activation Rate = Users who complete key action / Total signups × 100

Feature Adoption = Users using feature / Total active users × 100

Time to Value = Median time from signup to first value moment
```

### Growth Metrics

```
Rule of 40 = Revenue Growth Rate % + Profit Margin %

Quick Ratio = (New MRR + Expansion MRR) / (Churned MRR + Contraction MRR)

Burn Multiple = Net Burn / Net New ARR
```

---

## Funnel Benchmarks (B2B SaaS)

### Top of Funnel

| Étape | Benchmark Médian | Top Quartile |
|-------|------------------|--------------|
| Visitor → Lead | 2-3% | 5%+ |
| Lead → MQL | 30-40% | 50%+ |
| MQL → SQL | 40-50% | 60%+ |

### Bottom of Funnel

| Étape | Benchmark Médian | Top Quartile |
|-------|------------------|--------------|
| SQL → Opportunity | 50-60% | 70%+ |
| Opportunity → Close | 20-30% | 40%+ |
| Trial → Paid | 15-25% | 30%+ |
| Freemium → Paid | 2-5% | 8%+ |

### PLG Specific

| Étape | Benchmark Médian | Top Quartile |
|-------|------------------|--------------|
| Signup → Activation | 20-30% | 40%+ |
| Activation → Paid | 5-10% | 15%+ |
| Free → Team Plan | 10-15% | 25%+ |

---

## Templates Dashboard

### Weekly Growth Dashboard

```
═══════════════════════════════════════════════
WEEKLY GROWTH REPORT — Week of [DATE]
═══════════════════════════════════════════════

📊 NORTH STAR
┌─────────────────────────────────────────────┐
│ [Metric Name]: [Value]                      │
│ WoW: [+/-X%] | vs Target: [+/-X%]          │
└─────────────────────────────────────────────┘

💰 REVENUE
┌─────────────┬─────────┬─────────┬──────────┐
│ Metric      │ This Wk │ Last Wk │ WoW      │
├─────────────┼─────────┼─────────┼──────────┤
│ MRR         │ $XXX    │ $XXX    │ +X%      │
│ New MRR     │ $XXX    │ $XXX    │ +X%      │
│ Expansion   │ $XXX    │ $XXX    │ +X%      │
│ Churn       │ $XXX    │ $XXX    │ -X%      │
└─────────────┴─────────┴─────────┴──────────┘

🎯 FUNNEL
┌─────────────┬─────────┬─────────┬──────────┐
│ Stage       │ Volume  │ Conv %  │ vs Bench │
├─────────────┼─────────┼─────────┼──────────┤
│ Visitors    │ XXX     │ -       │ -        │
│ Signups     │ XXX     │ X%      │ +/-X%    │
│ Activated   │ XXX     │ X%      │ +/-X%    │
│ Paid        │ XXX     │ X%      │ +/-X%    │
└─────────────┴─────────┴─────────┴──────────┘

🔬 EXPERIMENTS IN FLIGHT
• [Test name]: Day X/Y, [current result]
• [Test name]: Day X/Y, [current result]

⚠️ ALERTS
• [Issue requiring attention]

✅ ACTIONS THIS WEEK
1. [Action item]
2. [Action item]
```

### Monthly Cohort Analysis

```
COHORT RETENTION (% of users still active)
═══════════════════════════════════════════════

         M0    M1    M2    M3    M4    M5    M6
Jan     100%   45%   38%   35%   33%   32%   31%
Feb     100%   48%   40%   36%   34%   33%   -
Mar     100%   50%   42%   38%   35%   -     -
Apr     100%   52%   44%   40%   -     -     -
May     100%   55%   46%   -     -     -     -
Jun     100%   58%   -     -     -     -     -
Jul     100%   -     -     -     -     -     -

Trend: ▲ Improving (M1 retention +13pp vs 6 months ago)
```

---

## A/B Testing Guidelines

### Sample Size Calculator

```
Baseline Conversion Rate: X%
Minimum Detectable Effect: Y%
Statistical Significance: 95%
Statistical Power: 80%

Required Sample Size per Variant:
n = 16 × p × (1-p) / (MDE)²

Where:
- p = baseline conversion rate
- MDE = minimum detectable effect (absolute)
```

### Test Duration Rules

| Traffic Level | Min Duration | Recommendation |
|---------------|--------------|----------------|
| <1K visitors/week | 4+ weeks | Consider qualitative instead |
| 1K-10K/week | 2-4 weeks | Standard testing |
| 10K+/week | 1-2 weeks | Can iterate faster |

**Always:** Run for at least 1 full business cycle (usually 1 week minimum)

### Statistical Significance Interpretation

| Confidence | Interpretation | Action |
|------------|----------------|--------|
| <90% | Not significant | Do not ship, continue test |
| 90-95% | Marginally significant | Ship if low risk, consider extending |
| 95-99% | Significant | Ship with confidence |
| >99% | Highly significant | Ship immediately |

---

## Analytics Stack Recommendations

### Pre-PMF (Keep it simple)

| Function | Tool | Why |
|----------|------|-----|
| Product Analytics | Mixpanel Free / Amplitude Free | Event tracking, funnels |
| Web Analytics | Plausible / Fathom | Privacy-friendly, simple |
| Session Recording | Hotjar Free | Understand user behavior |
| Dashboards | Google Sheets | Free, flexible |

### PMF (Add depth)

| Function | Tool | Why |
|----------|------|-----|
| Product Analytics | Mixpanel / Amplitude | Full feature set |
| Revenue Analytics | ProfitWell / ChartMogul | Subscription metrics |
| BI Layer | Metabase / Mode | Custom queries |
| CDP | Segment | Data unification |

### Scale (Enterprise grade)

| Function | Tool | Why |
|----------|------|-----|
| Data Warehouse | Snowflake / BigQuery | Central source of truth |
| ETL | Fivetran / Airbyte | Automated pipelines |
| BI | Looker / Tableau | Advanced visualization |
| Experimentation | Statsig / Eppo | Rigorous A/B testing |

---

## Red Flags & Warning Signs

### Revenue Red Flags
- MRR growth declining 3+ months in a row
- Churn increasing while acquisition stays flat
- Expansion revenue < 20% of new revenue
- CAC increasing without LTV improvement

### Engagement Red Flags
- DAU/MAU declining steadily
- Time to value increasing
- Feature adoption flat despite launches
- Support tickets/user increasing

### Funnel Red Flags
- Top of funnel shrinking while costs stable
- Conversion rates declining across stages
- Sales cycle lengthening
- Win rate dropping

### Data Quality Red Flags
- >10% of events with null critical properties
- Significant discrepancies between tools
- Tracking gaps in key user journeys
- No documentation of event taxonomy
