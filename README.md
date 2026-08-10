# liquid-credit-portfolio-risk-analytics
End-to-end fixed income risk analytics platform for liquid credit portfolios, featuring portfolio exposure monitoring, duration and spread risk analysis, benchmark-relative performance evaluation, stress testing, return attribution, sector and rating concentration analysis, and synthetic credit portfolio data generation using Python.


# Liquid Credit Portfolio Risk Analytics Engine

## Overview

A fixed income portfolio analytics platform developed in Python for analyzing liquid credit portfolios. The platform evaluates portfolio exposures, duration and spread risk, benchmark-relative performance, stress scenarios, and return attribution across diversified corporate bond portfolios.

The project also includes a synthetic credit portfolio generator that creates realistic bond universes with issuer, sector, rating, duration, spread, yield, and benchmark data for testing and analysis.

---

## Key Features

### Portfolio Analytics
- Portfolio market value calculation
- Position and exposure analysis
- Sector allocation analysis
- Country allocation analysis
- Credit rating distribution analysis

### Risk Analytics
- Weighted average duration
- Spread duration analysis
- Credit spread exposure measurement
- Concentration risk monitoring
- Benchmark-relative risk assessment

### Performance Analytics
- Portfolio return calculation
- Excess return analysis
- Benchmark comparison
- Active weight analysis

### Return Attribution
- Sector attribution
- Security selection attribution
- Allocation effects
- Performance contribution analysis

### Stress Testing
- Interest rate shock scenarios
- Credit spread widening scenarios
- Portfolio impact estimation
- Sensitivity analysis

### Data Generation
- Synthetic credit portfolio creation
- Realistic issuer generation
- Sector and industry mapping
- Credit rating distribution modeling
- Benchmark weight generation

---

## Dataset

The generated portfolio contains:

- 150 corporate bonds
- Multiple sectors and industries
- Global issuer coverage
- Credit ratings from AAA to CCC
- Duration, spread, yield, and return metrics
- Portfolio and benchmark weights

Example fields:

| Field |
|---------|
| Bond_ID |
| Issuer |
| Sector |
| Industry |
| Rating |
| Country |
| Position |
| Price |
| Duration |
| Spread_bps |
| Yield |
| Daily_Return |
| Benchmark_Return |
| Market_Value |
| Portfolio_Weight |
| Benchmark_Weight |

---

## Technology Stack

- Python
- Pandas
- NumPy
- Excel
- VS Code

---

## Project Structure

```text
liquid-credit-portfolio-risk-analytics-engine/

├── data_generator/
│   └── generate_credit_portfolio.py

├── analytics/
│   ├── portfolio_analytics.py
│   ├── risk_analytics.py
│   ├── attribution.py
│   └── stress_testing.py

├── sample_data/
│   └── credit_portfolio_150_bonds.csv

├── README.md
└── requirements.txt
```

## Sample Portfolio Metrics

- Total Market Value
- Weighted Average Duration
- Weighted Average Yield
- Average Credit Spread
- Sector Exposures
- Rating Exposures
- Benchmark Active Weights

---

## Running the Project

Install dependencies:

```bash
pip install -r requirements.txt
```

Generate sample portfolio:

```bash
python generate_credit_portfolio.py
```

Run analytics:

```bash
python portfolio_analytics.py
```

---

## Future Enhancements

- Yield curve risk decomposition
- Tracking error analysis
- VaR and CVaR calculations
- Interactive dashboard
- Portfolio optimization module
- Scenario analysis framework

---

## Author

Developed as a fixed income portfolio analytics and risk management project demonstrating quantitative finance, portfolio management, and Python-based analytics capabilities.
