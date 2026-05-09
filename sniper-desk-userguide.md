# 🎯 Sniper Desk — User Guide

**Version 2.1** · Educational tool. Not financial advice.

A precision-built ICT/SMC trading assistant for Philippine timezone forex traders. This guide walks you through every tab, in the recommended order of use during a typical trading day.

---

## 📑 Table of Contents

1. [Getting Started — First Launch](#getting-started)
2. [Dashboard](#dashboard)
3. [Bias Board](#bias-board)
4. [Playbook](#playbook)
5. [ICT Fibs](#ict-fibs)
6. [Pivots](#pivots)
7. [Killzones](#killzones)
8. [Active Zones](#active-zones)
9. [Entry Score](#entry-score)
10. [Risk & R:R](#risk--rr)
11. [News](#news)
12. [Journal](#journal)
13. [Stats](#stats)
14. [Cheat Sheet](#cheat-sheet)
15. [Settings & Backup](#settings--backup)
16. [Recommended Daily Workflow](#recommended-daily-workflow)

---

<a id="getting-started"></a>
## 1. Getting Started — First Launch

`[IMAGE: Welcome / setup screen with greeting and registration form]`

When you open Sniper Desk for the first time, you'll see a setup screen.

**Steps:**

1. **Trader name** — Your handle. This will greet you on the dashboard ("Good morning, John").
2. **Email** — Used only for password recovery if you forget it. Stored locally.
3. **New password** — At least 4 characters. Hashed locally with SHA-256 and never transmitted.
4. **Confirm password** — Must match.
5. **Newsletter opt-in** — Optional. Tick if you want updates from the developer.
6. Click **Set Up & Enter**.

**Returning users:** You'll see the unlock screen with a time-of-day greeting. Type your password and press Enter.

**Forgot your password?** Click "Forgot password?" → enter your registered email → set a new one. Your trading data is preserved.

---

<a id="dashboard"></a>
## 2. Dashboard

`[IMAGE: Full dashboard view showing greeting, session, composite verdict, 5-pair strip, KPI tiles]`

The Dashboard is your situational awareness panel. Every time you open Sniper Desk, this is where you start.

### What you see, top to bottom:

**Greeting + Session card**
`[IMAGE: Greeting card with current session and 3 quick-action buttons]`
Time-of-day greeting + your trader name + the live PHT session (Sydney/Tokyo, London KZ, NY KZ, etc.) with a contextual message ("Sniper window. London-NY overlap. All pairs active.").

**Quick action buttons**
- **Mark Bias** → Bias Board
- **Log News** → News tab
- **Score Setup** → Entry Score

**Tech vs Fund — Featured Pair**
`[IMAGE: Composite verdict card with featured pair and 5-pair strip below]`
The most important card on the page. Pick a pair from the dropdown. The card shows:
- **Tech direction** (from your Bias Board)
- **Fund direction** (from your News tab)
- **Composite verdict** — A+ LONG, A SHORT, CONFLICT, NEED TECH, etc.
- **Detail message** — what this means and what to do

Below it, a 5-pair strip shows every pair's verdict at a glance. Click any pair to feature it.

**KPI Tiles**
`[IMAGE: 4 stat tiles — Account, Trades 7d, Win Rate, R Captured]`
Account balance, last 7 days of trades, win rate, R captured.

**Daily routine + No-trade conditions**
Two reference cards at the bottom — your pre-trade checklist and your stop signs.

### How to use it:
- **Open Sniper Desk → glance at the featured pair verdict.** If it says A+ or A, you have a high-probability day. If it says CONFLICT or NO DATA, you have prep work to do.
- The session badge top-right tells you whether you're in a tradeable window.

---

<a id="bias-board"></a>
## 3. Bias Board

`[IMAGE: Bias Board with 5 pair cards showing Daily/4H/1H buttons]`

Where you mark your multi-timeframe bias for each of the 5 pairs. Saved per day (resets at midnight Manila time).

### How to use it:

For each pair card:

1. **Daily** — Click Bull, Bear, or Neutral based on the macro trend.
2. **4H** — Click Bull, Bear, or Neutral based on 4H structure (last BOS direction).
3. **1H** — Click Bull, Bear, or Neutral based on 1H refinement.

`[IMAGE: Single pair card with Bull selected on Daily, Bear on 4H, Tier showing C — NO TRADE]`

The card automatically calculates a **Tier**:

| Tier | Meaning | Action |
|---|---|---|
| **A+** (green) | All 3 TFs aligned (all Bull or all Bear) | Hunt setups in that direction |
| **B** (amber) | 2 of 3 aligned, 1 Neutral | Wait for misaligned TF to flip |
| **C** (gray) | Conflicting timeframes | NO TRADE |

### Reset button:

`[IMAGE: Reset button highlighted on a single pair card]`

Each pair has a **Reset** button to clear all 3 timeframes at once.

### Tip:
Mark all 5 pairs before London opens (3:00 PM PHT). This sets your menu for the day — only A+ pairs deserve sniper attention.

---

<a id="playbook"></a>
## 4. Playbook

`[IMAGE: Playbook with all 6 collapsible setup cards visible]`

Reference library of your 6 ICT/SMC setups, each as an expandable card.

### How to use it:

Click any setup to expand it.

`[IMAGE: Single expanded setup card showing Prep / Trigger / Entry & SL / TP columns]`

Each setup contains:
- **Prep (Bias First)** — what your Bias Board must show before you even consider this setup
- **Trigger** — the chart event that activates the setup
- **Entry & SL** — exact entry method + stop placement
- **TP** — profit targets

### The 6 setups:

1. **London Judas Reversal** — GBP/USD, EUR/USD
2. **NY Open Displacement** — XAU/USD, USD/JPY
3. **Sydney-Range Reversal** — AUD/USD
4. **FRVP Breakout-Retest** — All Pairs
5. **ORB (Opening Range Breakout)** — All pairs
6. **AMD (Accumulation, Manipulation, Distribution)** — All pairs

### AMD Identification Guide

`[IMAGE: AMD identification card at the bottom of the Playbook]`

A reference card explaining how to spot the 3-phase smart-money cycle on the chart:
- **Accumulation (A)** — tight Asian range
- **Manipulation (M)** — false break / liquidity sweep
- **Distribution (D)** — true move with HTF bias

### Tip:
Read through the Playbook once a week. The setups don't change — but your discipline does.

---

<a id="ict-fibs"></a>
## 5. ICT Fibs

`[IMAGE: ICT Fibs tab with both retracement and extension dropdowns visible]`

Reference for ICT-specific Fibonacci levels with definitions for every coefficient.

### How to use it:

**Click "Retracement Levels — definitions"** to expand the retracement coefficients:

`[IMAGE: Expanded retracement dropdown showing levels 0, 0.236, 0.382, 0.5, 0.618, 0.705, 0.79, 1.0]`

| Level | Name | Meaning |
|---|---|---|
| 0 | Swing Origin | Anchor — where the impulse started |
| 0.5 | Equilibrium | Above = Premium, below = Discount |
| 0.618 | OTE Start (Golden) | Smart-money entry zone begins |
| **0.705** | **OTE Sweet Spot** | **Highest-probability turning point** |
| 0.79 | OTE Deep | Deepest sniper entry before invalidation |
| 1.0 | INVALIDATION | If broken, your trade idea is wrong |

**Click "Extension Coefficients — definitions"** to expand the extensions:

`[IMAGE: Expanded extension dropdown showing levels 0, 0.5, 1.0, 1.5, 2.0, 2.5, 3.0, 4.0]`

These are your TP projections.

### TradingView setup:

`[IMAGE: TradingView setup card showing copy-paste coefficient strings]`

Two pre-formatted strings ready to paste into TradingView's Fib tool settings:
- Retracement: `0, 0.236, 0.382, 0.5, 0.618, 0.705, 0.79, 1`
- Extension: `0, 0.5, 1, 1.5, 2, 2.5, 3, 4`

### Tip:
The 0.705 ICT sweet spot is the single most useful number on this tab. Many ICT traders only enter inside the 0.618-0.79 OTE band.

---

<a id="pivots"></a>
## 6. Pivots

`[IMAGE: Pivot Calculator with input form on top and pivot ladder below]`

Calculates daily pivot levels using yesterday's H/L/C (and optional Open).

### How to use it:

**Step 1 — Configure:**
1. Pick your **Pair** from the dropdown
2. Pick your **Method**:
   - **Standard** — classic floor pivots, most widely watched
   - **Fibonacci** — uses fib retracement (38.2%, 61.8%, 100%)
   - **Camarilla** — tight intraday levels, R3/S3 are key reversal zones
   - **Woodie** — weights close more heavily

`[IMAGE: Method dropdown open showing all 4 options]`

**Step 2 — Enter values:**
3. **Open** (optional) — today's opening price
4. **High** — yesterday's high
5. **Low** — yesterday's low
6. **Close** — yesterday's close

`[IMAGE: Filled input form with all 4 numeric values]`

**Step 3 — Read the ladder:**

`[IMAGE: Pivot ladder showing R3, R2, R1, PP, S1, S2, S3 with values]`

The ladder shows resistance levels (green) above PP (orange) and support levels (red) below.

**Step 4 — Click any level to auto-copy:**

`[IMAGE: Pivot row highlighted after click with toast notification "PP = 1.27450 copied"]`

Click any row to copy that price to your clipboard. A toast confirms the copy. Paste it directly into TradingView, MT4, or your trade ticket.

### Reset buttons:

- **× button** next to each input — clears just that field
- **Reset All button** (top-right) — clears all inputs and selections

### Tip:
- Open above PP = bullish bias for the session
- Open below PP = bearish bias
- R1/S1 are your first reaction zones
- Camarilla R3/S3 are the highest-probability reversal levels

---

<a id="killzones"></a>
## 7. Killzones

`[IMAGE: Killzones tab with all 7 zones, one showing LIVE indicator]`

The 7 trading sessions of the day in Manila time, with a live "LIVE" badge on whichever is currently active.

### How to use it:

Click any killzone to expand it.

`[IMAGE: Single expanded killzone card showing Definition, ✓ DO, ✗ DON'T sections]`

Each zone shows:
- **Definition** — what's structurally happening in this session
- **✓ DO** — green checklist of recommended actions
- **✗ DON'T** — red checklist of what to avoid

### The 7 zones (PHT):

| Window | PHT Time | Priority |
|---|---|---|
| Sydney/Tokyo | 5:00 AM – 1:00 PM | Low |
| Pre-London Lull | 1:00 – 3:00 PM | Low |
| **London Killzone** | 3:00 – 6:00 PM | **High** |
| London Lunch | 6:00 – 8:30 PM | Low |
| **NY Killzone** | 8:30 – 11:00 PM | **PRIME** |
| **NY/London Overlap** | 11:00 PM – 12:00 AM | **PRIME** |
| NY PM | 12:00 – 4:00 AM | Mid |

### Tip:
Set phone alarms for **3:00 PM** (London open) and **8:30 PM** (NY open). These are your sniper windows.

---

<a id="active-zones"></a>
## 8. Active Zones

`[IMAGE: Active Zones tab with Add Zone form open and 2-3 saved zones below]`

Your sniper watchlist — pre-marked zones you're waiting to play.

### How to use it:

**Adding a zone:**

1. Click **+ Add Zone**

`[IMAGE: Add Zone form expanded with all fields visible]`

2. Fill in:
   - **Pair** + **Direction** (Long/Short)
   - **Type** (OTE + FVG, OTE + OB, FRVP Breakout-Retest, ORB, AMD, etc.)
   - **Entry** + **SL** (required)
   - **TP1, TP2, TP3** (TP1 required, TP2/TP3 optional)
   - **Notes** — why this zone matters
3. Click **Save Zone**

**Filtering zones:**

`[IMAGE: Filter pill row showing All, Active, Triggered, Hit TP, Stopped Out, Expired]`

Use the filter pills to view zones by status.

**Updating zone status:**

`[IMAGE: Single zone card with status update buttons highlighted]`

As price reaches your zones, click the buttons to update:
- **→ Triggered** — price hit your entry
- **→ Hit TP** — TP1 was reached
- **→ Stopped Out** — SL hit
- **→ Expired** — zone is no longer valid

### Tip:
Zones auto-calculate R-multiples for each TP based on your entry and SL. Anything below 1:2 R should be deleted, not traded.

---

<a id="entry-score"></a>
## 9. Entry Score

`[IMAGE: Entry Score tab with 12 confluence rows, several checked, summary card at bottom]`

A 12-point confluence checklist that gates you into A+ / A / B / NO TRADE verdicts.

### How to use it:

1. Read each confluence row.
2. **Tick** every box that is genuinely true for the setup in front of you.
3. Watch the **Score / Grade / Verdict** card update at the bottom.

`[IMAGE: Score summary card showing 11/12, Grade A+, Verdict TRADE — full size]`

### Grade thresholds:

| Score | Grade | Verdict |
|---|---|---|
| 11-12 | **A+** | TRADE — full size |
| 9-10 | **A** | TRADE — full size |
| 7-8 | **B** | SKIP or half size |
| 0-6 | **C** | NO TRADE |

### Reset All button:

`[IMAGE: Reset All button at top-right of Entry Score tab]`

After taking the trade, click **Reset All** to clear the checklist for the next setup.

### Tip:
Be brutally honest with yourself. If a confluence isn't *genuinely* there, don't tick it. The score is only useful if it reflects reality.

---

<a id="risk--rr"></a>
## 10. Risk & R:R

`[IMAGE: Risk & R:R tab with Position Calculator on top and R:R Calculator below]`

Two calculators in one tab. Position size + R:R.

### Section 1: Position Size Calculator

`[IMAGE: Position Calculator with Account, Risk %, Pair, SL Distance fields filled]`

**How to use it:**
1. **Account ($)** — your trading capital
2. **Risk %** — your per-trade risk (default 1%, never higher)
3. **Pair** — pick from dropdown
4. **SL Distance** — in pips (or dollars for XAU/USD)

The 3 result tiles show:
- **Risk $** — dollar amount at risk on this trade
- **Position** — exact lot size + mini/micro equivalents
- **Per-Unit** — pip value used for the calculation

### Section 2: R:R Calculator

`[IMAGE: R:R Calculator with Entry, SL, TP1, TP2, TP3 fields and weighted R result]`

**How to use it:**
1. **Entry** — your planned entry price
2. **SL** — your stop loss price
3. **TP1, TP2, TP3** — your profit targets

Results show:
- **SL Distance** — calculated absolute distance
- **Weighted R (50/30/20)** — assumes you scale out 50% at TP1, 30% at TP2, 20% at TP3
- **Individual R-multiples** for each TP

### Reset buttons:

`[IMAGE: Reset buttons highlighted on both calculators]`

Each calculator has a **Reset** button to clear all fields. Each input also has an **× clear** button.

### Tip:
If your weighted R is below 2.0, the trade isn't worth taking. Walk away.

---

<a id="news"></a>
## 11. News

`[IMAGE: News tab with Iron Rule banner, calendar links, fundamental bias engine]`

Track today's economic events and let the engine compute your fundamental bias.

### How to use it:

**Step 1 — Open a live calendar:**

`[IMAGE: Live calendar links section with 4 cards (ForexFactory, Investing.com, FXStreet, MyFXBook)]`

Click any of the 4 calendar cards to open the source in a new tab. Identify the day's red and orange folder events.

**Step 2 — Log each major event:**

`[IMAGE: Add Event form expanded showing Folder, Currency, Direction, Event, Theme, Notes fields]`

1. Click **+ Add Event**
2. Fill in:
   - **Folder** — Red, Orange, or Yellow (volatility level)
   - **Currency** — USD, GBP, AUD, EUR, JPY, XAU
   - **Direction** — Bullish, Bearish, or Neutral (your read of the data)
   - **Event** — name (e.g. "NFP", "CPI", "BoE")
   - **Theme** — Normal, Risk-Off, Risk-On
3. Click **Save Event**

**Step 3 — Read the per-pair fundamental bias:**

`[IMAGE: 5 per-pair fundamental bias cells showing STRONG LONG / LEAN SHORT / NEUTRAL etc.]`

The engine weights events (Red=3, Orange=1.5, Yellow=0.5) × direction (+1, -1, 0) and produces a per-pair verdict:
- **STRONG LONG / LEAN LONG** (green)
- **STRONG SHORT / LEAN SHORT** (red)
- **NEUTRAL** (gray)

This feeds directly into the Dashboard's composite verdict.

### Iron Rule banner:

`[IMAGE: Red Iron Rule banner at top]`

**No trades 30 minutes before/after red-folder news.** This is non-negotiable.

### Tip:
Log events the night before or the morning of. Don't wait until the news is releasing.

---

<a id="journal"></a>
## 12. Journal

`[IMAGE: Journal tab with Log Trade form open and 2-3 saved trades below]`

Log every trade — both winners and losers. This is where your edge is built.

### How to use it:

**Logging a trade:**

1. Click **+ Log Trade**

`[IMAGE: Log Trade form expanded with all 16 fields visible]`

2. Fill in (all fields recommended):
   - **Pair** + **Direction** + **Session** + **Setup**
   - **Daily / 4H / 1H Bias** — what your bias was at entry
   - **Entry / SL / TP / Exit** — actual prices
   - **Confluences (0-12)** — your Entry Score grade
   - **Result** — Win / Loss / BE
   - **R Multiple** — e.g. `+2.5` or `-1`
   - **Emotion** — Calm, Confident, Hesitant, FOMO, Frustrated, Tilted
   - **Notes / Lesson** — one lesson from this trade
3. Click **Save Trade**

**Reviewing trades:**

`[IMAGE: List of saved trades showing pair, direction, setup, result, R, emotion]`

Each trade card shows everything at a glance. Click the trash icon to delete.

### Export / Import:

`[IMAGE: CSV / Import buttons highlighted at top]`

- **Export CSV** — download all trades as CSV (Excel/Google Sheets compatible)
- **Import** — upload a previously exported CSV to restore

### Tip:
Log the trade *the moment you exit*. Don't wait until end of day — your emotional state and reasoning fade fast.

---

<a id="stats"></a>
## 13. Stats

`[IMAGE: Stats tab with KPI tiles, equity curve, pie chart, edge math, by-pair, by-session]`

Performance dashboard built from your journaled trades.

### What you see:

**Top KPI tiles** — Total trades, Win Rate, Total R, Expectancy

`[IMAGE: 4 KPI tiles at top]`

**Equity Curve** — cumulative R over time

`[IMAGE: SVG equity curve chart showing line + area fill]`

**Win/Loss pie + Edge Math**

`[IMAGE: Pie chart showing W/L/BE distribution beside Edge Math card]`

Edge Math shows:
- Avg Win (positive R)
- Avg Loss (negative R)
- Profit Factor (anything ≥ 1.5 is healthy)

**By Pair** — performance per pair

`[IMAGE: By-Pair grid showing each traded pair with R captured and WR%]`

**By Session — R captured** — bar chart showing which sessions are profitable for you

`[IMAGE: SVG bar chart with sessions on x-axis and R captured on y-axis]`

### Tip:
After 30+ trades, look at "By Session" carefully. If one session is consistently negative, **stop trading it** until you can rebuild the edge.

---

<a id="cheat-sheet"></a>
## 14. Cheat Sheet

`[IMAGE: Cheat Sheet tab in white printable view, showing all 10 sections]`

Auto-summary daily plan. Pulls live data from Bias Board, News, Active Zones, Pivots, Calc, and Score into one printable page.

### How to use it:

1. Open this tab **after** completing your prep (Bias, News, Pivots, Active Zones).
2. The page auto-populates with everything you've entered.
3. **Edit** the two free-text fields:
   - **Today's Plan / Notes** — write your specific plan for the day
   - **End-of-Day Reflection** — write at session close
4. Both auto-save per day.

`[IMAGE: Editable plan textarea with example plan written in it]`

### Print or save as PDF:

`[IMAGE: Print / PDF button highlighted at top-right]`

Click **Print / PDF** at the top. Your browser's print dialog opens — choose:
- **Print** to physical paper
- **Save as PDF** to file

The page is print-styled (white background, black text, no UI chrome).

### What's auto-summarized:

1. **Bias Grid** — Daily/4H/1H/Tier/Composite for all 5 pairs
2. **Fundamental Events** — every event you logged
3. **Active Sniper Zones** — every zone with Active status
4. **Pivot Levels** — your latest pivot calculation
5. **Position Size summary** — current calc settings
6. **Entry Score** — today's score / grade / verdict
7. **Plan / Notes** (editable)
8. **Killzones reference**
9. **Non-Negotiables** — the 10 edge rules
10. **End-of-Day Reflection** (editable)

### Tip:
Print this every morning. Tape it next to your monitor. Glance at it when temptation hits.

---

<a id="settings--backup"></a>
## 15. Settings & Backup

`[IMAGE: Settings tab showing Profile, Appearance, Security, Backup, Danger Zone sections]`

### Profile

`[IMAGE: Profile section with Trader Name and Email fields]`

Edit your trader name (shown on dashboard greeting) and email (used for password recovery).

### Appearance

Toggle between **Dark** and **Light** themes.

### Security

`[IMAGE: Security section with Lock Now and Reset Password buttons]`

- **Lock Now** — re-locks the app immediately
- **Reset Password** — removes the current password (data preserved); you'll be asked to set a new one

### Backup & Restore

`[IMAGE: Backup section with Export Full Backup and Import Backup buttons]`

- **Export Full Backup** — downloads a JSON file with everything (trades, zones, bias, fundamentals, cheat sheet, settings, score, pivot, calc)
- **Import Backup** — upload a previously exported JSON to restore

**⚠️ Why this matters:** Sniper Desk stores all data in your browser's localStorage. If you clear your browser cache, switch browsers, or change devices, **your data is gone unless you've exported a backup.**

**Recommended schedule:** Export a full backup every Sunday. Save it to Google Drive or Dropbox.

### CSV Export/Import (Trades only)

For round-tripping trade data with Excel or Google Sheets.

### Danger Zone

`[IMAGE: Red Danger Zone card with three Clear buttons]`

- **Clear All Trades** — deletes journal only
- **Clear All Zones** — deletes Active Zones only
- **Clear Everything** — wipes all trading data (profile preserved)

All three require modal confirmation. None can be undone.

---

<a id="recommended-daily-workflow"></a>
## 16. Recommended Daily Workflow

`[IMAGE: Optional: timeline graphic showing the workflow across PHT hours]`

### Morning (anytime before 3:00 PM PHT):

1. **Dashboard** — glance at the featured pair verdict to set tone
2. **News** — open ForexFactory, log every red and orange event
3. **Bias Board** — mark Daily / 4H / 1H for all 5 pairs
4. **Pivots** — calculate yesterday's H/L/C for your top pair(s)
5. **Active Zones** — pre-mark any 1H POIs inside aligned 4H zones
6. **Cheat Sheet** — review auto-summary, write your plan, print/save PDF

### London Killzone (3:00 – 6:00 PM):

7. Watch your A+ pairs only
8. Wait for sweep + CHoCH
9. **Entry Score** — score the setup; only A+ or A qualifies
10. **Risk & R:R** — calculate position size and confirm R:R ≥ 2
11. Execute with discipline — SL is sacred

### NY Killzone (8:30 – 11:00 PM):

12. Repeat the process for NY-aligned setups
13. Stop after 2 trades or 2 losses, whichever comes first

### After session close:

14. **Journal** — log every trade with notes and emotion
15. **Cheat Sheet** — fill in End-of-Day Reflection
16. **Stats** — review weekly trends if it's been 5+ trading days

### Weekly:

17. **Settings → Export Full Backup** — every Sunday, save to cloud

---

## 🎯 Final Notes

- **Discipline > prediction.** This tool exists to enforce a process, not to predict the market.
- **Every tab feeds another.** Bias → Score → Calc → Journal. Use them as a chain.
- **The cheat sheet is your daily contract.** Sign it, follow it, review it.
- **Trade your plan, not your P&L.**

---

*Sniper Desk v2.1 — Built for Filipino retail traders working PHT hours.*
*Educational tool. Not financial advice.*
