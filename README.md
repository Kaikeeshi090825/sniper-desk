<div align="center">

<img src="https://img.shields.io/badge/-SNIPER%20DESK-f97316?style=for-the-badge&logoColor=white&labelColor=09090b" alt="Sniper Desk"/>

# 🎯 Sniper Desk

**A precision-built ICT/SMC trading assistant for Philippine timezone forex traders.**

*Single-file. Zero dependencies. Your data never leaves your browser.*

[![Version](https://img.shields.io/badge/version-2.1-f97316?style=flat-square)](#)
[![License](https://img.shields.io/badge/license-MIT-10b981?style=flat-square)](LICENSE)
[![No Backend](https://img.shields.io/badge/backend-none-71717a?style=flat-square)](#)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-10b981?style=flat-square)](#)
[![Pairs](https://img.shields.io/badge/pairs-5-0ea5e9?style=flat-square)](#)
[![Timezone](https://img.shields.io/badge/timezone-PHT-d946ef?style=flat-square)](#)

[**Live Demo**](#) · [**Features**](#-features) · [**Quick Start**](#-quick-start) · [**Self-Host**](#-self-host) · [**Roadmap**](#-roadmap)

</div>

---

## 📖 What is Sniper Desk?

Sniper Desk is a self-contained, password-protected trading desk that turns scattered prep work — bias-marking, fib levels, pivot calcs, news tracking, position sizing, journaling — into one focused workflow built around the **ICT/SMC top-down methodology**. It's tuned specifically for traders working in **Manila time (PHT)** who hunt setups across the London and New York killzones.

It runs entirely in your browser. There is no server, no account, no telemetry, no analytics. Open the HTML file, set a password, start trading sharper.

> ⚠️ **Educational tool. Not financial advice.** Trade your plan, log every trade, respect your stops.

---

## ✨ Features

### 🧭 Top-Down Bias Workflow

- **Bias Board** — Mark Daily / 4H / 1H bias for all 5 pairs. Auto-calculates A+ / A / B / C alignment tier per pair with per-pair reset.
- **Fundamental Bias Engine** — Log red/orange/yellow folder events with currency + direction; the engine weights and scores them into a per-pair fundamental verdict.
- **Composite Verdict** — Tech bias × Fundamental bias = single verdict (A+ LONG, A SHORT, CONFLICT, NEED TECH, etc.) for every pair, with a featured-pair selector on the dashboard.

### 🎯 Precision Tools

- **Pivot Calculator** — Standard / Fibonacci / Camarilla / Woodie methods with H/L/C/Open inputs. Click any level to auto-copy. Reset all + per-field clear buttons.
- **ICT Fibs** — Retracement (0 → 1.0) and Extension (0 → 4.0) coefficients with full definitions for every level. Copy-paste strings for TradingView.
- **Active Zones Watchlist** — Build a sniper watchlist with Entry / SL / TP1-3, auto-calculated R-multiples, and 5 status states (Active, Triggered, Hit TP, Stopped Out, Expired).
- **Entry Confluence Scorer** — 12-point checklist gating you into A+ (11/12), A (9/12), B, or NO TRADE verdicts. Saved per day.
- **Position Size Calculator** — Account × Risk % × SL distance → exact lot size (standard / mini / micro). Pip values pre-configured per pair including JPY and XAU.
- **R:R Calculator** — Entry/SL/TP1-3 → individual R-multiples + weighted R (50/30/20 partial-exit model).

### 📅 Session Awareness

- **Live Killzone Tracker** — 7 sessions in PHT with live "LIVE" indicator that updates without page flicker. Each zone is a dropdown with a definition, a DO list, and a DON'T list.
- **Session-Tuned Dashboard** — Greeting + featured pair verdict + live session message that adapts (Sydney/Tokyo, London KZ, NY KZ, NY/London Overlap, NY PM, Off Hours).

### 📓 Journaling & Performance

- **Trade Journal** — Log every trade with pair, direction, session, setup, all 3 bias TFs, entry/SL/TP/exit, R-multiple, confluence score, emotion, and lesson notes.
- **Stats Dashboard** — Win rate, total R, expectancy, profit factor, equity curve, win/loss pie, by-pair breakdown, by-session R-bars.
- **CSV Export/Import** — Round-trip your trades to Google Sheets / Excel.
- **Full JSON Backup** — One-click export of *everything* (trades, zones, bias, fundamentals, cheat sheet, settings) for cross-device sync.

### 📋 Auto-Summary Cheat Sheet

A printable / save-as-PDF daily plan that **pulls live** from every other tab:

- Bias Grid (from Bias Board) — Daily/4H/1H/Tier/Composite per pair
- Fundamental events (from News)
- Active sniper zones (from Active Zones)
- Pivot levels (from Pivot Calculator)
- Position size summary (from Calc)
- Entry score + grade (from Score)
- Editable plan + end-of-day reflection (auto-saved per day)

### 📚 Playbook & Rules

- **6 collapsible setups**: London Judas, NY Displacement, Sydney-Range, FRVP Breakout-Retest, **ORB (Opening Range Breakout)**, **AMD (Accumulation, Manipulation, Distribution)** — each with prep, trigger, entry, and TP rules.
- **AMD identification guide** for spotting the 3-phase smart-money cycle on the chart.
- **Edge Rules lockdown** — 10 non-negotiables, mindset rules, tilt triggers.

### 🔐 Security & Privacy

- **Password-protected** — SHA-256 hashed locally. Never transmitted.
- **Session-based unlock** — Re-locks every new browser session.
- **Email-verified password recovery** — Local verification, data preserved on reset.
- **100% client-side** — No server, no analytics, no tracking. Your trading data is yours alone.

---

## 🚀 Quick Start

### Use it instantly

1. Download `index.html` (or clone this repo)
2. Open it in any modern browser
3. On first launch:
   - Enter your **trader name**
   - Enter your **email** (used for password recovery only)
   - Set a **password** (min 4 chars)
   - Optional: opt in to newsletter updates
4. Trade sharp

---

## 📐 Pair Configuration

Pre-configured for **5 majors** with correct pip values:

| Pair | Base | Quote | $/pip (1 lot) | Decimals |
|---|---|---|---|---|
| GBP/USD | GBP | USD | $10 | 5 |
| XAU/USD | XAU | USD | $1 | 2 |
| AUD/USD | AUD | USD | $10 | 5 |
| EUR/USD | EUR | USD | $10 | 5 |
| USD/JPY | USD | JPY | ~$9 | 3 |

To add or modify pairs, edit the `PI` (pair info) and `PAIRS` constants at the top of the script.

---

## 🗺️ Killzones (Manila Time / PHT)

| Window | PHT Time | Priority | Best Pairs |
|---|---|---|---|
| Sydney/Tokyo | 5:00 AM – 1:00 PM | Low | AUD |
| Pre-London Lull | 1:00 – 3:00 PM | Low | (Plan only) |
| **London Killzone** | 3:00 – 6:00 PM | High | GBP, EUR, AUD |
| London Lunch | 6:00 – 8:30 PM | Low | Caution |
| **NY Killzone** | 8:30 – 11:00 PM | **PRIME** | All pairs |
| **NY/London Overlap** | 11:00 PM – 12:00 AM | **PRIME** | All pairs |
| NY PM | 12:00 – 4:00 AM | Mid | XAU, JPY, AUD |

---

## 🛣️ Roadmap

- [ ] Multi-day cheat sheet history
- [ ] Setup heatmap (which setups perform best by session)
- [ ] Custom pair configurator UI
- [ ] Dark theme accent customization
- [ ] PWA install + offline mode
- [ ] Optional cloud sync via webhook

Have a feature request? [Open an issue](../../issues).

---

## ⚖️ MIT License

Copyright (c) 2026 Sniper Desk.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

ADDITIONAL NOTICE — TRADING DISCLAIMER
This software is provided for educational purposes only. It is NOT financial
advice, investment advice, or a recommendation to trade. Trading foreign
exchange, gold, or any financial instrument carries a high level of risk and
may not be suitable for all investors. The high degree of leverage common in
forex trading can work against you as well as for you. Before deciding to
trade, you should carefully consider your investment objectives, level of
experience, and risk appetite. The possibility exists that you could sustain
a loss of some or all of your initial investment, and therefore you should not
invest money that you cannot afford to lose.
The author(s) of this software bear no responsibility for any trading losses,
account drawdowns, missed trades, missed news events, incorrect signals, or
any other financial outcome resulting from the use of this tool. Past
performance does not guarantee future results. Trade at your own risk.

---

## 🙏 Credits

- ICT/SMC concepts from the broader smart-money trading community
- Icon set: [Lucide](https://lucide.dev) (inlined as SVG, no dependency)
- Built for Filipino retail traders working PHT hours

---

<div align="center">

**Built for snipers who think in Daily / 4H / 1H, not in 1-min FOMO.**

⭐ Star this repo if it helps you trade sharper.

</div>
