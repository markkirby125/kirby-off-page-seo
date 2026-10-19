# Module 23: Nofollow Link Graph Ranking Physics & Clickstream Transmission (Edward Sturm Ep. 1198)

*Source: The Edward Show, Episode 1198 (Edward Sturm)*

Conventional SEO dogma asserts that `rel="nofollow"` links pass zero PageRank, carry zero ranking authority, and are completely ignored by Google’s core ranking algorithms. This belief originated in 2005 when Google introduced `nofollow` to fight comment spam.

In **September 2019**, Google officially revised its documentation: links marked `nofollow`, `rel="sponsored"`, and `rel="ugc"` are officially treated as **hints** rather than absolute directives. Long before 2019—and cemented by Google API leaks and empirical split-tests in 2024–2026—rigorous data confirms that nofollow backlinks produce direct, measurable keyword ranking surges and AI citations when specific conditions are met.

---

### **23.1 Kyle Roof's Two-Factor Law for Nofollow Transmission**

Kyle Roof established that a nofollow backlink acts almost identically to a standard `dofollow` link if and only if it satisfies two strict criteria:

1. **Host Page Ranking**: The specific page hosting the nofollow link already ranks in Google's top results for relevant target terms.
2. **Real Organic Clicks**: The hosting page receives active, ongoing organic traffic and real user interactions.

```
┌────────────────────────────────────────────────────────┐
│               KYLE ROOF'S 2-FACTOR LAW                │
│                                                        │
│  [Page Ranks on Google]  +  [Page Gets Real Clicks]    │
│           │                           │                │
│           └─────────────┬─────────────┘                │
│                         ▼                              │
│       Nofollow Link Acts as Followed Link              │
│       (Passes Measurable Ranking Authority)            │
└────────────────────────────────────────────────────────┘
```

When a nofollow link is embedded on a page that meets both criteria, Google's algorithms treat the link as an active navigational citation rather than discarded text.

---

### **23.2 Empirical Controlled Experiments**

1. **Rand Fishkin’s Split-Tests (2014)**:
   - *Test 1*: Built nofollow links across 55 distinct domains pointing to a URL ranking at #16 on Google. The page climbed to **#6** (+10 positions).
   - *Test 2*: Built nofollow links across 42 distinct domains pointing to a URL at #9. The page climbed to **#5** (+4 positions).
   - *Removal Test*: When the nofollow links were pulled down, the pages maintained their elevated positions and in several instances continued to climb, proving that nofollow authority transmission does not instantaneously collapse upon link removal.
2. **Joy Hawkins' Validation (Sterling Sky, 2024)**:
   - Joy placed a comment containing a nofollow link on a high-traffic local search forum thread that was actively ranking for commercial keywords.
   - *Day 2*: The target keyword jumped in SERPs immediately. Furthermore, an embedded YouTube video on the destination page began ranking in Google search results where the page had previously never ranked.
   - Replicated across multiple high-traffic forum/community pages with identical positive ranking velocity, confirming that nofollow links on ranking, high-traffic pages pass significant ranking value.
3. **Link Research High-Authority Case Studies (2025)**:
   - *BBC Nofollow Link*: Triggered immediate brand entity inclusion in Google’s "People Also Search For" (PASF), bumped supporting blog posts 3–5 positions, and significantly accelerated new URL indexation across the target domain.
   - *gov.uk Nofollow Link*: Surged compliance-related keyword rankings, catalyzed organic tier-2 backlinks from private sector blogs citing gov.uk, and skyrocketed B2B lead conversion trust.

---

### **23.3 The 2024 Google API Leak & Clickstream Physics**

The May 2024 Google API leak confirmed the underlying mechanical reason why nofollow links work:
* **Chrome Clickstream & Navigational Journeys**: Google tracks user clickstreams, interaction rates, and navigational paths. 
* **The $50,000 Internal Linking Experiment (Ep. 1163)**: Proved that links receiving real user clicks carry exponentially more algorithmic weight than unclicked links.
* **The Physics**: If users visit a page and click a nofollow link, Google's systems register user satisfaction, navigational flow, and entity endorsement. Authority and relevance pass through the clickstream, regardless of whether the HTML tag contains `rel="nofollow"`.

---

### **23.4 The Semrush 2025 AI Citation Study (Nofollow > Follow)**

Semrush and Kevin Indig analyzed 1,000 domains across 5 major AI search engines (Perplexity, ChatGPT Search, Gemini, Claude, Copilot):
* Backlinks strongly correlate with AI visibility and LLM citations.
* **Critical Finding**: **Nofollow backlinks showed a slightly STRONGER correlation with AI mentions than followed backlinks**.
* *The Mechanism*: Major knowledge-dense platforms (Reddit, Wikipedia, Quora, GitHub) enforce nofollow on user-submitted links by default. However, these exact platforms form the primary retrieval corpora and RAG sources for LLM-generated search answers. Winning nofollow citations on these platforms directly forces LLM brand citations.

---

### **23.5 Natural Profile Balance & Footprint Defense (Ep. 948)**

An unnatural backlink profile triggers algorithmic suppression:
* **The 100% Follow Footprint Trap**: A backlink profile consisting exclusively of `dofollow` links is an immediate statistical anomaly that flags algorithmic link-spam filters. Natural profiles always contain a significant ratio of nofollow, UGC, and sponsored attributes.
* **Low-Authority vs. High-Authority Balance**: As demonstrated in Episode 948, building low-authority and natural nofollow backlinks to balance an artificially high-DR profile frequently unlocks stuck keyword rankings by restoring natural profile entropy.

---

### **23.6 Executable Nofollow Placement SOP**

1. **Identify Ranking Forum / Community Nodes**: Search for `"[target keyword]" site:reddit.com`, `site:quora.com`, or niche authority forums. Identify threads ranking in positions #1–#5 on Google with ongoing traffic.
2. **Contextual Value Placement**: Post high-effort, authoritative responses that answer the primary inquiry, placing the target link as a supporting citation, tool, or research asset.
3. **Destination Optimization**: Ensure the destination landing page features embedded media (YouTube video or interactive calculator) and rapid load speeds to maximize engagement when clickstream traffic arrives.
