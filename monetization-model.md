# Monetization Model: STACKRIFT
*Hybrid Monetization Strategy*

---

## Philosophy

STACKRIFT uses a **hybrid monetization model** — the industry-validated approach that combines advertising revenue, in-app purchases, and optional subscriptions. This model reflects market reality: pure ad-based hyper-casual LTV (~$2.80) cannot sustain profitable UA at current CPIs ($1.50–$2.50). The hybrid model targets a blended LTV of **$5.50–$8.00**, creating the necessary margin for scaled user acquisition.

The guiding principles are:
- **Never block progress behind a paywall.** All levels and core gameplay are free.
- **Sell convenience and cosmetics, not power.** IAP purchases must not create a P2W dynamic.
- **Ads serve the player.** Rewarded ads are opt-in and tied to meaningful rewards.

---

## Revenue Streams

### Stream 1: Rewarded Video Ads (Primary — Free Users)
Rewarded video is the backbone of free-user monetization. Players opt in to watch a 15–30 second ad in exchange for:
- Continuing after a failed run (one "Rift Revive" per level)
- Doubling end-of-level Rift Shard rewards
- Unlocking a bonus "Mystery Block" power-up for the next run

**Target metrics:**
- Rewarded ad impressions per DAU: 3–5
- eCPM (US, iOS): $20–$35
- eCPM (Tier 2 geos): $5–$12
- Estimated ad ARPDAU: $0.08–$0.15

Mediation stack: Google AdMob + Meta Audience Network + ironSource, managed via MAX (AppLovin) to optimize fill rates and eCPM in real time.

### Stream 2: Interstitial Ads (Secondary — Free Users)
Non-skippable interstitials are shown at natural session break points only:
- Between Zone transitions (not between individual levels)
- After every 5 level completions
- On app re-open after 2+ hours

Frequency cap: **maximum 4 interstitials per session**. Capping is critical — excessive interstitials are the #1 driver of uninstalls in casual games.

**Target metrics:**
- Interstitial eCPM (US): $8–$15
- Contribution to ARPDAU: $0.03–$0.06

### Stream 3: In-App Purchases (Monetization Depth)

#### a) Starter Pack (First-Purchase Offer)
A time-limited (72-hour) offer shown to new players after Level 10 completion:
- **Price: $2.99**
- Contents: 3× Rift Shard boost (1 week), 1 exclusive character skin, 500 bonus shards
- Target conversion: 8–12% of engaged players (D3+ who reached Level 10)

#### b) Shard Bundles (Progression Currency)
| Bundle | Price | Shards | Effective Rate |
|---|---|---|---|
| Handful | $0.99 | 300 | Baseline |
| Pouch | $2.99 | 1,100 | +22% bonus |
| Chest | $7.99 | 3,500 | +46% bonus |
| Vault | $19.99 | 10,000 | +67% bonus |

Shards are used to accelerate Rift Codex progression. Prices set at Apple / Google recommended price points for strong conversion.

#### c) Cosmetic Shop
Direct-purchase cosmetics with no shard intermediary — for players who want to bypass the currency layer:
- Character skins: $1.99–$4.99
- Portal effect packs: $0.99–$2.99
- Block trail effects: $1.99
- Zone-themed UI themes: $2.99

New cosmetic bundles introduced with each Season / Zone drop (every 6–8 weeks).

#### d) No-Ads IAP
- **Price: $3.99 (one-time) or $1.99/month**
- Removes all interstitial ads permanently; rewarded ads remain opt-in
- Targets players who engage daily but find ads disruptive
- Expected conversion: 3–5% of DAU within 90 days

### Stream 4: Rift Pass (Battle Pass — Season Revenue)
Launched at Month 10, the Rift Pass is a 6-week seasonal content subscription:

| Tier | Price | Contents |
|---|---|---|
| Free Track | $0 | Basic rewards at each level milestone |
| Rift Pass | $4.99/season | 2× shard rewards, exclusive seasonal skin set, animated profile frame, 1 bonus Zone chapter |
| Rift Pass + | $9.99/season | All above + 10-level head start, Discord badge |

**Targets:**
- Battle pass conversion: 5–8% of MAU
- Retention uplift: Battle pass holders show 35–45% higher D30 retention (industry benchmark)
- Contribution to monthly revenue: 20–25% at maturity

---

## Revenue Model Summary

### Year 1 Projections (Post-Global Launch, Month 8 Onward)

Assumptions: 500K DAU at Month 12, blended ARPDAU of $0.18

| Revenue Stream | % of Total | Monthly Revenue (M12) |
|---|---|---|
| Rewarded Video Ads | 40% | $36,000 |
| Interstitial Ads | 20% | $18,000 |
| IAP (packs + cosmetics) | 25% | $22,500 |
| No-Ads Subscription | 5% | $4,500 |
| Rift Pass | 10% | $9,000 |
| **Total** | **100%** | **~$90,000/month** |

*Conservative scenario. Scales linearly with DAU growth.*

### LTV Model

| User Segment | % of Players | Avg LTV (12-month) |
|---|---|---|
| Ad-only (free, churns by D30) | 65% | $1.20 |
| Engaged free (D30+, rewarded ads) | 20% | $4.80 |
| Light spender (1–2 IAP) | 10% | $12.00 |
| Mid spender (Rift Pass + bundles) | 4% | $38.00 |
| Whale (recurring IAP + cosmetics) | 1% | $120.00+ |
| **Blended LTV** | **100%** | **~$6.20** |

With a target CPI of $1.50 (Android) and $2.50 (iOS), the blended LTV of $6.20 yields a **LTV:CPI ratio of 2.5–4.1×** — above the 2× minimum required for sustainable scaled UA spend.

---

## Monetization Risk & Mitigation

| Risk | Mitigation |
|---|---|
| Ad eCPMs decline in Tier 2 geos | Prioritize US/UK/DE installs in UA; diversify with IAP depth |
| IAP conversion below target | A/B test price points at soft launch; optimize starter pack timing |
| Battle pass fatigue | Keep pass to 6-week cycles; ensure free track is genuinely rewarding |
| iOS ATT limits ad targeting | Build SKAdNetwork campaigns; invest in owned channels (push, email) |
| Whale concentration risk | Diversify mid-tier spending options; avoid over-reliance on top 1% |

---

## Benchmarks vs. Industry

| Metric | STACKRIFT Target | Hybrid-Casual Industry Avg |
|---|---|---|
| Blended LTV (12-month) | $6.20 | $4.50–$7.00 |
| IAP Conversion (D30) | 4–5% | 3–6% |
| ARPDAU | $0.18 | $0.12–$0.22 |
| Battle Pass Conversion | 5–8% | 4–9% |
| LTV:CPI | 2.5–4.1× | 2–4× |

All targets are within industry benchmarks, with upside from strong D7/D30 retention driven by the meta-game layer.
