# Scope — AI-Assisted Policymaking Index

## What belongs here

Repositories where **AI is used to produce or interrogate a policy position** — a manifesto, a
policy paper, a set of costed proposals, or a structured deliberation over a public problem.

Include a repo if it does one of:

- **Builds a platform or manifesto** at any tier of government — national, municipal, agency
- **Encodes a policy method**: a pipeline, a gate, an evidence rule, a classification scheme for
  legal authority
- **Runs a deliberation** over a public problem — council patterns, multi-lens panels, adversarial
  review — and keeps the output
- **Researches a single policy question** in depth, with the working kept in the open
- **Assembles a case record** as the evidence base for a policy argument, where the argument is the
  point of the record

The defining test: **does the repo end in a claim about what should be done, and is that claim
traceable to something?** If yes, it belongs here.

## What does NOT belong here

- **Policy about AI.** AI governance, alignment, safety and responsible-AI work →
  [AI-Safety-Projects-Index](https://github.com/danielrosehill/AI-Safety-Projects-Index). The name
  of this index invites exactly that misfile; it is the single most likely one
- **Forecasting rather than prescription.** "What will happen" is not "what should be done" →
  [Geopol-Forecasts-Index](https://github.com/danielrosehill/Geopol-Forecasts-Index) and
  [Geopolitical-And-OSINT-Index](https://github.com/danielrosehill/Geopolitical-And-OSINT-Index)
- **Council and deliberation machinery with no policy subject.** The decision, career, health and
  hypothesis councils are the same pattern pointed elsewhere →
  [Awesome-LLM-Council-Projects](https://github.com/danielrosehill/Awesome-LLM-Council-Projects)
- **Civic-data infrastructure with no policy argument.** `noisycity-api-blueprint` and
  `esp32-porch-decibel-monitor` design the plumbing that would *generate* evidence for a noise
  policy. They stay out until a repo builds the argument on top of them
- **Consumer complaints and disputes** handled as personal administration rather than as a case for
  changing a rule
- **Israel reference material** — regulations, standards, translated official guidance →
  [Israel-Reference-Repos](https://github.com/danielrosehill/Israel-Reference-Repos)

## Edge cases

- **Case records.** In scope only when a policy argument is built on the record. The ADHD pair is
  the model: the case record lives in one repo, the policy work in another, and both are listed —
  the record because it is the evidence, the workspace because it is the argument
- **Plugins.** A Claude Code plugin that encodes a policy method is listed **with its parent repo**,
  not separately, while it ships inside that repo. If it is extracted to its own repo it gets its
  own entry here *and* an entry in the plugin indexes
- **Templates vs runs.** Both are listed. The template is what you fork; the run is what shows the
  method surviving contact with a real question. Link each to the other in the description
- **Other people's work.** One curated list of external projects is kept here as a feed of methods.
  Individual third-party projects are not listed — they belong inside that list
- **Tier of government.** National and municipal both belong. Where a repo could sit in a
  geography-specific index as well, list it in both — this index cuts by *what the repo does*, the
  Israel indexes cut by *what it is about*

## Privacy

This index is public and lists **public repositories only**.

Several entries have private companions — unredacted case files, correspondence, and material
naming individuals. Those are deliberately unlisted, and an entry here should never link into one
or describe its contents.
