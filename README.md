# Max Moran

Financial crime and digital asset compliance professional (CAMS) based in the NYC metro area. Focused on the intersection of crypto, AML/CFT, and AI-assisted compliance tooling — on-chain monitoring, KYT alert triage, typology detection, and regulatory intelligence.

A collection of personal projects covering autonomous agent systems, blockchain intelligence dashboards, and compliance frameworks. All work here is independent and built outside of professional engagements.

---

## Pinned

- **[Claude Agent Fleet](https://github.com/maxmoran23/Claude-Agent-Fleet)** — Production-grade autonomous agent framework on Claude Code. Thirteen architectural patterns — agent kernel with local-state authority, idempotency outbox, human-gated self-modification (propose-and-gate), generated fleet registry with drift detection and deadman liveness, independent eval harness, JIT budget throttling, self-repair, fleet evolution, and more — plus six runnable Python reference agents wired to GitHub Actions, twenty-five example agent specs (including a compliance-operations tier: sanctions-list and PEP screening, control testing, risk register maintenance, data-quality gating, case-file QA, model governance, committee reporting, examination response), structural CI lint over every spec, and companion analytical dashboards with live demos.
- **[analyst-toolkit](https://github.com/maxmoran23/analyst-toolkit)** — Reference library for AI-assisted analytical work at financial institutions, covering every function of a financial-crime organization. 70 copy/paste prompt templates across 13 categories, 14 runnable pure-stdlib scoring engines that each ship reproducible validation evidence (false-negative safety gates enforced in CI), and 15 team hubs indexing it all by who does the work — sanctions and screening, transaction monitoring, fraud, surveillance, investigations, crypto, controls and testing, model risk, data governance, new-product approval, regulatory affairs. Three workflows (methodology base + thin prompts, single-file standalone, browsable catalog), a multi-format Word/Excel/PDF/HTML renderer, and a dependency-free quant library in Python with a parity-tested Kotlin/JVM port.

## AI Agents & Automation

- **Claude Agent Fleet** *(see above)* — JIT budget management with declared model-policy tiers, weekly gated self-evolution loop with experiment tracking, multi-channel Slack orchestration, SQLite append-only data layer, local state-file authority with canvas display mirrors for persistent inter-run memory.
- **Fleet Console** — Bloomberg-terminal style dashboard for monitoring agent fleet health. Composite indices, trend charts, and an agent maturity matrix. Local Express deployment.

## Blockchain Intelligence

- **Signal Forge** — Digital asset intelligence terminal pulling on-chain data (Blockscout), market signals (Crypto.com), and social sentiment (LunarCrush) into a single monitoring surface.
- **KYT Triage Dashboard** — Alert triage cockpit for crypto transaction monitoring. Severity queue, drill-down on flagged addresses, filter by typology and exposure.

## Regulatory & Compliance Tools

- **Crypto AML Typology Engine** — Interactive reference library covering 15 crypto money laundering typologies with detection rules, investigation playbooks, and regulatory citations. Live demo in the [Claude Agent Fleet showcase](https://github.com/maxmoran23/Claude-Agent-Fleet/tree/main/showcase).
- **Reg Intelligence Tracker** — Digital asset regulatory landscape tracker. Legislation status, agency actions, enforcement timelines, and a cross-impact matrix covering the major frameworks. Live demo in the [Claude Agent Fleet showcase](https://github.com/maxmoran23/Claude-Agent-Fleet/tree/main/showcase).
- **Digital Asset AML Control Matrix** — 27-control reference framework spanning CDD, transaction monitoring, sanctions screening, SAR filing, and governance. Written as a generic bank-side architecture, not tied to any specific institution.

## Data & Analytics Dashboards

- **Betting Portfolio** — Systematic edge research dashboard. Hypothesis testing for positive expected value, quarter-Kelly position sizing, and out-of-sample validation across market segments.
- **Betting Analytics Deep Dive** — Statistical validation layer for the above. Closing-line value analysis, variance decomposition, and process-vs-outcome diagnostics to isolate skill from variance.

## Research & Experimental

- **Exotic Propulsion Observatory** — Breakthrough-physics intelligence hub. Tracks anti-gravity, zero-point energy, and metric engineering research across arXiv, NASA, AARO, and FOIA sources with a theory-network visualization.
- **Personal Portfolio Site** — [maxmoran.org](https://maxmoran.org) (in development). Writeups on compliance topics, project summaries, and a central hub for the above.
