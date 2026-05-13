---
title: "Espresso Extraction Time: How Long Should a Shot Take and Why the Clock Lies"
date: 2026-05-13
description: "How long should an espresso shot take, where the clock actually starts, why time alone is a bad target, and how to read pre-infusion, channeling, and roast-specific timing windows. Complete extraction-time playbook for home baristas."
tags: ["espresso extraction", "espresso shot time", "pre-infusion", "channeling", "extraction theory", "home barista", "espresso troubleshooting"]
categories: ["guides"]
author: "Home Espresso Lab"
showToc: true
TocOpen: false
draft: false
faq:
  - question: "How long should an espresso shot take?"
    answer: "25 to 32 seconds for a standard 1:2 ratio double shot (18g in, 36g out) on a medium-roast blend. Start counting from when you press the brew button on a machine without programmable pre-infusion; if your machine has a separate pre-infusion phase, start from when the first drop hits the cup. The 25–32s window is a starting target, not a hard rule — yield in grams matters more than seconds on the clock, and lighter roasts can pull beautifully at 30–38 seconds while traditional dark Italian roasts can pull at 22–28 seconds. Use time to diagnose flow, not to decide when to stop."
  - question: "When does the espresso shot timer start?"
    answer: "Two valid conventions exist and you have to pick one and stick with it. (1) Press-to-pour: start the timer when you press the brew button. This includes pre-infusion in the shot time. Standard for Breville, Gaggia, De'Longhi consumer machines. (2) First-drop: start the timer when the first drop of espresso falls into the cup. This excludes pre-infusion. Standard for La Marzocco, professional cafés, and most barista training. The 25–32s window references the first convention; if you measure first-drop, subtract 5–10 seconds and target 20–27 seconds."
  - question: "What is pre-infusion and how long should it last?"
    answer: "Pre-infusion is a low-pressure (1–3 bar) wetting phase before the full 9-bar extraction begins. It saturates the puck evenly so the coffee bed swells uniformly and the high-pressure phase pushes water through with minimal channeling. Target 4–8 seconds of pre-infusion for medium roasts at 18g doses. Lighter and more dense roasts need 8–12 seconds. Dark, oily, soft roasts need 2–4 seconds — over-pre-infusion can dissolve the puck before pressure reaches it. If your machine doesn't have programmable pre-infusion, the natural ramp-up of a vibe pump (2–3 seconds) functions as a passive pre-infusion."
  - question: "What is espresso channeling and how do I spot it from shot time?"
    answer: "Channeling is when water finds a low-resistance path through the puck and shoots through that one spot instead of extracting evenly. The shot-time signature: extraction starts very fast (first drop under 5 seconds), the stream is wild and uneven (spurts, side jets, donut pours), the shot finishes in 18–22 seconds instead of 27, and the cup tastes sour AND bitter at the same time — the under-extracted channels release acidity while the over-extracted dry zones release bitterness. Confirmation: pull the next shot with a bottomless portafilter. If you see streams shooting from one corner or a fast spurt early on, you're channeling. Fix with WDT distribution and a level tamp."
  - question: "Why does my espresso shot finish in 15 seconds?"
    answer: "Three causes ranked by likelihood. (1) Grind too coarse — go 2–3 increments finer and retry. (2) Channeling masking what would otherwise be a slower shot — see the channeling answer above. (3) Dose too low — under 17g in a double basket leaves the puck loose, water finds easy paths, the shot blows through fast and weak. Diagnostic: a 15-second shot with the right yield (36g out) and the right taste means your grind was right and you just had channeling. A 15-second shot with high yield (45g+) and watery taste means the grind is wrong."
  - question: "Why does my espresso shot take 45 seconds?"
    answer: "Three causes ranked by likelihood. (1) Grind too fine — go 2–3 increments coarser. The puck is choking the machine; pressure builds to 12+ bars and water barely seeps through. (2) Dose too high — over 20g in a 18g basket compresses the puck so tight that flow is permanently slow regardless of grind. Drop 1–2 grams. (3) Tamp pressure too aggressive on top of an already-fine grind — though most home machines max out around 30 lbs of tamp force without noticeably extending shot time, the combined effect with a fine grind can stretch shots past 40 seconds. Fix grind first, dose second, tamp last."
  - question: "Does shot time vary by roast level?"
    answer: "Yes, substantially. Dark Italian-style roasts (Lavazza Crema e Gusto, Illy Dark) pull at 22–28 seconds because the beans are porous, soft, and degas fast. Medium roasts (most American 'espresso blends', most Starbucks, most supermarket espresso) pull at 25–32 seconds — the canonical window. Medium-light to light roasts (most specialty coffee from Counter Culture, Onyx, Heart) pull at 30–38 seconds because the beans are dense, less porous, and resist flow at typical grinds. White espresso roasts pull at 35–45 seconds — the densest beans on the market. If you're getting 45 seconds on a Lavazza dark roast something is wrong; if you're getting 25 seconds on a light Ethiopian specialty roast you're probably under-extracting."
  - question: "Should I use time or yield to decide when to stop the espresso shot?"
    answer: "Yield. Always yield. The clock is a diagnostic readout, not a stop signal. Set your scale to target yield (36g for a 1:2 ratio on an 18g dose) and stop at yield regardless of what the clock says. If 36g hits at 22 seconds, the shot is probably fast — re-dial. If 36g hits at 38 seconds, the shot is probably slow — re-dial. But the cup is correct at yield, not at a target time. Time tells you what's happening with the puck; yield tells you what's in the cup."
  - question: "How long should a single espresso shot take vs a double?"
    answer: "Roughly the same time, despite half the coffee and half the water. A single shot (7–9g in, 14–18g out) on a properly-sized single basket pulls at 22–30 seconds because the puck depth is similar (single baskets are narrower and roughly the same depth as a double basket). Most home machines have only double baskets; pulling 'a single' from a double basket is actually a starved shot and will pull much faster (12–18 seconds) and taste thin. If you want a true single shot, buy a single basket — don't half-dose the double basket."
  - question: "What does a perfectly timed espresso look like as it pours?"
    answer: "The first drop appears at 6–10 seconds (or right at the start if you start from first-drop). Drops form a quick patter for 2–3 seconds, then merge into a thin steady stream the color of warm honey. The stream thickens to a tiger-striped reddish-brown by 12–15 seconds — this is peak extraction. Around 22–25 seconds the stream lightens to a pale tan, the so-called 'blonding' moment. Stop at yield or just before significant blonding. If you watch the bottomless portafilter, the stream emerges from the center of the basket and stays centered through the whole shot — no side jets, no spurts, no donuts."
