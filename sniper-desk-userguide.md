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

<img width="1862" height="884" alt="image" src="https://github.com/user-attachments/assets/43402113-e146-4652-8fc6-0dda19d27901" />

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

<img width="1866" height="881" alt="image" src="https://github.com/user-attachments/assets/4ad7072b-6b48-44b5-986c-0112b140cd36" />

The Dashboard is your situational awareness panel. Every time you open Sniper Desk, this is where you start.

### What you see, top to bottom:

**Greeting + Session card**
<img width="1574" height="384" alt="image" src="https://github.com/user-attachments/assets/8e8e3008-94e1-42db-88eb-7dfcd2434a3b" />

Time-of-day greeting + your trader name + the live PHT session (Sydney/Tokyo, London KZ, NY KZ, etc.) with a contextual message ("Sniper window. London-NY overlap. All pairs active.").

**Quick action buttons**
- **Mark Bias** → Bias Board
- **Log News** → News tab
- **Score Setup** → Entry Score

**Tech vs Fund — Featured Pair**
<img width="1603" height="586" alt="image" src="https://github.com/user-attachments/assets/833204bd-48d2-48a7-9912-23b9c871e55c" />

The most important card on the page. Pick a pair from the dropdown. The card shows:
- **Tech direction** (from your Bias Board)
- **Fund direction** (from your News tab)
- **Composite verdict** — A+ LONG, A SHORT, CONFLICT, NEED TECH, etc.
- **Detail message** — what this means and what to do

Below it, a 5-pair strip shows every pair's verdict at a glance. Click any pair to feature it.

**KPI Tiles**
<img width="1594" height="797" alt="image" src="https://github.com/user-attachments/assets/3192a672-5ee9-45a8-9010-3a00ef0bbc21" />

Account balance, last 7 days of trades, win rate, R captured.

**Daily routine + No-trade conditions**
Two reference cards at the bottom — your pre-trade checklist and your stop signs.

### How to use it:
- **Open Sniper Desk → glance at the featured pair verdict.** If it says A+ or A, you have a high-probability day. If it says CONFLICT or NO DATA, you have prep work to do.
- The session badge top-right tells you whether you're in a tradeable window.

---

<a id="bias-board"></a>
## 3. Bias Board

<img width="1081" height="880" alt="image" src="https://github.com/user-attachments/assets/5198839b-dcf5-4a6c-b294-f26f865f7684" />

Where you mark your multi-timeframe bias for each of the 5 pairs. Saved per day (resets at midnight Manila time).

### How to use it:

For each pair card:

1. **Daily** — Click Bull, Bear, or Neutral based on the macro trend.
2. **4H** — Click Bull, Bear, or Neutral based on 4H structure (last BOS direction).
3. **1H** — Click Bull, Bear, or Neutral based on 1H refinement.

<img width="1075" height="881" alt="image" src="https://github.com/user-attachments/assets/084920a1-6824-4960-a492-4836dbe5e7d7" />

The card automatically calculates a **Tier**:

| Tier | Meaning | Action |
|---|---|---|
| **A+** (green) | All 3 TFs aligned (all Bull or all Bear) | Hunt setups in that direction |
| **B** (amber) | 2 of 3 aligned, 1 Neutral | Wait for misaligned TF to flip |
| **C** (gray) | Conflicting timeframes | NO TRADE |

### Reset button:

<img width="1085" height="882" alt="image" src="https://github.com/user-attachments/assets/fe2da639-9508-4e99-ac2b-cf6e7b61d9b9" />

Each pair has a **Reset** button to clear all 3 timeframes at once.

### Tip:
Mark all 5 pairs before London opens (3:00 PM PHT). This sets your menu for the day — only A+ pairs deserve sniper attention.

---

<a id="playbook"></a>
## 4. Playbook

<img width="1093" height="882" alt="image" src="https://github.com/user-attachments/assets/be459925-331b-4a60-b789-b7f5daacfd7e" />

Reference library of your 6 ICT/SMC setups, each as an expandable card.

### How to use it:

Click any setup to expand it.
<img width="1075" height="874" alt="image" src="https://github.com/user-attachments/assets/6ecf3595-bbe4-4c85-b223-d07a4fdeb09b" />

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

