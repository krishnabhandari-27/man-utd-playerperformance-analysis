# MANCHESTER UNITED PLAYER PERFORMANCE ANALSYIS 2024-25 ⚽

## 📌 Overview

Methodology
Data Cleaning: Handled messy string data in xG and xA columns by extracting the base value, ensuring accurate numerical data for calculation.

Feature Engineering: Created key derived metrics:

G+A (Total Goal Contributions)

xG+xA (Total Expected Goal Contributions)

G_A_per_90 (Goals and Assists per 90 Minutes)

Filtering: Rate statistics were calculated on players with more than 450 minutes played to ensure reliability and minimize noise from small sample sizes.

Visualization: Generated 14 plots across four categories: Distribution, Ranking, Efficiency, and Positional Analysis, using matplotlib and seaborn.

Key Findings Summary
Top Contributors: Identified the top 10 players by both volume (G+A) and expected impact (xG+xA).

Finishing Efficiency: Revealed players who significantly overperformed or underperformed their Expected Goals (xG), highlighting clinical finishers and those struggling to convert chances.

Creative Profile: Established the relationship between Key Passes (KP90) and quality of chances created (xA90).

Squad Usage: Analyzed how minutes and appearances are distributed across different positions.


---


