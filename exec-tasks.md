# Campaign Master Tasks — Verified by dotPH

**Document type:** Week-by-week execution checklist
**Last updated:** 2026-03-17
**Companions:**
- Copy → [creative-copy.md](creative-copy.md)
- Creative briefs → [creative-production-briefs.md](creative-production-briefs.md)
- A/B variants + testing → [creative-testing.md](creative-testing.md)
- Full schedule → [exec-schedule.md](exec-schedule.md)

---

## HOW TO READ THIS DOCUMENT

Each week is broken into sections by work type:

| Icon | Section | Who does it |
|------|---------|------------|
| 🎨 | **Creative Production** | Designer / AI tools |
| ⚙️ | **Campaign Setup & Launch** | Media buyer |
| 📝 | **Content Publishing** | Content / social team |
| 📧 | **Email** | Email / CRM team |
| 📊 | **Performance Review** | Media buyer |

**Dependency rule:** Creative production for Week N must be done by the END of Week N-1.
**Testing rule:** Always launch 2 variants per ad. Reference [creative-testing.md](creative-testing.md) for specs.
**Priority flags:** 🔴 Hard blocker — do not proceed without this. 🟡 Soft dependency. 🟢 Can run in parallel.

---

## PRE-LAUNCH — BEFORE WEEK 1 STARTS
> Everything here is a hard blocker. Do not launch any paid ad until all 🔴 items are checked.

### Triage First (5 minutes)

Answer these before doing anything else:

- [x] Is the **landing page live**? ✅ UI complete
- [ ] Is the **Meta Pixel installed** and firing a `Lead` event on form submit?
- [ ] Is the **Meta Ads account** active with billing set up?
- [ ] Is the **warm email list** (.ph domain holders) exported and ready?

If any is No → complete it before moving forward.

---

### ⚙️ Meta Ads Account Structure 🔴

- [ ] Create 3 campaigns:
  - `Campaign 1` — Awareness (Objective: Engagement / Video Views) — **no landing page link needed**
  - `Campaign 2` — Consideration (Objective: Traffic to landing page)
  - `Campaign 3` — Conversion (Objective: Leads)
- [ ] Build custom audiences:
  - Warm: Page engagers — 30 / 60 / 90 days
  - Website: All LP visitors (30 days)
  - Website: LP visitors who did NOT submit form
  - Lookalike: Based on page engagers — 1%, 2–3%, 4–5%
- [ ] Set up UTM parameters for all ad destination URLs
- [ ] Verify Pixel is firing correctly in Events Manager

---

### 🎨 Creative Production — Batch 1 (for Week 1 launch) 🔴

> Produce ALL of these before Week 1. Brief the designer now.
> Full specs in [creative-production-briefs.md](creative-production-briefs.md) + [creative-testing.md](creative-testing.md)

**Ad 1 — "423% Surge"** *(Awareness — All business owners PH, 25–55)*
- [ ] **Variant A** — 15s motion graphic, 1:1 feed + 9:16 Stories
  - Dark bg, "423%" slams in, kinetic typography, stat build, end card question
  - Poster frame: freeze "423%" at ~70% scale (not black screen)
  - Ref: creative-production-briefs.md → AD 1
- [ ] **Variant C** — Static image, 1080x1080
  - Black bg, white system font, plain text block: "Phishing websites copying PH businesses: 2024: 731 / 2025: 3,824 / That's 423% in one year. Is yours one of them? — Check Point, 2025"
  - No design elements. Looks like a Notes app screenshot.
  - Ref: creative-testing.md → AD 1, Variant C

**Ad 2 — "Bantayan Resort Story"** *(Awareness — Tourism / Visayas geo)*
- [ ] **Variant A** — Carousel, 4 slides, 1080x1080
  - Slide 1: Beach photo + "A resort in Bantayan had its Facebook page copied." (photo bleeds right edge — implies swipe)
  - Slide 2: Desaturated beach + "The fake page got 50,000 likes. The real page was offline."
  - Slide 3: Dark bg + "200+ guests paid. The resort had no record of them." (most impactful — bold type)
  - Slide 4: "P500,000 lost from one fake page. How would YOUR guests know the difference?" — works standalone as a screenshot
  - Source: "SunStar Cebu" bottom corner of slide 4
  - Ref: creative-testing.md → AD 2, Variant A
