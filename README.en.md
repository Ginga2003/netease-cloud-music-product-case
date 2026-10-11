# NetEase Cloud Music | Product Research & Requirements Case

[中文](README.md) · [English case PDF](downloads/NetEase_Cloud_Music_Case_EN.pdf) · [中文案例 PDF](downloads/NetEase_Cloud_Music_Case_CN.pdf)

**Yiyu Mao / 毛一羽 · August–September 2026 · Product research and requirements design**

A mobile-product study connecting survey findings, public feedback and QQ Music/Spotify comparisons to three bounded proposals: **complete artist catalog browsing, promotion interruption control, and report-status transparency for comments and stranger interactions**.

This is a personal product-analysis exercise. The named products are research subjects. Deliverables are research and design artifacts; wireframes show proposed behavior and illustrative values. Business effects require future validation.

## Start here

| Artifact | What it shows |
| --- | --- |
| [English case](docs/en/case-study.md) / [PDF](downloads/NetEase_Cloud_Music_Case_EN.pdf) / [Editable DOCX](downloads/NetEase_Cloud_Music_Case_EN.docx) | Findings, scope revision, competitor lenses, three task flows, business rules, acceptance and validation |
| [English concept wireframes](assets/wireframes/en) | Six screens redrawn from the final PRD |
| [Full Chinese PRD](docs/zh/prd.md) / [PDF](downloads/Full_PRD_CN.pdf) | Architecture, flows, state rules, events, acceptance and traceability |
| [Research synthesis](docs/zh/research.md) | Aggregate results, association methods and interpretation boundaries |
| [Requirements analysis](docs/zh/requirements-analysis.md) | Twelve groups, thirteen scored entries and four prioritization criteria |
| [Competitive analysis](docs/zh/competitive-analysis.md) | QQ Music and Spotify comparisons by task, structure and business model |
| [Visual browsing page](index.html) | Download the repository and open this file in a browser; Chinese/English toggle |

## Research and evidence

The 19-question survey collected 159 responses and retained 110. Thirty public feedback items (15 positive, 15 negative) supported seven issue categories. Public artifacts use aggregate findings from the original project reports.

- Search: 109/110 respondents; personal music management: 72; recommendations: 64.
- Promotion friction: 51 (46.4%), rated 2.50/5.
- Navigation friction: 37 (33.6%).
- Catalog problems: 25 respondents; 23 reported changes in usage/payment. This supports an association-based hypothesis.
- Ages 18–30: 91.8%; students: 75.5%. Personal-network recruitment limits population generalization.

Association analysis used 3,000 permutation tests, Cramer's V / epsilon-squared, and Benjamini–Hochberg FDR adjustment across 34 tests. The advertising–behavioral-change association did not remain significant after adjustment. Individual-level data and filtering files stay local; the public package supports aggregate checks rather than complete statistical reruns.

## Decision trail

1. Organize seven issue categories into twelve requirement groups. R01 contains A/B subrequirements, giving thirteen scored entries.
2. Score reach, task impact, behavioral impact and evidence strength; use P0 gates for core-task blockers and safety.
3. Use QQ Music as the domestic direct competitor and Spotify as a product-model reference.
4. Recheck concrete feedback and existing capabilities. Remove weakly supported or dependency-heavy synchronization/cloud-library/licensing mechanisms from the final scope. Original scoring remains decision history.
5. Map scenario → flow → wireframe → event → acceptance in the **September 12, 2026 final PRD**.

## Final proposals

| Proposal | Design focus | Validation focus |
| --- | --- | --- |
| Artist catalog / P1 | Accessible full-catalog entry, type/date sorting, explicit playback scope, batch outcomes and retries | Discovery-task completion, batch success and recovery |
| Promotion control / P1 | Session limits, separate dismissal hit areas, task recovery and optional modules | Current-release retesting; experience and revenue guardrails |
| Report transparency / P0 | Server case IDs, review/evidence/outcome states, immediate exit and local blocking | Acceptance success, latency, visible outcomes and contact isolation |

Research and requirements are complete. Current-version verification, technical review, usability testing, a 14-day baseline and staged rollout are proposed next steps. Historical cutoffs remain explicit: research August 8, competitive report August 20, final PRD September 12, 2026.

## Package boundaries

The repository contains a complete English case, a Chinese case, six wireframes in each language, and the full historical supporting reports in Chinese. [Aggregate findings](data/aggregate-findings.json) include denominators and provenance. Original respondent records, contacts, resumes, private verification documents, signatures and working caches remain local. Third-party brands and referenced materials belong to their respective owners.

Public package assembled October 11, 2026. Original project files are preserved locally.
