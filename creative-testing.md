# Campaign Creative Testing — Verified by dotPH

**Document type:** A/B testing variants and creative testing framework for media buyers
**Companion to:** [creative-copy.md](creative-copy.md), [creative-production-briefs.md](creative-production-briefs.md)
**Last updated:** 2026-03-17
**Purpose:** Give the media buyer testable creative variants to optimize CPM, CTR, thumb-stop rate, and cost-per-engagement across Awareness ads

---

## How to Use This Document

Each ad below has:
- **Variant A** — the current polished concept (from creative-production-briefs.md), refined for testing
- **Variant B** — an alternative visual treatment with a different emotional hook
- **Variant C** — a lo-fi or format-shift variant (where applicable)
- **Hook frame specs** — the first 3 seconds that determine thumb-stop
- **Format test matrix** — which formats to test against each other
- **KPIs per variant** — what you're measuring and what "winning" looks like

### Testing Protocol

1. **Phase 1 — Format test:** Run Variant A in all specified formats (static, motion, carousel) with identical copy. Kill underperformers at 1,000 impressions per format. This tells you which *format* works for this concept.
2. **Phase 2 — Hook test:** Take the winning format from Phase 1 and run all 3 hook variants. Kill underperformers at 2,000 impressions per hook. This tells you which *emotional angle* resonates.
3. **Phase 3 — Creative test:** Run the winning hook from Phase 2 in Variant A, B, and C treatments. Kill underperformers at 3,000 impressions per variant.
4. **Phase 4 — Scale:** Put 80% of budget behind the winning combination. Keep 20% testing new variants.

### Budget Allocation for Testing

| Phase | % of Ad Set Budget | Duration | Kill Threshold |
|-------|-------------------|----------|----------------|
| Format test | 15% | 48 hrs | <0.5% CTR or >2x avg CPM |
| Hook test | 20% | 72 hrs | Lowest thumb-stop rate (3s views / impressions) |
| Creative test | 25% | 72 hrs | Lowest cost-per-engagement |
| Scale winner | 40% | Ongoing | Review weekly |

### AI Production Note

Per the constraints in [creative-production-briefs.md](creative-production-briefs.md), AI-generated visuals cannot convincingly produce UGC/phone-shot style. Variant C options below that call for "lo-fi" mean **stripped-down design** (plain text, minimal graphics, raw typography) — not fake phone footage. If actual UGC-style video is desired, it requires real phone recording with a real person, not AI generation.

---

# AD 1: "423% Surge" — Stat-Driven Hook

## Current State

One treatment exists: 15-second motion graphic, dark background, kinetic typography. Detailed scene-by-scene in [creative-production-briefs.md](creative-production-briefs.md).

## Hook Frame Variants (First 3 Seconds)

The first frame determines thumb-stop rate. Test these three opening approaches:

### Hook A: "The Number First" (current)
- **Frame 1:** Black screen. "423%" slams in center-screen with scale-up impact animation
- **Why it might work:** Big number is inherently scroll-stopping. Data-driven audiences (business owners) react to stats
- **Risk:** Number without context might get scrolled past — "423% of what?"

### Hook B: "The Question First"
- **Frame 1:** Black screen. Text types out: "Is someone collecting payments using your business name?"
- **Frame 2 (2s):** Beat. Then: "Here's how fast it's growing →"
- **Why it might work:** Personal threat hook. Speaks directly to the fear. The question creates a micro-commitment — they want the answer
- **Risk:** Text-heavy opening might lose fast scrollers

### Hook C: "The Visual Shock"
- **Frame 1:** AI-generated split screen — left side shows a legitimate-looking business Facebook page, right side shows an identical copy with a red "FAKE" overlay fading in
- **Frame 2 (2s):** Pages multiply. 2, 4, 8 copies appearing. Text: "423% more of these. In one year."
- **Why it might work:** Visual rather than text-based — might stop thumbs faster in a feed full of text ads
- **Risk:** Requires more complex AI production. Visual might read as cluttered on mobile

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **15s Motion Graphic** (current) | 1:1 feed + 9:16 Stories | Full kinetic typography treatment |
| **Static Image** | 1080x1080 (1:1) + 1080x1350 (4:5) | Big "423%" center, supporting text below, source citation. One frame, no animation |
| **6s Micro-Video** | 9:16 Reels/Stories only | Number slam + one line of context + end card. Cut scenes 2-3 entirely. Tests if the stat alone is enough |
| **3-Slide Carousel** | 1080x1080 per slide | Slide 1: "423%" / Slide 2: "731 → 3,824 fake sites. One year." / Slide 3: "Is someone copying YOUR business right now?" |

**Hypothesis:** The 6s micro-video will outperform the 15s version on thumb-stop rate because there's less commitment. The static might win on CPM because Meta's ad auction favors statics for impressions. The 15s version should win on cost-per-engagement if the audience watches past 3 seconds.

## Creative Variants

### Variant A: "Data Punch" (current, refined)

The existing motion graphic treatment from creative-production-briefs.md. Dark background, kinetic typography, "423%" impact animation.

**Refinements for testing:**
- Add a **thumbnail-safe first frame** — the number "423%" should be visible even as a still image in the feed before autoplay starts. Currently the scene starts with a black screen and the number slams in, but on slow connections or paused autoplay, the thumbnail is black. Instead: freeze the number at ~70% scale as the poster frame
- **End card hold:** Extend end card from 3s to 4s. On Facebook, the last frame loops — a longer hold on "Is someone copying YOUR business right now?" gives the question more weight on the loop

### Variant B: "News Ticker"

**Concept:** Mimics a breaking news broadcast. The stat is delivered as if it's a news report — ticker at the bottom, "BREAKING" flash, news-anchor-style typography.