- [ ] **Variant C** — Single static, 1080x1350 (4:5)
  - Split image: Left = AI-generated Facebook page mockup (resort name, 50K likes, GCash visible, warm colors). Right = empty beach lot, dark/muted, text: "No record. 200+ victims. P500,000 lost."
  - Center dividing line: torn-paper or glitch effect
  - Bottom: "One fake Facebook page. — SunStar Cebu"
  - Ref: creative-testing.md → AD 2, Variant C

**Ad 4 — "52% of Filipinos"** *(Awareness — All business owners PH, 25–55)*
- [ ] **Variant A** — 15s motion graphic, 1:1 feed + 4:5
  - Count-up "52%", bar chart PH vs ASEAN, "96% worried", end card: "They blame you. Not the scammer."
  - Poster frame: "52%" at full size (not 0%)
  - Ref: creative-production-briefs.md → AD 4
- [ ] **Variant C** — Static image, 1080x1080
  - Big "52%" centered. Below: "of Filipinos have been scammed at least once." One line. Source: "GSMA, 2025." Nothing else.
  - Ref: creative-testing.md → AD 4, Variant C "Billboard"

**Ad 5 — "Household Name Gets Faked"** *(Awareness — F&B / all business owners)*
- [ ] **Variant A** — Carousel, 4 slides, 1080x1080
  - Slide 1: AI-generated Facebook page mockup showing a fake giveaway post (no real brand — generic fast food visual)
  - Slide 2: "Fake anniversary promos. P7,000 cash. P10,000 vouchers." + "Verafiles fact-checked, confirmed fake."
  - Slide 3: Mockup of official brand statement — "These are scams." (shows scale: even big brands had to respond)
  - Slide 4: "Your page. Your brand. No legal team to issue a statement."
  - Ref: creative-testing.md → AD 5, Variant A
- [ ] **Variant C** — Static image, 1080x1080
  - White bg, black text, clean sans-serif: "If scammers can fake one of the biggest brands in the Philippines, what's stopping them from faking yours?" — Source: "Verafiles fact-checked, confirmed fake." bottom corner.
  - Ref: creative-testing.md → AD 5, Variant C

---

### 📝 Blog — Pre-Campaign Publishing 🔴

- [ ] Publish **B1** on newsroom.dot.ph — "Phishing Sites Targeting Philippine Businesses Surge 423% in 2025"
- [ ] Publish **B2** on newsroom.dot.ph — "How Fake Facebook Pages Are Stealing Customers from Real Philippine Resorts"
  > Must be live before ads launch. Ref: creative-copy.md → Article 1 and Article 2

---

### 📧 Email Infrastructure 🟡

- [ ] Set up cold email sending domain (separate from dot.ph main domain)
- [ ] Begin 2-week warm-up sequence (use Lemlist, Instantly, or Smartlead) — **start this now, it takes 2 weeks**
- [ ] Configure warm email automation platform (Mailchimp, ConvertKit, or similar)
- [ ] Export .ph domain holders warm list — segment by industry if possible
- [ ] Build cold prospect list: DTI registry, Google Maps, industry associations (target: 5K minimum)

---

### 📊 Landing Page — Pixel Setup 🔴

> UI is complete. Only tracking setup remains.

- [ ] Create a Meta Pixel in Events Manager (Business Manager → Events Manager → Connect Data Source → Web)
- [ ] Add the Pixel base code to the landing page `<head>` on every page
- [ ] Fire a `Lead` event on form submit — triggers when the user clicks the signup CTA or submits the form
- [ ] Fire a `PageView` event on the thank-you/confirmation page — confirms the signup completed
- [ ] Verify in Events Manager → Test Events tab: load the LP and submit the form, confirm both `PageView` and `Lead` events appear in real time
- [ ] QA on mobile: confirm events fire on mobile browsers (Safari iOS + Chrome Android)
- [ ] Add Pixel to the thank-you page if it's a separate URL

---

---

## WEEK 1 — AWARENESS LAUNCH
> **B2B campaign goes live.** Cold audiences only. No product mention.
> **Ads live:** Ad1, Ad2
> **Email:** WE1

