# NetEase Cloud Music | Product Research and Requirements

[中文](README.md) · [English case PDF](downloads/NetEase_Cloud_Music_Case_EN.pdf) · [中文案例 PDF](downloads/NetEase_Cloud_Music_Case_CN.pdf)

**Yiyu Mao / 毛一羽 · Personal course project · User research and product requirements**

Survey responses, public feedback and hands-on task records inform seven issue categories, twelve requirement groups and three proposals: **complete artist catalog browsing and organization, promotion interruption control, and transparent report handling for comments and stranger interactions**.

Deliverables are a research report, requirement analysis, competitive analysis and PRD. Diagrams and concept pages describe proposed behavior. Implementation and business impact require subsequent validation.

## Start here

| Material | Contents |
| --- | --- |
| [English case](docs/en/case-study.md) / [PDF](downloads/NetEase_Cloud_Music_Case_EN.pdf) / [DOCX](downloads/NetEase_Cloud_Music_Case_EN.docx) | Eight-page case covering evidence, selection, competitor inputs, three proposals and validation |
| [中文案例](docs/zh/case-study.md) | Equivalent Chinese case and diagrams |
| [Research report](docs/zh/research.md) / [PDF](downloads/Research_Report_CN.pdf) | Survey findings, public feedback, task checks and evidence limits; Chinese |
| [Requirement analysis](docs/zh/requirements-analysis.md) / [PDF](downloads/Requirements_Analysis_CN.pdf) | Seven categories, twelve groups and selection criteria; Chinese |
| [Competitive analysis](docs/zh/competitive-analysis.md) / [PDF](downloads/Competitive_Analysis_CN.pdf) | QQ Music, Spotify and targeted mechanism references; Chinese |
| [PRD](docs/zh/prd.md) / [PDF](downloads/Full_PRD_CN.pdf) | Rules, flows, states, exceptions, metrics and acceptance; Chinese |
| [English diagrams](assets/wireframes/en) / [中文图示](assets/wireframes/zh) | Participation relations, promotion eligibility and four concept pages |
| [Bilingual browsing page](index.html) | Download the repository and open in a browser |

## Evidence-to-design chain

The 19-question survey collected 159 responses. Eight failed hard quality checks and another 41 were excluded in further screening, leaving 110. Thirty public feedback items, evenly sampled for positive and negative examples, add qualitative task context. Screenshots and task records from iOS 9.6.15 check specific capability gaps.

- 51/110 selected ads, pop-ups or activity prompts affecting use (46.4%); the relevant experience rating was 2.50/5.
- 37/110 selected information or entry-point friction (33.6%). Search, personal music management and recommendations were main functions for 109, 72 and 64 respondents respectively.
- Survey findings guide attention; concrete cases and checks of existing capabilities define the proposed changes.
- Selection considers **problem severity, evidence strength, reach and implementation dependencies**. Licensing procurement and complex synchronization remain in the wider requirement pool.

## Three proposal directions

| Proposal | Design | Validation focus |
| --- | --- | --- |
| Artist catalog / P1 supporting proposal | Retain Various Artists credits; verify contributor roles; repair artist–album relations and refresh existing lists; review conflicting differences | Discoverability from artist pages, accurate versions and participation scope, reversible errors |
| Promotion control / P1 main experience proposal | Check task, entitlement, dismissal and shared limits before matching content and format; protect music information and key entries; cancel missed opportunities | Task completion, elapsed time, mistaken navigation, effective rejection, valid conversion and revenue per use |
| Report feedback / P0 foundation | Persistent records after acceptance, truthful handling states, explanations for all closures, personal blocking and applicable next actions | Acceptance, progress visibility, closure coverage, record/notification consistency and immediate exit |

## Competitor inputs

- **Catalog relations:** Spotify compilations / Appears On and TuneCore Japan participating works support accurate compilation credits alongside verified artist links.
- **Promotion:** QQ Music personalization and Spotify preferences / ad-set caps separate relevance, rejection and exposure control. This proposal adds shared interruption rules across pages and preserves basic entries within personalized layouts.
- **Reporting:** Spotify interaction and reporting guidance, plus YouTube report history, inform exit controls, state clarity, outcome explanations and query coverage.

Official references were checked on November 1, 2026, with region, version and ad-product limits stated separately. Mobile task testing remains part of the validation plan. See the [competitive report](docs/zh/competitive-analysis.md) for sources.

## Delivery and evidence limits

The four reports, flows, concept pages, metrics and acceptance criteria are complete. Technical review, prototype task tests, baseline collection and limited rollout are next steps. Promotion control is the main experience proposal; reporting P0 denotes safety and trust foundations.

Ages 18–30 account for 91.8% and students for 75.5%. Personal-network recruitment limits generalization. Association analysis uses 3,000 permutations, BH FDR correction across 34 tests, Cramer’s V and eta-squared H. The advertising–self-reported-change association did not remain significant after adjustment. Retention and revenue benefits require experiments.

[Aggregate findings](data/aggregate-findings.json) include counts, denominators and provenance. Respondent-level data remains local. Third-party brands and materials belong to their owners; see [NOTICE](NOTICE.md).
