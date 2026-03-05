# Scaling Playbook

> Scaling is not just increasing budget. Done wrong, it raises CPA and wastes money. Done right, it grows volume while maintaining efficiency. This playbook covers the mechanics and sequence of each scaling method.

---

## Prerequisites Before Scaling

Never scale until these are in place:

- [ ] Out of learning phase (50+ conversions / 7 days for Meta)
- [ ] Conversion tracking verified (test conversions firing accurately)
- [ ] ROAS or CPA has been stable for 5+ consecutive days
- [ ] You know which specific campaign/ad set is the winner (not just "the account is doing well")
- [ ] You have replacement creative ready (scaling burns through creative faster)
- [ ] Attribution is reliable (UTMs set, GA4 aligned with platform data)

---

## The Three Scaling Methods

### 1. Vertical Scaling (Budget Increases)

**What it is:** Increase the budget on a winning campaign or ad set.

**Rules:**
- Maximum 20–30% increase per move
- Wait minimum 3–5 days between increases (let the algorithm re-learn)
- Never double or triple budget in one step — this resets learning on Meta
- Works best with CBO (Campaign Budget Optimization) on Meta

**Step-by-step:**
```
Day 1:   $100/day → $125/day (+25%)
Day 5:   $125/day → $155/day (+25%) — if CPA still on target
Day 10:  $155/day → $195/day (+25%) — if CPA still on target
Day 15:  $195/day → $245/day (+25%) — if CPA still on target
```

**Warning signs while scaling vertically:**
- CPA rising more than 15% after a budget increase → hold for 3 more days before next increase
- CPA rising more than 30% → pause increase, investigate (audience saturation? creative fatigue?)
- Delivery dropping despite higher budget → audience too narrow for the budget level

**Budget ceiling per ad set / audience:**
An audience can typically absorb ~$1 CPM per 1,000 people per day efficiently. A 1M person audience maxes out at ~$1,000/day before you start paying significantly more per impression.

---

### 2. Horizontal Scaling (Audience Expansion)

**What it is:** Duplicate the winning ad set into new audiences while keeping the same creative.

**When to use:**
- Vertical scaling is hitting CPA inefficiency
- Frequency is rising (> 2.5 on Meta) despite budget being stable
- You want to reach entirely new people, not just more of the same audience

**Horizontal scaling approaches:**

**A. Lookalike Expansion**
```
Start: 1% LAL of best customers (seed: purchasers/subscribers)
→ Expand to 2% LAL
→ Expand to 3–5% LAL
→ Stack: 1–3% LAL (combined)
```
*Never stack lookalikes with interest targeting — dilutes the signal*

**B. Interest Stack Expansion**
```
Current: [Interest A] (proven winner)
→ Duplicate with [Interest B] (similar audience, different interests)
→ Duplicate with [Interest C]
→ Test broad audience (no interest targeting — let algorithm find people)
```

**C. Geographic Expansion**
```
Current: [City A] performing well
→ Duplicate to [City B] with similar demographics
→ Duplicate to national
```

**D. Demographic Expansion**
```
Current: 25–44, Women
→ Duplicate to 25–44, Men (if product is gender-neutral)
→ Duplicate to 45–54, Women (if LTV data suggests they convert)
```

