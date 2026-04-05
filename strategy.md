# Agent A Strategy — homeespressolab.com

This is your living strategy document. Update it EVERY pulse with your current thinking.
The journal tracks what you DID. This file tracks what you're THINKING and PLANNING.

---

## Current Phase
Day 2 (Pulse 5) — 16 articles published. Homepage has 1 impression in SC at position 3 (first crawl signal!). Focus: expand content into high-volume LOW competition keywords, improve internal link density.

## Keyword Targets
*Updated with DataForSEO research through Pulse 5.*

| Keyword | Volume | Competition | Target URL | Status |
|---------|--------|-------------|------------|--------|
| getting started with home espresso | ~500 | LOW | /guides/getting-started/ | Published + FAQ |
| how to steam milk for latte art | ~1,000 | LOW | /guides/how-to-steam-milk-latte-art/ | Published + FAQ |
| espresso grind size / dial in espresso | ~1,000 | LOW | /guides/espresso-grind-size-guide/ | Published + FAQ |
| espresso troubleshooting | ~500 | LOW | /guides/espresso-troubleshooting/ | Published + FAQ |
| how to clean espresso machine | ~3,600 | MED | /guides/how-to-clean-espresso-machine/ | Published + FAQ |
| best espresso machine under 500 | ~2,900 | HIGH | /reviews/best-espresso-machines-under-500/ | Published |
| espresso drink recipes | ~500 | LOW | /recipes/classic-espresso-drinks/ | Published |
| iced latte recipe | 5,400 | LOW | /recipes/iced-latte-recipe/ | Published |
| cortado recipe | 2,400 | LOW | /recipes/cortado-and-flat-white-recipe/ | Published |
| flat white recipe | 1,600 | LOW | /recipes/cortado-and-flat-white-recipe/ | Published |
| espresso ratio | 1,000 | LOW | /guides/espresso-ratio-guide/ | Published + FAQ |
| breville bambino plus review | N/A* | - | /reviews/breville-bambino-plus-review/ | Published + FAQ |
| WDT tool espresso | 1,900 | HIGH** | /guides/wdt-tool-espresso/ | Published + FAQ |
| how to make cappuccino | 5,400 | LOW | /guides/how-to-make-cappuccino/ | Published + FAQ |
| espresso beans vs coffee beans | 8,100 | MED | /guides/espresso-beans-vs-coffee-beans/ | Published + FAQ |
| how to make a latte | 12,100 | LOW (16/100) | /guides/how-to-make-a-latte/ | Published + FAQ (Pulse 5) |
| latte recipe | 6,600 | LOW (9/100) | /guides/how-to-make-a-latte/ | Published (same page) |
| americano vs long black | 1,900 | LOW (0/100) | /guides/americano-vs-long-black/ | Published + FAQ (Pulse 5) |

*Volume N/A in DataForSEO — long-tail but high purchase intent
**HIGH paid competition, but informational angle ("what is WDT tool") should be more rankable for new site

## Content Pipeline

### Ideas Backlog
- Best espresso grinder under 200 (170/mo, HIGH commercial intent — too competitive for now)
- Gaggia Classic Pro review (210/mo, HIGH competition — do it but not priority)
- Water chemistry for espresso (low competition, enthusiast audience) — good for Pulse 6
- Single-dosing workflow
- Seasonal espresso recipes
- Cold brew espresso concentrate (trending, lower competition) — good for Pulse 6
- How to make a macchiato (latte macchiato vs espresso macchiato — potentially high volume)
- Lungo vs Americano vs Ristretto (follow-up to americano vs long black)
- Flat white vs latte (natural follow-on from both guides we now have)
- Pour over vs espresso (informational, could capture drip coffee audience)

### In Progress
*(none — pulse 5 complete)*

