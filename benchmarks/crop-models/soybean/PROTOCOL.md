# Proposed protocol — soybean yield

Status: draft, not preregistered.

- Target: observed harvested yield (kg/ha); define moisture basis, aggregation and inclusion criteria after data audit.
- Prediction setting: distinguish retrospective simulation with observed weather from genuine prospective forecasting. Do not mix these tracks.
- Candidate inputs: weather, soil, cultivar, management, planting date and observations, subject to availability and permission.
- Calibration: identical evaluation split and documented calibration budget; distinguish default parameters from locally calibrated models.
- Generalization: choose group-aware holdouts (site/farm and season where supported); report sample sizes and coverage.
- Baselines: training-only historical mean and a simple eligible statistical model; additional baselines depend on the final task.
- Metrics: MAE, RMSE, signed bias; stratify by conditions where sample size supports it. For probabilistic models, add calibration and proper scoring rules.
- Comparison: paired evaluation and dependence-aware uncertainty; report failures and missing predictions. Runtime and input burden are separate axes.
- Freeze the protocol, versions and splits before final evaluation. No ranking is planned until comparable observations and runs exist.
