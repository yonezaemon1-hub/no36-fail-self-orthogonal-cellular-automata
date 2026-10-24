# Historical computation report - not a rerun certificate

Recovered conversation reports, dated 24 October 2026:

| Search class | Reported cases | Reported self-orthogonal outcomes |
| --- | ---: | --- |
| Exactly quadratic central rule | 32,736 | 0 |
| Exactly cubic central rule | 33,521,664 | 0 |
| Linear central rule | 32 | 12 |

The degree-three number is for **exactly** degree three in the recovered detailed report, not all degrees up to three. The reported case totals match a five-variable algebraic normal form with zero constant term: 2^15-2^5=32,736 and 2^25-2^15=33,521,664; the linear class has 2^5=32 cases. Whether the original implementation explicitly used this normalization is not certified without its source. With both constant terms, the corresponding at-most-cubic total is 2^26=67,108,864. These arithmetic comparisons explain the numbers; they do not verify the original program or its output.

Original source, log, environment, test predicate, and independent implementation were not recovered. The author's Windows-machine execution is not established. No new quadratic/cubic/full-rule enumeration was run for this archive. The reports cannot be used as a universal nonlinear-impossibility proof or a substitute for the missing prior source.
