# Q1 Used Cars Analysis Findings

## Part (a) — Missing Values
- Numeric columns filled with median to handle outliers and skewed distributions.
- Categorical columns filled with mode to preserve the most common value.

## Part (b) — Numeric Conversion
- Units removed from Mileage, Engine, Power, and New_Price.

## Part (c) — One-Hot Encoding
- Fuel_Type and Transmission converted to numeric columns.

## Part (d) — Car Age Feature
- Added Car_Age = Current Year - Year.

## Part (e) — Data Manipulations
- Selected & renamed columns.
- Filtered cars priced > 10 lakhs.
- Created km_per_cc column.
- Sorted by Price.
- Grouped by Fuel_Type_Petrol with summary statistics.