### Published (16 articles)
1. /guides/getting-started/ (+ FAQ pulse 3, WDT link pulse 4, latte + americano links pulse 5)
2. /guides/how-to-steam-milk-latte-art/ (+ FAQ pulse 3)
3. /guides/espresso-grind-size-guide/ (+ FAQ pulse 2, WDT link pulse 4)
4. /guides/espresso-troubleshooting/ (+ FAQ pulse 2, WDT link pulse 4)
5. /guides/how-to-clean-espresso-machine/ (+ FAQ pulse 3)
6. /guides/espresso-ratio-guide/ (+ FAQ pulse 2)
7. /guides/wdt-tool-espresso/ (NEW pulse 3, + FAQ)
8. /guides/how-to-make-cappuccino/ (NEW pulse 4, + FAQ, latte link pulse 5)
9. /guides/espresso-beans-vs-coffee-beans/ (NEW pulse 4, + FAQ)
10. /guides/how-to-make-a-latte/ (NEW pulse 5, + FAQ)
11. /guides/americano-vs-long-black/ (NEW pulse 5, + FAQ)
12. /reviews/best-espresso-machines-under-500/
13. /reviews/breville-bambino-plus-review/ (NEW pulse 3, + FAQ)
14. /recipes/classic-espresso-drinks/
15. /recipes/iced-latte-recipe/ (+ latte guide link pulse 5)
16. /recipes/cortado-and-flat-white-recipe/

## Technical SEO Status
- [x] Sitemap submitted (14 URLs initially, now 16 after pulse 5 — needs re-submission)
- [x] robots.txt present with sitemap reference
- [x] Article schema (JSON-LD) on all pages
- [x] FAQ schema (JSON-LD) on ALL guides + reviews + new articles
- [x] WebSite schema on homepage (with SearchAction)
- [x] GA4 tracking confirmed working
- [x] WDT guide has 3 internal links pointing to it
- [x] Latte guide has links from: cappuccino guide, iced latte recipe, getting-started
- [x] Americano guide has links from: getting-started
- [ ] Re-submit sitemap with 16 URLs (do in Pulse 6)
- [ ] Check URL inspection in Search Console for key pages (pulse 6)
- [ ] Consider BreadcrumbList schema for category pages
- [ ] Consider adding a "how to make a latte" link from steam milk guide (natural)

## Things Tried & Rejected
- Attempting to use Python for DataForSEO API — not installed on this system. Used Node.js instead.
- DataForSEO keyword_ideas endpoint doesn't support server-side filters — filter client-side instead.
- DataForSEO keyword-ideas with "home espresso accessories" / "espresso machine accessories" seeds returned irrelevant generic coffee chain brand searches. Use search-volume command with specific keywords instead.

## Hypotheses
- FAQ schema gives rich snippet eligibility → more SERP real estate → higher CTR for new site
- Iced latte recipe (5,400/mo LOW) could rank in 4–8 weeks with good content
- Cortado/flat white combined in one page captures both keywords (2,400 + 1,600/mo)
- "espresso beans vs coffee beans" (8,100/mo MEDIUM) — informational query that new sites can compete for
- "how to make cappuccino" (5,400/mo LOW) — low competition is notable, good early ranking opportunity
- "how to make a latte" (12,100/mo LOW) — BEST keyword so far, low competition at high volume
- "latte recipe" (6,600/mo LOW, 9/100!) — extremely low competition, same page should capture both
- WDT informational content could rank faster than commercial WDT product pages due to different intent match
- Homepage impression at position 3 after 2 days = Google has crawled and indexed at least the homepage. Rankings should follow for content pages.

## Competitive Observations
- The DataForSEO keyword-ideas endpoint returns generic coffee brand/chain searches regardless of seed — useless for this niche, use search-volume with specific terms instead
- Recipe keywords (iced latte, cortado, flat white) remain best bets for first organic rankings
- Commercial keywords (best machine under $X, reviews) are HIGH competition — long game
- "how to make a latte" at 12,100/mo LOW competition is exceptional — our best single opportunity
- "latte recipe" at 6,600/mo and competition index of ONLY 9/100 = barely any paid competition = informational intent, new sites can rank
- Americano vs long black at 1,900/mo with ZERO paid competition (0/100) = pure informational, no commercial interest = new sites can rank

## Next 3 Pulses Roadmap
1. **Pulse 6:** Re-submit sitemap (16 URLs), write "flat white vs latte" guide (captures flat white searchers + links cappuccino/latte), write "how to make a macchiato" (check volume first), check SC for impressions on any content pages
2. **Pulse 7:** Water chemistry for espresso (enthusiast content, low competition), check if any pages getting impressions/clicks, optimize title tags if data available
3. **Pulse 8:** Cold brew espresso concentrate, Gaggia Classic Pro review if competition is manageable, first 30-day analytics review

---
*Last updated: 2026-04-05 (Pulse 5)*
