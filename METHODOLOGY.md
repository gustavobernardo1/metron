# Evaluation methodology

## 1. Define the estimand and task
Specify the target, units, time of prediction, spatial and temporal scale, intended users, and reference observations. Do not compare potential yield, attainable yield and observed yield as interchangeable targets.

## 2. Define comparability
Inventory model versions, input requirements, calibration opportunities, initialization, available outputs, licensing and compute costs. Define a common-information track and additional model-specific tracks only when justified. Record unavailable or failed runs.

## 3. Experimental design
Use identical eligible evaluation cases where possible. Split by relevant independent units (e.g. farm, site, region, year) and hold out complete groups to assess generalization. Fit and tune only on training/calibration data. Predefine metrics and sensitivity analyses before viewing held-out results.

## 4. Evaluation dimensions
Accuracy (MAE, RMSE, signed bias in original units), robustness to perturbations, generalization, uncertainty calibration where probabilistic output exists, physical plausibility, computational cost and data requirements. Compare uncertainty using paired, dependence-aware resampling or other justified methods. Measure runtime under documented hardware and workload conditions. Avoid ranking incompatible targets or averaging arbitrary normalized scores without explicit preferences and sensitivity analysis.

## 5. Reproducibility
Preserve configuration, model versions, dataset identifiers and hashes where appropriate, split manifests, commands, seeds, environment and output schema. Record limitations and negative results. Keep raw restricted data outside the repository.