---

Espresso extraction time is the most over-cited and most misunderstood number in home barista practice. Everyone repeats "25–30 seconds" like a magic formula, and yet half of bad home shots time perfectly in that window. The clock is a diagnostic tool — it tells you what's happening to the puck under pressure — not a recipe step. This guide covers what shot time actually measures, where the clock should start, why pre-infusion changes everything, how to spot channeling from timing patterns alone, and the roast-by-roast windows that the standard 25–32 second answer never mentions.

If you're still building the four-lever foundation, the [dial-in walkthrough](/guides/how-to-dial-in-espresso/) covers the full grind/dose/yield/time loop, and the [espresso ratio guide](/guides/espresso-ratio-guide/) covers the math of where 36g of yield comes from in the first place. This guide is the deep dive on the *time* lever — what it reads, what it lies about, and how to use it.

## Quick Answer Table

| Shot description | Target time | Where the clock starts | When to deviate |
|---|---|---|---|
| Standard 1:2 medium roast (18g → 36g) | 25–32 seconds | Press-to-pour | Yield is correct → trust time |
| Light specialty / white espresso (18g → 36g) | 32–42 seconds | Press-to-pour | Lighter roasts run slow at the same grind |
| Dark Italian (18g → 36g) | 22–28 seconds | Press-to-pour | Dark roasts run fast at the same grind |
| Single from single basket (9g → 18g) | 22–30 seconds | Press-to-pour | Same time, half the volume |
| Ristretto (18g → 18g, 1:1) | 18–24 seconds | Press-to-pour | Stop early at yield, see [ristretto vs espresso](/guides/ristretto-vs-espresso/) |
| Lungo (18g → 54g, 1:3) | 35–45 seconds | Press-to-pour | Yield is the stop, not the clock |

