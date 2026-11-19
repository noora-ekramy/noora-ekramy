# Nora Ekramy

**Applied AI Engineer.** I build production AI systems for domains where being wrong is expensive.

I design and build AI systems end to end — turning an ambiguous business problem into a deployed service with retrieval, structured extraction, evaluation, and human review where it matters. Most of my work has been in financial operations, real estate, and legal document processing.

## What I build

- **Document intelligence** — structured extraction from messy PDFs and statements
- **Retrieval over private data** — RAG that has to survive real organizational corpora
- **LLM orchestration with constrained writes** — the model may propose; the system decides what may commit
- **Evaluation as infrastructure** — knowing a prompt change still works tomorrow
- **Multi-channel delivery** — one brain behind chat, avatar, voice, and telephony

## Selected systems

Case studies live on [noraekramy.com](https://noraekramy.com). Client names are omitted; no measured results are claimed until they can be published.

| System | Hard part | Authored commits* |
|---|---|---|
| [Conversational accounting](https://noraekramy.com/work/constrained-writes-accounting) | Model can propose ledger changes and commit none of them | **409 / 863** |
| [Bank-statement extraction](https://noraekramy.com/work/structured-extraction-statements) | Every institution formats statements differently | part of the accounting system above |
| [Multi-service buyer's agent](https://noraekramy.com/work/evaluating-a-multi-service-agent) | Evaluation harness so prompt changes do not silently break the journey | **724 / 797** |
| [One brain, four channels](https://noraekramy.com/work/one-brain-four-channels) | Thin channel adapters over a single orchestrator | shared with the platforms above |

\*Deduplicated by commit hash on the private product repositories (verified 2026-08-08). Numerator = commits I authored; denominator = all commits in that repo. These are **not** GitHub public contribution totals — most of this work is private.

## Currently

Co-Founder & AI Engineer at [Youtiva](https://youtiva.com/), where I own AI architecture and still write the systems myself.

## A note on public activity

Public GitHub is only a slice of the work — most production systems live in private company and client repositories. The case studies and commit shares above are the better signal for depth.

## Research

**[NEUROPHONE: Real-Time Brain-Mobile Phone Interface](https://doi.org/10.3217/978-3-99161-014-4-085)** — 9th Graz Brain-Computer Interface Conference 2024. Fourth of five authors.

A P300-based BCI for smartphone control through visual attention. I contributed to EEG data collection, signal preprocessing, and CNN training. Under 5-fold cross-validation the lightweight CNN reached **98% average classification accuracy** and **0.95 F1**, ahead of EEGNet, ChronoNet, DCRNN, and RNN baselines. End-to-end latency was not accurately measured in the paper.

## Writing

- [A model may propose anything and commit nothing](https://noraekramy.com/writing/propose-anything-commit-nothing)
- [When an agent should just be a workflow](https://noraekramy.com/writing/when-an-agent-should-be-a-workflow)

## Links

- Website: [noraekramy.com](https://noraekramy.com)
- LinkedIn: [nora-ekramy](https://www.linkedin.com/in/nora-ekramy-89b2681b4)
- Email: [nora@youtiva.com](mailto:nora@youtiva.com)