<img width="1064" height="519" alt="image" src="https://github.com/user-attachments/assets/fe9bed84-2cd3-40d1-90ef-d7ed02e964ed" />

A reference card explaining how to spot the 3-phase smart-money cycle on the chart:
- **Accumulation (A)** — tight Asian range
- **Manipulation (M)** — false break / liquidity sweep
- **Distribution (D)** — true move with HTF bias

### Tip:
Read through the Playbook once a week. The setups don't change — but your discipline does.

---

<a id="ict-fibs"></a>
## 5. ICT Fibs

<img width="1605" height="843" alt="image" src="https://github.com/user-attachments/assets/8de9cfd5-1e3c-4cff-960c-003f1ea0a18c" />

Reference for ICT-specific Fibonacci levels with definitions for every coefficient.

### How to use it:

**Click "Retracement Levels — definitions"** to expand the retracement coefficients:

<img width="1074" height="794" alt="image" src="https://github.com/user-attachments/assets/62bb503a-e20c-45eb-9749-27989e9c99a4" />


| Level | Name | Meaning |
|---|---|---|
| 0 | Swing Origin | Anchor — where the impulse started |
| 0.5 | Equilibrium | Above = Premium, below = Discount |
| 0.618 | OTE Start (Golden) | Smart-money entry zone begins |
| **0.705** | **OTE Sweet Spot** | **Highest-probability turning point** |
| 0.79 | OTE Deep | Deepest sniper entry before invalidation |
| 1.0 | INVALIDATION | If broken, your trade idea is wrong |

**Click "Extension Coefficients — definitions"** to expand the extensions:

<img width="1106" height="674" alt="image" src="https://github.com/user-attachments/assets/52dab280-4c36-4ef6-be1b-f6833a472460" />

These are your TP projections.

### TradingView setup:

<img width="1601" height="313" alt="image" src="https://github.com/user-attachments/assets/51625cde-0c9d-4777-bc94-a80e70dac4ec" />

Two pre-formatted strings ready to paste into TradingView's Fib tool settings:
- Retracement: `0, 0.236, 0.382, 0.5, 0.618, 0.705, 0.79, 1`
- Extension: `0, 0.5, 1, 1.5, 2, 2.5, 3, 4`

### Tip:
The 0.705 ICT sweet spot is the single most useful number on this tab. Many ICT traders only enter inside the 0.618-0.79 OTE band.

---

<a id="pivots"></a>
## 6. Pivots

<img width="1208" height="881" alt="image" src="https://github.com/user-attachments/assets/ef6e6ddb-a758-47a6-9572-4367606dde94" />

Calculates daily pivot levels using yesterday's H/L/C (and optional Open).

### How to use it:

**Step 1 — Configure:**
1. Pick your **Pair** from the dropdown
2. Pick your **Method**:
   - **Standard** — classic floor pivots, most widely watched
   - **Fibonacci** — uses fib retracement (38.2%, 61.8%, 100%)
   - **Camarilla** — tight intraday levels, R3/S3 are key reversal zones
   - **Woodie** — weights close more heavily

<img width="1210" height="882" alt="image" src="https://github.com/user-attachments/assets/2c9fed11-c56e-4e98-a0c9-9f5ac669be99" />

**Step 2 — Enter values:**
3. **Open** (optional) — today's opening price
4. **High** — yesterday's high
5. **Low** — yesterday's low
6. **Close** — yesterday's close

<img width="1206" height="767" alt="image" src="https://github.com/user-attachments/assets/ff6babf3-e063-4942-8443-9d7a9a8ac1cd" />

**Step 3 — Read the ladder:**

<img width="1202" height="480" alt="image" src="https://github.com/user-attachments/assets/210fc49f-4925-4ab2-9b67-652c3e869366" />

The ladder shows resistance levels (green) above PP (orange) and support levels (red) below.

**Step 4 — Click any level to auto-copy:**

<img width="1272" height="885" alt="image" src="https://github.com/user-attachments/assets/fb931512-ddb4-44f1-8789-8702de0a2d6b" />

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

