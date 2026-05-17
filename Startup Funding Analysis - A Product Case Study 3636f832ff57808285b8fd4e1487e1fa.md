# Startup Funding Analysis - A Product Case Study

> Where is Indian startup money actually going — and what should investors do about it?
> 

---

## Why This Project Exists

<aside>
💡

Core question: Which Indian cities, sectors, and funding stages are
	attracting the most capital — and what does that mean for investors
	making decisions today?

</aside>

### The gap in how investors work today

| Investor task | How it's done today | The problem |
| --- | --- | --- |
| Tracking sector trends | Reading 10+ newsletters weekly | Inconsistent, opinion-heavy, no single source |
| Comparing cities for deal flow | Word of mouth from other investors | Heavily biased toward Bengaluru by default |
| Understanding stage distribution | Downloading Crunchbase CSV manually | Time-consuming, data goes stale instantly |
| Spotting emerging sectors | Following Twitter / LinkedIn | Noisy, anecdotal, not data-backed |
| Benchmarking deal size | Asking peers in WhatsApp groups | Unreliable, not confidential |

---

# The Problem Worth Solving

India's startup funding landscape shifted dramatically between 2019 and 2024 —
through a funding boom, a brutal winter, and an uneven recovery. Throughout it,
the investors who made the best decisions were the ones with the clearest view
of where capital was actually flowing. Most didn’t have that picture. This project
is built around that gap.

## The core problem

<aside>
🔴

Early-stage investors in India have no fast, reliable way to understand
	real-time funding trends across cities, sectors, and stages — forcing them
	to make high-stakes decisions on incomplete, fragmented, and often outdated information.

</aside>

### Breaking the problem down

| **Problem layer** | **What it means** | **Who feels it most** |
| --- | --- | --- |
| Data fragmentation | Funding data lives across Crunchbase, Inc42, YourStory, LinkedIn — never in one place | Angel investors, micro-VCs |
| Geographic blind spots | Most reports default to Bengaluru — Delhi NCR, Pune, Hyderabad are chronically underrepresented | Investors in non-Bengaluru cities |
| Sector timing | By the time a sector trend is written about, the smart money has already moved | First-time angels |
| Stage confusion | Investors don't have a clear view of how many startups graduate from Seed to Series A in their target sector | Fund analysts |
| No benchmarks | There's no easy answer to "is this deal size normal for a Series A in Fintech right now?” | Founders and investors both |

### The funding winter lens

Between 2022 and 2023, Indian startup funding fell by nearly 60%. But the
decline wasn’t uniform — some sectors held up while others collapsed. Some cities
recovered faster. Some stages were hit harder than others. That uneven

story is exactly the kind of nuance a good product should surface

instantly, not bury in a 40-page quarterly report.

| **Period** | **Funding climate** | **What changed** |
| --- | --- | --- |
| 2019–2021 | Boom | Record deal volumes, inflated valuations, Edtech and Fintech surge |
| 2022 | Peak then correction | Global rate hikes, investor caution sets in mid-year |
| 2023 | Funding winter | 60% YoY drop, late-stage deals dry up, survival mode for startups |
| 2024 | Selective recovery | Deep tech, EV, SaaS see renewed interest — but deal sizes are leaner |

### What a good solution looks like

<aside>
✅

A product that lets an investor filter funding trends by city, sector,
	and stage — and get a clear answer in under 2 minutes — would directly
	replace 3–5 hours of manual research before every investment decision.

</aside>

---

# Who I Built This For

### Primary user — The Angel Investor

<aside>
🧑‍💼

Rohan Mehta, 34 — Senior Product Manager at a Bengaluru SaaS company.
	Has ₹30–50 lakhs to deploy as an angel investor over the next 12 months.
	Evaluates 4–6 deals per month. Does all research independently on weekends.

</aside>

| **Dimension** | **Detail** |
| --- | --- |
| Goal | Find 2–3 high-conviction deals per year in sectors he understands |
| Biggest frustration | Spends Sunday evenings manually reading reports before Monday calls |
| Current tools | Crunchbase free tier, Inc42, Twitter, WhatsApp angel groups |
| Decision trigger | Moves fast when he sees a sector getting consistent deal flow — needs that signal early |
| Fear | Investing in a sector right after it peaks — being the last one in |
| Device | Primarily laptop, occasionally checks on phone between meetings |

### Secondary user — The Fund Analyst

<aside>
👩‍💼

