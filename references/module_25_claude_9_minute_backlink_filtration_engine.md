# Module 25: The Claude 9-Minute Backlink Filtration & Prospecting Engine

*Source: Nico | AI Ranking ("How I Built a Claude Skill That Finds Perfect Backlinks In Under 9 Mins (SEO: Claude/GPT)"). October 2026.*

Manual backlink prospecting from raw Ahrefs/Semrush CSV exports wastes 2–3 hours per target domain as operators manually weed out scraper networks, dead directories, PBNs, and auto-generated subdomains. By passing raw competitor backlink exports through a structured LLM classification pipeline, an agent can strip out 95% of toxic noise and output a prioritized, outreach-ready link acquisition matrix in under 9 minutes.

---

### **25.1 The 3-Gate Automated Filtration Funnel**

Before generating any outreach angles, the agent must filter raw referring-domain rows through three sequential elimination gates:

```
┌─────────────────────────────────────────────────────────────────────────┐
│             3-GATE LLM BACKLINK FILTRATION PIPELINE                     │
├─────────────────────────────────────────────────────────────────────────┤
│ Gate 1: Toxic & Automated Footprint Elimination                         │
│         - Strip scraper TLDs (.xyz, .top, .info, .click), IP-indexed    │
│           pages, SEO stats aggregators, and coupon/whois directories    │
│                                                                         │
│ Gate 2: Semantic & Topical Relevance Scoring (1–10 Scale)               │
│         - Evaluate link source title, URL slug, and anchor context      │
│         - Discard domains scoring < 7 in commercial/local alignment     │
│                                                                         │
│ Gate 3: Acquisition Feasibility Classification (The 4 Buckets)          │
│         - Classify surviving prospects into one of 4 actionable buckets │
│         - Generate a bespoke "Value-First" hook per Module 22 rules     │
└─────────────────────────────────────────────────────────────────────────┘
```

---

### **25.2 The 4 High-Yield Link Acquisition Buckets**

Surviving referring domains must be categorized into four operational buckets ordered by acquisition probability:

1. **Bucket 1: Vendor, Accreditation & Partner Directories (Highest Conversion)**:
   - *Pattern*: Upstream software vendors, hardware manufacturers, certifying bodies, or trade regulators listing accredited partners (e.g., Microsoft Solution Providers, Cyber Essentials certifying bodies, manufacturer installer locators).
   - *Execution*: Zero cold pitching required—verify active client certification or partner status and submit the canonical profile URL via the vendor's partner portal.
2. **Bucket 2: Regional Chamber, Municipal & Trade Associations**:
   - *Pattern*: Local Chambers of Commerce, Rotary clubs, municipal business registries, and regional trade guilds (complementing [`kirby-local-seo`](../../kirby-local-seo/SKILL.md) Module 5 community sponsorship links).
   - *Execution*: Flag membership cost vs. harmonic centrality authority (Module 4 §4.15) and prioritize regional hubs carrying high local entity trust.
3. **Bucket 3: Contextual Resource Page & Guide Insertions**:
   - *Pattern*: Non-competing complementary businesses (e.g., commercial realtors, accountants, local business advisors) publishing curated resource guides or checklists containing outdated references or dead external links.
   - *Execution*: Identify the exact broken or outdated technical claim on the prospect's page and pitch a drop-in replacement asset.
4. **Bucket 4: Editorial Guest Contributions & Niche Roundups**:
   - *Pattern*: Industry trade blogs or regional business publications accepting expert commentary. (For SaaS product listicles, route to Module 18).

---

### **25.3 Integration with Module 22 Cold-Outreach Guardrails**

When generating outreach copy for Bucket 3 and Bucket 4 targets, the agent MUST strictly enforce the empirical email constraints defined in **Module 22**:
* **Word Count**: Strictly **60–90 words** total body length.
* **Subject Line**: Under **30 characters**, lower-case conversational framing.
* **Value-First Open**: Lead immediately with the specific content gap, broken resource, or editorial value proposition in Sentence 1—never open with self-referential company bios.
* **Recipient Selection**: Address the Managing Editor, Content Lead, or Specific Author—never generic `info@` inboxes or CEOs of mid-size firms.