<img width="816" height="741" alt="image" src="https://github.com/user-attachments/assets/d19344ef-af93-4ff6-90d4-780524b8a670" />

The 7 trading sessions of the day in Manila time, with a live "LIVE" badge on whichever is currently active.

### How to use it:

Click any killzone to expand it.

<img width="1861" height="886" alt="image" src="https://github.com/user-attachments/assets/3c772bae-1301-4901-b38f-4c0df0623550" />

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

<img width="1477" height="750" alt="image" src="https://github.com/user-attachments/assets/12fe3332-f80f-43ee-9853-b095467439b3" />

Your sniper watchlist — pre-marked zones you're waiting to play.

### How to use it:

**Adding a zone:**

1. Click **+ Add Zone**

<img width="1451" height="659" alt="image" src="https://github.com/user-attachments/assets/2c5c746f-d1ce-4790-a102-e5a8c9fb3c3b" />

2. Fill in:
   - **Pair** + **Direction** (Long/Short)
   - **Type** (OTE + FVG, OTE + OB, FRVP Breakout-Retest, ORB, AMD, etc.)
   - **Entry** + **SL** (required)
   - **TP1, TP2, TP3** (TP1 required, TP2/TP3 optional)
   - **Notes** — why this zone matters
3. Click **Save Zone**

**Filtering zones:**

<img width="1421" height="734" alt="image" src="https://github.com/user-attachments/assets/8e993742-752b-4e0f-a876-9ef581dd5cc0" />

Use the filter pills to view zones by status.

**Updating zone status:**

<img width="1437" height="750" alt="image" src="https://github.com/user-attachments/assets/9c4c1a23-7b3d-49e5-905b-ff0793ce9894" />

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

<img width="1087" height="882" alt="image" src="https://github.com/user-attachments/assets/eb28d809-0755-4318-bcfe-65fa752f2371" />

A 12-point confluence checklist that gates you into A+ / A / B / NO TRADE verdicts.

### How to use it:

1. Read each confluence row.
2. **Tick** every box that is genuinely true for the setup in front of you.
3. Watch the **Score / Grade / Verdict** card update at the bottom.

<img width="1105" height="885" alt="image" src="https://github.com/user-attachments/assets/9c801942-f2bc-4253-a27d-170534a7859b" />

### Grade thresholds:

| Score | Grade | Verdict |
|---|---|---|
| 11-12 | **A+** | TRADE — full size |
| 9-10 | **A** | TRADE — full size |
| 7-8 | **B** | SKIP or half size |
| 0-6 | **C** | NO TRADE |

### Reset All button:

<img width="1088" height="883" alt="image" src="https://github.com/user-attachments/assets/c00e1d28-95b8-4612-a34e-97f2a317e6ce" />
<img width="1095" height="882" alt="image" src="https://github.com/user-attachments/assets/2c39c66b-9986-457a-ba00-9f5bfc7a70ce" />

After taking the trade, click **Reset All** to clear the checklist for the next setup.

### Tip:
Be brutally honest with yourself. If a confluence isn't *genuinely* there, don't tick it. The score is only useful if it reflects reality.

---

<a id="risk--rr"></a>
## 10. Risk & R:R

<img width="1074" height="851" alt="image" src="https://github.com/user-attachments/assets/b3a8e3a5-9cb8-45f9-af48-66ff72ce1f20" />

Two calculators in one tab. Position size + R:R.

### Section 1: Position Size Calculator

<img width="1096" height="432" alt="image" src="https://github.com/user-attachments/assets/5348495a-0b80-4ae0-a619-b444c3462569" />

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

<img width="1616" height="598" alt="image" src="https://github.com/user-attachments/assets/9b5d1a27-9a2d-4b22-9951-b8425a138881" />

**How to use it:**
1. **Entry** — your planned entry price
2. **SL** — your stop loss price
3. **TP1, TP2, TP3** — your profit targets

Results show:
- **SL Distance** — calculated absolute distance
- **Weighted R (50/30/20)** — assumes you scale out 50% at TP1, 30% at TP2, 20% at TP3
- **Individual R-multiples** for each TP

### Reset buttons:

<img width="1306" height="879" alt="image" src="https://github.com/user-attachments/assets/afbe04b1-3cac-4076-8d10-d4fc8374547d" />