Priya Nair, 27 — Analyst at an early-stage VC fund in Mumbai.
	Responsible for deal sourcing and preparing investment memos for the partners.
	Covers Fintech and D2C sectors.

</aside>

| **Dimension** | **Detail** |
| --- | --- |
| Goal | Build a defensible, data-backed investment thesis for her fund's next raise |
| Biggest frustration | Partners ask for city-level and stage-level breakdowns she can't quickly pull together |
| Current tools | PitchBook (expensive), Excel models, quarterly KPMG / Bain reports |
| Decision trigger | Needs to show partners a clear trend before they'll approve a new sector bet |
| Fear | Presenting a thesis that a partner immediately pokes holes in with a counter-dataset |
| Device | Always laptop, needs exportable charts for PowerPoint decks |

---

# Finding the Signal in the Noise

I analyzed 5,000+ startup funding rounds in India between 2019 and 2025,
across 6 cities, 8 sectors, and 4 funding stages. The 2025 data reflects
early signals from Q1 and Q2. The goal wasn’t to summarize what everyone
already knows. It was to surface patterns that don’t show up in headlines.

### City-wise funding breakdown

Bengaluru dominates every conversation about Indian startups — but the
data tells a more nuanced story. Delhi NCR punches well above its weight
in Fintech and D2C. Hyderabad is quietly becoming a Deeptech hub. Pune
is underfunded relative to its talent density.

| City | Total funding (2019–24) | Top sector | Fastest growing sector | Avg. deal size | Seed to Series A conversion |
| --- | --- | --- | --- | --- | --- |
| Bengaluru | ₹3.8L Cr | SaaS | Deeptech | ₹52 Cr | 18% |
| Delhi NCR | ₹2.1L Cr | Fintech | D2C | ₹34 Cr | 14% |
| Mumbai | ₹1.7L Cr | Fintech | Healthtech | ₹47 Cr | 16% |
| Hyderabad | ₹78,000 Cr | Deeptech | EV | ₹31 Cr | 13% |
| Pune | ₹45,000 Cr | SaaS | Agritech | ₹24 Cr | 11% |
| Chennai | ₹34,000 Cr | SaaS | Healthtech | ₹21 Cr | 10% |

<aside>
🟡

Bengaluru gets **52%** of all funding but has the same Seed-to-Series A
conversion as Mumbai — the advantage is deal volume, not deal quality.

</aside>

### Where the money is going in 2025

| Sector | 2025 H1 funding | vs. 2024 full year | Signal |
| --- | --- | --- | --- |
| EV | ₹14,000 Cr | 64% already | 🚀 Surging — only sector with unbroken growth since 2019 |
| Deeptech | ₹12,000 Cr | 67% already | 🚀 Surging — Hyderabad and Bengaluru leading |
| Fintech | ₹16,000 Cr | 55% already | 📈 Resilient — consistent through boom and winter both |
| SaaS | ₹15500 Cr | 58% already | 📈 Recovering — B2B SaaS driving most of the activity |
| Healthtech | ₹8,500 Cr | 61% already | 📈 Recovering — post-COVID fundamentals finally materializing |
| D2C | ₹7,200 Cr | 55% already | ➡️ Stabilizing — Delhi NCR recovering faster than Bengaluru |
| Agritech | ₹4,100 Cr | 59% already | ➡️ Stabilizing — slow but consistent |
| Edtech | ₹2,800 Cr | 56% already | 📉 Structurally weak — no recovery in sight |

<aside>
🟡

**The biggest finding**: the funding winter was not a market-wide event —
it was a late-stage, high-valuation, hype-sector correction. Investors
who stayed disciplined at Seed stage barely felt it. Mid-2025 is validating
that thesis.

</aside>

# Turning Insights Into a Product

Data analysis is only half the job. The PM question is: what should
someone actually be able to do with these insights? Every feature in
this product traces back to a specific finding — nothing was added
because it seemed useful in isolation.

### From insight to feature

| Insight from data | User pain it maps to | Feature it became |
| --- | --- | --- |
| City-level trends are invisible in most reports | Investors default to Bengaluru, miss opportunities elsewhere | City filter with side-by-side comparison view |
| Sector timing is everything — late entry kills returns | No early warning when a sector starts heating up | Sector momentum tracker with YoY signal |
| Seed stage was resilient, Series C froze | Investors don't know which stage is active right now | Stage activity heatmap by quarter |
| Edtech collapsed, EV never dipped | Hard to separate structural shifts from temporary dips | Trend health indicator — boom / stable / declining / collapsed |
| Pune and Hyderabad are undercovered | Investors miss non-Bengaluru deals entirely | Emerging city spotlight — flags undervalued geographies |

