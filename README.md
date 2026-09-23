# university-notes

Notes and worked problems from my first years at NSU FIT. Kept separate from
[university-labs](https://github.com/te1pe/university-labs): that repository
holds the lab code, this one holds theory and solutions.

The notes themselves are in Russian.

## Sections

| Section | Folder | What is inside |
| --- | --- | --- |
| Discrete mathematics | [`discrete-maths`](discrete-maths) | 93 worked problems in Markdown: Boolean functions, truth tables, minimisation |
| Digital circuitry | [`circuitry`](circuitry) | 11 labs in SystemVerilog + a term project |
| Informatics | [`informatics`](informatics) | three labs on text-file processing |
| Probability theory and statistics | [`probability-theory-math-stat`](probability-theory-math-stat) | histogram, empirical distribution function, Kolmogorov test in Python |

## Digital circuitry

Modules and testbenches in SystemVerilog (`*.sv`), a pair of files per lab:
`pr.sv` is the circuit, `pr_TB.sv` the testbench. Verified in a simulator.

## Probability theory

Three Python scripts: `Gistogram.py`, `EFR.py`, `Kolmogorov.py`.
Dependencies: `numpy` and `matplotlib`.

```bash
python3 probability-theory-math-stat/Gistogram.py
```
