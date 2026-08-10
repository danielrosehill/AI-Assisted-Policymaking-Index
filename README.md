# AI-Assisted Policymaking Index

[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Github-Master-Index)
[![Index Repo](https://img.shields.io/badge/Type-Index_Repo-purple?style=flat-square)](https://github.com/danielrosehill/Subindices)
[![GitHub](https://img.shields.io/badge/GitHub-danielrosehill-blue?style=flat-square&logo=github)](https://github.com/danielrosehill)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

An index of repositories that use AI to **formulate and explore public policy** — manifestos,
policy papers, multi-lens deliberation runs, and the research workspaces behind them.

The subject is *policy made with AI*, not *policy about AI*. AI governance, alignment and
responsible-AI material lives in
[AI-Safety-Projects-Index](https://github.com/danielrosehill/AI-Safety-Projects-Index).

See [SCOPE.md](SCOPE.md) for what belongs here and how this index relates to the neighbouring ones.

---

## Platforms & Manifestos

Sustained attempts to build a full political platform with AI assistance, published in public while
unfinished.

| Project | Description | Links |
|---------|-------------|-------|
| **MK-Claude** | A national political platform for Israel — a manifesto for a party that doesn't exist, built the way a platform ought to be: researched, cited, costed and honest about who loses as well as who gains. Policy moves through four gated stages, from dated first-person testimony to a think-tank-style paper. Ships the `policy-development-assistant` Claude Code plugin and publishes as an Astro/Starlight site | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/MK-Claude) |
| **Claude-For-Mayor** | The municipal sibling — a Jerusalem mayoral platform. It forks MK-Claude's *method*, not its content, and adds a gate the national repo has no need for: **no proposal is published without a named legal instrument and the named body that holds it**, with every lever classified A–D by how much power the municipality actually has. The highest-value output of that gate is an unused class-A power. Ships the `municipal-policy-assistant` plugin with an Israeli CBS statistics MCP server bundled | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Claude-For-Mayor) |

## Deliberation Methods

Machinery for putting a policy problem through several specialist lenses at once, and the runs that
came out of it.

| Project | Description | Links |
|---------|-------------|-------|
| **LLM-Council-Policy-Ideation** | A variant of Karpathy's LLM Council tuned for local-governance problems. Six specialist lenses — urban planner, municipal fiscal officer, community & equity advocate, legal & regulatory analyst, service-delivery practitioner, comparative policy scholar — respond independently, peer-review each other anonymised, and a Chairman synthesises a structured Policy Ideation Report with a Typst PDF digest. The template to fork for a new question | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/LLM-Council-Policy-Ideation) |
| **Jerusalem-Honking-LLM-Council-Run** | A concrete run of that template against one real problem: chronic noise from unnecessary car-horn use in Jerusalem. Carries the narrated problem statement, the grounding material, the council output from the run of 2026-04-23, and scripts for Hebrew translation and report rendering. The worked example to read before writing your own problem statement | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Jerusalem-Honking-LLM-Council-Run) |

## Single-Issue Policy Research

One question, taken seriously, with the evidence kept separate from the argument.

| Project | Description | Links |
|---------|-------------|-------|
| **Claude-ADHD-Research-Workspace** | A live, public research workspace on ADHD drug-access policy, run as a Claude Code project: `/context` as a hand-chunked mini-RAG, `/prompts` staged into drafting / to-run / run, `/outputs` gathered and distilled towards PDF. Deliberately dual-purpose — a real policy project *and* an exhibit of the repo-as-research-workspace pattern | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Claude-ADHD-Research-Workspace) |
| **Israel-ADHD-Medication-Access** | The evidence layer under that workspace: a redacted case record of trying to fill a valid, in-date controlled-stimulant prescription in Jerusalem between 29 July and 9 August 2026. Written from primary material — counter recordings and transcripts, correspondence with the district pharmacist, closure letters from the health fund and the Ministry of Health, and the published procedures the whole thing was supposed to run on, including the regulation nobody mentioned | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Israel-ADHD-Medication-Access) |

## Other People's Work

| Project | Description | Links |
|---------|-------------|-------|
| **AI-Geopol-Projects** | Not my own projects — a curated list of other people's work on AI wargaming, policy simulation and strategic forecasting (Snowglobe, WargamesAI and similar), including simulated policy fora. Kept as a source of methods worth stealing for the repos above | [![View Repository](https://img.shields.io/badge/View-Repository-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/AI-Geopol-Projects) |

---

## The recurring method

These repos were built separately but converge on the same shape, and the convergence is the
interesting part:

| Element | What it looks like |
|---|---|
| **Evidence before proposal** | Nothing is proposed from the armchair. A policy area opens on a dated first-person account (MK-Claude, Claude-For-Mayor) or a documented case record (the ADHD pair), and the account is kept as its own artifact rather than paraphrased away |
| **An authority gate** | Before *what should be done*, establish *who may do it*. Claude-For-Mayor's A–D power classification is the fullest version; the same instinct shows up as "which instrument creates this?" everywhere else |
| **A citation rule that bites** | An uncited claim is marked `[UNVERIFIED]` and **blocks advancement**, rather than being quietly published with a hedge |
| **Several lenses, then a synthesis** | The council pattern — independent specialist responses, anonymised peer review, a Chairman who names tensions rather than dissolving them |
| **Published while unfinished** | Status tables that say what is unverified, and version history that keeps changes of mind visible |

Anything that adopts most of that shape on a policy question belongs in this index, whatever the
tooling.

---

## Related Indexes

| Index | Covers |
|---|---|
| [AI-Safety-Projects-Index](https://github.com/danielrosehill/AI-Safety-Projects-Index) | Policy *about* AI — safety, ethics, responsible development. The opposite direction to this index |
| [Geopolitical-And-OSINT-Index](https://github.com/danielrosehill/Geopolitical-And-OSINT-Index) | OSINT, geopolitical analysis and situational awareness |
| [Geopol-Forecasts-Index](https://github.com/danielrosehill/Geopol-Forecasts-Index) | Forecast runs and their accuracy tracking — prediction rather than prescription |
| [Awesome-LLM-Council-Projects](https://github.com/danielrosehill/Awesome-LLM-Council-Projects) | Every LLM Council variant, policy or otherwise |
| [Open-Research-Workspaces-Index](https://github.com/danielrosehill/Open-Research-Workspaces-Index) | Public research notebooks across all subjects |
| [Israel-Projects-Index](https://github.com/danielrosehill/Israel-Projects-Index) | Israel-related repositories generally |

---

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
