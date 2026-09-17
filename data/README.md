# Public data for the longitudinal PRL analyses

`prl_trials.csv.gz` contains the 1,000 analytic PRL sessions (160 trials each).
Choice labels A–C preserve within-session choice identity but not original deck
colors. `rewarded` is 1 for reward and 0 for loss.

`weekly_measures.csv` contains the ten R-GPTS persecution items (0–4), the
session-level HGF volatility prior (`mu03`), the supplied HGF tonic-volatility
fits (`omega2`, `omega3`) and their two half-session estimates, and Omicron
concern where measured.
The notebook computes the R-GPTS persecution total from the ten released items.
The HGF quantities are supplied estimates from a previously fitted model; the
public Python notebook evaluates these parameters but does not refit the HGF.
The original fitting workflow and optimizer diagnostics are not reproduced in
this release. The two half-session fits are order-dependent rather than
independent replications, so omega analyses remain provisional pending
verification or refitting of the original HGF implementation.

The three `supplementary_table_*.csv` files contain aggregate, non-identifying
inputs for final Supplementary Tables 1 and 2.

Participant IDs are study-specific pseudonyms. The mapping to recruitment
platform identifiers is not released.
