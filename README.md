<p align="center"><strong>English</strong> | <a href="README.pt-BR.md">Português (Brasil)</a></p>

# Metron — Comparative Model Evaluation

A multidisciplinary initiative for reproducible benchmarking, uncertainty analysis and comparative evaluation of mathematical, process-based and machine learning models.

**Status:** initial research infrastructure. No benchmark results are claimed.

## First investigation

[Crop models / Soybean](benchmarks/crop-models/soybean/README.md): evaluate feasibility of a fair comparison of soybean yield models under Brazilian conditions, with a focus on the Cerrado when suitable observations are available.

## Organization

- `benchmarks/`: independent investigations organized by domain and research question.
- `src/metron/`: shared evaluation code, introduced only when actual reuse is justified.
- `protocols/`: experiment and reporting templates.
- `tests/`: verification of shared utilities.

See [methodology](METHODOLOGY.md), [roadmap](ROADMAP.md), and [agent instructions](AGENTS.md). No restricted research data may be published without authorization. External model code and datasets retain their own licensing terms.
