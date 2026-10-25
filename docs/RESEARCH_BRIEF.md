# Research brief

Source idea: #2 in the original ten-idea document. Revised ranking: high-effort.

## Product and evidence boundary

Reconstruct sequenced depth where available, test short-horizon prediction against simple baselines, report gaps and costs. Predicting mid-price moves does not establish executable profit.

## Data path

Public LOB sample or generated stream first. Longer compliant self-recorded depth and trades may be used after rights review; snapshot-only history is not event-complete.

## Research evidence

Book integrity metrics, feature definitions, blocked time splits, baseline-vs-model results across days, horizon decay, failure cases and cost limits.

## Product hypothesis and stop rule

Integrity or research tooling may be reusable; alpha sales and live trading claims are unsupported without broad data and fills. If gaps invalidate reconstruction or gains disappear across days, retain the integrity tooling and publish the negative research result.

## Source link and data caution

[LOBSTER's message and order-book samples](https://data.lobsterdata.com/info/DataSamples.php) support parser and feature checks. A short sample cannot establish an across-day alpha claim. Check terms before using or redistributing any raw data; snapshot-only history cannot reconstruct intervening order-flow events.

Planning assessment: 19 October 2026.
