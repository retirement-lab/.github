# Retirement Lab

  Monte Carlo retirement simulator with fat-tail distributions, dynamic spending strategies, and historical stress testing.

  ## What it does

  - Runs Monte Carlo simulations across user-defined market assumptions
  - Models returns with Student's t-distribution and Fernandez-Steel skewness for fatter, asymmetric tails
  - Compares four withdrawal policies: fixed amount, Guyton-Klinger guardrails, percentage of portfolio, floor & ceiling
  - Cross-checks parametric simulations against 1928 to 2025 historical S&P 500 and Treasury returns
  - Exposes every assumption: expected returns, volatility, correlation, skewness, tax rate, inflation

  ## Stack

  TypeScript, Next.js, Supabase. Engine is pure TypeScript, DOM-free, deterministic via seeded PRNG.

  ## Links

  - Product: https://retirement-lab.com
  - How it works: https://retirement-lab.com/how-it-works
  - Pricing: https://retirement-lab.com/pricing

  Built by an independent software engineer in Switzerland.
