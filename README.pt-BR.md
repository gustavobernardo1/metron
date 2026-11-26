<p align="center"><a href="README.md">English</a> | <strong>Português (Brasil)</strong></p>

# Metron — Avaliação Comparativa de Modelos

Uma iniciativa multidisciplinar de benchmarking reprodutível, análise de incertezas e avaliação comparativa de modelos matemáticos, baseados em processos e de aprendizado de máquina.

**Estado:** infraestrutura inicial de pesquisa. Nenhum resultado de benchmarking é alegado.

## Primeira investigação

[Modelos de culturas agrícolas / Soja](benchmarks/crop-models/soybean/README.md): avaliar a viabilidade de uma comparação justa entre modelos de produtividade da soja em condições brasileiras, com foco no Cerrado quando houver observações adequadas.

## Organização

- `benchmarks/`: investigações independentes por domínio e questão de pesquisa.
- `src/metron/`: código compartilhado de avaliação, introduzido apenas quando o reuso efetivo se justificar.
- `protocols/`: modelos de experimentos e relatórios.
- `tests/`: verificação de utilitários compartilhados.

Consulte a [metodologia](METHODOLOGY.md), o [planejamento](ROADMAP.md) e as [instruções para agentes](AGENTS.md). Dados restritos de pesquisa não podem ser publicados sem autorização. Códigos de modelos externos e conjuntos de dados mantêm seus respectivos termos de licenciamento.

## Limite de escopo

O [matematications](https://github.com/gustavobernardo1/computational-mathematics) reúne estudos de métodos matemáticos e aprendizado de máquina científico. O metron concentra avaliações comparativas independentes de modelos concorrentes, não estudos gerais ou validações internas de aplicações.
