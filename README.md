# SPY vs. Mortgage Tradeoff Chart

An interactive personal finance tool for visualizing the tradeoff between paying down a mortgage early and investing the same dollars in the S&P 500. Built as a standalone HTML file — no dependencies, no backend, runs entirely in the browser.

## Tool

### SPY vs. Mortgage Tradeoff Chart (`mortgage_vs_spy_chart.html`)
Interactive chart plotting quarterly payment size against the SPY growth advantage over mortgage interest savings, with curves for SPY return assumptions from 5% to 11%.

**Features:**
- Visual break-even line separating "SPY wins" and "Mortgage wins" zones
- Hover crosshair showing exact values at any quarterly payment level
- Configurable loan parameters, windfall, and extra monthly payment

## Usage

Fully self-contained — visit the live link below or open the HTML file directly in a browser. All calculations run locally; no data is sent anywhere.

Update the input fields to match your loan balance, interest rate, remaining months, windfall, and extra monthly payment.

## Live

- **Tradeoff Chart:** [stephenrmoreno.github.io/mortgage-vs-spy](https://stephenrmoreno.github.io/mortgage-vs-spy)

## Assumptions & Disclaimers

- SPY returns are modeled at a flat annual rate — real market returns vary significantly year to year
- Mortgage interest savings are guaranteed; SPY growth projections are not
- Capital gains taxes on SPY investments are not factored in, which would reduce the invest-side figures
- These tools are for personal modeling purposes only and do not constitute financial advice
