# Girls' Education ROI Model — Kenya

## Project Overview
This project is a financial model built in Google Sheets that estimates 
the lifetime return on investment (ROI) of four years of secondary 
education for a girl in rural Kenya. The model applies a discounted cash 
flow (DCF) framework to compare the direct costs of schooling against 
projected increases in lifetime earnings, using academic research on 
returns to education in Sub-Saharan Africa.

The project was developed to connect my background in girls' education 
advocacy through the Mwanga Initiative in Kitui County, Kenya, 
with financial analysis methods used in development finance and impact 
investing.

## Data Sources
1. Psacharopoulos, G., & Patrinos, H. A. (2018). Returns to investment 
   in education: A decennial review of the global literature. *Education 
   Economics*, 26(5), 445–458. — source for the 9–10% annual wage 
   premium per year of schooling (global average).
2. Ozier, O. (2015). The Impact of Secondary Schooling in Kenya: A 
   Regression Discontinuity Analysis. World Bank Policy Research Working 
   Paper 7384. — Kenya-specific evidence that secondary schooling 
   increases human capital and shifts workers out of low-skill informal 
   employment into formal employment.
3. Baseline annual income (KES 70,000) and schooling cost (KES 20,000 
   per year) are working estimates based on typical rural Kenyan 
   household income levels and public secondary school fee structures. 
   These are flagged as estimates intended to be refined with Kenya 
   National Bureau of Statistics (KNBS) Labour Force Survey data in 
   future iterations.

## Model Structure
Built in Google Sheets across four tabs:

- **Assumptions** - all input values with sources and notes
- **Model** — step-by-step DCF calculations referencing Assumptions tab
- **Scenarios** — sensitivity analysis across low, base, and high 
  wage premium assumptions
- **Summary** — key findings, scenario table, and chart

## Methodology
1. Estimate total cost of four years of secondary schooling: 
   KES 20,000/yr × 4 = KES 80,000.
2. Apply annual wage premium compounded over four years of schooling 
   to project income with vs. without secondary education.
3. Calculate additional annual income in base case: KES 32,487/yr.
4. Apply 8% discount rate over 35-year working life using NPV 
   calculation to find present value of future earnings gains.
5. Compute discounted ROI: (NPV of earnings gains − schooling cost) 
   / schooling cost × 100.

## Key Findings

| Scenario | Wage Premium/yr | NPV of Earnings (KES) | Discounted ROI |

| Low | 5% | 175,814 | 120% |
| Base | 10% | 378,622 | 373% |
| High (girls-specific) | 12% | 467,888 | 485% |

In the base-case scenario, four years of secondary education generates 
a **373% discounted return on investment**, with the NPV of lifetime 
additional earnings reaching KES 378,622 against a total schooling cost 
of KES 80,000.

Even under conservative assumptions (5% wage premium), the discounted 
ROI remains above 100%, confirming that girls' secondary education 
delivers positive returns across all scenarios modeled. Under 
girls-specific wage premium assumptions — consistent with research 
showing women experience above-average returns to schooling — the 
estimated ROI rises to 485%.

These results support the case that girls' secondary education 
represents one of the highest-return investments available in 
development finance, with compounding economic benefits for individuals, 
households, and communities.

## Files
- `girls_education_roi_model.xlsx` — full model with four tabs
- `roi_by_scenario_chart.png` — column chart of ROI across scenarios
- `writeup.pdf` — written analysis with methodology and findings

## Author
Rachael Richard  
Columbia University
