# ASTRAL KPI Sandbox

An authored, interactive teaching tool for ASTRAL's detection KPIs: learn the statistical tradeoffs by manipulating one shared ASTRAL world, then use Reference Mode for deeper metric detail.

**Live demo:** https://shubhudharmadhikari-commits.github.io/astral-kpi-sandbox/

ASTRAL reads a sea of AI-interaction logs, scores each session for biological-misuse risk, and
surfaces the few worth a human review. This sandbox lets someone with no statistics background
*feel* what the detection metrics mean: one shared synthetic world driven by a few dials, where
moving any dial makes every metric react at once.

Covers Guided Discovery lessons for the core ASTRAL evaluation loop, signal rarity, threshold tradeoffs, base-rate
effects, false-alarm load, audit visibility, ROC vs PR interpretation, actor-tier hiding, and ranked reviewer attention. The Reference layer
keeps F2 (North-Star) · Precision · False Positive Rate · Recall · ROC-AUC · PR-AUC · NDCG@k · Attribution
(weighted κ), plus a live **north-star** better/worse signal, Batch vs Operational mode, dark/light themes, and
an "Under the hood — for the curious" panel on every tab.

## Use it

It's a single, self-contained HTML file: no framework, backend, analytics, runtime network calls, or external
assets. Fonts are embedded. Just open `index.html` in any browser, or visit the live demo above.

## Credits

Built for the ASTRAL project. Design language: ASTRAL Design System (allele mark, spindle-field motif,
Space Grotesk · IBM Plex).
