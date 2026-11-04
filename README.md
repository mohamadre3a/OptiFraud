# OptiFraud

Machine learning and optimization for human-AI fraud review, inspired by my PhD research on human-AI decision-making.

Combines calibrated XGBoost fraud predictions, analyst-specific cost models, and Gurobi optimization to choose automatic approvals, rejections, and reviewer assignments under limited capacity.

## Approach

- Compare automation, risk-based review, greedy assignment, and joint optimization.
- Evaluate held-out decision costs, fraud errors, and analyst workloads.
- Examine review capacity, analyst workloads, and analyst absences.

## Getting started

Download [FiFAR](https://doi.org/10.6084/m9.figshare.28351172) and place the extracted `FiFAR` folder alongside the notebook. Run the notebook cells in order, starting with dependency installation. Gurobi requires a valid license.

The dataset is excluded from this repository. Reviewers are synthetic, and business costs and review capacities are assumed.