Each calculator has a **Reset** button to clear all fields. Each input also has an **× clear** button.

### Tip:
If your weighted R is below 2.0, the trade isn't worth taking. Walk away.

---

<a id="news"></a>
## 11. News

<img width="1319" height="880" alt="image" src="https://github.com/user-attachments/assets/47bb6775-91c8-4142-8627-cf099ccdbcf6" />

Track today's economic events and let the engine compute your fundamental bias.

### How to use it:

**Step 1 — Open a live calendar:**

<img width="1287" height="229" alt="image" src="https://github.com/user-attachments/assets/319825c5-4d5a-49e8-b5fd-35725a9ecca7" />

Click any of the 4 calendar cards to open the source in a new tab. Identify the day's red and orange folder events.

**Step 2 — Log each major event:**

<img width="1280" height="223" alt="image" src="https://github.com/user-attachments/assets/216c536b-df02-49c0-b2b4-b81476e59f14" />

1. Click **+ Add Event**
2. Fill in:
   - **Folder** — Red, Orange, or Yellow (volatility level)
   - **Currency** — USD, GBP, AUD, EUR, JPY, XAU
   - **Direction** — Bullish, Bearish, or Neutral (your read of the data)
   - **Event** — name (e.g. "NFP", "CPI", "BoE")
   - **Theme** — Normal, Risk-Off, Risk-On
3. Click **Save Event**

**Step 3 — Read the per-pair fundamental bias:**

<img width="1286" height="388" alt="image" src="https://github.com/user-attachments/assets/15edc297-9745-41e6-8e64-78ff10bce93c" />

The engine weights events (Red=3, Orange=1.5, Yellow=0.5) × direction (+1, -1, 0) and produces a per-pair verdict:
- **STRONG LONG / LEAN LONG** (green)
- **STRONG SHORT / LEAN SHORT** (red)
- **NEUTRAL** (gray)

This feeds directly into the Dashboard's composite verdict.

### Iron Rule banner:

<img width="1266" height="101" alt="image" src="https://github.com/user-attachments/assets/f1e190aa-dfbd-4824-be35-dd8449128f80" />

**No trades 30 minutes before/after red-folder news.** This is non-negotiable.

### Tip:
Log events the night before or the morning of. Don't wait until the news is releasing.

---

<a id="journal"></a>
## 12. Journal

<img width="1293" height="873" alt="image" src="https://github.com/user-attachments/assets/9b3d97a6-daac-44a5-b7ee-bd06e7a99211" />

Log every trade — both winners and losers. This is where your edge is built.

### How to use it:

**Logging a trade:**

1. Click **+ Log Trade**

<img width="1281" height="442" alt="image" src="https://github.com/user-attachments/assets/4a29bae8-65a3-46af-9ded-7edfeb0de9b4" />

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

<img width="1285" height="593" alt="image" src="https://github.com/user-attachments/assets/00f80dcf-3286-4bc7-91d4-3ac2cbfba68f" />

Each trade card shows everything at a glance. Click the trash icon to delete.

### Export / Import:

<img width="1285" height="583" alt="image" src="https://github.com/user-attachments/assets/c0f830c0-0af6-4c62-87f4-13d8ea72df08" />

- **Export CSV** — download all trades as CSV (Excel/Google Sheets compatible)
- **Import** — upload a previously exported CSV to restore

### Tip:
Log the trade *the moment you exit*. Don't wait until end of day — your emotional state and reasoning fade fast.

---

<a id="stats"></a>
## 13. Stats

<img width="587" height="877" alt="image" src="https://github.com/user-attachments/assets/898c6f6f-3d5b-481b-88d4-648cae7335f9" />

Performance dashboard built from your journaled trades.

### What you see:

**Top KPI tiles** — Total trades, Win Rate, Total R, Expectancy

<img width="1619" height="691" alt="image" src="https://github.com/user-attachments/assets/14c7c17d-e5e7-4f09-af19-57fb3e50f4c0" />

**Equity Curve** — cumulative R over time

<img width="1607" height="632" alt="image" src="https://github.com/user-attachments/assets/fa98433e-ac49-436e-bf4b-c1fec3d1f716" />

