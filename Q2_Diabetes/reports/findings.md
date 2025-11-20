# Q2 Diabetes Analysis Findings

## Part (a) — Glucose sample vs population
- Population mean Glucose = 120.895; population max = 199
- Sample (n=25, seed=42) mean Glucose = 116.640; sample max = 183
  - See figures/Q2a_glucose_kde_compare.png and Q2a_glucose_box_compare.png.

## Part (b) — BMI 98th percentile
- Population 98th percentile BMI = 47.526
- Sample 98th percentile BMI = 40.248
  - See figures/Q2b_bmi_p98_compare.png.

## Part (c) — Bootstrap on BloodPressure (R=500, m=150)
- Population mean/std/98th = 69.105, 19.356, 99.320
- Bootstrap average mean/std/98th = 69.136, 19.186, 98.125
  - See figures/Q2c_bootstrap_bp_stats.png and reports/bootstrap_summary_comparison.csv
