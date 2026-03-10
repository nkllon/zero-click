# zero-click

Search used to work like this: you asked, you got links, you clicked. The click was where the value lived. Publishers. Ads. The open web.

Not anymore.

Now you ask and the answer lands in the box. No click. No trip to the site. No share of the attention. The number that used to measure that—how many clicks per thousand searches actually leave the page—keeps dropping. In the US, for every thousand Google searches, something like 360 clicks make it to the open web. The rest? Resolved right there. Zero-click.

That’s not a small tweak. It’s a transfer. Value moves from the click layer—sites, headlines, display, affiliate—to the answer layer. The one that owns the box. The one that can serve an answer, an ad, an overview, without ever sending you away. AI overviews, featured snippets, one-box answers: they’re all the same story. The query ends where it started. The open web gets the leftovers.

So zero-click isn’t just a metric. It’s the beat of a larger shift: discovery and intent getting captured before the click. Traffic that used to go out now stays in. Revenue that used to flow to the open web now flows to the surface. And the “click for dollars” model—the whole idea that you monetize by sitting between intent and resolution—starts to erode. Not in a year. Not in a quarter. Every time someone gets an answer without clicking, it’s already happening.

We are taking our attention back.

This repo is about that story. The numbers, the studies, the references—the back matter—live in the research.

---

**The back**

We’re on the other side of the bow tie. Here’s what’s in the stack.

**Primary research — zero-click and traffic**

- [SparkToro (2024)](https://sparktoro.com/blog/2024-zero-click-search-study-for-every-1000-us-google-searches-only-374-clicks-go-to-the-open-web-in-the-eu-its-360/) — Clicks per 1,000 searches to the open web: US ~360, EU ~374. The number that pins the transfer.
- [SEO Bazooka (2025)](https://www.seo-bazooka.com/zero-click-search-research-2025/) — Synthesis of US studies: ~60% of Google searches end without a click.
- [eMarketer](https://www.emarketer.com/chart/272112/share-of-zero-click-keyword-searches-us-with-without-ai-overviews-jan-march-2025-of-queries) — Zero-click share with and without AI Overviews (US, Jan–Mar 2025).
- [Innerspark (2025)](https://www.innersparkcreative.com/news/ai-search-zero-click-statistics-2025-verified) — AI Overviews in ~13% of US desktop queries; news zero-click 56% → ~69% (May 2024–May 2025).

Full ref list: [REFERENCES.md](https://github.com/nkllon/zero-click/blob/content/.content/REFERENCES.md) on the content branch.

**Model and interactive**

- [Interactive decay model](https://github.com/nkllon/zero-click/blob/content/.content/interactive.html) — Sliders for V0 (baseline market cap), ad fraction, tau_ad, tau_platform, tau_c. Two-compartment (ad layer vs platform layer) plus consolidator capture. Run locally or open the raw file; Plotly. How fast the click layer decays, how fast the rest gets captured.
- Scenario outputs (in the corpus): exponential sweep, two-compartment CSV, scenario_expected (resilient / hybrid / collapse / tail), consolidator sweep. SVG charts for the same. All driven off the same V(t), C(t) story.

**Corpus — the rest of the bow tie**

The [internet-biz corpus](https://github.com/nkllon) pulls this into the full picture: click-for-dollars vs walled gardens, Gen AI erosion of the discovery layer, growth dependency, agentic bypass, and where the value goes when the click goes away. In there you get:

- **Research gaps** — DMA and gatekeepers, data portability and delegated access, zero-click (the studies above), accessibility as interoperability symptom, ad tech consolidation and PE rollups. Tagged observed / derived / speculative.
- **Argument matrix** — Where five model runs agree and disagree (re-rate vs collapse, bypass vs recapture). Quantified estimates, unsupported claims, missing evidence.
- **Narrative** — Baseline taxonomy, first divergence (redistribution vs growth-dependency collapse), second divergence (agentic bypass vs incumbent recapture), convergence (accessibility, shadow protocols, repricing), end-states with scenario weights (40% resilient, 35% hybrid, 15% collapse, 10% tail) and human impact by stakeholder.
- **Ontology and SHACL** — 21+1 dimensions, scenario and evidence nodes, validation. Machine-readable backbone.

**Where it lives**

- [Content branch](https://github.com/nkllon/zero-click/tree/content) — This repo’s back matter: REFERENCES.md, interactive.html, and whatever else we add. Main is README only; content is the rest.
