# Binary Payment Schemes: Moral Hazard and Loss Aversion — Experimental Design

[![Status](https://img.shields.io/badge/Status-Completed-green)]
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex)]
[![Course](https://img.shields.io/badge/Course-Market%20Design%20and%20Behaviour-blue)]

Academic presentation proposing an experimental design to test the central
prediction of Herweg, Müller, and Weinschenk (2010), *Binary Payment
Schemes: Moral Hazard and Loss Aversion*.

## Project Information

| Item | Details |
|---|---|
| Author | Theo Osterhaus, 7443693 |
| Faculty | Faculty of Management, Economics and Social Sciences |
| Course | Seminar Market Design and Behaviour, SuSe 2026 |
| Institution | Universität zu Köln |
| Date | June 2026 |
| Format | Academic presentation (experimental design proposal) |
| Main paper | Herweg, Müller & Weinschenk (2010), *American Economic Review* |

## Abstract

This project proposes a laboratory experiment to test the central,
previously untested prediction of Herweg, Müller, and Weinschenk (2010):
that binary bonus contracts induce higher effort than richer, multi-level
contracts once expectation-based loss aversion is taken into account. Using
a real-effort slider task (Gill & Prowse, 2019) in a 2×2 between-subject
design, the study manipulates contract structure (binary vs. multi-level)
and reference point (low vs. high), while independently eliciting
participants' individual loss aversion parameter.

## Research Question

> Do binary bonus contracts increase effort beyond multi-level contracts,
> and is this effect driven by agents' expectation-based loss aversion?

## Outline

1. Motivation
2. Related Literature
3. Experiment Design
4. Analyses

## Motivation: Why Binary Schemes?

Classical contract theory (Holmström, 1979) predicts that optimal contracts
should be **complex**, exploiting all available information. In practice,
real-world contracts are often remarkably **simple** (e.g., binary bonus
schemes, flat wages).

Herweg, Müller, and Weinschenk (2010) address this puzzle by introducing
**expectation-based loss aversion** into the standard principal-agent model
with moral hazard, building on Kőszegi and Rabin (2007). They identify a
trade-off between two opposing effects of adding wage levels:

| Effect | Description |
|---|---|
| Incentive Gain | More wage levels (complexity) provide better incentives |
| Loss Aversion Cost | Every additional wage level creates more possible unfavourable comparisons, raising expected psychological costs |

**The gap:** The central theoretical prediction — that binary payment
schemes are optimal — has not yet been directly tested empirically.

## Related Empirical Literature

| Study | Contribution |
|---|---|
| Abeler et al. (2011) | Laboratory experiment showing expectation-based reference points directly drive workers' effort provision |
| Crawford & Meng (2011) | Shows a model with expectation-based targets significantly outperforms the neoclassical benchmark in predicting cab drivers' effort |

This project builds on Abeler et al. (2011) by explicitly testing the
**contractual solution** (binary vs. multi-level) proposed by Herweg,
Müller, and Weinschenk (2010), rather than the existence of
expectation-based reference points per se.

## Experimental Design

### Sampling & Recruitment

- **Target population**: Undergraduate and graduate students across various disciplines
- **Recruitment**: University subject pool system (e.g., ORSEE, Cologne Laboratory for Economic Research)
- **Sample size**: N = 252 (63 per treatment group), based on a priori power analysis (α = 0.05, 1−κ = 0.80) for a medium effect size
- **Randomisation**: Pure between-subject design; random assignment to one of 4 conditions
- **Incentives**: Performance-based pay + base show-up fee (e.g., 2.5€) to minimise selection bias and attrition

### 2×2 Between-Subject Design

|  | Low Reference Point | High Reference Point |
|---|---|---|
| **Binary Contract** | G1 | G2 |
| **Multi-level Contract** | G3 | G4 |

### Experimental Flow

1. **Instructions & Control Questions** (~8 min) — general rules, slider task tutorial, comprehension test
2. **Round 0: Baseline Task** (~3 min) — unrewarded measurement of individual ability
3. **Round 1: Main Task** (randomised to 1 of 4 groups) — real-effort task under assigned contract/reference-point condition
4. **Post-Experimental Questionnaire** (~10 min) — loss aversion, risk preference, checks, demographics
5. **Payout / Incentive Realisation** (~5 min) — show-up fee + earnings from Round 1

### Real-Effort Task: Slider Task (Gill & Prowse, 2019)

- Participants move 48 sliders to position 50
- Time limit: 120 seconds per round
- Real-time feedback on correctness
- Outcome measure: number of sliders correctly positioned

### Round 0: Baseline Task

- Unpaid slider task determines individual ability `a_i`
- Success probability standardised across participants: `ê_i = 0.8 × a_i`
- Ensures loss aversion effects are comparable across groups and effort
  differences reflect behavioural response, not underlying ability

### Post-Experimental Survey

| Variable | Method |
|---|---|
| Loss Aversion (λᵢ) — primary variable | Incentive-compatible lottery choice task (Gächter et al., 2007); 6 coin-toss decisions |
| Risk Preference (ρᵢ) — control | SOEP general risk attitude scale (0–10) & financial risk domain |
| Demographics & Controls (Xᵢ) | Age, gender, field of study, self-assessed math/cognitive ability |

## Data Analysis Plan

### Model 1: 2×2 Factorial Design


**Hypotheses:**

| Hypothesis | Prediction |
|---|---|
| H1 | β₁ ≥ 0 — Binary contract yields equal or greater effort than multi-level |
| H2 | β₂ > 0 — High reference point strictly increases effort |
| H3 | β₃ < 0 — The High RP effect is smaller under the Binary contract (interaction) |

Given the RCT design, individual personality traits do not need to be
separately instrumented.

## Discussion

### Design Choice: Real-Effort Slider Task

Brüggen & Strobel (2007) show that "real effort" and "chosen effort" tasks
produce different effect sizes. The slider task (Gill & Prowse, 2019) was
chosen because it:

1. **External validity** — realistic work behaviour relevant for practice
2. **Theoretical fit** — Herweg, Müller, and Weinschenk (2010) is
   interested in real effort decisions, not stylised choices
3. **Mechanism clarity** — loss aversion affects actual productivity, not
   just the psychology of choice

### Limitations & Trade-offs

- **Ability confounder**: Round 0 measurement may itself create strategic
  incentives to under-perform in order to secure an artificially low
  baseline
- **Deception & rational expectations**: The lottery task avoids deception
  but may feel artificial relative to real-world peer comparisons
  (precedent: Abeler et al., 2011)
- **Corner solutions in effort**: Marginal cost of physical effort/fatigue
  may be negligible; unclear whether bonuses of up to 8€ provide sufficient
  incentive; no control group without payment
- **Disentangling risk aversion from loss aversion**: The intermediate wage
  in multi-level contracts provides partial insurance and reduces income
  variance, making it difficult to conclusively attribute effort
  differences to loss aversion rather than standard risk aversion

### Appendix: Between-Subject Design Considerations

- **Low statistical power** → addressed via multiple rounds per person and covariates
- **No intra-individual comparison** → addressed via randomisation (RCT), which ensures causal identification
- **Why a within-subject design would contaminate the reference point**: The
  reference point is not the status quo but the rational expectation
  regarding one's own wage distribution; exposing the same participant to
  multiple contracts would confound this expectation

## Materials

- [Presentation PDF](./Osterhaus_Binary_Payment_Schemes__Moral_Hazard_and_Loss_Aversion__Experiment.pdf)
- [LaTeX source](./main.tex)
- [Bibliography](./references.bib)

## Reproducibility

The presentation was created with LaTeX (Beamer). The main source file is
`main.tex`; references are stored in `references.bib`.

## References

- Abeler, J., Falk, A., Goette, L., & Huffman, D. (2011). *Reference Points and Effort Provision*. American Economic Review, 101(2), 470–492.
- Brüggen, A., & Strobel, M. (2007). *Real effort versus chosen effort in experiments*. Economics Letters, 96(2), 232–236.
- Crawford, V. P., & Meng, J. (2011). *New York City Cab Drivers' Labor Supply Revisited*. American Economic Review, 101(5), 1912–1932.
- Gächter, S., Johnson, E. J., & Herrmann, A. (2007). *Individual-Level Loss Aversion in Riskless and Risky Choices*. IZA Discussion Paper No. 2961.
- Gill, D., & Prowse, V. (2019). *Measuring costly effort using the slider task*. Journal of Behavioral and Experimental Finance, 21, 1–9.
- Herweg, F., Müller, D., & Weinschenk, P. (2010). *Binary Payment Schemes: Moral Hazard and Loss Aversion*. American Economic Review, 100(5), 2451–2477.
- Holmström, B. (1979). *Moral Hazard and Observability*. The Bell Journal of Economics, 10(1), 74–91.
- Kőszegi, B., & Rabin, M. (2007). *Reference-Dependent Risk Attitudes*. American Economic Review, 97(4), 1047–1073.

## Disclaimer

This repository contains academic coursework and presentation materials.
The theoretical framework and design principles referenced here originate
from the cited studies; the proposed experiment has not been conducted and
no empirical results are reported.