# Quantium Data Analytics Job Simulation

A three-part data analytics project completed as part of Quantium's Data Analytics Job Simulation on [Forage](https://www.theforage.com/), simulating real commercial analytics work for the data science team.

## Project overview

Quantium's client, a retail chain, wanted to understand how customers behave when purchasing chips, and whether a new store layout trial actually drove a measurable increase in sales. The project moved through three stages: data cleaning and customer segmentation, experimentation and uplift testing, and a client-ready commercial report.

## Task 1 — Data preparation and customer analytics

- Cleaned and merged transaction data (264,836 rows) with customer purchase-behaviour data (72,637 customers)
- Removed a non-chip product and one outlier/commercial-buyer customer; standardized inconsistent brand names
- Segmented customers by life stage and premium (affluence) tier, analyzing total sales, customer counts, units per customer, price per unit, and brand affinity
- **Key finding:** Older Families – Budget is the single highest-value segment, driven by spend per customer rather than customer count; household size (not premium tier) is the main driver of purchase volume


## Task 2 — Experimentation and uplift testing

- Selected control stores for three trial stores (77, 86, 88) using a weighted blend of pre-trial sales correlation and magnitude
- Ran t-tests to assess statistical significance of the sales uplift during the trial period (Feb–Apr 2019) against each control store
- Broke down the driver of any significant uplift (customer numbers vs. average transactions per customer)
- **Key finding:** All three trial stores showed a statistically significant uplift in March 2019; the effect held into April for two of the three stores


## Task 3 — Commercial application

- Built a client-ready report for the Category Manager using the Pyramid Principle (headline conclusion first, then supporting evidence)
- Combined Task 1 and Task 2 findings into data visualizations, key callouts, and commercial recommendations
- Delivered as a PowerPoint/PDF report plus a cover email


## Tools used

Python (pandas, numpy, matplotlib, seaborn, scipy), Jupyter Notebook, PowerPoint


