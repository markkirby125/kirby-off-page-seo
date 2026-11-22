# Module 23: Reported Nofollow Signals & Clickstream Hypothesis (Edward Sturm Ep. 1198)

*Source: The Edward Show, Episode 1198 (Edward Sturm)*

Conventional SEO dogma asserts that `rel="nofollow"` links pass zero PageRank, carry zero ranking authority, and are completely ignored by Google’s core ranking algorithms. This belief originated in 2005 when Google introduced `nofollow` to fight comment spam.

In **September 2019**, Google officially revised its documentation: links marked `nofollow`, `rel="sponsored"`, and `rel="ugc"` are officially treated as **hints** rather than absolute directives. Practitioners cite the 2024 Google API leak and reported split-tests (directional, single-source, unverified) as suggesting that nofollow backlinks can produce measurable keyword ranking gains and AI citations when specific conditions are met.

---

### **23.1 Kyle Roof's Two-Factor Hypothesis for Nofollow Transmission (Reported)**

Kyle Roof reported (single-source, unverified) that a nofollow backlink acts almost identically to a standard `dofollow` link if and only if it satisfies two strict criteria:

1. **Host Page Ranking**: The specific page hosting the nofollow link already ranks in Google's top results for relevant target terms.
2. **Real Organic Clicks**: The hosting page receives active, ongoing organic traffic and real user interactions.

```
┌────────────────────────────────────────────────────────┐
│      KYLE ROOF'S REPORTED HYPOTHESIS (UNVERIFIED)      │
│                                                        │
│  [Page Ranks on Google]  +  [Page Gets Real Clicks]    │
│           │                           │                │
│           └─────────────┬─────────────┘                │
│                         ▼                              │
│         Nofollow Link May Act as Followed Link         │
│              (May Pass Ranking Authority)              │
└────────────────────────────────────────────────────────┘
```

Roof's hypothesis (unverified) is that when a nofollow link is embedded on a page that meets both criteria, Google treats the link as an active navigational citation rather than discarded text.

---

### **23.2 Reported Experiments (Single-Source, Unverified)**

1. **Rand Fishkin’s Split-Tests (2014, reported)**:
   - *Test 1*: Built nofollow links across 55 distinct domains pointing to a URL ranking at #16 on Google. The page climbed to **#6** (+10 positions).
   - *Test 2*: Built nofollow links across 42 distinct domains pointing to a URL at #9. The page climbed to **#5** (+4 positions).
   - *Removal Test*: When the nofollow links were pulled down, the pages maintained their elevated positions and in several instances continued to climb, suggesting that nofollow authority transmission does not instantaneously collapse upon link removal.
2. **Joy Hawkins' Test (Sterling Sky, 2024, as reported in Ep. 1198; unverified)**:
   - Joy placed a comment containing a nofollow link on a high-traffic local search forum thread that was actively ranking for commercial keywords.
   - *Day 2*: The target keyword reportedly jumped in SERPs. An embedded YouTube video on the destination page was also reported to begin ranking in Google search results where the page had previously never ranked.
   - Reportedly replicated across multiple high-traffic forum/community pages with identical positive ranking velocity, reported as indicating that nofollow links on ranking, high-traffic pages pass significant ranking value.
3. **Link Research High-Authority Case Studies (2025, reported, single-source, unverified)**:
   - *BBC Nofollow Link*: Reportedly coincided with brand entity inclusion in Google’s "People Also Search For" (PASF), bumped supporting blog posts 3–5 positions, and faster new URL indexation across the target domain.
   - *gov.uk Nofollow Link*: Reportedly coincided with higher compliance-related keyword rankings, organic tier-2 backlinks from private sector blogs citing gov.uk, and improved B2B lead conversion trust.

---

### **23.3 The 2024 Google API Leak & Clickstream Hypothesis**

Practitioners read the May 2024 Google API leak as explaining why nofollow links work (interpretation, unverified):
* **Chrome Clickstream & Navigational Journeys**: Practitioners infer from leaked attribute names that Google may track user clickstreams, interaction rates, and navigational paths (unverified).
* **The $50,000 Internal Linking Experiment (Ep. 1163)**: Reportedly (single-source, unverified) showed that links receiving real user clicks carry exponentially more algorithmic weight than unclicked links.
* **The Hypothesis**: If users visit a page and click a nofollow link, Google's systems may register user satisfaction, navigational flow, and entity endorsement. Authority and relevance may pass through the clickstream, regardless of whether the HTML tag contains `rel="nofollow"` (hypothesis, unverified).

---

### **23.4 The Semrush 2025 AI Citation Study (Nofollow Correlation ≥ Follow, Reported)**

Semrush and Kevin Indig analyzed 1,000 domains across 5 major AI search engines (Perplexity, ChatGPT Search, Gemini, Claude, Copilot):
* Backlinks reportedly correlate strongly with AI visibility and LLM citations.
* **Critical Finding**: **Nofollow backlinks showed a slightly STRONGER correlation with AI mentions than followed backlinks** (a correlation, directional and single-source; not evidence that nofollow links cause AI mentions).
* *The Mechanism*: Major knowledge-dense platforms (Reddit, Wikipedia, Quora, GitHub) enforce nofollow on user-submitted links by default. However, these exact platforms form the primary retrieval corpora and RAG sources for LLM-generated search answers. Winning nofollow citations on these platforms can improve the odds of LLM brand citations (directional, single-source).

---

### **23.5 Natural Profile Balance & Footprint Defense (Ep. 948)**

An unnatural backlink profile can reportedly trigger algorithmic suppression (practitioner view, unverified):
* **The 100% Follow Footprint Trap**: A backlink profile consisting exclusively of `dofollow` links can look like a statistical anomaly to link-spam filters (practitioner view, unverified). Natural profiles usually contain a significant ratio of nofollow, UGC, and sponsored attributes.
* **Low-Authority vs. High-Authority Balance**: As demonstrated in Episode 948, a single-source observation (no guarantee) is that an unusually high-DR profile with few editorial or nofollow mentions can look lopsided; earn genuine links and mentions through real coverage rather than manufacturing links to engineer the profile (see the Module 18 bans on PBNs and junk directories).

---

### **23.6 Executable Nofollow Placement SOP**

1. **Identify Ranking Forum / Community Nodes**: Search for `"[target keyword]" site:reddit.com`, `site:quora.com`, or niche authority forums. Identify threads ranking in positions #1–#5 on Google with ongoing traffic.
2. **Contextual Value Placement**: Post high-effort, authoritative responses that answer the primary inquiry, placing the target link as a supporting citation, tool, or research asset; disclose affiliation, follow each community's self-promotion rules, and never post paid or undisclosed links.
3. **Destination Optimization**: Ensure the destination landing page features embedded media (YouTube video or interactive calculator) and rapid load speeds to maximize engagement when clickstream traffic arrives.