---

### ⚙️ Campaign Launch 🔴

- [ ] Upload **Ad1** creatives to Campaign 1 — cold ad set (all business owners PH, 25–55)
  - Set Variant A (motion) vs. Variant C (static) as an A/B split in the same ad set
  - Objective: Engagement / Video Views. No CTA button. No link.
- [ ] Upload **Ad2** creatives to Campaign 1 — cold geo ad set (Visayas)
  - Set Variant A (carousel) vs. Variant C (split static) as an A/B split
  - Objective: Engagement. No CTA button.
- [ ] Set Campaign 1 budget: 50% of total weekly ad budget
- [ ] Launch — check for Meta policy rejections within first 2 hours

---

### 📝 Content Publishing

- [ ] Schedule **organic posts** for this week (Mon / Wed / Fri):
  - P1 — Stat infographic
  - P2 — Scam story
  - P3 — Poll
  - Ref: strategy-marketing.md → Content Calendar

---

### 📧 Email

- [ ] Send **WE1** (warm list) — Problem seed + soft product name drop
  - Ref: strategy-marketing.md → Sequence A, Email 1

---

### 📊 Performance Review (end of Week 1)

- [ ] After 72 hours: check Ad1 and Ad2 thumb-stop rate (target: >25%), CPM, CTR
- [ ] Compare Variant A vs. Variant C per ad — note early leader
- [ ] Kill any creative with CPM >2x average AND <0.5% CTR at 1,000+ impressions
- [ ] Log: which format (motion vs. static vs. carousel) is winning → informs Batch 2 priorities

---

### 🎨 Creative Production — Batch 2 (for Week 2 launch) 🔴

> Produce these during Week 1 so they're ready to go live in Week 2.

**Ad 3 — "Cabanas La Union"** *(Awareness — Tourism / La Union / North Luzon geo)*
- [ ] **Variant A** — 20s video, 4:5 feed + 9:16 Stories
  - Open with AI-generated tropical beach (warm, travel-ad feel) → desaturate → empty lot → truth reveal → end card
  - Poster frame: beach at golden hour with "This resort in La Union had 8,000 likes."
  - Ref: creative-production-briefs.md → AD 3

**Ad 5 — "Household Name"** *(Awareness — F&B / all business owners)*
- [ ] **Variant B** — 20s video, 4:5 feed + 9:16 Stories — "The Ad That Looks Like a Scam"
  - 0:00–0:05: Looks like a real festive promo ad (P7,000 giveaway, celebratory music, generic fast food visual)
  - 0:05–0:07: FREEZE → music cuts → grayscale → red "FAKE" stamp slams across frame
  - 0:07–0:20: Reveal, stats, "million-peso budget and they still got faked", end card question
  - **Poster frame: must show the "FAKE" stamp — not the clean promo (risk mitigation)**
  - Ref: creative-testing.md → AD 5, Variant B

**Ad 6 — "Book Now, Fly Never"** *(Awareness — Travel agencies / tour operators)*
- [ ] **Variant A** — 20s video, 4:5 feed + 9:16 Stories
  - Open mimicking a real travel ad → "Book now..." → freeze → "...fly never." in red → stats → end card
  - Poster frame: travel paradise photo with "Book now..." — looks like a real travel ad
  - Ref: creative-production-briefs.md → AD 6

---

---

## WEEK 2 — AWARENESS CONTINUES
> **Ads live:** Ad1, Ad2 (ongoing), Ad3, Ad4, Ad5, Ad6 (new)
> **Email:** WE2, CE1 (cold sequence starts)

---

### ⚙️ Campaign Launch

- [ ] Upload **Ad3** to Campaign 1 — cold geo ad set (La Union / North Luzon)
  - Variant A (20s video) only — no second variant yet (produce Variant C in Week 3 based on performance)
- [ ] Upload **Ad4** to Campaign 1 — cold all-business ad set
  - Variant A (motion graphic) vs. Variant C (billboard static) — A/B split
- [ ] Upload **Ad5 Variant B** (video) to Campaign 1 — cold F&B ad set
  - A/B test: Variant A (carousel) vs. Variant B (video) in same ad set
