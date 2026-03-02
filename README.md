# CNH CCS Spread Matrix Calculator

Offline calculator for CNH Cross-Currency Swap spreads and butterflies.

## Features

- 14 tenors (6M to 15Y)
- 91 spreads, 364 butterflies with configurable filters
- Multi-pass calculation engine with provenance tracking
- Crossed spread/butterfly formulas
- Back-calculation of outrights from manual spread inputs
- Narrowing override logic with bid ≤ ask enforcement
- Recursive dependency highlighting
- Recursive leaf-level trade chain descriptions (Take/Give decomposition)
- Input validation (keydown + paste filtering)

## Usage

Open `index.html` in any browser. No server or dependencies required.

Enter outright rates, spreads, or butterflies — the engine auto-calculates all derivable values. Click any calculated cell to see the full trade decomposition and source highlighting.

## Deployment

Hosted via Vercel. Any push to `main` auto-deploys.