## Where the Clock Starts: The Two Conventions

Half the disagreements about espresso shot time are people using different start points without realizing it. There are two valid conventions:

**Press-to-pour timing.** Start the timer the moment you press the brew button. The clock includes the pump ramping up, the puck wetting, the pre-infusion phase (if any), and the full extraction. This is what consumer machine manuals (Breville, Gaggia, De'Longhi, Sage) reference when they cite "27 seconds". It's the most repeatable home convention because home machines vary wildly in how much pre-infusion they add — measuring press-to-pour bakes that variation into a single number.

**First-drop timing.** Start the timer the moment the first drop of espresso falls into the cup. The clock measures only the high-pressure extraction phase, after the puck is fully saturated. This is the convention used in most café and barista training contexts, La Marzocco's documentation, the Specialty Coffee Association curriculum, and most professional dial-in protocols. First-drop timing is more comparable across machines because it isolates the extraction itself from the wetting phase.

**The 5–10 second difference.** First-drop typically falls at the 6–10 second mark on a machine with passive pre-infusion (vibe pump ramp-up). On a machine with programmed pre-infusion (Lelit, Profitec, La Marzocco Linea Mini), first-drop can be as late as 12–15 seconds. So a press-to-pour shot at 28 seconds is roughly a first-drop shot at 18–22 seconds. Both numbers describe the same shot.

**Pick one and write it down.** If you're following someone else's recipe ("18g in, 36g out, 27 seconds"), find out which convention they used or you'll be chasing a shot time that doesn't apply to your start point. Most home content uses press-to-pour by default; most café and SCA content uses first-drop.

## What Shot Time Actually Measures

Shot time is a downstream readout of upstream variables. It is a number that tells you what's happening to the puck under pressure — it does not, by itself, tell you whether the shot will taste good. Three other variables determine taste: yield (grams in the cup), extraction yield (% of the dry coffee mass dissolved into the cup), and flavor balance.

What time *does* measure reliably:

| What time tells you | What time does not tell you |
|---|---|
| Whether flow rate is in the expected range for your grind | Whether the cup tastes balanced |
| Whether channeling is likely (shots ending early but with right yield) | Whether yield hit target |
| Whether the puck is choking (shots over 45s with low yield) | Whether the roast level matches the time window |
| Whether pre-infusion is doing its job (when first drop appears) | Whether the temperature was right |

Use time as a fast diagnostic — it's the easiest variable to measure mid-shot — and use yield + taste as the verdict on whether the shot was correct.

## The Pre-Infusion Phase: Where Time Bends

Pre-infusion is a low-pressure (typically 1–3 bar) wetting phase before the full 9-bar extraction begins. The pump pushes a small volume of water into the puck slowly, the coffee bed absorbs water and swells, channels in the dry bed close as grounds expand, and the puck becomes uniformly saturated.

Why pre-infusion matters for shot time: it changes when the clock should start and how long the high-pressure phase actually runs. Without pre-infusion, water hits a dry puck at 9 bars and channels are pre-formed before pressure stabilizes. With pre-infusion, the high-pressure phase finds an even, swollen, fully-wetted puck that resists evenly.

**Pre-infusion windows by roast:**

| Roast level | Pre-infusion time | Why |
|---|---|---|
| Dark, oily, soft (Italian, French, espresso roast) | 2–4 seconds | Beans are porous, absorb water fast, over-PI dissolves the puck before pressure reaches it |
| Medium-dark (Lavazza Crema e Gusto, most "espresso blend") | 4–7 seconds | The canonical window for the canonical roast |
| Medium-light (third-wave omni-roasts, most American specialty) | 6–10 seconds | Denser beans, slower water uptake |
| Light specialty (single-origin Ethiopian, Kenyan) | 8–12 seconds | Very dense beans, need extended wetting before pressure |
| White espresso (under-roasted) | 12–18 seconds | The densest beans on the market — see [white espresso guide](/guides/white-espresso/) for full window |

**If your machine has no programmable pre-infusion**, the vibe pump's natural ramp-up (2–3 seconds before reaching full pressure) acts as a passive pre-infusion. It's enough for dark and medium-dark roasts and marginal for medium-light. Lighter roasts on no-PI machines often need a workaround: pause the shot for 5–10 seconds after the first 5–10 ml of water enters the puck, then resume. Breville Bambino, Gaggia Classic Pro Mod, and rotary-pump enthusiast machines all benefit from a manual paddle-style PI when used with lighter roasts.

## Channeling: What Shot Time Reveals About the Puck

Channeling is the most common reason a shot times in the "right" window but tastes wrong. Water finds a low-resistance path through the puck and shoots through one spot instead of extracting the whole bed evenly. The result: some coffee is over-extracted into bitterness, some is under-extracted into sourness, and the cup contains both at once — the classic "sour and bitter at the same time" taste signature.

**Time signatures of channeling:**

| Time pattern | What it means |
|---|---|
| First drop in 3–5 seconds, shot finishes at 22 seconds with 36g yield | Likely channeling. The fast first drop and fast finish despite normal yield = water found one path |
| First drop in 5–8 seconds, shot at 28 seconds with 36g yield, even stream | Healthy shot, no channeling |
| First drop in 5–8 seconds, shot at 28s but yield is 45g (over) | Possible end-shot channeling — flow accelerated after blonding started |
| First drop in 12+ seconds, shot at 40+ seconds with 36g yield | No channeling, just a slow puck — likely grind too fine or roast too dense |
| Stream spurts mid-shot, ends at 24 seconds, yield 38g | Channeling visible. Mid-shot pressure release through a crack |

**Visual confirmation requires a bottomless portafilter.** With a bottomless basket, channeling shows as side jets shooting from the edges of the puck, a donut pour (extraction only around the rim), or a single fast stream from one quadrant while the rest of the puck stays dry. Without a bottomless, the spouted portafilter hides everything — you're inferring from time alone. A bottomless portafilter is $35–50 and is the single most useful diagnostic upgrade in home espresso.

**Fixes for channeling**, in order:

1. **Distribution.** Use a WDT (weiss distribution technique) tool — 5–10 thin needles you swirl through the dose in the basket to break up clumps and even the bed. $15. Cuts channeling roughly in half on most setups.
2. **Level tamp.** Use a calibrated tamper or a self-leveling tamper. A 2-degree tilt in the tamp creates a thinner zone the water finds in milliseconds.
3. **Puck screen.** A puck screen on top of the basket distributes water more evenly from the dispersion plate. $15.
4. **Dose reduction.** Over-dosing into a tight headspace creates compaction inconsistencies and channels.

See the [grinder cleaning guide](/guides/how-to-clean-coffee-grinder/) for the upstream cause that creates most channeling — boulder clumps from a dirty grinder hitting the basket and creating low-resistance pockets.

## The Four Signals: What to Read During the Shot

A dialed-in shot gives you four readouts. Read them in this order:

**1. First drop time.** The most reliable early signal.

- 4–6 seconds: probably channeling, or very dark roast, or very coarse grind
- 6–10 seconds: healthy on most setups
- 10–15 seconds: tight grind, dense roast, or programmed pre-infusion working as intended
- 15+ seconds: choked or extended pre-infusion programmed

**2. Stream pattern.** Watch the stream from the spouts (or, with a bottomless, from the basket bottom).

- Thin patter for 1–2s, merging into a steady honey-thin stream: healthy
- Spurts, side jets, donut: channeling
- A single thick "rope" emerging from the start: very fine grind, very dense puck
- Foamy droplets only, no continuous stream: too coarse, no extraction

**3. Stream color over time.** A proper shot is a color gradient.

- Seconds 0–3: clear water or pale tan (first drop)
- Seconds 3–10: golden honey
- Seconds 10–20: tiger-striped reddish-brown (peak extraction, peak crema)
- Seconds 20–30: lightening to pale tan or straw color (blonding starts)
- Seconds 30+: pale yellow to clear (over-extraction territory)

The moment the stream visibly lightens to straw color is **blonding** — extraction has moved past the soluble sweet/aromatic compounds and into bitter/astringent. Most clean shots stop at or just before blonding.

**4. Yield + total time.** The cup verdict.

If yield hits target at the expected time window and the cup tastes balanced, the shot is dialed. If yield hits target outside the window, the grind needs adjustment but the cup may still taste fine. If yield is wrong, the shot is wrong regardless of time.

## Roast-by-Roast Timing Windows

The 25–32 second answer assumes a medium roast — the most common espresso blend roast level in the world. Other roast levels have different windows, and applying the medium-roast number to a light or dark roast will give bad shots.

**Dark Italian / espresso roast** (Lavazza Crema e Gusto, Illy Dark, Caffè Vergnano dark blends):

- Press-to-pour: 22–28 seconds
- First-drop: 18–22 seconds
- Pre-infusion: 2–4 seconds
- Why faster: porous, brittle, oily beans — water moves through them easily and extracts quickly. Pushing a dark roast to 30+ seconds produces ash and bitterness.

**Medium roast** (most American "espresso blends", Starbucks Espresso Roast, Peet's Major Dickason — when used for espresso, most supermarket "espresso" coffees):

- Press-to-pour: 25–32 seconds
- First-drop: 20–25 seconds
- Pre-infusion: 4–7 seconds
- The canonical window. The 25–30s rule was designed around this roast level.

**Medium-light / third-wave omni-roast** (Stumptown Hair Bender, Intelligentsia Black Cat, Counter Culture Hologram):

- Press-to-pour: 28–35 seconds
- First-drop: 22–28 seconds
- Pre-infusion: 6–10 seconds
- Slightly denser beans, slightly slower extraction.

**Light specialty single-origin** (most Counter Culture single-origins, Onyx geographies, Heart single-origins, light Ethiopian/Kenyan/Colombian):

- Press-to-pour: 30–38 seconds
- First-drop: 24–32 seconds
- Pre-infusion: 8–12 seconds
- Dense, retains structure, needs longer wetting and longer extraction to develop sweetness.

**White espresso** (under-roasted, see [white espresso guide](/guides/white-espresso/)):

- Press-to-pour: 35–45 seconds
- First-drop: 28–36 seconds
- Pre-infusion: 12–18 seconds
- The densest commonly available espresso beans. White espresso is the edge case where most home machines need active pre-infusion or paddle assistance to get a decent shot.

## Equipment-Specific Shot Time Considerations

Shot time depends on the machine as well as the bean. Here's what to expect across common home setups.

**Breville Bambino / Bambino Plus.** Passive 8-second auto pre-infusion at low pressure, then 9-bar extraction. Press-to-pour shots on this machine target 32–38 seconds because of the long pre-infusion. First-drop at 8–10 seconds is normal. The pre-infusion is non-programmable but the natural ramp matches medium roasts well.

**Gaggia Classic Pro.** No programmed pre-infusion — passive vibe pump ramp (2–3 seconds) only. Press-to-pour and first-drop almost converge. Target 24–28 seconds press-to-pour for medium roasts. Mod options (PID, OPV adjustment) don't significantly change shot time at the same grind.

**Breville Dual Boiler / Oracle.** Programmable pre-infusion. Default settings give 4–6 second pre-infusion. Press-to-pour at 28–32 seconds for medium roasts. The DB allows extending PI to 12+ seconds for light roasts, which is one of its biggest practical advantages.

**Lelit Mara X / Bianca / La Marzocco Linea Mini.** Saturated groups, paddle or rotary pre-infusion, programmable extended PI. Use first-drop timing as the primary signal on these machines because press-to-pour can stretch 35–45 seconds while the actual extraction is healthy.

**De'Longhi Dedica / Stilosa / EC685.** Vibe pump, no programmed PI, 15-bar pump (over-pressured). These machines often run shots in 18–25 seconds and produce thinner crema because of the over-pressure. Time is less reliable as a signal — focus on yield and taste.

**Manual lever espresso (Flair, Cafelat Robot).** You control pressure manually. Pre-infusion can be 10–30 seconds depending on how you handle the lever. Press-to-pour timing doesn't apply — time only the high-pressure phase, and target 12–25 seconds for the pressure phase plus whatever PI you chose.

## When to Break the 25–32 Second Rule

The 25–32 second window is a starting target for one specific configuration: an 18g dose, a 1:2 ratio, a medium roast, and a standard double basket. Step outside that configuration and the window moves.

**Ristretto (1:1 ratio).** Stop the shot early at half the yield. Time falls to 18–24 seconds press-to-pour. See the [ristretto vs espresso comparison](/guides/ristretto-vs-espresso/) for the full ratio-to-time mapping.

**Lungo (1:3 ratio).** Pull longer for more volume. Time stretches to 35–45 seconds. The cup is more extracted, more bitter, and more astringent — most home baristas prefer americanos (espresso + water) to true lungos for that reason.

**Light specialty single-origin.** Extend to 30–38 seconds at the same yield. Going long with light coffee is part of unlocking the sweetness; cutting at 27 seconds leaves the shot sour and thin.

**Updosing (20g+ in an 18g basket).** Stretches shot time roughly 1 second per gram added because of the tighter puck and lower headspace. A 21g dose in an 18g basket typically times at 30–35 seconds at the same grind.

**Smaller basket (e.g. 14g basket).** Reduces all the numbers proportionally. A 7g single in a 14g basket times similarly to a 14g double in a 18g basket on the same machine: 22–28 seconds.

## Common Mistakes That Distort Shot Time

**Counting from the wrong start.** Half of bad home shot-time data is people switching conventions mid-week — measuring press-to-pour Monday and first-drop Wednesday. Pick one convention, write it on the machine in tape, never deviate.

**Stopping at time instead of yield.** Pulling to 27 seconds regardless of yield gives wildly inconsistent shots. A 27-second shot at 30g out is over-concentrated and sharp; a 27-second shot at 45g out is over-extracted and bitter. Always stop at yield.

**Comparing shots across grinders.** Two grinders at the same nominal setting produce different particle distributions and different shot times. Settings transfer poorly — you have to dial each grinder independently.

**Mixing roast levels and applying one timing rule.** Most home baristas have 2–3 bags of coffee open at once at different roast levels. Each one needs its own timing window. Treat each bag as a fresh dial-in.

**Ignoring temperature drift.** A cold machine on its first shot of the day extracts slower than a fully heated machine on the third shot. First-shot time can be 3–5 seconds longer than fourth-shot time at the same grind. Flush 5 seconds of water through the group before the first shot to reduce this drift.

## How to Use Shot Time in Daily Practice

A short loop for using time correctly:

1. **Set the convention.** Press-to-pour or first-drop. Write it on the machine.
2. **Set the yield target.** 1:2 ratio for medium roasts. Adjust for the roast level.
3. **Pull the shot, stop at yield, read the clock as a diagnostic.**
4. **If yield landed in the time window and the cup tastes balanced**: done. Same grind tomorrow.
5. **If yield landed outside the time window**: adjust grind one increment in the direction the time tells you (long time = coarser, short time = finer). Same yield target tomorrow.
6. **If the cup tastes bad despite landing in the time window**: time isn't the problem. Look at distribution (channeling), water, temperature, or roast.

The goal is to use time as one of four signals, not as the destination. The destination is the taste in the cup; the clock is one of four instruments that told you how the puck behaved getting there.

## Related Guides

The other levers and contexts for shot time:

- **[How to Dial In Espresso](/guides/how-to-dial-in-espresso/)** — the full grind/dose/yield/time loop and the 4-shot dial-in protocol.
- **[Espresso Grind Size Guide](/guides/espresso-grind-size-guide/)** — the most powerful lever for changing shot time.
- **[Espresso Ratio Guide](/guides/espresso-ratio-guide/)** — where the yield target comes from and how to set it for each roast.
- **[Water for Espresso](/guides/water-for-espresso/)** — water mineral content affects extraction rate independent of grind.
- **[How to Clean Coffee Grinder](/guides/how-to-clean-coffee-grinder/)** — grinder boulders cause most channeling and most shot-time drift.
- **[White Espresso Guide](/guides/white-espresso/)** — the longest shot-time window on the spectrum.
- **[Ristretto vs Espresso](/guides/ristretto-vs-espresso/)** — same four levers, different stop point.
- **[Espresso Troubleshooting](/guides/espresso-troubleshooting/)** — taste-based diagnosis when shot time looks right.