- [ ] Upload **Ad6** to Campaign 1 — cold travel/tourism ad set
  - Variant A (video) only to start
- [ ] Warm ad set: run Ad1 or Ad2 variant with soft product teaser copy for existing page followers

---

### 📝 Content Publishing

- [ ] Publish **B3** — "The P480 Billion Problem" on newsroom.dot.ph
  - Ref: creative-copy.md → Article 3
- [ ] Schedule organic posts (Mon / Wed / Fri):
  - P4 — How scammers copy your business
  - P5 — 3 signs a page is fake
  - P6 — Industry-specific scam story

---

### 📧 Email

- [ ] Send **WE2** (warm list) — "Your .ph domain proves ownership, but..."
  - Ref: strategy-marketing.md → Sequence A, Email 2
- [ ] Send **CE1** cold batch (Day 0 of cold sequence — only if 2-week warm-up is complete)
  - Ref: strategy-marketing.md → Sequence B, Email 1

---

### 📊 Performance Review (end of Week 2)

- [ ] Pull week-over-week comparison: Ad1 and Ad2 frequency (target: <2.5), CTR trend
- [ ] Check Ad3, Ad4, Ad5, Ad6 first 48 hours: kill any creative with CPM >2x average
- [ ] For Ad4: Variant A (motion) vs. Variant C (billboard) — which has lower cost per 3s view?
- [ ] For Ad5: Variant A (carousel) vs. Variant B (video) — which has higher share rate?
- [ ] Log top-performing creative per ad set → this is the reference for Phase 2 creative briefs

---

### 🎨 Creative Production — Batch 3 (for Week 3 / Phase 2 start) 🔴

> Consideration ads need to be ready by end of Week 2.

**Ad 7 — "Prevention vs. Prosecution"** *(Consideration — retargeting Phase 1 engagers)*
- [ ] **Variant A** — 20s animated split-screen, 1:1 feed
  - Left (red/dark): prosecution steps pile up. Right (green/light): 3 prevention steps with checkmarks.
  - End card: "Prevention beats prosecution. Every time." + dotPH logo + CTA: "Learn How — It's Free"
  - Ref: creative-production-briefs.md → AD 7
- [ ] **Variant B** — Static split-screen, 1080x1080
  - Same split layout as video but as a single image. Left side crowded/red. Right side clean/green.
  - CTA button mockup visible bottom right.

**Ad 8 — "They Checked Everything"** *(Consideration — retargeting Phase 1 engagers)*
- [ ] **Variant A** — Static editorial, 1080x1080 + 1080x1350
  - Dark background. Opening line: "Your Customers Can't Tell Anymore." — diligent customer scammed via verified-looking fake resort page.
  - Key beat: they read the reviews, checked the photos, confirmed the price — and still got scammed.
  - Then dotPH value prop. CTA: "Give them one check that works." dotPH logo visible.
  - Ref: creative-copy.md → Ad 8

**Consumer posts Batch 1 — Fear Activation** *(organic, non-paid)*
- [ ] **C1** — "Spot the Fake" side-by-side image: 2 FB page mockups (both look real, subtle differences). Label "A" and "B". Reveal in pinned comment, not in image.
- [ ] **C2** — "I Booked a Resort" text post or single image (first-person tone, no product mention)
  - Ref: creative-copy.md → Post C2

---

---

## WEEK 3 — AWARENESS CLOSES + CONSIDERATION OPENS + CONSUMER CAMPAIGN STARTS
> **B2B:** Consideration campaign launches (Ad7, Ad8). Awareness ads continue.
> **Consumer:** #CheckBeforeYouPay Phase 1 begins (organic only).
> **Retargeting:** Phase 1 engager audience must have 1,000+ people before Ad7/Ad8 launch.

---

### ⚙️ Campaign Launch — Consideration

- [ ] Confirm retargeting audience size: Engaged with Awareness ads (video viewers 25%+, post engagers) — minimum 1,000 people before launching
- [ ] Build Campaign 2 ad sets:
  - Retarget: Phase 1 video viewers 25%+ (30 days)
  - Retarget: Phase 1 post engagers (30 days)
  - Warm: Page followers
