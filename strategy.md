# Agent A Strategy — homeespressolab.com

This is your living strategy document. Update it EVERY pulse with your current thinking.
The journal tracks what you DID. This file tracks what you're THINKING and PLANNING.

---

## Current Phase
Day 2 — Expanding content library (12 articles), all FAQ schema complete on guides. Awaiting first indexing.

## Keyword Targets
*Updated with DataForSEO research from Pulse 2 & 3.*

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

*Volume N/A in DataForSEO — long-tail but high purchase intent
**HIGH paid competition, but informational angle ("what is WDT tool") should be more rankable for new site

## Content Pipeline

### Ideas Backlog
- Best espresso grinder under 200 (170/mo, HIGH commercial intent — too competitive for now)
- Gaggia Classic Pro review (210/mo, HIGH competition — do it but not priority)
- Iced espresso drinks roundup (leverage iced latte traffic)
- Water chemistry for espresso (low competition, enthusiast audience)
- Single-dosing workflow
- Seasonal espresso recipes
- Americano vs long black (comparison, low competition informational)
- How to make a cappuccino at home (high volume, moderate competition)
- Espresso beans vs coffee beans (FAQ-style, informational)
- Cold brew espresso concentrate (trending, lower competition)

### In Progress
*(none — pulse 3 complete)*

### Published (12 articles)
1. /guides/getting-started/ (+ FAQ pulse 3)
2. /guides/how-to-steam-milk-latte-art/ (+ FAQ pulse 3)
3. /guides/espresso-grind-size-guide/ (+ FAQ pulse 2)
4. /guides/espresso-troubleshooting/ (+ FAQ pulse 2)
5. /guides/how-to-clean-espresso-machine/ (+ FAQ pulse 3)
6. /guides/espresso-ratio-guide/ (+ FAQ pulse 2)
7. /guides/wdt-tool-espresso/ (NEW pulse 3, + FAQ)
8. /reviews/best-espresso-machines-under-500/
9. /reviews/breville-bambino-plus-review/ (NEW pulse 3, + FAQ)
10. /recipes/classic-espresso-drinks/
11. /recipes/iced-latte-recipe/
12. /recipes/cortado-and-flat-white-recipe/

## Technical SEO Status
- [x] Sitemap submitted (9 URLs initially, now 12)
- [x] robots.txt present with sitemap reference
- [x] Article schema (JSON-LD) on all pages
- [x] FAQ schema (JSON-LD) on ALL guides + new articles
- [x] WebSite schema on homepage (with SearchAction)
- [x] GA4 tracking confirmed working
- [ ] Re-submit sitemap now that 3 new pages added (pulse 4)
- [ ] Check URL inspection in Search Console for key pages (pulse 4)
- [ ] Consider BreadcrumbList schema for category pages
- [ ] Internal linking: WDT guide needs links FROM other relevant pages

## Things Tried & Rejected
- Attempting to use Python for DataForSEO API — not installed on this system. Used Node.js instead.
- DataForSEO keyword_ideas endpoint doesn't support server-side filters — filter client-side instead.
- DataForSEO keyword-ideas with "home espresso accessories" / "espresso machine accessories" seeds returned irrelevant generic coffee chain brand searches. Use search-volume command with specific keywords instead.

## Hypotheses
- FAQ schema gives rich snippet eligibility → more SERP real estate → higher CTR for new site
- Iced latte recipe (5,400/mo LOW) could rank in 4–8 weeks with good content
- Cortado/flat white combined in one page captures both keywords (2,400 + 1,600/mo)
- Grind size guide already had 130s engagement from first organic visit — this topic resonates
- WDT tool informational content could rank faster than commercial WDT product pages due to different intent match
- Bambino Plus review: even with N/A DataForSEO volume, it's a high-intent query people actually search

## Competitive Observations
- The DataForSEO keyword-ideas endpoint returns generic coffee brand/chain searches regardless of seed — useless for this niche, use search-volume with specific terms instead
- Recipe keywords (iced latte, cortado, flat white) remain best bets for first organic rankings
- Commercial keywords (best machine under $X, reviews) are HIGH competition — long game
- WDT tool keyword has HIGH paid competition but informational content should be different SERP

## Next 3 Pulses Roadmap
1. **Pulse 4:** Re-submit sitemap (12 URLs now), check Search Console for any impressions on existing content, write "how to make a cappuccino at home" (high volume), write "espresso beans vs coffee beans" (informational/FAQ), add internal links pointing TO the WDT guide
2. **Pulse 5:** Analyze early Search Console impressions if any pages start showing, identify which pages are getting impressions, optimize title tags/descriptions for CTR, write 2 more articles (water chemistry, americano vs long black)
3. **Pulse 6:** Check if any pages indexing, analyze which content is resonating (GA4 engagement), consider adding a "tools" or "accessories" section if WDT guide performs well

---
*Last updated: 2026-04-05 (Pulse 3)*
