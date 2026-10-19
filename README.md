# university-notes

Конспекты и решённые задачи с первых курсов ФИТ НГУ. Хранятся отдельно от
[university-labs](https://github.com/te1pe/university-labs): там код
лабораторных, здесь — теория и решения.

## Разделы

| Раздел | Папка | Что внутри |
| --- | --- | --- |
| Дискретная математика | [`discrete-maths`](discrete-maths) | 93 решённые задачи в Markdown: булевы функции, таблицы истинности, минимизация |
| Цифровая схемотехника | [`circuitry`](circuitry) | 11 лабораторных на SystemVerilog + курсовой проект |
| Информатика | [`informatics`](informatics) | три лабораторные по обработке текстовых файлов |
| Теория вероятностей и математическая статистика | [`probability-theory-math-stat`](probability-theory-math-stat) | гистограмма, эмпирическая функция распределения, критерий Колмогорова на Python |

## Цифровая схемотехника

Модули и тестбенчи на SystemVerilog (`*.sv`), по паре файлов на лабораторную:
`pr.sv` — сама схема, `pr_TB.sv` — тестбенч. Проверено в симуляторе.

## Теория вероятностей

Три скрипта на Python: `Gistogram.py`, `EFR.py`, `Kolmogorov.py`.
Зависимости: `numpy` и `matplotlib`.

```bash
python3 probability-theory-math-stat/Gistogram.py
```