- [ ] Upload **Ad7** to Campaign 2 — Variant A (video) vs. Variant B (static split) A/B test
  - Objective: Traffic (link clicks to landing page). CTA: "Learn How."
- [ ] Upload **Ad8** to Campaign 2 — Variant A (static editorial)
  - Objective: Traffic. CTA: "Get Verified — It's Free."
- [ ] Confirm UTM parameters on all landing page links are firing
- [ ] Budget: shift to 40% Awareness / 40% Consideration / 20% Conversion placeholder

---

### 📝 Content Publishing

- [ ] Publish **CA1** — "How to Spot a Fake Business Page on Facebook" on newsroom.dot.ph (consumer blog)
  - Ref: creative-copy.md → Consumer Article 1
- [ ] Publish **CA2** — "I Paid a Scammer Who Copied a Real Resort" on newsroom.dot.ph
  - Ref: creative-copy.md → Consumer Article 2
- [ ] Post **C1** — "Spot the Fake" interactive (organic, consumer audience)
- [ ] Post **C2** — "I Booked a Resort" victim story (organic)
- [ ] Schedule organic B2B posts (Mon / Wed / Fri): P7–P9

---

### 📧 Email

- [ ] Send **CE2** cold batch (Day 3 of cold sequence — agitate the cost of inaction)
  - Ref: strategy-marketing.md → Sequence B, Email 2

---

### 📊 Performance Review (end of Week 3)

- [ ] Landing page conversion rate: target >5% of visitors submit form. If <3% → fix headline + CTA copy before scaling spend.
- [ ] Ad7 / Ad8: check CPC (target <P5) and landing page arrival rate (target >60% of clicks actually reach LP)
- [ ] Consumer posts C1/C2: check organic engagement rate. If >5% → add to boost list for Week 4.
- [ ] Log confirmed signup count → update landing page counter + ad copies for Conversion phase

---

### 🎨 Creative Production — Batch 4 (for Weeks 4–5)

**Ad 1 — Hook test (from testing results)** *(if Variant A or C is clearly winning)*
- [ ] Based on Week 1–2 format test winner, produce the best-performing hook variant:
  - Hook B: "Is someone collecting payments using your business name?" (question-first opening)
  - OR Hook C: split-screen showing real page + fake page multiplying (visual shock)
  - Ref: creative-testing.md → AD 1, Hook Frame Variants

**Ad 2 — Video variant** *(produce if carousel is fatiguing or underperforming)*
- [ ] **Variant B** — 20s "Victim Testimony" video, 4:5 feed
  - First-person text types on screen like a Facebook post. Beach photo warms → desaturates → cuts to black → stats.
  - Music: gentle acoustic → dead cut at 0:08 → low drone
  - Ref: creative-testing.md → AD 2, Variant B

**Consumer posts Batch 2**
- [ ] **C3** — "8,000 Likes. It Didn't Exist." carousel (4 slides) — Cabanas La Union story
- [ ] **C4** — "52% of Filipinos" consumer static (1080x1080) — consumer angle, not business owner angle
  - Ref: creative-copy.md → Post C4

---

---

## WEEK 4 — AWARENESS + CONSIDERATION + CONSUMER FEAR ACTIVATION
> **Ads live:** All Awareness ads + Consideration ads (Ad7, Ad8)
> **Consumer:** C3, C4 posts. Boost decision based on C1/C2 performance.

---

### ⚙️ Campaign Actions

- [ ] Review Ad1/Ad2 frequency: if >2.5 → rotate to hook test variants produced in Batch 4
- [ ] Check if retargeting audience for Consideration has grown enough to split by engagement depth (25% vs 75% video viewers)
- [ ] **Boosting decision:** If C1, C2, or C3 hit >5% organic engagement rate → set up as boosted consumer post (separate from B2B campaigns)

---

### 📝 Content Publishing

- [ ] Post **C3** — "8,000 Likes. It Didn't Exist." carousel (organic)
- [ ] Post **C4** — "52% of Filipinos" consumer stat (organic)
- [ ] Schedule B2B organic posts: P10–P12

---

### 📧 Email

- [ ] Send **CE3** cold batch (Day 7 — solution reveal)
  - Ref: strategy-marketing.md → Sequence B, Email 3