**Horizontal scaling rules:**
- Always duplicate — don't edit the original winning ad set
- Give new ad sets 7–10 days before judging performance
- Keep ad sets separate for clean data (don't merge audiences)
- Start new ad sets at the same budget as the original winner, not lower

---

### 3. CBO Scaling (Campaign Budget Optimization)

**What it is:** Let Meta/TikTok allocate budget across ad sets based on real-time performance signals.

**When to switch to CBO:**
- You have 3+ proven ad sets with consistent CPA
- You want Meta's algorithm to dynamically shift budget to best-performing ad sets
- You're at $200+/day where manual ABO becomes hard to manage

**CBO setup:**
```
Campaign Budget: [Total budget you'd allocate manually]
Ad Sets: [3–6 proven performers, same creative or tested creative]
Min/Max spend per ad set: Optional — set minimums to ensure test ad sets get data
```

**CBO scaling:**
- Increase CBO campaign budget 20–30% at a time (same rule as ABO)
- Add new ad sets to test within existing CBO (give them a minimum daily spend)
- Remove underperformers from CBO rather than lowering their budget to zero (zero budget ≠ paused)

**CBO traps to avoid:**
- Don't mix very different audience sizes in one CBO — Meta will dump all budget on the broadest audience
- Don't put testing ad sets and proven ad sets in the same CBO without spend minimums
- Don't use CBO when each ad set needs controlled budget allocation for structured testing

---

## Scaling Sequence: From $0 to $10K/Day

**Stage 1: Proof of Concept ($0–$100/day)**
- 1 campaign, 1–3 ad sets, 3–5 ads per ad set
- Goal: Find 1 winning creative + 1 winning audience
- ABO (manual budgets), equal allocation per ad set
- Duration: 2–4 weeks minimum

**Stage 2: Stabilize ($100–500/day)**
- Kill losing ad sets, double-down on winners
- Vertical scale winner by 20–25% every 5 days
- Begin 1–2 horizontal duplicates of the winning ad set
- Keep 20% budget in new creative testing
- Duration: 4–6 weeks

**Stage 3: Expand ($500–2K/day)**
- Convert top campaigns to CBO
- Add lookalike tiers (1%, then 2%, then 3–5%)
- Launch retargeting campaigns with converted traffic
- Add new creative angles informed by winner data
- Duration: ongoing

**Stage 4: Scale ($2K–10K/day)**
- Multiple CBO campaigns by funnel stage (cold/warm/hot)
- Dedicated creative testing budget (10–15% of total spend)
- Automated rules for budget management
- Weekly creative refreshes before fatigue hits
- Expand to new ad formats (Reels, Stories, Advantage+)

---

## Scaling on Google Ads

### Smart Bidding Scaling
- Target CPA / Target ROAS requires 50+ conversions/month to function
- Once you have data: set tROAS 10–15% above actual ROAS to give room for algorithm
- Increase budgets 20–30% at a time, same principle as Meta

### Search Campaign Scaling
1. **Expand keyword match types**: Exact → Phrase → Broad (with careful negative keyword management)
2. **Expand to new keyword themes**: Adjacent problem keywords, competitor keywords, solution keywords
3. **Add new ad groups** for each new keyword theme (don't dilute Quality Score by mixing themes)
4. **Increase bids** on top-converting keywords to capture more impression share

### Performance Max Scaling
- PMax scales when given broad signals — expand asset groups, add more creative variations
- Ensure conversion tracking is accurate before scaling (PMax is blind without good data)
- Use audience signals (customer lists, similar segments) to bias toward high-value audiences

---

## When to Stop Scaling

Stop or pause scaling if you see:

| Signal | Action |
|--------|--------|
| CPA rises > 30% after budget increase | Hold for 5 days, don't increase further |
| Frequency > 3.5 (Meta) | Horizontal scale to new audiences or rotate creative |
| ROAS drops below 1.0 | Scale down, investigate root cause |
| Delivery < 70% of budget | Audience is too narrow for the budget level — expand audience or reduce budget |
| New customer % falling | You're retargeting the same people — expand cold audience reach |
| Conversion volume declining despite stable spend | Audience saturation — need fresh audiences |

---

## Scaling Mistakes to Avoid

**Doubling the budget overnight**: Resets Meta's learning phase, almost always spikes CPA temporarily.

**Scaling creative that isn't working**: Scaling amplifies problems, not just results. Only scale proven winners.

**Ignoring the post-click side**: If landing page CVR is 1%, scaling spend just means scaling waste. Fix post-click first.

**Scaling too many things at once**: If you increase budget AND add new audiences AND change creative at the same time, you won't know what caused any change in performance.

**Treating scale as a one-time event**: Scaling is ongoing. You need to keep adding fresh creative, expanding audiences, and monitoring efficiency as you grow.

**Scaling before retargeting is set up**: Every dollar you spend building awareness without a retargeting system is partly wasted — you can't recapture the warm traffic.
