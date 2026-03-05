# Diagnostic Trees

> Use when something is broken and you need to find the root cause before making changes. Follow the tree top-down, answering each question with data. Don't skip steps — the symptom rarely tells you the cause directly.

---

## Tree 1: CPA Is Too High

**Symptom**: Cost per acquisition is above target.

```
CPA too high
│
├── Did CPM increase?
│   ├── YES → Auction-level issue
│   │   ├── Is it seasonal? (holiday, Q4 surge, competitor spend spike)
│   │   │   ├── YES → Wait it out or adjust bids/budgets for the period
│   │   │   └── NO → Check audience size (too narrow?), bid strategy, or competition
│   │   └── Is frequency rising? (> 3.0)
│   │       ├── YES → Audience fatigue → rotate creative, expand to new audiences
│   │       └── NO → Investigate bid strategy and auction pressure
│   │
├── Did CTR decrease?
│   ├── YES → Creative is the problem
│   │   ├── Is it fatigue? (same creative running > 4 weeks, frequency > 2.5)
│   │   │   ├── YES → Pause creative, launch new variations
│   │   │   └── NO → Audience mismatch — wrong message for this audience
│   │   └── Did the ad angle change recently?
│   │       ├── YES → New angle isn't resonating — test another angle
│   │       └── NO → Investigate hook specifically (first 3 seconds)
│   │
├── Did landing page CVR decrease?
│   ├── YES → Post-click problem (not the ad)
│   │   ├── Did the landing page change?
│   │   │   ├── YES → Roll back or A/B test the change
│   │   │   └── NO → Audience quality may have changed (new audience seeing different intent)
│   │   ├── Is page load speed acceptable? (< 3 sec)
│   │   │   ├── NO → Fix page speed first
│   │   │   └── YES → Check offer alignment: does the ad match what's on the page?
│   │   └── Has traffic quality changed? (new audiences, broad targeting)
│   │       └── YES → New audiences have lower purchase intent — tighten targeting or adjust offer
│   │
└── None of the above changed — CPA rose without explanation
    ├── Check attribution window (did it change?)
    ├── Check if there's a tracking/pixel issue (conversions not firing)
    ├── Check if major competitor entered the market (auction insights)
    └── Check iOS/platform changes affecting attribution
```

**Priority order to check**: CVR → CTR → CPM → Frequency → Attribution

---

## Tree 2: ROAS Dropped Suddenly

**Symptom**: ROAS was acceptable last week, now it's significantly lower.

```
ROAS dropped suddenly
│
├── Did it happen account-wide or in one campaign?
│   ├── ACCOUNT-WIDE → External/platform issue
│   │   ├── Seasonality? (post-holiday slump, off-peak period)
│   │   ├── Attribution change? (iOS update, browser privacy changes)
│   │   ├── Competitor surge? (Q4, major competitor promotion)
│   │   └── Pixel/tracking issue? (test a conversion event)
│   │
│   └── ONE CAMPAIGN → Isolated issue
│       ├── Did budget change recently? (> 20% increase can spike CPA temporarily)
│       │   └── YES → Wait 5–7 days — may be temporary learning phase disruption
│       ├── Did creative change?
│       │   └── YES → New creative underperforming. Reactivate winner while testing new creative.
│       ├── Did audience change?
│       │   └── YES → New audience has different conversion rates. Monitor 7 days.
│       └── Did bid strategy change? (switched to auto-bidding)
│           └── YES → Auto-bidding needs 50+ conversions to calibrate. May take 2 weeks.
│
├── Is revenue down or just attributed revenue?
│   ├── Revenue down in reality → ROAS issue is real
│   └── Revenue stable in backend → Attribution problem, not performance problem
│       └── Fix tracking before making campaign changes
│
└── Is ROAS below 1.0? (spending more than earning)
    └── YES → Immediate action: pause low-ROAS ad sets, investigate root cause above
        Do NOT increase budget on a sub-1.0 ROAS campaign
```

---

## Tree 3: CTR Falling Off

**Symptom**: Click-through rate is declining over time.

```
CTR falling off
│
├── What is current frequency?
│   ├── > 3.0 → Almost certainly fatigue
│   │   └── ACTION: Rotate creative immediately. New angles, new hooks.
│   │       Don't change audience — it's a creative problem.
│   │
│   └── < 2.5 → Frequency is fine, something else changed
│       ├── Did the audience change? (new ad set, targeting edit)
│       │   └── YES → Different audience, different response. Adjust creative for this audience.
│       ├── Did the creative change?
│       │   └── YES → New creative isn't as strong. Reactivate old winner while testing.
│       └── Is there a platform-wide CTR decline? (check other campaigns for pattern)
│           └── YES → Seasonal effect or algorithm change. Not a campaign-specific problem.
│
├── Is CTR declining on all ads or just one?
│   ├── ALL ADS → Audience issue (saturated, wrong segment, seasonal)
│   └── ONE AD → That specific creative is fatiguing or was always weak
│       └── ACTION: Pause the specific ad, let other ads compete in the ad set
│
└── What is the absolute CTR level?
    ├── CTR still > 1.0% → May not need action — monitor for 3 more days
    └── CTR < 0.5% → Already in poor performance territory
        └── Immediate creative audit: hook, visual, copy, CTA
```

