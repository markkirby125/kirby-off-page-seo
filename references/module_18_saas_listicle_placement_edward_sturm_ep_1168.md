# Module 18: SaaS Listicle Placement & Competitive Gap Outreach

*Source: Kristiyan Yankov (Above Apex) / Edward Sturm, The Edward Show Episode 1168. Guest heuristics unless marked as Kirby law.*

**This module is the how.** Identify cited URLs in Module 4 §4.11. Paid #1 / URL buyout thesis in §4.13. Low-quality paid-link GEO penalty in §4.12. First-party “Best X” pages in `kirby-aiseo-skill` Module 2 §2.16. Score publisher retrievals in `kirby-seo-telemetry`. LinkedIn *posts* (slug/keyword) stay in §4.14; LinkedIn *DMs for placements* live here.

Do not append SaaS outreach into Module 4. Do not route this play to `kirby-technical-aeo` or `kirby-local-seo`.

### **18.1 Fast intercept vs primary bias**

Treat AI SEO as two halves:

| Half | Owner | Clock |
|---|---|---|
| Off-page: insert the brand into URLs already feeding ChatGPT / Perplexity | This module | Weeks |
| On-site: commercial pages + selection-rate (SRO / click-selection) | `kirby-aiseo-skill` | ~6–8 months for “primary bias” |

**Priority:** for a ~200-query commercial set, get into the ~10 roundups with the most AI retrievals *before* waiting on model-authority updates. Roundups also sit in the evaluation / comparison stage (e.g. “best CRM for small agency”).

### **18.1.1 The Off-Page Boundary Mandate: On-Page Undertargeting First (Edward Sturm Ep. 1169)**

*Source: Edward Sturm, The Edward Show Episode 1169 ("How SEOs Actually Find Keywords in 2026").*

Before committing budget or hours to third-party listicle placement, backlink outreach, or competitive gap acquisition:
* **The Pre-Requisite Undertargeting Check:** Run the 4-Spot SERP Undertargeting Inspection (`kirby-aiseo-skill` Module 2 §2.29) on the primary target keyword.
* **The Deferral Rule:** If the SERP is **undertargeted** (i.e. $\le 2$ of the top 5 ranking competitors target the exact keyword across their `<title>`, URL slug, `<h1>`, and first sentence hook), **halt off-page outreach**. A dedicated, high-intent on-page landing page can rank in 1–2 weeks with bare-minimum on-page matching and zero link building.
* **When Off-Page Is Strictly Indicated:** Third-party listicle placement and competitive gap outreach are indicated **only** when:
  1. The SERP is **defended** (top competitors already target all 4 spots and hold high domain authority).
  2. The target URL is an indexed-but-unranked citation node that actively feeds LLM answer synthesis (ChatGPT / Perplexity).
  3. The keyword is an evaluation-stage "Alternatives / Best X" query where searchers demand third-party consensus (§18.1).

### **18.2 Competitive gap SOP (Ahrefs)**

Cheapest Ahrefs tier is enough. Read-only MCP rules: `kirby-agent-security`.

1. Competitive Analysis: list **all** competitors — direct **and** partial. More is better.
2. Aggregate their referring domains.
3. Filter (heuristic): DR ~40–50+, ~2–3k organic, language/geo match (e.g. US English if that is the market).
4. Keep only domains where **≥2 competitors already have links**.
5. Why the ≥2 filter: relevance (they already cover this product class), publisher will likely take another, and a *cluster* of inclusions is the narrative — one link on a giant competitor profile is not proof of lift.

Prefer **updating an existing indexed URL** over a net-new guest post, especially in saturated verticals.

### **18.3 Discovery overlap (do not use Ahrefs alone)**

Intersect three lists for the same query set:

1. Ahrefs gap (18.2)
2. Manual SERP for “best / alternatives / roundup” queries
3. AI-visibility tracker on entities + queries (source says “PKI”; confirm product before buying — Peec or equivalent)

Keep URLs that **feed the models even if they are not Google top-10**. Indexed-but-unranked citers are valid intercept targets.

Industry pattern: a handful of listicles (~10–20, sometimes ~15) dominate. Work those first.

### **18.4 Qualify the URL, not the domain brand**

Must-check:

* Indexed.
* Pulls relevant keywords **or** shows material AI retrievals/citations (18.3).
* Lasted (not a week-old farm URL).

Editorial tell: **5–10 companies** with real overviews beat 25-tool dumps. No hard “too many brands” cutoff — depth is the tell.

