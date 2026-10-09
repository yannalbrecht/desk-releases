# Desk

**A private portfolio desk that runs on your own computer.** See your whole book, how it's really doing against the index you could have bought instead, what it's exposed to, and what the great investors' rules would say about each holding. No account, no cloud, no subscription. Your data never leaves your machine.

![Desk overview](assets/overview.png)

**[⬇ Download the latest version](https://github.com/yannalbrecht/desk-releases/releases/latest)** · Mac (Apple Silicon and Intel, signed by Apple) and Windows · updates itself

<p align="center"><img src="assets/desk-tour.gif" alt="A tour through Desk" width="900"></p>
<p align="center"><sub>A one-minute tour (<a href="assets/desk-tour.mp4">full-quality video</a>). All screens show a demo book.</sub></p>

---

## What it does

### Your book, honestly measured
- **Overview** says in one sentence how you're doing against your benchmark (MSCI World by default, or your own blend), with today, month, year, max drawdown, Sharpe and a diversification score.
- **Positions** shows every holding with its weight, distance from the 200-day average, RSI, 52-week range and a 30-day sparkline. The default sort is by weight, not by gain, because ranking by gain nudges you to sell your best and worst names.
- **Import from Trade Republic** (exact weights, average cost with fees, real buy dates), or set it up by hand with any broker. Crypto (Bitcoin, Ether and more) counts as a holding, priced in euros.
- **Privacy switch** (the eye) hides every amount at a glance.

![Positions](assets/positions.png)

### What you're really exposed to
- **Exposure** by country of listing, headquarters, revenue or currency, with ETFs looked through to their holdings, a diversification score and your regions against the world index.
- **Preview a trade** before you make it: exposure, risk share and concentration, before and after.

![Exposure](assets/exposure.png)

### Analytics
- **Returns** against MSCI World, the S&P 500 or your own blend; monthly heatmap; **risk** (drawdown, risk contribution per holding); **correlation** clusters.
- **Fundamentals** for every stock: revenue, margins, cash flow and balance sheet from the companies' own filings (SEC EDGAR for US companies, ESEF annual reports for European ones), annual, half-year and quarterly. Upload a quarterly report (PDF) and Desk reads its figures.

![Fundamentals](assets/instrument-fundamentals.png)

### Viewpoints: the great investors' rules, applied to your holdings
Switch on any of them, alone or together. Each checks every holding rule by rule with the number used and a link to its source, and comes with an explainer: who it's from, what it checks, how to read it, and where it falls short.

| Viewpoint | After | What it checks |
|---|---|---|
| **Defensive value** | Benjamin Graham | Graham's seven criteria for the defensive investor, the Graham number and margin of safety |
| **Quality at a fair price** | Warren Buffett and Charlie Munger | Returns on equity and capital, margin stability, debt, dilution, owner-earnings yield against the bond |
| **Financial strength** | Joseph Piotroski and Edward Altman | The nine-point F-Score and the Altman Z distress zones |
| **Magic formula** | Joel Greenblatt | Earnings yield and return on capital, ranked across what you hold and watch |
| **Growth at a reasonable price** | Peter Lynch | Lynch's six company categories, PEG and the dividend-adjusted ratio |
| **All Weather** | Ray Dalio | Which economic seasons your book's risk depends on, against equal risk in each |
| **Cycles and sentiment** | Howard Marks and John Templeton | Where the market stands against its own history (CAPE, credit spreads, VIX, breadth), and fallen stocks at the bottom of their own valuation |
| **Passive core** | John C. Bogle | What your funds cost, where they overlap, and whether your picks beat the index |
| **Technical** | RealValue Trend Phase Framework | Trend phase first, then the tools that suit it; also measured in gold |

![Quality at a fair price](assets/viewpoint-quality.png)

![All Weather](assets/viewpoint-allweather.png)

![Cycles and sentiment](assets/viewpoint-cycles.png)

![Technical](assets/technical.png)

### Markets
Fear & Greed for stocks (CNN) and crypto, VIX and VSTOXX, gold in euros, silver, Brent, US and German 10-year yields, Shiller's CAPE, the high-yield credit spread, EUR/USD, Bitcoin and Ether. Each reading shows its source and when it was last updated, and none is shown as current once it's stale.

![Markets](assets/markets.png)

### Plan, watchlist and alerts
Buy levels and zones, accumulation ladders, a swing book with stops and targets, and a watchlist that shows each name's viewpoint scores. Desk notifies you when a price reaches a level, a holding breaks a rule you set, or the data behind a number changes.

### Data you can trust
- A nightly **Data check** compares sources, flags figures that disappear, and spots periods where results are out but figures haven't arrived.
- **Data reports** keep 90 days of checks. Share an anonymised copy for support: it names no holdings, ISINs or amounts.
- Every number links to where it came from.

### Ask Claude (optional, off by default)
Let an AI assistant read your Desk at the level you choose (market data only, weights, or everything) through MCP, with setup for Claude Desktop and Claude Code.

---

## Download

Go to **[Latest release](https://github.com/yannalbrecht/desk-releases/releases/latest)** and, under **Assets**, download the one file for your computer:

| Your computer | Download | |
|---|---|---|
| **Mac with Apple Silicon** (M1, M2, M3, M4 …) | `Desk-<version>-arm64.dmg` | Most Macs from late 2020 on |
| **Mac with Intel** | `Desk-<version>.dmg` (no "arm64" in the name) | Older Macs |
| **Windows 10 / 11** | `Desk-Setup-<version>.exe` | |

You don't need the `.zip`, `.blockmap` or `.yml` files; Desk uses those to update itself.

**Which Mac do I have?** Apple menu  → **About This Mac**. If it says **Chip: Apple M…**, take the `arm64` file. If it says **Processor: … Intel …**, take the other `.dmg`.

## Install

**Mac:** open the `.dmg`, drag **Desk** into **Applications**, open it. Desk is signed and notarised by Apple, so it opens like any other app.

**Windows:** run the `.exe`. If Windows shows "Windows protected your PC", click **More info → Run anyway** (the Windows installer isn't certificate-signed yet; this happens once).

## First start

Choose **Import from Trade Republic**. Desk shows step by step how to export your transactions in the Trade Republic app (Profile → Account statements → Transaction export). Or set it up by hand with any broker, or restore a Desk backup.

## Updates

Automatic: Desk checks on start and every few hours, and shows **Restart to update** in Settings → Updates. Your data is never touched by an update.

---

<sub>Desk shows information, not investment advice. Market data comes from free public sources (SEC EDGAR, ESEF filings, the ECB, the Bundesbank, FRED, Yahoo Finance and others), each named where it's used. Screenshots show a demo portfolio.</sub>
