# Source Review

Updated: 2026-05-17 03:07:53 AEST

## Paper Evidence

The chapter reports regression analyses for Twin Cities traffic management systems: ramp metering, variable message signs, and the Highway Helper freeway service patrol. It states that the study used 22 selected freeway corridors, loop-detector data from 1998-2000, selected Tuesday-Wednesday-Thursday samples, gap periods around improvements, and Stata for ordinary least-squares regressions.

## Local Source Evidence

The local source tree `/Users/dlev2617/Documents/Data/~Nexus_Data/Twin Cities Traffic Management/Transportation Management Systems CDs` contains regression-ready Stata `.dta` files whose variables match the paper's model variables, including `speed`, `density`, `rm`, `vms`, `hhelper`, HOV indicators, lane-count indicators, corridor dummies, and incident-position variables.

The package stages compact Stata inputs and metadata. It does not copy the giant route-level Excel processing tree, project reports, drafts, or questionnaires.
