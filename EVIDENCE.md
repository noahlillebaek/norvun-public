# Research standards & limitations

[← Norvun overview](README.md) · [Statistical inference](STATISTICAL_INFERENCE.md)

## Historical evaluation

Norvun’s internal U.S. business-cycle research examines historical macroeconomic release vintages and retrospective out-of-sample assessment. Comparing model families against meaningful benchmarks is central to the evaluation design.

| Research concern | Why it matters |
| --- | --- |
| Point-in-time integrity | An observation or revised label may not have been known at the historical forecast origin. Using it prematurely introduces look-ahead bias. |
| Benchmark selection | A model must be evaluated against meaningful alternatives, not solely against its own fit. |
| Probability scoring | Mean squared prediction error (Brier score) and logarithmic loss assess probabilistic predictions differently. |
| Calibration and discrimination | Agreement between estimated probabilities and observed relative frequencies (calibration) is distinct from the ability to rank outcomes (discrimination). |
| Temporal dependence | Monthly origins and overlapping horizons do not constitute independent experiments. Serial dependence limits the use of standard iid sampling assumptions. |
| Model selection | Repeated specification comparisons can introduce selection bias and make retrospective findings optimistic. Estimation uncertainty matters when comparing models. |

## Research disclosure

This portfolio shares selected research questions and evaluation principles. Detailed numerical results, historical predictions, current estimates and source datasets remain private. Independent reproduction of the original results is outside the scope of this public overview. Retrospective evaluation and prospective performance are distinct research stages.

## Engineering principles

The Economic State Engine research concerns source-native economic observations, dated releases, revisions and historical as-of reconstruction. Data integrity and forecast validation are distinct research disciplines. The architecture overview presents Norvun’s intended product direction.

[Disclosure & usage](NOTICE.md)
