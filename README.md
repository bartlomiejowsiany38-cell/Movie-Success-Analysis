# Movie Financial vs. Critical Success

## Overview
Do films that make the most money also tend to be the most critically acclaimed, or are box office success and critical reception largely independent?

## Key Findings
- Financial success and critical reception (IMDb score) show a weak correlation — blockbusters and beloved films are largely different populations
- Applied the official IMDb weighted rating formula to correct for vote-count bias, ensuring fair comparison between widely-reviewed and niche titles
- Identified patterns in genre, budget range, and release period that distinguish commercially successful from critically acclaimed films

## Methodology
1. Data cleaning and processing of a 5,000+ film dataset
2. Implemented IMDb's Bayesian weighted rating formula to normalise scores across films with vastly different review counts
3. SQL queries via duckdb for aggregation and filtering


## Tools
- Python (pandas, numpy, scipy, duckdb, matplotlib, seaborn)
- SQL (via duckdb)
