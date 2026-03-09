# Projet-empirique-suite-de-Dube-Arindrajit-Minimum-wages-and-the-distribution-of-the-family-income-

Certainly! Here is the README.md for the EMPIRICAL-project, translated into English for your GitHub:
📈 EMPIRICAL-project: Minimum Wage & Income Distribution
An Extension of Dube (2019): Heterogeneity, Dynamic Interactions, and the Social Safety Net

This repository contains the full analytical pipeline and research report for a project dedicated to quantifying the redistributive effects of the minimum wage. Moving beyond the traditional "minimum wage vs. employment" debate, this study employs advanced econometric methods to analyze the entire income distribution and the substitution mechanisms with social safety nets.
🧐 The Research Question

"How do minimum wage hikes affect the distribution of family income, and what underlying mechanisms explain the variations in this impact?"

The project extends the seminal work of Arindrajit Dube (2019) by exploring three critical dimensions:

    Spatial Disaggregation: Why is the impact twice as strong in the South (e.g., Texas) compared to the Northeast (e.g., New York)?

    Dynamic Interactions: What is the role of the minimum wage as an automatic stabilizer during economic recessions?

    Welfare Articulation: Is there a substitution effect between the minimum wage and public transfers?

🛠️ Econometric Toolkit

The project utilizes US panel data (CPS, 1990–2020) and state-of-the-art models:

    Dynamic GMM Models (xtabond2): Used to capture the temporal persistence of poverty and address endogeneity.

    RIF (Recentered Influence Function) Regressions: To estimate partial effects on unconditional income quantiles.

    Instrumental Variables (2SLS): Leveraging lags and interactions to isolate causal relationships.

    Software: Analysis primarily conducted using Stata and R.

📂 Repository Structure

    Conducing_an_empirical_project.pdf: The final academic report detailing theoretical extensions and empirical results.

    Minimum Wages and the Distribution of Family.odp: Presentation slides summarizing the empirical strategy and marginal effect visualizations.

    NBER WORKING PAPER SERIES.pdf: The original paper by Dube (2019) used as the baseline for replication.

    scripts/: (Referenced in the report) Stata code for logit/probit models and robustness checks (Arellano-Bond, Hansen tests).

📈 Key Findings

    Targeted Poverty Reduction: The efficiency of the minimum wage peaks at the 10th and 15th income percentiles.

    The Stabilizer Effect: The poverty-reduction elasticity is significantly stronger during crises (e.g., -0.43 in 2008) than during growth periods (-0.21 in 2019).

    Substitution Effect: A 10% increase in public assistance reduces the minimum wage's efficiency by 3.2 points, suggesting these policies must be finely coordinated.

    The Welfare Paradox: For certain groups, such as single mothers, wage gains are often offset by a decrease in public benefits (like TANF), limiting the net impact on poverty to -1.7%.
