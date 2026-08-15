# Misperceived Social Norms and Climate Action

[![Status](https://img.shields.io/badge/Status-Completed-green)]
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex)]
[![Course](https://img.shields.io/badge/Course-Climate%20and%20Human%20Behavior-blue)]

Academic seminar presentation on social norm misperceptions and climate-related behaviour.

## Project Information

| Item | Details |
|---|---|
| Author | Theo Osterhaus |
| Course | Climate and Human Behavior |
| Institution | University of Cologne |
| Year | 2025 |
| Format | Academic presentation |
| Main paper | Bergquist & Nilsson (2024), *Review of Economic Studies* |

## Abstract

This project discusses how misperceived social norms influence climate-related
behaviour and support for climate policies. It focuses on an information
experiment that corrects individuals' beliefs about the climate-related
behaviour and preferences of other Americans.

The presentation examines whether providing accurate information about social
norms increases charitable donations and policy support, and whether effects
differ across individuals with different prior beliefs.

## Research Questions

1. Which behavioural factors predict willingness to act against climate change?
2. Do individuals underestimate public support for climate action?
3. Can correcting these misperceptions affect donations and policy support?
4. Are treatment effects heterogeneous across individuals?

## Study Design

The underlying study uses a two-wave survey experiment conducted in the United
States.

| Wave | Date | Sample | Purpose |
|---|---|---:|---|
| Wave 1 | March 2021 | 2,000 | Descriptive analysis and baseline beliefs |
| Wave 2 | April 2021 | 6,000 | Information experiment |

The sample was quota-based and designed to approximate the US adult population
with respect to gender, age, education, and region. Respondents participated
in only one wave.

### Incentivised Outcome

Participants allocated **$450** between themselves and atmosfair, a climate
protection organisation. The allocations of 25 randomly selected participants
were implemented.

### Information Treatments

| Group | Information |
|---|---|
| Control | No information |
| Behaviour treatment | 71% of Americans try to fight global warming |
| Norms treatment | 87% of Americans think people should fight global warming |

The treatment information was based on aggregate responses from Wave 1.

## Main Findings

### Misperceived Social Norms

Respondents underestimated the prevalence of climate-related behaviour and
support for climate action.

| Measure | Actual share | Perceived share | Difference |
|---|---:|---:|---:|
| Trying to fight global warming | ~71% | ~43% | −28 percentage points |
| Believing people should fight global warming | ~87% | ~65% | −22 percentage points |

### Predictors of Donations

Perceived behaviour and perceived social norms were positively associated with
climate-related donations. These associations were comparable in magnitude to
several economic and moral preferences when predictors were standardised.

### Treatment Effects

Providing information about climate-related behaviour and norms increased
donations:

| Treatment | Estimated effect |
|---|---:|
| Behaviour treatment | +$5.00 |
| Norms treatment | +$3.20 |

The effects were concentrated among respondents whose prior beliefs were below
the actual population shares.

### Heterogeneous Effects

Treatment effects were particularly pronounced among:

- respondents who initially underestimated climate action;
- individuals sceptical about climate change;
- participants receiving information about peer behaviour.

These results suggest that non-moralising peer information may be an effective
way to correct misperceptions while limiting potential backlash.

## Related Literature

The presentation also discusses:

> Andre, P., Boneva, T., Chopra, F., & Falk, A. (2024).  
> *Globally representative evidence on the actual and perceived support for climate action.*  
> Nature Climate Change, 14(3), 253–259.  
> DOI: 10.1038/s41558-024-01925-3

The two studies complement each other:

- the ReStat study provides causal evidence from an information experiment;
- the Nature Climate Change study documents misperceptions across 125 countries;
- together, they motivate further research on scalable norm-correction
  interventions.

This comparison should not be interpreted as evidence that a global
intervention would necessarily have identical effects across countries.

## Limitations

Important limitations include:

- quota-based rather than probability sampling;
- possible spillover between treatment conditions;
- social desirability and experimenter-demand effects;
- hypothetical or self-reported measures for some outcomes;
- limited external validity of a US-based online experiment;
- uncertainty about the long-term persistence of treatment effects.

## Materials

- [Presentation PDF](./PAP.pdf)
- [Academic report](./CaHB_Osterhaus_MisperceivedSocialNormsandWillingnesstoActAgainstClimateChange.pdf)
- [LaTeX source](./main.tex)
- [Bibliography](./references.bib)
- [Supplementary material](./rest_a_01468-supp.pdf)
- [Notes](./rest_a_01468_ONENOTE.pdf)

## Reproducibility

The presentation was created with LaTeX. The main source file is
`main.tex`; references are stored in `references.bib`.

## Disclaimer

This repository contains academic coursework and presentation materials.
The empirical results reported here originate from the referenced studies and
are not original estimates by the repository author unless explicitly stated.