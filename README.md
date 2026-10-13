# Monte Carlo Engine -- Probability & Simulation
## Objective
To test probability theories and estimate financial risk using simulated data
## Methodology
- Simulated 10,000 coin flips and plotted the running share of heads
- Simulated 10,000 Monty Hall games
- Simulated a disease screening test on 100,000 people using a 1% prevalence, 95% sensitivity, and 90% specificity
- Computed Monte Carlo VaR and Expected Shortfall for a $1M portfolio
- Checked that Monte Carlo error shrinks like 1/sqrt(n) by estimating pi
## Key Findings
- Switching won approximately 6,667 of the simulated Monty Hall games
- In the disease screening simulation, only 9.2% of the positive tests belonged to people who were actually sick
- The 95% VaR was $19,494, and the 95% ES was $24,230
