# Data Dictionary

## Unit of analysis

One row represents one detailed U.S. occupation in the 2025 National Employment Matrix. The Step 12 analysis contains 831 detailed occupations.

## Source fields

| Field | Definition | Source | Notes |
|---|---|---|---|
| `occupation_title` | Detailed occupation name | BLS Employment Projections | Display label. |
| `occupation_code` | 2025 National Employment Matrix occupation code | BLS Employment Projections | Join key across source files. |
| `ai_exposure_category` | Low, Moderate, High, or Very high relative AI exposure | BLS AI exposure categories | A relative category, not a job-loss or replacement probability. |
| `employment_2025` | Employment level in 2025 | BLS Employment Projections | Employment is reported by BLS in thousands in source tables. |
| `employment_2035` | Projected employment level in 2035 | BLS Employment Projections | Projection, not observed employment. |
| `employment_change_percent` | Projected percentage employment change from 2025 to 2035 | BLS Employment Projections | Primary outcome measure in this project. |
| `annual_openings` | Average annual occupational openings for 2025–2035 | BLS Employment Projections | Contextual field; not a replacement measure. |
| `median_annual_wage` | Median annual wage | BLS Employment Projections | Contextual field used in prior analysis. |
| `typical_education` | Typical education needed for entry | BLS Employment Projections | Contextual field used in prior analysis. |
| `skill_*` | BLS occupational skill score | BLS Skills Data | Scores are occupational measures, not individual assessments. |

## Derived fields and groups

| Field or group | Definition |
|---|---|
| `high_ai_group` | Occupations categorized as High or Very high relative AI exposure. |
| `outcome_direction` | Growing when projected employment change is positive; declining when negative; essentially flat when near zero. |
| `core_skill_set` | Critical & analytical thinking, problem solving & decision making, science, leadership, and writing & reading. This is an analytical construct, not a BLS score. |
| `core_skill_index` | Equal-weight composite of the five core skills used in earlier exploratory analysis. It is not a causal index or a career ranking. |
| `mean_difference_growing_minus_declining` | Average skill score among growing high-AI occupations minus the corresponding average among declining high-AI occupations. |
| `correlation_with_projected_growth` | Descriptive correlation between a skill score and projected employment growth within the High/Very high exposure group. |

## Publication exports

| File | Grain | Intended use |
|---|---|---|
| `data/dashboard-metrics.csv` | Summary metric | Exposure distribution and outcome charts. |
| `data/skill-evidence.csv` | Skill | Comparison bars and correlation dot plots. |
| `data/occupation-examples.csv` | Occupation | Narrative examples and annotated visuals. |

Source documentation: [BLS AI exposure categories](https://www.bls.gov/emp/publications/ai-exposure-categories.htm) and [BLS Skills Data](https://www.bls.gov/emp/data/skills-data.htm).
