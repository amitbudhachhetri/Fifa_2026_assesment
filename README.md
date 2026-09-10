# FIFA World Cup 2026 – Foundation of Data Science

CDU Assessment 2: Group Project Presentation — Objective 1.

## Project purpose
This repository contains the Python analysis, raw FBref datasets, processed outputs, figures, and presentation materials for four distinct FIFA World Cup 2026 analytic tasks.

## Analytic tasks
1. **Attacking threat:** Compare on-target attacking threat relative to possession for knockout-stage teams and group-stage exit teams.
2. **Shooting accuracy:** Compare shooting accuracy of forwards and midfielders after minimum participation/shooting filters.
3. **Discipline:** Compare fouls committed per 90 minutes for midfielders and defenders.
4. **Goalkeeping:** Compare squad save percentage for knockout-stage teams and group-stage exit teams.

## Data source
Raw tables were exported from **FBref – 2026 World Cup statistics** using `Share & Export → Get table as CSV`.

Raw files are stored under `data/raw/`.

## Methodology
Each analytic task includes:
- analytic question formulation and justification
- data acquisition and validation
- data wrangling and preparation
- reproducible sampling (`random_state=42`)
- descriptive statistics
- 95% confidence interval estimation
- Welch two-sample t-test
- assumption checks (normality, variance, outliers)
- Mann–Whitney U sensitivity analysis where useful
- football interpretation and methodological limitations







