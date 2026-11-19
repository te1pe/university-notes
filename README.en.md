# university-notes

[Русский](README.md) · **English**

Notes and solved problems from my first years at NSU FIT. Kept apart from
[university-labs](https://github.com/te1pe/university-labs): the lab code is
there, the theory and solutions are here. The notes themselves are in Russian.

## Sections

| Section | Folder | Contents |
| --- | --- | --- |
| Discrete mathematics | [`discrete-maths`](discrete-maths) | 93 solved problems in Markdown: Boolean functions, truth tables, minimization |
| Digital circuit design | [`circuitry`](circuitry) | 11 labs in SystemVerilog + a course project |
| Informatics | [`informatics`](informatics) | three labs on text file processing |
| Probability theory and statistics | [`probability-theory-math-stat`](probability-theory-math-stat) | histogram, empirical distribution function, Kolmogorov test in Python |

## Digital circuit design

SystemVerilog modules and testbenches (`*.sv`), a pair of files per lab:
`pr.sv` is the circuit, `pr_TB.sv` its testbench. Checked in a simulator.

## Probability theory

Three Python scripts: `Gistogram.py`, `EFR.py`, `Kolmogorov.py`.
Dependencies: `numpy` and `matplotlib`.

```bash
python3 probability-theory-math-stat/Gistogram.py
```