**Why test this:** Filipino business owners are heavy news consumers. A creative that looks like GMA/ABS-CBN breaking news might trigger a different attention pattern than a branded-looking motion graphic. It signals "this is real, this is happening now" rather than "this is an ad."

**Scene Breakdown:**
- **0:00–0:02:** Red "BREAKING" flash animation. News ticker bar slides in from right at the bottom: "Phishing sites targeting PH businesses surge 423%..."
- **0:02–0:06:** Upper screen: headline text types in news-style font: "PHISHING SITES TARGETING PHILIPPINE BUSINESSES SURGE 423% IN ONE YEAR." Source: "Check Point, 2025" below in smaller text
- **0:06–0:10:** Ticker continues scrolling: "...from 731 to 3,824 sites... fake brand profiles up 37%..." Upper screen shifts to supporting stats, stacking vertically
- **0:10–0:13:** Ticker stops. Upper screen clears. Single question in center: "Is someone copying YOUR business right now?"
- **0:13–0:15:** End card holds

**Specs:** 1:1 (feed) + 9:16 (Stories). 15 seconds. Dark background with red accent. News-style sans-serif typography (condensed, bold).

**Music/Sound:** News broadcast-style urgency tones. No voiceover — text-on-screen only. Subtle "breaking news" sting at 0:00.

### Variant C: "Raw Text" (Lo-Fi)

**Concept:** No graphics. No motion. Just white text on a solid black background — like a text message or a note someone screenshotted. Stripped down to the raw message.

**Why test this:** In a feed full of polished ads, something that looks like a raw screenshot or plain-text post can stop the scroll by being *different*. Low production cost = can iterate fast. Tests whether the message alone carries enough weight without any visual design.

**The Creative:**
- Single static image. 1080x1080 (1:1)
- Black background. White text. System font (San Francisco or similar)
- Text reads:

```
Phishing websites copying
Philippine businesses:

2024: 731
2025: 3,824

That's a 423% increase.
In one year.

Is yours one of them?

— Check Point, 2025
```

- No logo. No design elements. No gradients. Looks like someone typed it in Notes and screenshotted it.

**Why this might win:** The "screenshot of a note" format has historically high engagement on Filipino Facebook because it triggers curiosity ("why is this so plain?") and gets shared as if it's insider information. The raw look signals "this is so important someone just typed it out and posted it."

**Risk:** May look unfinished or unprofessional. Test at low budget first.

## KPIs & Win Conditions

| Metric | Target | How to Measure |
|--------|--------|---------------|
| **Thumb-stop rate** | >25% (3s views / impressions) | Meta Ads Manager → Video Plays at 3 sec |
| **Cost per 3s view** | <P0.50 | Total spend / 3s views |
| **CTR (all)** | >1.5% | Clicks / Impressions |
| **Engagement rate** | >3% | (Reactions + Comments + Shares) / Reach |
| **Share rate** | >0.5% of reach | Shares / Reach — critical for organic amplification |

**Winner definition:** Lowest cost per 3-second view WITH engagement rate >3%. If a variant has cheap views but low engagement, it's not the winner — it means people watched but didn't care.

## Copy Test — Headline A/B

Run in parallel with the winning visual format from the hook/format tests above.

| Element | Variant A (stat-led) | Variant B (personal threat — recommended) |
|---------|---------------------|------------------------------------------|
| **Headline** | Fake Pages Up 4x Last Year | Someone Is Using Your Name |
| **Description** | Is your business being copied? | Is your business being copied? |