**Win/Loss pie + Edge Math**

<img width="1587" height="589" alt="image" src="https://github.com/user-attachments/assets/6f910b92-0787-4811-a02e-9d8128f8f1a8" />

Edge Math shows:
- Avg Win (positive R)
- Avg Loss (negative R)
- Profit Factor (anything ≥ 1.5 is healthy)

**By Pair** — performance per pair

<img width="1579" height="558" alt="image" src="https://github.com/user-attachments/assets/4ee9e10a-432e-478c-937f-1e295d2f9436" />

**By Session — R captured** — bar chart showing which sessions are profitable for you

<img width="1586" height="856" alt="image" src="https://github.com/user-attachments/assets/e4305638-5900-43ba-a89c-497246af2ce2" />

### Tip:
After 30+ trades, look at "By Session" carefully. If one session is consistently negative, **stop trading it** until you can rebuild the edge.

---

<a id="cheat-sheet"></a>
## 14. Cheat Sheet

<img width="825" height="883" alt="image" src="https://github.com/user-attachments/assets/a1d7edeb-b6a6-4077-ae16-b8917f9a1230" />

Auto-summary daily plan. Pulls live data from Bias Board, News, Active Zones, Pivots, Calc, and Score into one printable page.

### How to use it:

1. Open this tab **after** completing your prep (Bias, News, Pivots, Active Zones).
2. The page auto-populates with everything you've entered.
3. **Edit** the two free-text fields:
   - **Today's Plan / Notes** — write your specific plan for the day
   - **End-of-Day Reflection** — write at session close
4. Both auto-save per day.

<img width="1278" height="887" alt="image" src="https://github.com/user-attachments/assets/3c51a5dd-7f68-4d6f-b12a-4f304da55b59" />
<img width="1287" height="886" alt="image" src="https://github.com/user-attachments/assets/95a46a34-8dee-4d9e-892c-27ee7d3c2c28" />

### Print or save as PDF:

<img width="1311" height="886" alt="image" src="https://github.com/user-attachments/assets/298c793b-66b0-40fe-b75d-8718793a7edf" />

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

<img width="1324" height="635" alt="image" src="https://github.com/user-attachments/assets/2a630055-4c2c-4275-b91b-e5dd5c01d961" />

### Profile

<img width="1274" height="666" alt="image" src="https://github.com/user-attachments/assets/70b4081c-3186-41db-9026-c96a11823cf6" />

Edit your trader name (shown on dashboard greeting) and email (used for password recovery).

### Appearance

Toggle between **Dark** and **Light** themes.

### Security

<img width="1618" height="172" alt="image" src="https://github.com/user-attachments/assets/0f8f3990-61ee-4a78-a6ad-dd381ebc5ae0" />

- **Lock Now** — re-locks the app immediately
- **Reset Password** — removes the current password (data preserved); you'll be asked to set a new one

### Backup & Restore

<img width="1617" height="203" alt="image" src="https://github.com/user-attachments/assets/cb180fe4-c130-4539-937f-10b61e0b7334" />

- **Export Full Backup** — downloads a JSON file with everything (trades, zones, bias, fundamentals, cheat sheet, settings, score, pivot, calc)
- **Import Backup** — upload a previously exported JSON to restore

**⚠️ Why this matters:** Sniper Desk stores all data in your browser's localStorage. If you clear your browser cache, switch browsers, or change devices, **your data is gone unless you've exported a backup.**

**Recommended schedule:** Export a full backup every Sunday. Save it to Google Drive or Dropbox.

### CSV Export/Import (Trades only)

For round-tripping trade data with Excel or Google Sheets.

### Danger Zone

<img width="1601" height="188" alt="image" src="https://github.com/user-attachments/assets/c2cd94b9-f953-48bf-93ad-5cae68b2efc9" />

- **Clear All Trades** — deletes journal only
- **Clear All Zones** — deletes Active Zones only
- **Clear Everything** — wipes all trading data (profile preserved)

All three require modal confirmation. None can be undone.

---

<a id="recommended-daily-workflow"></a>
## 16. Recommended Daily Workflow

---

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
