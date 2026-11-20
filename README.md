# mohaserei_network_ecosystem_projection
Mohaserei System Network (MSN) — Ecosystem Projection (mohaserei_network_ecosystem_projection)

The Mohaserei Ecosystem Projection module (mohaserei_network_ecosystem_projection/index.html) is a standalone web-based modeling and scenario simulation interface for the Mohaserei System Network (MSN). It projects multi-year growth from 2026 to 2032 across projected member counts, Universal Economic Score (UES) readiness, Human Capital Value (HCV) pools, MSN Coin liquidity and unit valuation, Layer 2 Marketplace GMV, member profit-sharing dividends, and regional adoption across Cambodia's 25 provinces and capital.

Core Capabilities

Multi-Scenario Presets & Parameter Tuning:

Switch between Conservative, Baseline, and Accelerated growth presets or fine-tune individual sliders for horizon year (2026–2032), annual member/commune growth, UES target score, HCV velocity, target MSN Coin valuation (USD), profit-sharing pool rate, and Layer 2 monthly marketplace flow per member.

Includes a one-click parameter reset action.

Interactive Trajectory Chart (2026–2032):

Renders a responsive HTML5 <canvas> line and area chart comparing projected values against a conservative baseline (plus a secondary layer where applicable) across MSN Liquidity, UES & HCV, Members, and Marketplace.

Supports hover and touch inspection with a floating year-by-year tooltip and clickable year readout strip.

Regional Adoption Across All 25 Cambodian Provinces & Capital:

Models regional member share, active communes/sangkats, and regional UES scores across Phnom Penh and all 24 provinces.

Includes an interactive SVG top-10 bar chart, a province selector dropdown, a 25-region chip list, and a detailed regional focus card.

Annual Projection Schedule Table:

Displays a year-by-year schedule (2026–2032) covering members, UES index, HCV pool, MSN liquidity, marketplace GMV, and annualized profit-sharing dividends, highlighting the selected horizon year.

Bilingual UI (EN / ភាសាខ្មែរ), Voice Announcements & Local Persistence:

Switches interface labels and regional/KPI descriptions between English (EN) and Khmer (ភាសាខ្មែរ) using Kantumruy Pro and Inter.

Supports on-demand and toggleable automated Web Speech API (speechSynthesis) announcements with non-blocking visual notifications as a fallback.

Persists active parameters, presets, language, selected metric, and focused province in localStorage under mohaserei_ecosystem_projection_v1.

Running Locally

Open index.html directly in a modern browser or serve it through a static HTTP server:

python3 -m http.server 8080


Then visit http://localhost:8080/mohaserei_network_ecosystem_projection/index.html.

Ecosystem Integration Notes

Maintain the exact brand spelling Mohaserei across all documentation, modules, and datasets.

Align regional administrative hierarchies and commune/sangkat totals with the Mohaserei registration dataset as live network telemetry becomes available.
