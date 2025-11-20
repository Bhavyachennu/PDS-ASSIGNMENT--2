# Q1 Used Cars Analysis Findings

## Part (a) — Missing Values
- Numeric columns filled with median, categorical columns filled with mode.

## Part (b) — Numeric Conversion
- Units removed from Mileage, Engine, Power, New_Price.

## Part (c) — One-Hot Encoding
- Fuel_Type and Transmission converted to numeric columns.

## Part (d) — Car Age Feature
- Added Car_Age = Current Year - Year.

## Part (e) — Data Manipulations
- Selected & renamed columns.
- Filtered cars priced > 10 lakhs.
- Created km_per_cc column.
- Sorted by Price.
- Grouped by Fuel_Type_Petrol with summary stats.
