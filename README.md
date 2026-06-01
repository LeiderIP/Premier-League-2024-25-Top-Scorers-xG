# Premier League 2024/25 — Top Scorers vs xG

Interactive scatter plot comparing actual goals vs expected goals (xG) for every player in the 2024/25 Premier League season.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python) ![Plotly](https://img.shields.io/badge/Plotly-5.x-informational?style=flat-square&logo=plotly) ![Data](https://img.shields.io/badge/Data-StatsBomb-red?style=flat-square)

---

## Live Demo

**[Open Top Scorers vs xG](https://leiderip.github.io/Premier-League-2024-25-Top-Scorers-xG/Top_Scorers_xG.html)**

---

## Features

- **Scatter plot** of Goals vs xG for every outfield player
- Points **coloured by club** using official Premier League colours
- Points **sized by shots taken** — bigger = more active shooter
- **Above the diagonal** = overperforming xG; **below** = underperforming
- Filter by **team**, **minimum shots**, and **top N players**
- **Top 10 scorers** labelled directly on the chart
- **Sortable stats table** showing Goals, xG, +/- xG, Shots, Conversion %
- **Dark / Light theme toggle**

---

## How it works

| Metric | Description |
|---|---|
| xG | Sum of StatsBomb expected goals across all shots taken |
| +/- xG | Goals minus xG — positive means outperforming the model |
| Conversion % | Goals divided by shots taken |
| Circle size | Proportional to total shots taken |

---

## Related Projects

**[Title Race Visualiser](https://leiderip.github.io/Premier-League-2024-25-Title-race/pl_position_race.html)**

**[xG Race Explorer](https://leiderip.github.io/Premier-League-2024-25-xG-Title-race-/xG_Race_Explorer.html)**

**[Season Shot Map](https://leiderip.github.io/Premier-League-2024-25-Shot-Map/Shot_Map.html)**

---

*Data © StatsBomb. Project code MIT licensed.*
