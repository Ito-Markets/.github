<p align="center">
  <a href="https://itomarkets.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/ito-lockup-light.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/ito-lockup-dark.svg">
      <img alt="Ito Markets" src="assets/ito-lockup-dark.svg" width="420">
    </picture>
  </a>
</p>

<p align="center"><b>The fixed-rate compute desk for AI teams</b></p>

<p align="center">
  <a href="https://itomarkets.com">itomarkets.com</a> ·
  <a href="https://compute.itomarkets.com">compute.itomarkets.com</a> ·
  <a href="https://github.com/affaan-m/ECC">ECC</a> ·
  <a href="https://x.com/absurdistphil">𝕏</a>
</p>

---

## What we do

GPU spot prices move. Training budgets don't. Ito writes fixed-rate compute contracts: lock a GPU-hour price for 30 to 365 days and pay that rate for the whole term. The desk holds the other side and hedges it across providers. First contracts executed July 2026.

- Term contracts on GPU-hours, 30 to 365 days
- One fixed rate per term, priced off live multi-provider spot data
- The desk carries the price risk, not the buyer

Get a quote at [compute.itomarkets.com](https://compute.itomarkets.com).

## The agent rail

Agents spend compute too, so we ship the rail for them to buy it directly:

- **[ECC](https://github.com/affaan-m/ECC)**: the agent harness performance system for Claude Code, Codex, Cursor and beyond. Ito sponsors it and the compute desk plugs in as a skill.
- **ito-compute-cli**: quote, lock, and manage contracts from the terminal. Bundled into the Ito runtime; npm publish lands when it exits demo mode.
- Inside the harness, an agent can price a contract and lock it without leaving its loop.

## Earlier work

Ito started as a systematic prediction-markets desk. That research is still public: [iran-oil-statarb](https://github.com/Ito-Markets/iran-oil-statarb) (Brent crude signals from Middle East contracts, Sharpe 1.27), [polymarket-universe](https://github.com/Ito-Markets/polymarket-universe) (graph database of 546k Polymarket contracts), and [pm-history-tracker](https://github.com/Ito-Markets/pm-history-tracker).

---

<p align="center"><sub>
  <a href="https://itomarkets.com">itomarkets.com</a> ·
  <a href="https://compute.itomarkets.com">compute desk</a> ·
  <a href="https://github.com/affaan-m/ECC">ECC</a> ·
  <a href="https://itomarkets.substack.com">Substack</a>
</sub></p>