---

### 📊 Performance Review (end of Week 4)

- [ ] Ad7 (Prevention vs. Prosecution): Variant A (video) vs. Variant B (static) — which has lower CPC?
- [ ] Landing page traffic from ads — check bounce rate and time on page (should be >30s average)
- [ ] Update "[X] businesses verified" counter on landing page

---

### 🎨 Creative Production — Batch 5 (for Weeks 5–6)

**Ad 9 — "Already Verified"** *(Conversion — retargeting LP visitors who didn't sign up)*
- [ ] **Variant A** — Static, 1080x1080 + 1080x1350
  - Clean minimal layout. Headline: "Already Verified." Social proof count: "[X] businesses listed this week."
  - Sub-line: "They're already being found by customers who check." CTA: "Get Verified — It's Free."
  - Update "[X]" with real signup count before producing. dotPH full branding.
  - Ref: creative-copy.md → Ad 9

**Ad 10 — "Hesitation Costs"** *(Conversion — retargeting LP visitors who didn't sign up)*
- [ ] **Variant A** — Static, 1080x1080
  - Minimal text. Headline: "Hesitation Costs." Sub-line: P480B supporting stat as single line, not infographic.
  - Trust gap closer: "Customers are already choosing verified businesses over unverified ones." CTA + dotPH branding.
  - Ref: creative-copy.md → Ad 10

**Ad 11 — "Your Page Looks Real"** *(Awareness — cold business owners)*
- [ ] **Variant A** — Dark minimal static, 1080x1080 + 1080x1350
  - Headline: "Your Page Looks Real. So Does Theirs." Dark background, high contrast text.
  - Sub-line: "Likes can be bought. Fakes can't be verified." dotPH logo. CTA: "See if you're verified."
  - Ref: creative-copy.md → Ad 11

**Ad 12 — "What Your Customers See Now"** *(Conversion — retargeting warm audiences)*
- [ ] **Variant A** — Before/after static, 1080x1080 + 1080x1350
  - Left: unverified page ("Is this real?"). Right: verified page with badge ("Verified Businesses Close More.")
  - Sub-line: "No more 'Is this your real page?'" CTA: "Get Verified — It's Free." dotPH branding.
  - Ref: creative-copy.md → Ad 12

**Consumer posts Batch 3**
- [ ] **C5** — "They Faked a Household Name" consumer carousel (4 slides)
  - Ref: creative-copy.md → Post C5

---

---

## WEEK 5 — CONVERSION LAUNCHES + CONSUMER FEAR ACTIVATION CLOSES
> **New:** Conversion campaign goes live (Ad9, Ad10).
> **Consumer:** C5 posts. Fear Activation phase closes.
> **Trigger check:** Confirm LP visitor audience ≥ 500 before launching conversion ads.

---

### ⚙️ Campaign Launch — Conversion

- [ ] Confirm LP visitor audience size: minimum 500 visitors before launching Campaign 3
- [ ] Build Campaign 3 ad sets:
  - "Did not convert": LP visitors (30 days) MINUS form submitters
- [ ] Upload **Ad9** and **Ad10** to Campaign 3
  - Objective: Leads (Pixel Lead event)
- [ ] Set bid strategy: lowest cost to start — calibrate target cost per lead after 50+ leads
- [ ] Budget shift: 30% Awareness / 35% Consideration / 35% Conversion

---

### 📝 Content Publishing

- [ ] Post **C5** — "They Faked a Household Name" consumer carousel (organic)
- [ ] Publish **B4** — "Why a .ph Domain Alone Isn't Enough to Prove Your Business Is Real" on newsroom.dot.ph
  - First B2B article with product mention. Ref: creative-copy.md → Article 4
- [ ] Publish **CA3** — "How to Check if a Business Is Verified by dotPH" on newsroom.dot.ph (consumer)
  - Ref: creative-copy.md → Consumer Article 3
- [ ] Schedule B2B organic posts: P13–P15

---

### 📧 Email

- [ ] Send **WE3** (warm list) — Social proof + "[X] businesses already verified"
  - Ref: strategy-marketing.md → Sequence A, Email 3
- [ ] Send **CE4** cold batch (Day 12)
  - Ref: strategy-marketing.md → Sequence B, Email 4

---

### 📊 Performance Review (end of Week 5)

- [ ] Check cost per lead from Campaign 3 (Conversion) — establish baseline
- [ ] Check conversion rate: leads from LP visitors (target: >15% of LP visitors who saw a Conversion ad)
- [ ] Consumer Fear Activation (C1–C5): review total reach and shared content volume. Did any post go organic-viral?

---

### 🎨 Creative Production — Batch 6 (for Weeks 6–8, Consumer Empowerment phase)

> Only produce Empowerment content if verified business count ≥ 300–500. Check before briefing.

- [ ] Confirm verified business count — gate for Empowerment phase
- [ ] **C6** — "How to Check" tutorial carousel, 5 slides, 1080x1080
  - Step-by-step: badge → click → verification page → check GCash → pay
  - Use actual badge/verification page mockups (the closer to real, the better)
  - Ref: creative-copy.md → Post C6
- [ ] **C7** — "The GCash Check" carousel, 4 slides, 1080x1080
  - Messenger-style chat mockup opening. "Stop asking. Start checking."
  - Ref: creative-copy.md → Post C7
- [ ] **C8** — "3 Signs a Page Is Fake" carousel, 4 slides, 1080x1080
  - Ref: creative-copy.md → Post C8
- [ ] **C9** — "#CheckBeforeYouPay" launch video, 30s, 4:5 feed + 9:16 Reels
  - Rapid fake-page montage → "FAKE" stamps → badge reveal → click → GCash match → CTA
  - Ref: creative-production-briefs.md → POST C9

---

---

## WEEK 6 — FULL FUNNEL ACTIVE + CONSUMER EMPOWERMENT STARTS
> All 3 campaigns running. Consumer campaign shifts to Empowerment phase.
> **Gate:** Do not publish C6–C9 until verified business count ≥ 300–500.

---

### ⚙️ Campaign Actions

- [ ] Review Awareness ad fatigue: Ad1/Ad2 frequency >2.5? → rotate to hook test variants
- [ ] Scale winning creatives: increase budget by 20% on best-performing creative per ad set
- [ ] Check lookalike audience performance vs. interest-based targeting — shift budget to winner

---

### 📝 Content Publishing

- [ ] Confirm gate: verified business count ≥ 300–500 before posting C6/C7
- [ ] Post **C6** — "How to Check" visual tutorial (organic consumer post)
- [ ] Post **C7** — "The GCash Check" tutorial (organic consumer post)
- [ ] Publish **CA4** — "Before You Send Money: The 3-Step Check" on newsroom.dot.ph
  - Ref: creative-copy.md → Consumer Article 4
- [ ] Schedule B2B organic posts: P16–P18

---

### 📧 Email

- [ ] Send **CE5** cold batch (Day 18 — final push)
  - Ref: strategy-marketing.md → Sequence B, Email 5
- [ ] Send **WE4** (warm list) — Final push to sign up
  - Ref: strategy-marketing.md → Sequence A, Email 4

---

### 📊 Performance Review (end of Week 6)

- [ ] C6/C7 engagement rate: target >5% for empowerment posts (they're instructional — saves and shares matter more than reactions)
- [ ] Update conversion ad copies (Ad9, Ad10) with current "[X] businesses verified" count

---

---

## WEEK 7 — OPTIMIZATION + CONSUMER EMPOWERMENT CONTINUES

---

### ⚙️ Campaign Actions

- [ ] A/B test results review for Ads 1, 2, 4, 5 (ref: creative-testing.md):
  - Declare format winner (Phase 1 test complete at ~2 weeks)
  - Produce winning hook variant if not already done
  - Kill underperforming variants
- [ ] Scale conversion campaign: if cost per lead is stable → increase Campaign 3 budget 20–30%

---

### 📝 Content Publishing

- [ ] Post **C8** — "3 Signs a Page Is Fake" checklist carousel (organic)
- [ ] Schedule B2B organic posts: P19–P21

---

### 📊 Performance Review (end of Week 7)

- [ ] Full funnel review: impression share → LP visitors → signups (Week 5–7 cohort)
- [ ] Email sequence results: cold email open rate (target >30%), reply rate (target >3%)

---

---

## WEEK 8 — HABIT FORMATION LAUNCHES + CAMPAIGN REVIEW

---

### ⚙️ Campaign Actions

- [ ] Refresh any fatigued Awareness ads (frequency >2.5): rotate to next hook variant from creative-testing.md
- [ ] Consider expanding Conversion audience: if LP visitors list is large enough, add 1% LAL of form submitters

---

### 📝 Content Publishing

- [ ] Launch **C9** — "#CheckBeforeYouPay" video (make this a moment — pin it, boost it)
  - This is the hashtag launch. Boost if organic engagement >5% within first 6 hours.
- [ ] Post **C10** — "Tell Your Nanay" family protection post (organic)
- [ ] Publish **CA5** — "Tell Your Nanay: A Family Guide to Avoiding Online Scams" on newsroom.dot.ph
  - Ref: creative-copy.md → Consumer Article 5
- [ ] Schedule B2B organic posts: P22–P24

---

### 📊 Performance Review (end of Week 8)

- [ ] 8-week campaign review: total signups, cost per signup, top-performing channel
- [ ] Compare signup sources: FB Ads vs. Organic vs. Email — which has the best cost per acquisition?
- [ ] Decide: extend campaign with new creative or shift to retention/referral focus

---

---

## WEEKS 9–10 — HABIT FORMATION + SCALE

---

### 📝 Content Publishing

- [ ] Post **C11** — UGC showcase prompt (organic) — invite consumers to screenshot their verification check
- [ ] Collect UGC submissions from C11 over 7 days
- [ ] Post **C12** — Milestone post "X consumers checked this month" — update with real analytics
  - Ref: creative-copy.md → Post C12
- [ ] Update **B5** — "[X] Businesses Already Verified" with real signup numbers and publish
  - Ref: creative-copy.md → Article 5

---

### 📊 Final Performance Review (Week 10)

- [ ] Total signups vs. target
- [ ] Cost per lead by campaign (Awareness-to-Consideration vs. direct Conversion)
- [ ] Identify: which ad concept drove the most LP visits? which drove the most signups?
- [ ] Archive winning creative specs for future campaign reference
- [ ] Decide on next campaign phase: referral program, B2B case studies, enterprise outreach

---

---

## WEEKLY RECURRING CHECKLIST
> Every week from Week 1 onwards. Takes ~30 minutes.

### Every Monday
- [ ] Pull weekly report: CPM, CTR, thumb-stop rate, cost-per-engagement, cost-per-lead
- [ ] Flag any creative with frequency >2.5
- [ ] Update "[X] businesses verified" counter on landing page and in Ad9/Ad10 copies

### Every Wednesday
- [ ] Review A/B test results — minimum 2,000 impressions before declaring winner
- [ ] Kill underperformers per kill thresholds in [creative-testing.md](creative-testing.md)
- [ ] Adjust budget split between Awareness / Consideration / Conversion based on funnel pressure

### Every Friday
- [ ] Request next creative batch from designer if any ads are approaching fatigue (7–10 days for statics, 10–14 for carousels, 14–21 for video)
- [ ] Review cold email open + reply rates
- [ ] Log weekly signup count for "[X]" placeholder updates in B5, Ad9, Ad10, C12

---

## DOCUMENT QUICK REFERENCE

| Document | What's in it | Use it for |
|----------|-------------|------------|
| [creative-copy.md](creative-copy.md) | All ad copy, blog articles, social posts | Writing briefs, copy review |
| [creative-production-briefs.md](creative-production-briefs.md) | Scene-by-scene video/motion briefs | Briefing designer / AI tools |
| [creative-testing.md](creative-testing.md) | A/B variants, hook tests, KPIs, kill thresholds | Ad testing, optimization |
| [creative-copy-enhancements.md](creative-copy-enhancements.md) | Reels scripts, organic additions | Organic content calendar |
| [exec-schedule.md](exec-schedule.md) | Full week-by-week channel map | Cross-channel scheduling |
| [strategy-marketing.md](strategy-marketing.md) | Warm + cold email sequences, B2B organic copy | Email and organic execution |
