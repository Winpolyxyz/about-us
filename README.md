# Winpoly

Automated +EV sports trading infrastructure for Polymarket.

→ [winpoly.xyz](https://winpoly.xyz)

---

## What is Winpoly?

Winpoly is an automated trading system that identifies and
executes +EV positions on Polymarket sports markets. It
benchmarks every Polymarket line against sharp sportsbooks
like Pinnacle, tracks profitable on-chain wallets, detects
structural arbitrage opportunities, and reacts to breaking
injury news — all in real time.

Every position is sized using Quarter-Kelly criterion with
a 5% max allocation per market and a 30% cash reserve floor.

## The Engines

**The Pinnacle Gap** — Cross-references Polymarket prices
against Pinnacle in real time. Executes automatically when
the edge exceeds 3.5%.

**Structural Arbitrage** — Detects when outcome prices on
a market fail to sum to $1.00. Captures the guaranteed
profit in under 200ms.

**Whale Copy** — Monitors every Polymarket wallet profitable
over 30 days. Mirrors their positions within one second of
entry.

**News Reflex** — Ingests injury reports and breaking sports
news. Trades the repricing gap before Polymarket catches up,
targeting a 15-second execution window.

## Links

- Website: [winpoly.xyz](https://winpoly.xyz)
- Docs: [winpoly.xyz/docs](https://winpoly.xyz/docs)
- X: [@winpoly](https://twitter.com/winpoly)

© 2026 Winpoly
