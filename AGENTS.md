# Research agent instructions

Metron is a benchmarking research initiative, not a leaderboard factory. Agents may autonomously investigate literature, implementations, datasets, alternative evaluation strategies and reproducibility, within authorized access and compute budgets.

- Begin with the question, target variable, prediction time, population, observed reference and decision context. Establish feasibility before claiming comparability.
- Audit model versions, licenses, crop coverage, parameter requirements, inputs, output definitions and calibration. Record verified sources and unresolved questions. Never invent citations, model support, results or permissions.
- Predefine fair experimental conditions and holdouts. Separate calibration from evaluation; avoid leakage across farm, location, season and forecast issue time. If input availability differs, report separate evaluation tracks.
- Establish simple baselines. Report paired comparisons, uncertainty, missingness, failure cases and domain-specific limitations. Do not force a universal ranking.
- Keep domain-specific code inside its investigation. Extract shared utilities only once the abstraction is justified. Do not duplicate entire external model engines.
- Record data provenance, configuration, environment, random seeds and commands. Do not commit secrets, personal information, proprietary farm data or large datasets.
- Clearly label planned, executed and independently reproduced experiments. Human review is required before publication of novel claims or restricted results.
- Use the benchmark protocol template. Keep the first study narrow and complete before expanding to other domains.

## Scope boundary

Method-focused learning, derivations, implementations and paper reproductions belong in [matematications](https://github.com/gustavobernardo1/computational-mathematics). Metron owns independent comparative research questions, common evaluation protocols, model adapters, comparative experiments and their evidence. Do not duplicate learning studies or application-specific validation; link to their canonical sources.
