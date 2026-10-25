# Book Research Lab execution plan

Prepared 2026-10-25. **Queued; implementation inactive.** Original idea #2.

## Product contract

Reconstruct sequenced depth where available, test short-horizon prediction against simple baselines, report gaps and costs. Predicting mid-price moves does not establish executable profit.

## Architecture and data

Public LOB sample or generated stream first. Longer compliant self-recorded depth and trades may be used after rights review; snapshot-only history is not event-complete. Version inputs and generated seeds. Separate ingestion/generation, domain model, evaluation and public interface. First measure a bounded local run; paid data and cloud compute are outside this plan.

## Evaluation contract

Book integrity metrics, feature definitions, blocked time splits, baseline-vs-model results across days, horizon decay, failure cases and cost limits. Prespecify baselines, data splits and failure categories before final evaluation. Record exact commands, resource measurements, all tried variants and negative results. Simulated evidence remains separate from real-market or user validation.

## Milestones and hours

Months are relative to future activation. First public functional result: month 3; final decision: by month 12. One candidate uses the shared 16-hour weekly capacity, never six concurrent commitments. Total 420 hours includes 120 reserve.

| Milestone | Relative window | Task hours | Reserve | Cumulative |
| --- | --- | ---: | ---: | ---: |
| QB-M1: Data rights and event semantics | Months 1–2 | 50 | 20 | 70 |
| QB-M2: Book replay and feature slice | Months 1–2 | 50 | 20 | 140 |
| QB-M3: First public integrity artifact | Month 3 | 50 | 18 | 208 |
| QB-M4: Leakage-controlled modeling | Months 5–7 | 50 | 22 | 280 |
| QB-M5: Robustness and cost boundary | Months 6–8 | 50 | 20 | 350 |
| QB-M6: Final research case and product decision | Months 7–12 | 50 | 20 | 420 |

## Public result and release gate

At milestone 3 publish a runnable artifact, generated or permitted inputs, correctness checks, a baseline, exact run instructions and an honest limitations report. This planning repository is not that artifact. A later stable release needs reproducible evaluation, failure evidence, bounded resource use and a named user workflow.

## Product decision

Integrity or research tooling may be reusable; alpha sales and live trading claims are unsupported without broad data and fills. If gaps invalidate reconstruction or gains disappear across days, retain the integrity tooling and publish the negative research result. At each milestone decide continue, narrow or park using actual hours and evidence. No recurring monitor, spending, live trading, conference submission or implementation is activated by this plan.