---

## Tree 4: CPM Spiked

**Symptom**: Cost per thousand impressions has increased significantly (> 30% in a week).

```
CPM spiked
│
├── Is it happening across all campaigns or one?
│   ├── ALL CAMPAIGNS → External factor
│   │   ├── Q4 / Holiday period? (CPMs spike Oct–Dec, especially Nov–Dec)
│   │   ├── Major news event drawing ad spend?
│   │   ├── New large competitor entered your target audience space?
│   │   └── Platform-wide change? (Check industry forums / Twitter for reports)
│   │
│   └── ONE CAMPAIGN → Campaign-specific issue
│       ├── Did audience size shrink? (exclusion applied, targeting narrowed)
│       │   └── YES → Smaller audience = higher CPM (fewer supply, same demand)
│       ├── Did you raise bids or switch to aggressive bid strategy?
│       │   └── YES → Bid strategy is overpaying for auctions. Lower target or cap bids.
│       └── Did relevance score / ad quality drop?
│           └── YES → Poor quality ads cost more. Improve creative relevance.
│
├── Is the CPM spike hurting CPA?
│   ├── YES → CPA has risen proportionally → investigate via Tree 1
│   └── NO → CTR also rose, offsetting the CPM increase → monitor, may not need action
│
└── Is CPM still within acceptable range?
    ├── Meta: < $25 acceptable for most offers
    ├── Google Display: < $5 acceptable
    └── If above range → reduce audience overlap, improve ad quality, consider time-of-day / placement adjustments
```

---

## Tree 5: Delivery Issue (Not Spending Budget)

**Symptom**: Campaign is spending significantly below daily budget (< 70% delivery).

```
Campaign not spending budget
│
├── Is the ad in review or flagged?
│   └── YES → Check ad status in dashboard
│       ├── In review → Wait 24 hours, then contact support if no resolution
│       ├── Disapproved → Fix the policy violation. Common issues: health claims,
│       │   before/after images, restricted categories, misleading copy
│       └── Account flagged → Contact platform support
│
├── Is the audience too small for the budget?
│   ├── Rule of thumb: Meta needs ~100K+ audience for efficient delivery at $100+/day
│   └── YES → Expand audience (remove restrictions, broaden interests, use Advantage+)
│
├── Is the bid too low?
│   ├── Manual bids: Is your bid below the suggested bid range?
│   └── YES → Raise manual bid or switch to automatic bidding
│
├── Is there audience overlap with other ad sets?
│   ├── Meta will de-prioritize ad sets competing for the same people
│   └── YES → Use Audience Overlap tool. Consolidate overlapping ad sets.
│
├── Is frequency cap limiting delivery? (Awareness objective)
│   └── YES → Increase frequency cap or remove it if retargeting small audience
│
├── Is the campaign schedule limiting hours?
│   └── YES → Remove dayparting or expand delivery hours
│
└── Is the account-level daily budget too low for the number of campaigns?
    └── YES → Consolidate campaigns or increase account-level budget
```

---

## Tree 6: Conversion Tracking Issue

**Symptom**: Conversions reporting seems wrong (too low, too high, not firing).

```
Conversion tracking seems wrong
│
├── Are conversions suddenly zero?
│   ├── Check if pixel is still installed on landing page (use Meta Pixel Helper / GTM Preview)
│   ├── Check if the conversion event is triggering correctly (test with a real conversion)
│   └── Check if a landing page update removed the pixel or broke the GTM tag
│
├── Are conversions much lower than expected?
│   ├── Attribution window change? (1-day vs. 7-day click)
│   ├── iOS privacy changes reducing reported conversions? (Compare to backend revenue)
│   └── Audience exclusions accidentally excluding converters before they convert?
│
├── Are conversions much higher than backend shows?
│   ├── Duplicate pixel fire? (Check with Pixel Helper — should fire once per page)
│   ├── Wrong event being tracked? (Tracking page views instead of purchases?)
│   └── View-through conversions inflating numbers? (Turn off or reduce VTC window)
│
└── Platform data vs. GA4 doesn't match
    ├── This is normal — platforms over-claim credit by 20–60%
    ├── Use GA4 as the source of truth for actual conversions
    ├── Use platform data for optimization signals (relative performance between ads)
    └── Set up UTM parameters on all ads if not already done
```

---

## Quick Diagnostic Reference

| Symptom | Most Likely Cause | First Action |
|---------|------------------|--------------|
| CPA rising + CPM stable + CTR falling | Creative fatigue | Rotate creative |
| CPA rising + CPM rising + CTR stable | Audience saturation or competition | Expand audience or check competition |
| CPA rising + CPM stable + CTR stable | Post-click issue | Check landing page CVR |
| CTR falling + Frequency > 3.0 | Ad fatigue | Pause ad, launch fresh creative |
| No delivery + budget set | Ad in review or audience too small | Check ad status; expand audience |
| ROAS dropped account-wide | Attribution or seasonal change | Check tracking; check period vs. last year |
| CVR dropped + ad metrics fine | Landing page issue | Check page speed, offer alignment, form friction |
| High CPM + low CTR | Creative not resonating | Improve hook and visual — creative problem, not audience |
| Low CPM + low CVR | Traffic quality or post-click | Check audience intent, landing page relevance |
