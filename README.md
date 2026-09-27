# Environmental Dynamics and Persistent Evolutionary Novelty

This repository contains an exploratory computational study of whether environmental dynamics and interaction-network structure jointly affect persistent phenotype recurrence in a finite digital population. The project does **not** demonstrate open-ended evolution.

## Complete exploratory package

Download the [complete v0.3 archive](https://github.com/masudhassan4172-droid/cas-oee-research/raw/refs/heads/main/cas_oee_research_complete_exploratory_v0.3.tar.xz) (336 trajectories; source, raw data, seeds, tests, analyses, figures, model/protocol documentation, and manuscript draft). On macOS or Linux, extract with:

`tar -xJf cas_oee_research_complete_exploratory_v0.3.tar.xz`

The earlier ZIP archives in this repository are retained as historical snapshots; v0.3 is the latest complete package.

## Observed results

The package combines the original 240 exploratory trajectories with 96 documented extension trajectories. Fourteen automated tests pass, and the nine-stage raw-data/provenance audit passes.

For the primary fast-versus-static environment × network comparison, the estimated difference-in-differences is **−0.0078 persistent events per 1,000 eligible births** (95% seed-block bootstrap interval **−0.0234 to 0.0078**, 12 independent seed blocks). The interval includes zero, so this experiment does not resolve a clear interaction. Matched aperiodic schedules likewise do not resolve an interaction. A parallel phenotype descriptor changes the measured rate while replaying the same evolutionary trajectories, showing that conclusions depend on the operational measurement map. Recovery calibration was performed as a separate exploratory extension; the resulting timescale ratio remains secondary.

## Interpretation and limits

These are exploratory results from one finite model, not confirmatory evidence about biological evolution, general network effects, criticality, or open-ended evolution. The model’s novelty measure is operational and observer-dependent. The draft manuscript and follow-up protocol are not externally preregistered or independently implemented/reviewed. Do not start confirmatory runs until an independent reviewer evaluates the model and measurement, the smallest effect of interest and precision target are justified, code and seeds are frozen, and the protocol is registered.

See the archive’s project status, audit, risk register, literature-search addendum, and manuscript for details. No software license has been selected.
