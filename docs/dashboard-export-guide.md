# Dashboard Export Guide

## Recommended four-panel dashboard

1. **Exposure distribution** — a four-bar chart using `data/dashboard-metrics.csv`, filtered to `AI exposure distribution`. Use occupation counts and retain the Low → Moderate → High → Very high order.
2. **High/Very high exposure outcomes** — a three-bar chart using the same file, filtered to `High/Very high exposure outcomes`. Label each bar with count and share. Title it “Projected employment outcome among High/Very high relative AI exposure occupations, 2025–2035.”
3. **Skill differences** — a horizontal bar chart using `data/skill-evidence.csv` and `mean_difference_growing_minus_declining`. Title it “Average skill-score difference: projected growth minus projected decline.”
4. **Skill correlations** — a dot plot using `correlation_with_projected_growth`. Title it “Descriptive correlation with projected employment growth.” Add “High/Very high relative AI exposure occupations only” as a subtitle.

## Export settings

- Export social graphics at 1600 × 900 px (16:9) or 1080 × 1350 px (4:5).
- Export portfolio/dashboard images at 1920 × 1080 px.
- Use a high-contrast palette and do not encode meaning through color alone.
- Put the period, population, and BLS source in every image footer.
- Add this caveat to every dashboard or image: “BLS AI exposure is relative exposure, not a measure of job loss or worker replacement. Skill results are descriptive associations.”

## Copy-ready source line

`Source: U.S. Bureau of Labor Statistics, AI exposure categories, employment projections, and skills data, 2025–2035. Analysis of 831 detailed occupations.`

## Do not use

- any career-protection ranking or replacement-likelihood label;
- arrows, colors, or titles that imply causal effects;
- a single combined score presented as a BLS measure.
