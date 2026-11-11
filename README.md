# Code release staging

This folder contains the analysis protocols and observed dependency versions available in the project. It does not yet contain the source scripts that generated the manuscript analyses, so it is not a reproducible code release.

The manuscript analysis source files named by the saved manifests were not present in `results_revision` or `results_revision.tar`. Do not describe these protocol files as executable analysis code.

Patient-level cohorts, predictions, fitted models, and other restricted-data artifacts are not included. Aggregate result tables and manuscript figures also remain outside this staging folder pending data-governance review.

## Contents

- `protocols/`: saved specifications for the main analysis and sensitivity analyses.
- `protocols/requirements-observed.txt`: software versions recorded with the analyses; this is not a complete installation lockfile.

The analysis source code and a validated reproduction workflow remain to be added before public release.
