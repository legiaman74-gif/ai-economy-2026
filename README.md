# AI Economy 2026: Exposure, Skills, and Employment Projections

## The question

This project asks a narrower, more useful question than “Which jobs will AI replace?”:

> Why do some occupations with high relative AI exposure have positive employment projections while others have negative projections?

It brings together U.S. Bureau of Labor Statistics (BLS) AI exposure categories, 2025–2035 employment projections, and occupational skills data for 831 detailed U.S. occupations.

## Key finding

High relative AI exposure is not the same thing as projected employment decline.

Of 412 occupations classified as **High** or **Very high** relative AI exposure:

| Projected outcome, 2025–2035 | Occupations | Share |
|---|---:|---:|
| Growth | 306 | 74.3% |
| Decline | 100 | 24.3% |
| Essentially flat | 6 | 1.5% |

The project therefore treats AI exposure and projected employment growth as separate measures.

## Skill evidence

Within the High/Very high exposure group, occupations projected to grow scored higher on average than declining occupations in several skills. The largest differences were Science (+0.623), Critical & analytical thinking (+0.440), Leadership (+0.377), Writing & reading (+0.296), and Problem solving & decision making (+0.294).

The strongest descriptive correlations with projected employment growth in the same group were Critical & analytical thinking (0.508), Problem solving & decision making (0.439), Writing & reading (0.377), Science (0.377), and Leadership (0.319).

These are descriptive associations. They do not establish that a skill causes growth, protects a job, or predicts an individual worker’s outcome.

## Included files

- `data/dashboard-metrics.csv` — chart-ready headline counts and shares.
- `data/skill-evidence.csv` — chart-ready skill differences and correlations.
- `data/occupation-examples.csv` — illustrative examples used in the narrative.
- `docs/data-dictionary.md` — field definitions and analytical outputs.
- `docs/methodology-and-limitations.md` — source handling, interpretation rules, and limitations.
- `docs/dashboard-export-guide.md` — how to turn the supplied CSVs into publication visuals.
- `content/linkedin-post.md` — a ready-to-edit LinkedIn post.
- `content/short-video-script.md` — a short-form video script.
- `docs/portfolio-case-study-outline.md` — a concise portfolio structure.
- `QA.md` — final consistency checks.

## Responsible interpretation

BLS defines its categories as **relative AI exposure** across occupations. The categories are not estimates of job loss, worker replacement, automation probability, AI adoption, productivity, wages, or absolute risk. “Low” exposure does not mean an occupation will be unaffected by technological change, and “High” exposure does not mean employment will decline.

Employment projections cover **2025–2035** and reflect BLS’s long-term projection methodology. They are estimates, not predictions of a guaranteed future.

## Sources

- [BLS AI exposure categories and 2025–2035 projections](https://www.bls.gov/emp/publications/ai-exposure-categories.htm)
- [BLS detailed skills data](https://www.bls.gov/emp/data/skills-data.htm)
- [BLS 2025–2035 employment projections summary](https://www.bls.gov/news.release/ecopro.nr0.htm)

## Reproduce or publish

The data exports in this repository are publication-ready summaries of the Step 12 analysis. For a full reproduction, retain the original BLS workbooks, join on the 2025 National Employment Matrix occupation code, and follow the methodology document. Before publishing, add the final dashboard images or a hosted dashboard link to this README.
