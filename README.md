# Mortgage & Investment Tradeoff Tools

A pair of personal finance tools for modeling mortgage payoff scenarios and comparing them against S&P 500 index investing. Built as standalone HTML files — no dependencies, no backend, runs entirely in the browser.

## Tools

### Mortgage Calculator (`index.html`)
Full PITI (Principal, Interest, Tax, Insurance) payment breakdown with payoff scenario modeling.

**Features:**
- True monthly housing cost breakdown including property tax and homeowner's insurance
- Windfall, extra monthly, and extra quarterly payment modeling
- Payoff scenarios with interest saved and time saved
- SPY investment tradeoff section — compares the same dollars invested in the S&P 500 against mortgage interest saved, modeled over your accelerated payoff timeline
- Configurable SPY annual return assumption

### SPY vs. Mortgage Tradeoff Chart (`mortgage_vs_spy_chart.html`)
Interactive chart plotting quarterly payment size against the SPY growth advantage over mortgage interest savings, with curves for SPY return assumptions from 5% to 11%.

**Features:**
- Visual break-even line separating "SPY wins" and "Mortgage wins" zones
- Hover crosshair showing exact values at any quarterly payment level
- Configurable loan parameters, windfall, and extra monthly payment

## Usage

Both tools are fully self-contained — open either HTML file directly in a browser or visit the live links below. All calculations run locally; no data is sent anywhere.

Update the input fields in each tool to match your loan balance, interest rate, property tax rate, home value, and insurance costs.

## Live

- **Mortgage Calculator:** [stephenrmoreno.github.io/mortgage-vs-spy](https://stephenrmoreno.github.io/mortgage-vs-spy)
- **Tradeoff Chart:** [stephenrmoreno.github.io/mortgage-vs-spy/mortgage_vs_spy_chart.html](https://stephenrmoreno.github.io/mortgage-vs-spy/mortgage_vs_spy_chart.html)

## Assumptions & Disclaimers

- SPY returns are modeled at a flat annual rate — real market returns vary significantly year to year
- Mortgage interest savings are guaranteed; SPY growth projections are not
- Capital gains taxes on SPY investments are not factored in, which would reduce the invest-side figures
- Property tax is calculated as a flat percentage of appraised value; actual bills may vary based on exemptions and assessment cycles
- These tools are for personal modeling purposes only and do not constitute financial advice
