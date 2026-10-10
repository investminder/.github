<div align="center">

# Investminder

### Systematic investing and portfolio management, with no black box

[![AI ready: MCP](https://img.shields.io/badge/AI%20ready-Model%20Context%20Protocol-blueviolet.svg)](#use-investminder-from-your-ai-assistant)
[![Bank sync: read-only PSD2](https://img.shields.io/badge/Bank%20sync-Read--only%20PSD2-blue.svg)](#security-and-privacy)
[![Platform: Web & mobile](https://img.shields.io/badge/Platform-Web%20%26%20mobile-orange.svg)](https://investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme)

**Invest on evidence, not on gut feeling.**

**[Start for free →](https://investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme)**
· [Help center](https://help.investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme)
· [Investminder on Claude](https://claude.ai/directory/investminder)

</div>

---

## What is Investminder?

Investminder is a SaaS platform for individual investors who want a method rather than a hunch.
Unlike trading apps built for compulsive clicking, or robo-advisors that hide their logic,
Investminder gives you a transparent framework you can inspect and adjust at every step:

1. **Design** your own allocation strategy, or start from a documented model.
2. **Test** it with backtests on 10 to 25+ years of real market data, back to the year 2000.
3. **Manage** your real accounts in one place and correct allocation drift with your monthly savings.
4. **Connect** your portfolio to AI assistants such as Claude through the Model Context Protocol (MCP).

---

## Key features

### 1. Strategy design

A guided **"4 questions, 1 strategy"** questionnaire, a library of ready-made models and a
no-code builder to create your own rules.

<details>
<summary>See the details</summary>

- **Guided questionnaire:** your investor profile (*Explorer*, *Builder* or *Optimizer*), horizon,
  capital and risk tolerance turn into strategies you can use right away.
- **Strategy library:** documented multi-asset models (world equity ETFs, bonds, gold, cash,
  active management, trend following, mean reversion) whose rules you can inspect.
- **No-code custom builder:** define your allocation rules step by step: asset selection,
  indicator thresholds, target weights and rebalancing rules.

</details>

### 2. Market tools and quantitative screener

Find the right stocks and ETFs, compare them and check that your ETFs don't overlap.

<details>
<summary>See the details</summary>

- **Stock and ETF screener:** large and mid-cap stocks, UCITS and international index trackers.
- **Multi-criteria filters:** fundamental, sector and geographic criteria, plus historical
  volatility, maximum drawdown, RSI, MACD, moving averages and ATR.
- **Saved presets:** store your filters and get back to your usual selections in one click.
- **Asset comparison:** side-by-side view to evaluate candidates before adding them to a strategy.
- **ETF overlap calculator:** measures the real share of holdings two or more ETFs have in common,
  with a look-through analysis of their top 15 holdings, for both physical and synthetic ETFs
  (based on the replicated index).

</details>

### 3. Backtest engine

See how a strategy would have held up through the 2000 dot-com bubble, the 2008 financial crisis
and the 2020 Covid crash, before you put money on it.

<details>
<summary>See the details</summary>

- **No black box:** every parameter, entry and exit rule and indicator is visible and editable.
- **Risk first:** maximum drawdown is shown before performance.
- **Performance metrics:** CAGR and total return against a benchmark, volatility and Sharpe ratio.
- **Data depth by plan:** from 10 years of history on the free plan up to the full history since
  2000 on Elite.

</details>

### 4. Account aggregation and dashboard

All your bank and brokerage accounts in one dashboard, synced in read-only mode, or entered by hand.

<details>
<summary>See the details</summary>

- **Secure Open Banking / PSD2 sync:** read-only connection to 300+ banks and brokers
  (BoursoBank, Fortuneo, Trade Republic, DEGIRO, Interactive Brokers, Revolut and more) through
  **Powens** (licensed by the French ACPR) for European banks and savings plans, and
  **SnapTrade** (SOC 2 Type II) for international brokers and exchanges.
- **Manual mode:** track every position without ever connecting your bank accounts.
- **Unified dashboard:** a consolidated or per-account view, broken down by asset class,
  region, sector and currency.
- **Multiple portfolios:** keep separate pockets apart, for example *Dividends*, *Momentum*
  or *Emergency fund*.

</details>

### 5. Rebalancing with your savings

Stop selling your winners to rebalance. Investminder tells you exactly what to buy with your
next deposit to get back to your target allocation.

<details>
<summary>See the details</summary>

- **Allocation gap tracking:** instantly see how far your real weights have drifted from your targets.
- **Cash-flow rebalancing:** the algorithm splits 100% of your new monthly deposit to fill the
  underweight positions, so you avoid capital gains tax and trading fees from selling.
- **Position sizing:** the exact number of shares or units to buy with the cash you have.
- **Ready-to-use action plan:** a step-by-step order list you can place at your broker in under
  five minutes.
- **Dividend tracking:** a history of the income you received and a calendar of upcoming payments.

</details>

### 6. Smart alerts

No more watching prices all day. You only get an alert when there is something to do: drift
beyond your tolerance, a technical signal triggered, or a rebalancing due.

---

## Use Investminder from your AI assistant

Investminder has a native [MCP](https://modelcontextprotocol.io) server. Claude and other
MCP-compatible assistants can securely read the state of your portfolios and work with your
Investminder account, with no copy-pasting.

```
https://api.investminder.com/mcp
```

Find Investminder in the [Claude directory](https://claude.ai/directory/investminder).

---

## Security and privacy

| Component | Technical guarantee |
| :--- | :--- |
| **Account access** | **Strictly read-only.** Investminder cannot initiate a transfer or a trade. |
| **Bank aggregation** | Certified PSD2 / Open Banking partners: **Powens** (ACPR) and **SnapTrade** (SOC 2 Type II). Investminder never stores your bank credentials. |
| **Encryption** | **AES-256** at rest and **TLS 1.2+** in transit. |
| **Hosting** | **Google Cloud Platform**, certified ISO 27001, SOC 1/2/3 and PCI DSS. Development follows the OWASP Top 10. |
| **Sign-in and payment** | Authentication by **Auth0**, billing by **Stripe**. |
| **Data protection** | GDPR (EU), CCPA (California) and PIPEDA (Canada) compliant. We never sell personal data. Full deletion on request. |

Found a vulnerability? Please read our
[security policy](https://github.com/investminder/.github/blob/main/SECURITY.md).

---

## Plans

| | Basic | Essential | Pro | Elite |
| :--- | :---: | :---: | :---: | :---: |
| **Price (billed annually)** | Free | $10 / month | $25 / month | $70 / month |
| **Active portfolios** | 1 (up to 10 positions) | 1 | 5 | Unlimited* |
| **Saved strategies** | 1 | 2 | 10 | Unlimited* |
| **Backtests per day** | 10 | 25 | 100 | Unlimited* |
| **Historical depth** | 10 years | 15 years | 20 years | Full (since 2000) |
| **Bank sync** | Manual only | ✅ | ✅ | ✅ |
| **Saved screener presets** | ❌ | ✅ | ✅ | ✅ |
| **Smart alerts** | ❌ | ✅ | ✅ | ✅ |
| **Support** | Standard | Standard | Priority | Dedicated |

<sub>* Subject to fair use.</sub>

**[Start with the free plan →](https://investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme_pricing)**

---

## Founders

Investminder was founded by two engineers who are individual investors themselves.

- **Thierry Marrec, CEO and product strategy.** EFREI Paris graduate and former consultant in
  banking and insurance systems. He designed the Strategy Builder and calibrated every model
  strategy on the platform.
- **Nordine El Housni, CTO and systems architecture.** École des Mines de Douai graduate, expert
  in distributed platforms, low-latency computing and cloud infrastructure. He built the backtest
  engine and data isolation, and leads R&D on AI agents and the MCP server.

### Independent by design

- **No brokerage commissions:** Investminder sells no financial products.
- **No conflicts of interest:** a pure software subscription model, so the analysis has no
  reason to push you towards any product.

---

## Get in touch

- 🌐 [investminder.com](https://investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme) · [Help center](https://help.investminder.com/?utm_source=github&utm_medium=org_profile&utm_campaign=readme)
- 💼 [LinkedIn](https://www.linkedin.com/company/investminder) · [X](https://x.com/investminder) · [Instagram](https://www.instagram.com/investminder_com)
- 💬 Talk investing strategies with the community on [r/Investminder](https://www.reddit.com/r/Investminder/)

---

<sub>**Disclaimer.** Investminder is a quantitative analysis and decision-support tool. It does not
provide personalised investment advice. Past performance and backtest results are not indicative of
future results. All investing involves a risk of capital loss. You remain solely responsible for
the orders you place with your broker.</sub>