**Farm exception:** a site that *only* publishes roundups across every industry is usually skip. **Pay that farm anyway** if *this* article ranks, has lasted, and pulls the right keywords. Do not treat “roundup site” as an automatic ban.

Publisher history (traffic/keywords up vs down after updates): case-by-case, not a universal gate.

### **18.5 Placement pricing (heuristic)**

Raise price as more of these are true: indexed, traffic, AI-visibility for the query, competitors already in positions 1–3, client SEO/marketing insists.

| Band | When |
|---|---|
| Below ~$300 | Weaker site; still relevant |
| ~$300–$500 | Typical qualifying roundup |
| ~$1,000+ | The roundup appears in *every* industry “best X” SERP/AI set; top 2–3 competitors occupy 1–3; client is convinced |

These are guest ballparks, not Kirby laws. Align with the client, then execute.

### **18.6 Intake and positioning lock**

Before any pitch, capture: primary product if they have many, USP, why these listicles, how people should think of the brand.

**Law:** the same narrative on every listicle. 100 inconsistent blurbs confuse LLM retrieval. Match *that article’s* structure and length; keep core positioning identical.

Keywords around the brand: yes. Do not over-stuff. Do not pile exact-match anchors on listicles if other campaigns already use them.

**Ban:** ChatGPT 60 generic 2–3 sentence product blurbs + “here is our H1 and domain.”

### **18.7 Channel, volume, copy freeze**

* Default: **LinkedIn DM > cold email** (face, case studies, personal profile). Personal profile ≫ company page for trust.
* Target list ~**50**, not thousands. ~**50–100 messages/day** if using a sequencer.
* Optional sequencers: Dripify (team CRM), Linked Helper. Agent must not run them unsupervised (`kirby-agent-security`).
* Finite publisher pool: expand by retrying people you never started a conversation with.
* If copy is net-positive, do not weekly-tweak. Revisit ~3 months or when you have a real test.

### **18.8 Two templates (never put the dollar amount in message 1)**

**Study / linkable asset**

> We built [study]. It supports the point in [their article]. If that holds, would you take a look and link it?

**Paid listicle (blunt)**

> We work with [product], highly relevant to this roundup. Surprised they are not in it. Happy to pay if you see the alignment.

Offer to pay **without naming a number**. Publishers often ask less than you would have paid.

Lead with money **only** when the publisher clearly monetizes roundups — then talk numbers immediately, still no first-message figure.

### **18.9 Incentives and follow-up**

Win-win. Stack what you can: payment, premium/product access, coupon/voucher, you write the blurb, a link they cannot get.

Route by owner:

* Head of content / active LinkedIn editor → premium access + a real conversation first (they drown in zero-value pitches).
* Roundup-monetizer → numbers.

Follow-up: **1–2 only**, **10–15 days** between. Larger gap after that. Do not burn the relationship.

### **18.10 Deep-link mix**

Roundups and expert quotes **naturally load brand/homepage anchors** (they name the company, not a blog URL). Spread other placements or you over-concentrate.

Holistic mix: homepage/domain + commercial + TOFU + comparison/evaluation.

Heuristic month: **5 listicles → ~3 domain + 2 commercial** (e.g. the data-privacy product page). Ask for two in-listicle links only if volume lets you spread.

### **18.11 Clicks on the backlink**

Default: do not chase. Equity + AI retrieval are the point.

Chase the **top slot** only if the roundup does ~**2–4k visits/month**.

### **18.12 Expert-quote outreach**

Platform list and anti-AI pitch ban: Module 4 §4.12.F. Human quotes only.

SaaS notes:

* Bandwidth: Connectively (formerly Featured) + Qwoted + HARO. SOS is not required.
* Featured/Connectively: fewer queries than HARO, higher close if you pitch on time.
* Connectively has a free tier; judge ROI by BBC/HubSpot-class mentions, not subscription cost.
* Quotes **compound**; paid interviews / sponsored homepage PR on the same domains do not substitute (the article is not labelled sponsored).
* Examples (not guarantees): daily HARO ~1 month → Healthline dofollow + rank spike; HubSpot dofollows via quotes.

### **18.13 Foundational SaaS directories**

Crunchbase as a **canonical entity node** is Module 16. This section is **launch / gap directories**.

New or SEO-naive SaaS (max output per hour): Crunchbase, Product Hunt, BetaList, plus a model-generated list of category directories if no directory-list product is used. Product Hunt launches can spike GSC organic (Sturm, one case).

Established SaaS: often already done — still **audit for gaps**. Do not skip because “they look like they do link building.”

