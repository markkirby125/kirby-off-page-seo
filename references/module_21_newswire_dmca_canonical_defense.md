# Module 21: Newswire Indexation Criteria, DMCA Defense & Canonical-Trap Auditing

*Source: Charles Floate parasite-SEO masterclass (The Edward Show E1193). Companion execution skills: `../../kirby-saas-syndicate/SKILL.md` Module 1 (platform matrix), `../../kirby-zero-to-100-seo/SKILL.md` Module 1 (incubation/longevity).*

### **21.1 Newswire Indexation Criteria (Paid Placement Vetting)**
A paid newswire/press placement is only worth its fee if it indexes and stays indexed. Vet every outlet against ALL five criteria before purchase:
1.  **Guaranteed indexation in writing** — the placement contract includes indexation (URL live in Google index) within a stated window, not just "distribution".
2.  **Self-canonical** — the article URL carries a self-referential canonical (verify on a recent client article; see §21.3). Syndication networks that canonical to a parent feed page never index under their own URL.
3.  **Standalone page, not a feed item** — the article has its own URL, nav path, and indexable body — not an iframe or JS-injected snippet.
4.  **Retention history** — sample 3–6 month-old articles from the same desk: still indexed in `site:` checks. Newswires that churn to `Crawled - currently not indexed` are renting you a screenshot.
5.  ** topical adjacency** — the outlet's section where your article lands actually covers your niche; irrelevant-desk placements get deindexed in cleanup passes.

**Recurring-need rule (from Module 12 §12.6):** press placements decay after 4–6 weeks; durable commercial terms need either the reload schedule or permanent tier-2 links into the placement URLs.

### **21.2 DMCA / Negative-SEO Defense Protocol (High-Competition Verticals)**
Fraudulent competitor DMCA takedowns are rampant in iGaming, crypto, and affiliate verticals: a competitor files a false copyright claim against your parasite placements or money pages to strip them from the host platform.
*   **Pre-position (before any attack):** Keep dated proof of authorship for every commercial asset (git history, published-first timestamps, drafts with provenance). Multi-platform redundancy: every load-bearing query covered by ≥2 properties on different platforms (`../../kirby-zero-to-100-seo/SKILL.md` Module 1 §1.3) so a single takedown never erases the citation footprint.
*   **On takedown notice:** Do not re-publish to the same platform first. File the platform's counter-notice with authorship proof within the platform's window; simultaneously stand the content up on the redundant platform so query coverage never gaps.
*   **Legal escalation:** Document a pattern (dates, URLs, claimant) — serial fraudulent filings expose the filer to perjury exposure under DMCA §512(f) and platform-level sanctions; a lawyer letter citing the pattern typically ends repeat attacks.
*   **Never retaliate in kind.** Filing fraudulent counter-DMCAs converts you into the liable party.

### **21.3 Canonical-Trap Auditing for Host Platforms**
Platforms that host third-party content frequently inject canonicals that silently kill indexation. Audit before publishing and re-audit monthly for load-bearing placements:
1.  **Fetch the rendered page** (not just the raw HTML — check post-JS canonical injection too).
2.  **Assert:** canonical points at the article's own URL (self-referential), not a parent category, author page, feed, or the platform root.
3.  **Check for duplicate-content consolidation:** if the same body appears on multiple platform URLs (AMP/print/syndication mirrors), exactly one may carry the self-canonical — the rest must reference it.
4.  **Common trap patterns:** UTM-stripped redirects that drop the article path; `rel=canonical` to a "canonical home" of the author profile; syndication partners rel-canonicaling to THEIR copy (fine only if the deal is deliberate and the citation flows back).
5.  **Remediation:** platform-native fixes (publish settings, support tickets) first; if the platform cannot emit a self-canonical, treat the placement as unindexable and shift the budget to a platform from the `../../kirby-saas-syndicate/SKILL.md` Module 1 §1.3 matrix.