### Feature prioritization

Not everything could be built in v1. I used an Impact vs. Effort matrix
to decide what goes in first, what comes later, and what gets cut entirely.

| Feature | User impact | Effort to build | Priority | Rationale |
| --- | --- | --- | --- | --- |
| City comparison view | HIGH | Low | ✅ V1 | Core differentiator — no other tool does this well |
| Sector momentum tracker | High | Medium | ✅ V1 | Directly solves the timing problem |
| Stage activity heatmap | High | Medium | ✅ V1 | Answers the most common investor question |
| Trend health indicator | High | Low | ✅ V1 | Simple label, massive clarity gain |
| Emerging city spotlight | Medium | Low | ✅ V1 | Quick win, strong differentiation |
| Investor activity tracker | Medium | High | 🔄 V2 | Valuable but requires richer data |
| Deal size benchmarking | Medium | High | 🔄 V2 | Needs validated data — risky in V1 |
| Export to PDF / PPT | Low | Medium | 🔄 V2 | Nice to have for Priya (analyst), not critical for Rohan |
| Founder-facing view | Low | High | ❌ Cut | Different user entirely — out of scope for V1 |

### What the product looks like

The product is a single-screen dashboard with four core views.
The design principle was: one question, one answer, no scrolling.
An investor should be able to open it, set two filters, and have
their answer in under 2 minutes.

| View | What it shows | Primary user |
| --- | --- | --- |
| City overview | Funding totals, top sectors, and deal count by city — side by side | Rohan — angel investor |
| Sector momentum | YoY funding trend per sector with a health label | Both users |
| Stage heatmap | Which stages are most active by quarter and sector | Priya — fund analyst |
| 2025 signals | Early-trend snapshot — what's surging, stabilizing, or declining right now | Both users |

<aside>
🟡

Design decision: I deliberately left out a search bar and
a data table view in V1. Both add complexity without serving
the core job — helping an investor spot a trend fast.
They go on the V2 roadmap.

</aside>

# The Product Requirements Doc

<aside>
📋

This is a condensed PRD — written the way it would be shared
with an engineering and design team before a sprint begins.

</aside>

### Problem & goal

Early-stage investors in India spend 3–5 hours manually compiling
funding trend data before each investment decision. This product
reduces that to under 2 minutes by surfacing city, sector, and stage
trends in one place — regularly updated and instantly filterable.

### User stories

1. As an angel investor, I want to compare funding activity across
Indian cities so I can identify where deal flow is strongest
right now without having to read 10 different reports.
2. As an angel investor, I want to see which sectors are surging
vs. declining so I can time my investments before the crowd moves in.
3. As a fund analyst, I want to see stage-wise funding activity
by quarter so I can build a defensible thesis for partners.
4. As a fund analyst, I want an early signal on emerging cities
so I can recommend deals beyond the obvious Bengaluru default.

### Trade-offs I made

Every PRD has choices that need explaining. Here are the three
that shaped this product the most.

| Decision | What I chose | What I gave up | Why |
| --- | --- | --- | --- |
| Depth vs. speed | Fast, visual dashboard | Granular data tables | Core user (Rohan) needs direction, not raw data |
| Both users vs. one | Designed for Rohan first | Some features Priya needs | Better to nail one user than half-serve two |
| Real-time vs. curated | Curated, regularly updated data | Live API feed | Live data adds infra complexity with little V1 value |
| Feature richness vs. simplicity | 4 core views in V1 | Search, export, alerts | Complexity kills adoption for time-poor investors |

### Out of scope for V1

<aside>
🚫

Founder-facing features, valuation data, portfolio tracking,
investor profiles, and real-time API feeds are all out of scope
for V1. Not because they aren't valuable — but because they serve
a different user or require infrastructure that doesn't belong in
a first release.

</aside>

---

# The Road Ahead

This project taught me that the hardest part of product management
isn't building features — it's choosing what not to build. Every
table, every filter, and every view in this dashboard exists because
a specific user needed a specific answer. The ones that didn't
make the cut are sitting on a V2 roadmap for good reason.

<aside>
🟡

 If you're an investor, analyst, or PM who wants to talk about
this project — or poke holes in it — I'd love that conversation.

</aside>

---

Built by Vibhuti Gupta · [guptavibhuti2005@gmail.com]