### **18.14 Adjacent-industry link swaps**

Internal name: “same service.” Non-competitors in overlapping journeys (house cleaning ↔ movers analog → complementary SaaS).

* Pitch founder or marketing manager. Overlapping **existing** in-content paragraphs. Not footer/partner blocks.
* Good: a user would not ask why the link is there. Bad: four new paragraphs written only to segue a mention.
* Prefer include-in-existing-URL. New posts only if the opportunity is clearly worth the approval chain.
* Worked on cold email in the source (LinkedIn not required).
* Side effect: outreach can generate **clients**. Guardrail: selective, relevant — not reciprocal networks (§4.12 GEO penalty).

Rolodex: sites whose organic + off-page grew a lot in the **last 12–24 months** (in-house marketers who already value links).

### **18.15 Guest posts (additional layer, not a scalable engine)**

Worth it when: industry/content overlap, real traffic mix (check **geo** of traffic, not only topic), high editorial friction (approvals = they understand the game).

Heuristic: ~**5 in 30 days** from **adjacent** companies talking about similar things.

Skip: 60–160 articles, ~70% quote-farm, then they sell links.

### **18.16 Relationship compounding**

Distinct from Module 15 micro-influencers ($25–$50 short-form).

* Industry meetups; partner links from people you actually met.
* Podcast guests who **already have blogs**; wait ~**30 days**; ask for an article; pay with social posts instead of a reciprocal site link.
* Publicly thank tools you actually use → vendor case-study links.
* Downstream: introductions, conference speaking, partnerships. Slow on purpose.

### **18.17 Natural profile**

Not a 3-month sprint then stop. No 5-links-then-silence-then-5. Mixed anchors (brand + long; not only exact match). Cadence is a system.

Compatible with `kirby-aiseo-skill` §1.11.D (60% branded inbound). Roundup/quote gravity (18.10) is why you must mix the rest.

Volume is relative: five links/month can be nothing or everything depending on the competitor set. Do not overdo any one tactic.

### **18.18 What a good link is (and what Google ignores)**

Do not accept client fantasy filters as the brief (e.g. DR 81+ and 12k+ monthly visits). DR is easy to fake.

A ~1k-visit real business with a **100–200 visit, hyper-relevant article** can beat a fat generic.

Score: traffic **source**, topical fit, content, **inlinks vs outlinks**. Not binary.

**Zero-value pattern:** site covers 6–7 unrelated industries; ~30 links in ~1,200 words; target is off-topic (e.g. marketing agency on a privacy article). If a human sees “this was bought,” treat it as ignored.

### **18.19 Anti-patterns**

* Mass write-for-us / guest-post farms (§4.6, §4.12).
* Paying junk directories/PBNs and calling it this play.
* Synthetic first-party listicle spam (`kirby-aiseo-skill` §2.16 ClickUp failure).
* **Nofollow bait-and-switch:** inviting industry experts to write, giving them nofollow author links they do not understand, then harvesting follow equity and social bragging. Ban. Honest bylines with disclosed link policy are fine.
* Virality recipes / “stupid calculators.” Weird specific studies or stunts are optional; Kirby-native study shape is §4.12 $n≥3,000 audits. If you ship a stunt: Product Hunt + journalists + Reddit — not Product Hunt only.

### **18.20 What compounds**

Competitive gap + qualifying roundups + expert quotes compound. Guest posts and swaps are supporting layers.

**Episode 1168 checklist**

- [ ] Intake: primary product, USP, desired narrative (18.6).
- [ ] Ahrefs gap: all competitors, DR/traffic/geo filters, ≥2-competitor overlap (18.2).
- [ ] Overlap with manual SERP + AI-visibility; keep high-retrieval URLs even if not Google top-10 (18.3).
- [ ] Qualify each URL: indexed, keywords or AI cites, lasted; 5–10 brand editorial; farm exception only if *this* article qualifies (18.4).
- [ ] Price with the 18.5 rubric; no dollar amount in message 1 (18.8).
- [ ] LinkedIn-first, ~50 targets; 1–2 follow-ups at 10–15 days (18.7–18.9).
- [ ] Same positioning on every blurb; mix homepage vs commercial vs TOFU (18.6, 18.10).
- [ ] New SaaS: directory gap audit (18.13). Established: still check.
- [ ] Quotes via §4.12.F platforms; human-only (18.12).
- [ ] Reject DR-only briefs and zero-value link patterns (18.18).
- [ ] Measure publisher retrievals in `kirby-seo-telemetry`; do not wait 6–8 months to start intercept (18.1).
