# Illegal Dumping in Philadelphia - Factors and Predictors

## The issue
- Disproportionately affects lower-income, Latinx, and Black majority neighborhoods
- Vacant lots, streetlights, foot traffic
  - Worsened over Covid
  - The Zero Waste and Litter Cabinet budget cut
  - Public health concerns
- Often small haulers and contractors from construction sites
- Over 8,000 tons in 2022 of litter and illegally dumped debris, defined as debris cleaned up outside of normal trash collection, were collected
  - City increased fines up to 5,000$
- Not enough transparency about what trash is picked up by the city
  - Insufficient communication with ESL speakers

## APIs Used
- 311 from Philadelphia Open Data
  - Illegal dumping complaints from 01/01/2020 to present
- License & Inspections from Philadelphia Open Data
  - New construction permits from 01/01/2020 to present
  - Licenses where the applicant is a contractor from 01/01/2020 to present
- Census
  - 2020 Decennial Census
    - Population by race per Census Tract
  - 2020 American Community Survey 5-Year Estimates
    - Population with Income below 50,000$ per Census Tract
    - Median Income per Census Tract
    - English fluency per Census Tract
  - Census Tract Shapes

## Workflow
<img width="473" alt="workflow" src="https://github.com/claire-crg/illegal_dumping_phl/assets/82127458/f2a344ab-57b2-40ae-b5fd-0ccdcd5952c4">

## Jupyter Notebooks

There are 5 notebooks in total:
  - The first is the analysis of the data,
  - Three show how I pulled and cleaned data from the APIs used (311, L&I, and Census),
  - And one contains the Random Forest analysis I conducted.

The jupyter notebook called analysis.ipynb is in a narrative format that contextualizes and comments on the analysis and brings together the other 4 notebooks. I recommend starting here.