**Note on Variant A:** The original stat headline "Phishing Sites Up 423% in PH" is retired — "phishing sites" refers to URL-based attacks, not Facebook page impersonation (the campaign's actual subject). If testing a stat-led headline, use "Fake Pages Up 4x Last Year" — accurate to the campaign's use case (37% social, plus the broader fake page trend), avoids dating, and the "4x" framing is more visceral than a percentage. The 423% stat is correctly used in the body copy (below fold) with full context.

**Why test this:** Variant A tests whether a quantified threat (scale of the problem) outperforms a personal threat (it's happening to you). Both are in play — the stat supports in the body either way.

**Winner condition:** Higher CTR. If Variant B wins, the personal confrontation beats scale as a hook. Scale still earns its place in the body.

---

# AD 2: "Bantayan Resort Story" — Narrative Hook

## Current State

One treatment: Facebook carousel (3-4 slides), clean text on muted beach/resort background. No video version exists despite this being a story-driven concept that naturally suits video.

## Hook Frame Variants (First 3 Seconds)

### Hook A: "The Scale" (current carousel lead slide)
- **Slide 1 / Frame 1:** "A Facebook page got 50,000 likes. It looked exactly like a real Bantayan resort."
- **Why:** Lead with the impressive/alarming scale. 50,000 is a big number for a local business page
- **Risk:** Carousel lead slides need to earn the swipe. This line is informative but might not be emotionally urgent enough

### Hook B: "The Arrival"
- **Slide 1 / Frame 1:** "They booked a resort. They sent their deposit. Then they showed up." (with a scenic beach photo that looks normal, inviting)
- **Slide 2:** "The resort had no record of them."
- **Why:** Start from the victim's perspective. Creates immediate empathy and curiosity. The reveal is on slide 2, which earns the swipe
- **Risk:** Slower build — some people won't swipe to get the payoff

### Hook C: "The Number"
- **Slide 1 / Frame 1:** "P500,000 lost." — big number, bold, center-screen on dark background. Below in smaller text: "From one fake Facebook page."
- **Why:** Money hook. P500K is a number every Filipino business owner can feel. It's concrete, not abstract
- **Risk:** Starting with money might feel like clickbait. Needs the follow-up slides to deliver on the promise

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Carousel (current)** | 1080x1080, 3-4 slides | Story told through swipeable slides |
| **20s Video — Reveal Style** | 4:5 feed + 9:16 Stories | Open with beach paradise → desaturate → reveal scam (same emotional arc as Ad 3 "Cabanas" but Bantayan story) |
| **20s Video — Victim Perspective** | 4:5 feed + 9:16 Stories | First-person narrated text: "I booked a resort..." (no voiceover — text types on screen as if someone is telling the story) |
| **Single Static — Stat Card** | 1080x1350 (4:5) | One image: "50,000 likes. 200+ guests scammed. P500,000 lost. One fake Facebook page." — beach photo background, text overlay |

**Hypothesis:** The video reveal format will outperform the carousel for total engagement because stories work better in motion. But the carousel might win on shares because each slide is screenshot-able and individually shareable in Messenger/Viber.

## Creative Variants

### Variant A: "Carousel Story" (current, refined)

The existing carousel from creative-copy.md with these refinements:

**Slide-by-slide:**
1. **Hook slide:** Scenic beach photo (AI-generated). Text overlay: "A resort in Bantayan Island had its Facebook page copied." — simple, sets the scene
2. **Escalation:** Same beach, slightly desaturated. Text: "The fake page got 50,000 likes. The real page was offline."
3. **Impact:** Dark background. Text: "200+ guests paid. The resort had no record of them."
4. **Close:** Dark background. Bold text: "P500,000 lost from one fake page." Below: "How would YOUR guests know the difference?" Source: "SunStar Cebu"

**Refinements:**
- **Slide 1 must earn the swipe.** Add a subtle "→" or "Swipe" indicator. Better: make the beach photo bleed off the right edge so it visually implies continuation
- **Slide 3 is the emotional peak.** Design this as the most visually impactful slide — it's the one people screenshot. Bold typography, high contrast
- **Slide 4 must work standalone.** When shared as a screenshot (common on Filipino Facebook), slide 4 alone needs to make sense without slides 1-3

### Variant B: "Victim Testimony Video"

**Concept:** A 20-second text-on-screen video told from a first-person perspective. No voiceover — text appears as if being typed, like someone telling their story in a Facebook post. The intimacy of the format creates empathy.

**Scene Breakdown:**
- **0:00–0:03:** Beach photo (warm, inviting). Text types on screen: "We found a resort on Facebook for our Bantayan trip."
- **0:03–0:06:** Same photo, slightly zoomed in. Text: "50,000 likes. Nice photos. GCash payment."
- **0:06–0:08:** Photo starts desaturating. Text: "We sent P3,500."
- **0:08–0:12:** Cut to black. Text types: "When we arrived, the resort had no record of us." Beat. "We were the fifth family that day."
- **0:12–0:16:** Black screen. Stats appear line by line: "200+ families scammed." / "P500,000 lost." / "From one fake Facebook page."
- **0:16–0:20:** End card: "The fake page had more likes than the real one." Source citation.

**Music/Sound:** Gentle acoustic at start (travel ad feel) → cuts to silence at 0:08 → low ambient drone through the stats.

**Why test this:** First-person stories outperform third-person stats for emotional engagement. The "typing" format feels like reading someone's real Facebook post, not watching an ad. High share potential — people share stories, not infographics.

### Variant C: "Split Reality"

**Concept:** A single static image designed as a side-by-side comparison. Left: the fake page (with real-looking likes, photos, branding). Right: the reality (empty beach lot, "no record" text). The visual contrast tells the entire story in one frame.

**The Creative:**
- 1080x1350 (4:5 portrait)
- Left half: AI-generated Facebook page mockup — resort name, beach cover photo, "50,000 likes," GCash payment option visible. Warm colors. Looks completely legitimate
- Right half: Dark/muted. Same beach location but empty — no resort building. Overlaid text elements: "No record." / "200+ victims." / "P500,000 lost."
- Dividing line in center: a torn-paper or glitch effect separating the two halves
- Bottom: "One fake Facebook page." Source: "SunStar Cebu"
- No logo. No CTA button.

**Why test this:** Single-image statics are the cheapest to produce and the cheapest in Meta's auction. If this performs within 80% of the video variant's engagement, it's the better choice because it scales at lower cost. The side-by-side format is inherently shareable — it works as a screenshot in Messenger.

## KPIs & Win Conditions

| Metric | Target | Notes |
|--------|--------|-------|
| **Carousel: Swipe-through rate** | >30% (reach slide 3+) | Measures if the story hooks. Below 20% = weak lead slide |
| **Video: Thumb-stop rate** | >30% (3s views / impressions) | Story ads should thumb-stop higher than stat ads |
| **Share rate** | >1% of reach | This is a story ad — sharing is the goal. Below 0.5% = wrong emotional tone |
| **Cost per engagement** | <P2.00 | Including reactions, comments, shares, saves |
| **Comment sentiment** | >70% relevant | Comments should be "OMG this happened to someone I know" not "nice ad" |

**Winner definition:** Highest share rate with cost-per-engagement under P2.00. For a story-driven awareness ad, shares > everything else because shares = organic reach = cheaper retargeting audiences.

## Copy Test — Caption Order

The creative assessment identified that Slide 4's challenge question — "How would YOUR guests know which page is real?" — is the strongest line in the ad. Test leading the caption with it rather than opening with the setup story.

| Element | Variant A (current) | Variant B (curiosity-first) |
|---------|--------------------|-----------------------------|
| **Above fold** | "A resort in Bantayan Island, Cebu had its Facebook page copied..." | "How would YOUR guests know which page is real? A resort in Bantayan found out the hard way." |
| **Story structure** | Setup → escalation → reveal → challenge | Challenge → setup → escalation → reveal |

**Why test this:** Curiosity-first opens with the reader's problem (can my customers tell?), then earns the story as proof. The current version opens with someone else's problem, asking the reader to follow a narrative before they feel implicated. For a retargeting-eligible audience, the personal challenge may outperform the cold-open story setup.

**Winner condition:** Higher swipe-through rate on the carousel (reaching slide 3+) and higher click-through on the end card CTA.

---

# AD 4: "52% of Filipinos" — National Stat Hook

## Current State

One treatment: 15-second motion graphic with count-up animation, bar chart, and data-driven typography. Detailed in creative-production-briefs.md.

## Hook Frame Variants (First 3 Seconds)

### Hook A: "The Number" (current)
- **Frame 1:** Dark navy background. "52%" counts up from 0 to 52 in 1.5 seconds
- **Why:** The count-up animation is inherently engaging — people watch numbers climb. "52%" is a personally relevant stat (it's about YOU, not abstract businesses)
- **Risk:** Count-up animations are common in data ads. May not differentiate

### Hook B: "The Personal Hit"
- **Frame 1:** Text appears: "Your customers don't blame the scammer." Beat. "They blame you."
- **Frame 2 (2s):** "And 52% of them have already been scammed."
- **Why:** Leads with the consequence, not the stat. The business owner feels the pain first, then gets the data. Reverses the current order (stat → consequence becomes consequence → stat)
- **Risk:** Two-frame hook is slower. May lose people before the "52%" appears

### Hook C: "The Comparison"
- **Frame 1:** A simple bar chart appears instantly (no animation). Philippines bar at 52%, ASEAN average at 45%. Philippines bar in red, ASEAN in grey. Text: "Philippines vs. ASEAN."
- **Why:** Competitive framing. Filipinos respond to "we're worse than our neighbors" — it triggers national pride/concern. The visual chart is immediately readable
- **Risk:** Requires the viewer to process a chart in 3 seconds. Might be too analytical for mobile scroll

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **15s Motion Graphic** (current) | 1:1 feed + 9:16 Stories | Full animated treatment with count-up, bar chart, transitions |
| **Static — "Billboard"** | 1080x1080 (1:1) | Big "52%" center. Below: "of Filipinos have been scammed at least once." Source: GSMA, 2025. That's it. One number, one line, one source. Tests if simplicity wins |
| **Static — Infographic** | 1080x1350 (4:5) | Full data card: 52% stat, ASEAN comparison bar, 96% worry stat, source citation. All visible at once — no scrolling, no animation |
| **6s Micro-Video** | 9:16 Reels/Stories | Count-up from 0 to 52% → "of Filipinos. Scammed." → End card. No bar chart, no supporting stats. Tests the number alone |

**Hypothesis:** The "Billboard" static will win on CPM (cheapest distribution). The full motion graphic will win on engagement time. Test both — if the static gets 80%+ of the engagement at 50% of the cost, scale the static.

## Creative Variants

### Variant A: "Data Story" (current, refined)

The existing motion graphic treatment. Count-up animation, bar chart, supporting stats.

**Refinements:**
- **First frame poster image:** The poster frame (visible before autoplay) should show "52%" at full size, not the beginning of the count-up at 0%. On slow connections or preview mode, "0%" is meaningless — "52%" is the hook
- **Bar chart timing:** Current treatment gives the bar chart 4 seconds (Scene 2). Reduce to 3 seconds — bar chart makes its point quickly, lingering reduces momentum
- **End card sharpness:** Current end card: "Your customers don't blame the scammer. They blame you." This is strong. But test a shorter variant: "They blame you. Not the scammer." — fewer words, same punch, better for loop replay

### Variant B: "The Map"

**Concept:** A visual comparison showing the Philippines highlighted on an ASEAN map, with countries color-coded by scam prevalence. The Philippines glows red — the worst (or near-worst) in the region. The data is spatial, not textual.

**Scene Breakdown:**
- **0:00–0:04:** ASEAN map fades in. Countries are grey. One by one, they fill with color: green (low scam rate) → yellow → orange → red. The Philippines fills last — bright red.
- **0:04–0:08:** Map stays visible. Philippines zooms in slightly. Text overlays: "52% of Filipinos scammed." / "7 points above ASEAN average." / Source: GSMA, 2025
- **0:08–0:12:** Map fades. Black screen. "96% are worried about being scammed again." Beat. "But when it happens — they blame YOUR business."
- **0:12–0:15:** End card: "Your reputation is the real target."

**Music/Sound:** Minimal. Soft map reveal sounds. Subtle alarm tone when Philippines fills red.

**Why test this:** Maps are inherently engaging — people look for their country/location. The "Philippines is the worst" framing triggers national concern, which Filipino audiences share and discuss. Geographic visuals are underused in the current campaign, which is mostly text-on-screen.

**Risk:** Map might feel too "infographic" and less emotionally urgent. The text-on-screen of Variant A might hit harder for business owners.

### Variant C: "The Receipt"

**Concept:** A single static designed to look like a receipt or transaction summary — as if the country's scam losses are an itemized bill.

**The Creative:**
- 1080x1350 (4:5 portrait)
- Designed to look like a paper receipt (slightly off-white background, monospace font, faint thermal-print texture)
- Content:

```
================================
       SCAM LOSSES — PH
         Annual Summary
================================

Filipinos scammed:        52%
ASEAN average:            45%
Worried about next scam:  96%

Fake brand profiles:   +37%
Phishing sites:       +423%

--------------------------------
TOTAL ANNUAL LOSS:
          P480,000,000,000
--------------------------------

"Your customers don't blame
 the scammer. They blame you."

Sources: GSMA 2025, Check Point,
         ScamWatch HQ
================================
```

- No logo. No design flourishes. The receipt format IS the design.

**Why test this:** The receipt format is visually distinct in a feed — it doesn't look like an ad, a news article, or a branded graphic. It triggers curiosity ("what is this?") and the familiar receipt format makes the numbers feel real and transactional. High screenshot/share potential.

**Risk:** The format is unconventional. It may confuse some users. Test at low budget.

## KPIs & Win Conditions

| Metric | Target | Notes |
|--------|--------|-------|
| **Thumb-stop rate** | >25% | Stat-driven ads typically thumb-stop lower than story ads — 25% is strong |
| **Save rate** | >0.3% of reach | Data content gets saved more than shared — measure saves as a signal |
| **Share rate** | >0.5% of reach | If the variant triggers "tag a business owner friend" behavior, it's working |
| **Cost per 3s view** | <P0.40 | Stat ads should be cheaper than story ads — lower emotional commitment to start watching |

**Winner definition:** Highest thumb-stop rate with cost per 3s view under P0.40. For stat-driven awareness, the goal is maximum eyeballs at minimum cost — these are audience-building ads, not conversion ads.

## Copy Test — Headline & Description A/B

| Element | Variant A (original) | Variant B (recommended) |
|---------|---------------------|------------------------|
| **Headline** | 52% of Filipinos Have Been Scammed | They Don't Blame the Scammer. |
| **Description** | Your business pays the price. | They blame your business. |

**Why test this:** The original headline reports a national stat. The new headline delivers the campaign's sharpest strategic insight — the reframe from bystander to victim. The above-fold opens with *"Your customers don't blame the scammer. They blame you."* The headline should match this register, not repeat a stat the viewer already saw in the video. The description moves from vague ("pays the price") to specific and personal ("They blame your business.").

**Winner condition:** Higher CTR and lower cost-per-click. A headline that speaks to personal consequence should drive more clicks than one reporting national data.

---

# AD 5: "They Faked a Household Name" — Brand Shock

## Current State

One treatment: carousel (4 slides) with bold text on simple backgrounds. No video version despite the concept having strong reveal/escalation energy.

## Hook Frame Variants (First 3 Seconds)

### Hook A: "The Challenge" (current)
- **Slide 1 / Frame 1:** "Scammers impersonated a major PH fast food chain on Facebook."
- **Why:** Direct statement. Industry-recognizable. Every Filipino knows which chains matter
- **Risk:** "A major fast food chain" is vague (we can't name the brand). Vagueness might reduce impact

### Hook B: "The Scale of the Fake"
- **Slide 1 / Frame 1:** "P7,000 cash giveaways. P10,000 gift vouchers. 'Labor Day gifts.' ALL FAKE."
- **Why:** Lead with the specifics of the scam. The amounts are relatable. "All fake" is the shock
- **Risk:** Leading with promo details might look like a promo ad itself before the "ALL FAKE" lands

### Hook C: "The Impossible Question"
- **Slide 1 / Frame 1:** "If scammers can fake one of the biggest brands in the Philippines..." (text only, large, centered)
- **Slide 2:** "...what's stopping them from faking yours?"
- **Why:** Goes straight to the personal threat. Skips the story setup entirely. The question IS the hook
- **Risk:** Two-slide hook means the payoff requires a swipe. But the cliffhanger format ("..." ending) is proven for swipe rates on Filipino Facebook

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Carousel (current)** | 1080x1080, 4 slides | Story told through swipeable slides. Each slide is a beat of the narrative |
| **20s Video — Escalation** | 4:5 feed + 9:16 Stories | Open with fake promo mockups (looks like a real promo ad) → reveal "ALL FAKE" → escalate to "If they can fake a household name..." |
| **Single Static — Quote Card** | 1080x1080 (1:1) | "They faked a household name. Your business could be next." One line. Bold. Cite: Verafiles. Tests if the single punchline is enough |
| **Single Static — "Promo Reveal"** | 1080x1350 (4:5) | Designed to look like a real promo ad (P7,000 giveaway, anniversary theme) with a red "FAKE" stamp overlaid. The creative IS the scam, shown and debunked |

**Hypothesis:** The "Promo Reveal" static will have the highest thumb-stop rate because it looks like a promo ad (which people click on) but subverts the expectation. The video escalation will have the highest overall engagement. The carousel will have the highest share rate per engaged user.

## Creative Variants

### Variant A: "Carousel Escalation" (current, refined)

The existing carousel from creative-copy.md:
1. "Scammers impersonated a major PH fast food chain on Facebook."
2. "Fake anniversary giveaways. P7,000 cash. P10,000 vouchers."
3. "Customers shared personal data. The company had to issue a warning."
4. "If they can fake a household name, they can fake you."

**Refinements:**
- **Slide 1 redesign:** Instead of text-on-background, show a mockup of what the fake promo page looked like (AI-generated Facebook page mockup with a giveaway post). Makes it visceral instead of abstract
- **Slide 3 emphasis:** "The company had to issue a warning" — show a mockup of an official brand statement. This makes the scale of the problem concrete: a major corporation had to publicly address this
- **Slide 4 personalization:** Add below the main text: "Your page. Your brand. No legal team to issue a statement." — makes it about the small business owner specifically
- **Cite placement:** "Verafiles fact-checked, confirmed fake." should appear on slide 2 or 3, not just the creative direction notes. Source visibility = credibility

### Variant B: "The Ad That Looks Like a Scam"

**Concept:** A 20-second video that intentionally starts looking like a giveaway promo ad — the kind of scam it's warning about. For the first 5 seconds, viewers think they're watching a promo. Then the reveal: it's all fake.

**Scene Breakdown:**
- **0:00–0:05:** Bright, festive design. Anniversary theme. "🎉 P7,000 Cash Giveaway! P10,000 Gift Vouchers! Claim yours now!" Big brand-style layout (no actual brand used — generic fast food visual). Background music: upbeat, celebratory. This should look like a real promo
- **0:05–0:07:** FREEZE. Music cuts. Color drains to black & white. Red "FAKE" stamp slams across the entire frame. Silence.
- **0:07–0:11:** Black screen. Text appears: "This is what scammers posted using a major PH fast food chain's name and photos." / "Thousands of customers clicked. They entered their personal data."
- **0:11–0:15:** "The real company had to issue an official statement: 'These are scams.'" — shown as a text card mockup
- **0:15–0:18:** "That brand has a legal team. A social media team. A million-peso marketing budget." / "And they still got faked."
- **0:18–0:20:** End card: "What's protecting YOUR business page right now?" Source: Verafiles.

**Music/Sound:** Celebratory music (0:00-0:05) → dead cut to silence → low tension drone (0:07-0:18) → silence on end card.

**Why test this:** The bait-and-switch format is high-risk, high-reward. If it works, it'll have the highest thumb-stop and completion rate of any variant because the viewer's expectation gets violated — they think it's a promo, then it's a warning. This pattern interruption is extremely memorable.

**Risk:** Some viewers might screenshot the promo part (0:00-0:05) and share it as if it's real, accidentally spreading a fake-looking promo. Mitigation: ensure the "FAKE" reveal happens by second 5 — early enough that even short-view audiences see it. Also: the ad thumbnail/poster frame should show the "FAKE" stamp, not the clean promo.

### Variant C: "Stripped-Down Question"

**Concept:** A single static image. Minimal design. Just the question — no story, no escalation, no scam details. Tests whether the threat alone is enough.

**The Creative:**
- 1080x1080 (1:1)
- White background. Black text. Clean sans-serif.
- Center text:

```
If scammers can fake
one of the biggest brands
in the Philippines,

what's stopping them
from faking yours?
```

- Bottom corner: "Source: Verafiles fact-checked, confirmed fake."
- No imagery. No logo. No promo mockups.

**Why test this:** Sometimes the simplest creative wins. A plain-text question on a white background stands out in a feed full of colorful images and videos. The question is strong enough to carry itself. Zero production cost = can iterate instantly.

**Risk:** May look too plain and get ignored. White backgrounds can blend into Facebook's UI on desktop (though they pop on mobile dark mode). Test in parallel with the more produced variants.

## KPIs & Win Conditions

| Metric | Target | Notes |
|--------|--------|-------|
| **Thumb-stop rate** | >30% | This concept should thumb-stop higher than pure stat ads — it's a story about a recognizable scenario |
| **Video completion rate** (Variant B) | >40% | The bait-and-switch should keep people watching. Below 30% = the reveal is too slow |
| **Carousel swipe-through** (Variant A) | >35% to final slide | Higher bar than Ad 2 because the escalation is faster here |
| **Comment volume** | Track "tag a friend" comments | This ad should trigger "businesses need to see this" sharing behavior |
| **Share rate** | >0.8% of reach | Brand shock content should share higher than stat content |

**Winner definition:** Highest share-to-reach ratio with thumb-stop rate above 30%. This ad's job is to make business owners feel personally threatened and share the threat with peers.

## Copy Test — Closing Line

The current closer — "What's protecting YOUR business page right now?" — is effective but generic. Test a sharper, more confrontational replacement.

| Element | Variant A (current) | Variant B (recommended) |
|---------|--------------------|-----------------------------|
| **Closing line** | "What's protecting YOUR business page right now?" | "They have a full legal team. You have this ad." |

**Why test this:** The current closer is a question — it's open-ended and reflective. The recommended closer is a statement that creates immediate contrast and urgency. It also removes the "big brand = different problem" objection by making the gap between a major chain and a small business owner explicit. The self-referential meta-humor ("You have this ad.") is distinct — nothing else in the campaign sounds like this.

**Winner condition:** Higher comment volume and share rate. This line is designed to provoke a reaction ("wait, that's actually true") not just a click.

---

# AD 6: "Book Now, Fly Never" — Travel Scam Angle

## Current State

One treatment: video or animated text. Opens with travel destination shot, text overlay fades in. The trust-damage line (*"They don't just steal money. They steal your customers' confidence in you"*) anchors the body and the description slot.

## Hook Frame Variants (First 3 Seconds)

### Hook A: "The Tagline" (current)
- **Frame 1:** Beautiful travel destination shot. Text fades in: *"Book now, fly never."*
- **Why:** Opens with the most memorable line in the ad — rhythmic, emotionally precise, instantly understood
- **Risk:** The quote marks slightly distance the viewer. Some may not immediately register it as a threat

### Hook B: "The Trust Damage Lead"
- **Frame 1:** Clean dark frame. Text only: *"They don't just steal money. They steal your customers' confidence in you."*
- **Frame 2 (2s):** Scenic destination photo fades in underneath. Text shrinks to corner.
- **Why:** Leads with the insight that matters most to a travel business owner — not the crime, but the reputational consequence. More personally threatening than the stat
- **Risk:** Leads with a long line — 11 words before the visual hook. May lose fast scrollers

### Hook C: "The Stat as Proof"
- **Frame 1:** Dark background. "89 travel scam reports." — large, bold. Smaller below: "Jan–May 2025. GMA News."
- **Frame 2:** "And those are only the ones that got reported."
- **Why:** Opens with data credibility, then undermines it — the real number is worse. Classic fear escalation
- **Risk:** 89 is a small number compared to 423% and P480B used elsewhere. May feel less alarming in context

## Copy Test — Structure Reorder

The assessment identified that the current above-fold buries the strongest insight. Test reordering the copy so the trust damage line leads.

| Element | Variant A (current) | Variant B (trust-lead) |
|---------|--------------------|-----------------------|
| **Above fold** | *"Book now, fly never." 89 travel scam reports in 5 months — and those are only the ones that got reported. | The scammers don't just steal money. They steal your customers' confidence in you. Every fake travel page that uses your name costs you bookings you'll never know you lost. |
| **Tagline position** | Above fold, line 1 | Final line of below fold — the lasting impression |
| **Stat position** | Above fold, line 2 | Description field |
| **Description** | They steal your customers' trust. | 89 travel scam reports. Jan–May 2025. |

**Why test this:** "Book now, fly never" is the only line in the campaign that functions as a genuine tagline. Its power is its rhythm and specificity. As an opener, it works. As a closer — after the reader has processed the trust-damage consequence — it may land harder. The stat in the description tests whether data or emotion performs better as the Meta ad preview text.

**Winner condition:** Higher CTR from the trust-lead version would confirm the insight leads better than the tagline. Higher share rate = tagline position is correct.

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Video — Reveal** (current) | 4:5 feed + 9:16 Stories | Travel paradise → trust betrayal arc |
| **Static — Dark text card** | 1080x1350 (4:5) | *"Book now, fly never."* alone — full bleed text on dark travel photo background |
| **Animated text only** | 4:5 feed | Lines appear one at a time. No video. No photography. Just the words building. |

## KPIs & Win Conditions

| Metric | Target | Notes |
|--------|--------|-------|
| **Thumb-stop rate** | >30% | Travel visuals should stop thumbs — paradise imagery is inherently attention-grabbing |
| **CTR** | >1.8% | Travel audience is niche — higher CTR expected from narrower targeting |
| **Share rate** | >0.6% | Travel content shares well on Filipino Facebook (trip inspiration) |
| **Comment volume** | Track "this happened to us" responses | Validation signal — victims of travel scams should recognize and comment |

**Winner definition:** Highest CTR among the travel-targeted audience segment. For a niche-targeted ad, click-through matters more than broad reach metrics.

---

# AD 7: "Prevention vs. Prosecution" — Legal Process Pain

## Current State

One treatment: static split-screen (dark/red left = prosecution; light/green right = prevention). The rational-decision copy is strong. The visual direction is the clearest metaphor in the campaign.

## Hook Frame Variants (First 3 Seconds)

### Hook A: "The Choice" (current)
- **Frame 1:** Split-screen visual. Left: "Take down a fake page:" — 6-step bulleted list begins appearing. Right: "Prevent one:" — single step.
- **Why:** The visual asymmetry immediately communicates the core message without reading the copy
- **Risk:** Split-screen is complex for 3 seconds. Viewers may not process both columns before scrolling

### Hook B: "The Process Pain"
- **Frame 1:** Dark background. Text types out: "Step 1: Screenshot every post. Step 2: Report to Meta. Step 3: Wait 30 days…"
- **Frame 2:** Beat. "Or — one free verification that prevents it."
- **Why:** Making the victim feel the pain of the 6-step process before offering the solution. The contrast hits harder when you've experienced the frustration first
- **Risk:** Opens with the problem, not the solution. Some viewers may disengage before the payoff

### Hook C: "Your Call."
- **Frame 1:** Black screen. White text: *"Your call."*
- **Frame 2:** "6 steps to take down a fake page. Months of waiting. Or — one free verification that prevents it."
- **Why:** Leads with the challenge — puts the decision back on the viewer immediately. The minimalism is jarring after awareness ads full of data and stories
- **Risk:** No context. Viewers who haven't seen awareness ads won't know what "your call" refers to. Best used as a retargeting ad (which it is)

## Copy Test — Headline Clarity

The assessment flagged that "Prosecution" may read as unfamiliar in a small business context.

| Element | Variant A (current) | Variant B (plain language) |
|---------|---------------------|---------------------------|
| **Headline** | Prevention vs. Prosecution | Prevention vs. Filing a Complaint |

**Why test this:** "Prosecution" implies legal proceedings most small business owners have never initiated. "Filing a Complaint" is the language they actually use — it's what the DTI, NBI, and Meta all call it. Clarity wins over precision for this audience.

**Winner condition:** Higher CTR. If plain language outperforms, it confirms the audience responds better to familiar terms over accurate legal vocabulary.

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Static split-screen (current)** | 1080x1080 + 1080x1350 | Visual metaphor — red/green, complex/simple |
| **Short video — process build** | 4:5 feed | The 6 steps appear one by one (typewriter effect), then hard cut to the single prevention step |
| **Single static — "Your Call."** | 1080x1080 | Minimal. Just the two options in stark contrast. No color coding. |

## KPIs & Win Conditions

| Metric | Target | Notes |
|--------|--------|-------|
| **CTR** | >2.5% | Consideration audience is warm — higher CTR expected |
| **Cost per landing page view** | <P25 | This ad's job is to drive traffic, not just clicks |
| **Landing page conversion from this ad** | >12% | Consideration ads should convert at higher rates than awareness ads |

**Winner definition:** Lowest cost per landing page view. This is a traffic ad — clicks that don't reach the landing page are wasted spend.

---

# CROSS-AD TESTING NOTES

## Aspect Ratio Testing

Run each winning variant in both aspect ratios for 48 hours, then kill the underperformer:

| Placement | Test Ratios | Expected Winner |
|-----------|-------------|-----------------|
| Facebook Feed | 1:1 vs 4:5 | 4:5 (takes more screen real estate on mobile) |
| Instagram Feed | 1:1 vs 4:5 | 4:5 |
| Stories/Reels | 9:16 only | No test needed — 9:16 is the only option |
| Facebook Right Column | 1:1 only | No test needed |

**Exception:** Ad 7 (Prevention vs. Prosecution) — the split-screen format works best at 1:1. Don't test 4:5 for split-screen layouts.

---

# AD 11: "Your Page Looks Real. So Does Theirs." — Contrarian Hook

## Current State

One treatment: dark minimal static (1080x1080 + 1080x1350). Headline challenges the standard trust signals (likes, photos, reviews) that business owners think protect their customers.

## Hook Frame Variants (First 3 Seconds)

### Hook A: Statement (current)
- **Frame 1:** "Your Page Looks Real. So Does Theirs." — white text on dark background. No logo. No design element. Just the line.
- **Why:** Stops the scroll because it's addressed at the viewer ("your"), and the second sentence reframes their assumption into a threat
- **Risk:** Some viewers won't immediately know what "theirs" refers to — ambiguity could reduce click-through if not resolved fast enough

### Hook B: Question
- **Frame 1:** "Can Your Customers Tell the Difference?" — single line, dark background. Second frame reveals: "Between your real page and the fake one?"
- **Why:** Direct question pulls the viewer in. Forces them to mentally answer before they can scroll past
- **Risk:** Questions are softer than statements — may underperform against the more confrontational Hook A

### Hook C: The Parallel
- **Frame 1:** Two columns side by side. Left: "Your Page. 4,800 likes. Real reviews. Real photos." Right: "Their page. 4,800 likes. Real reviews. Real photos." Below: "Which one is yours?"
- **Why:** Visual demonstration of the parity makes the problem undeniable. High screenshot potential
- **Risk:** More complex first frame — requires more processing time at scroll speed

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Static dark minimal (current)** | 1080x1080 + 1080x1350 | Pure copy hook, no visual distraction |
| **Two-column static** | 1080x1350 (4:5) | Side-by-side page comparison (Hook C visual) |
| **15s motion — text reveal** | 4:5 feed | "Your page" lines build on screen, then "So does theirs" slams in |

**Hypothesis:** The motion text reveal will outperform static on thumb-stop rate (movement triggers attention). But the two-column static may outperform on shares because it's visually self-explanatory.

## KPIs

| Metric | Target | Kill Threshold |
|--------|--------|----------------|
| Thumb-stop (3s view rate) | >35% | <20% |
| CTR | >1.5% | <0.8% |
| CPM | <₱120 | >₱200 |
| Engagement (likes/comments/shares) | >3% | <1% |

---

# AD 12: "What Your Customers See Now" — Identity / Aspiration

## Current State

One treatment: before/after static (1080x1080 + 1080x1350). Left panel shows unverified page with doubt signal ("Is this real?"). Right panel shows verified page with badge. Targets warm retargeting audiences who are already problem-aware.

## Hook Frame Variants (First 3 Seconds)

### Hook A: The After-State (current)
- **Frame 1:** Right panel only — verified page with badge, headline: "Verified Businesses Close More." Clean, confident, green tones.
- **Why:** Lead with the outcome the audience wants, not the problem they're trying to avoid. Aspirational for retargeting audiences who already know the problem
- **Risk:** Warm audience still needs to make the connection — some may not immediately recognize the "verified" visual

### Hook B: The Before/After Split (current layout)
- **Frame 1:** Full before/after layout. Left: dark/unverified. Right: clean/verified. Text: "What Your Customers See Now."
- **Why:** Contrast is visually compelling. The split makes the value of verification immediately clear
- **Risk:** More complex frame — but warm audiences have more patience than cold

### Hook C: The Quote
- **Frame 1:** Fake customer message mockup — "Ate, ito ba talaga yung store niyo?" (Sister, is this really your store?) Below: "No more of this."
- **Why:** Taglish + real conversational format triggers instant recognition. Every Filipino business owner has received this message or knows someone who has
- **Risk:** Platform policy — message mockups must not look like actual Facebook UI

## Format Test Matrix

| Format | Specs | What You're Testing |
|--------|-------|-------------------|
| **Before/after static (current)** | 1080x1080 + 1080x1350 | Contrast-driven aspiration |
| **Single panel static — after only** | 1080x1350 (4:5) | Lead with the destination, skip the pain |
| **Quote card static** | 1080x1080 | Customer question mockup (Hook C) |

**Hypothesis:** For warm retargeting audiences, Hook C (the customer question) will outperform because it's directly relatable and not abstract. The before/after will work better for conversion retarget audiences who haven't yet been primed by consideration ads.

## KPIs

| Metric | Target | Kill Threshold |
|--------|--------|----------------|
| CTR | >2.5% | <1.5% (warm audience threshold is higher) |
| Cost-per-click | <₱15 | >₱30 |
| Cost-per-signup | <₱80 | >₱150 |
| Landing page conversion from this ad | >20% | <12% |

---

## Copy Length Testing

For each winning creative, test two copy variants:

| Variant | What | Why Test |
|---------|------|----------|
| **Full copy** (current) | Complete above-fold + below-fold text | Maximum context. Converts harder but at higher CPM |
| **Short copy** | Above-fold text only. No below-fold. | Tests if the creative carries the message without long copy. Lower commitment = potentially higher CTR |

## Audience × Creative Interaction

Don't assume the same creative wins across all audience segments. Run the winning creative from each ad against:

| Audience | Why It Might React Differently |
|----------|-------------------------------|
| Tourism/hospitality | Story ads (Ad 2, Ad 5) will likely resonate more than stat ads |
| All business owners 25-40 | Might prefer lo-fi/raw formats (younger, more social-media-savvy) |
| All business owners 41-55 | Might prefer polished/data formats (traditional media consumers) |
| Visayas geo-targeting | Ad 2 (Bantayan) will outperform — local relevance is a massive lever |

## Creative Fatigue Timeline

| Ad Type | Expected Fatigue Point | Action |
|---------|----------------------|--------|
| Static images | 7-10 days at >P500/day spend | Rotate to next variant |
| Short video (6-15s) | 10-14 days | Rotate or refresh end card |
| Long video (20s+) | 14-21 days | Rotate |
| Carousel | 10-14 days | Rotate lead slide first, then full rotation |

**Fatigue signals:** Frequency >2.5, CTR drops >20% week-over-week, CPM increases >30% at same budget.

When a creative fatigues, don't just turn it off — test the next variant from this document. The testing pipeline should always have the next variant ready before the current one fatigues.
