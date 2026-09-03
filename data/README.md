# Public data for the longitudinal PRL analyses

`prl_trials.csv.gz` contains the 1,000 analytic PRL sessions (160 trials each).
Choice labels A–C preserve within-session choice identity but not original deck
colors. `rewarded` is 1 for reward and 0 for loss.

`weekly_measures.csv` contains the ten R-GPTS persecution items (0–4), the
session-level HGF volatility prior (`mu03`), and Omicron concern where measured.
The notebook computes the R-GPTS persecution total from the ten released items.
`mu03` is a supplied estimate from the previously fitted HGF; the public Python
notebook evaluates this parameter but does not refit the HGF.

The three `supplementary_table_*.csv` files contain aggregate, non-identifying
inputs for final Supplementary Tables 1 and 2.

Participant IDs are study-specific pseudonyms. The mapping to recruitment
platform identifiers is not released.
