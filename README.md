# 💳 CCBGone — Credit Card Balance, Gone

A powerful, private credit card tracker that lives entirely on **your** computer.
Built to answer one question at a glance: **"What do I need to pay next?"** —
and then to show you the whole road out of debt.

Designed with ADHD in mind: one clear "next action" banner, color-coded urgency,
big obvious buttons, a one-click "Mark it paid", reminders that come to *you*
(via your calendar), and little wins that keep you going (streaks, confetti,
a shrinking chart).

## How to use it

1. Download `index.html` from this repository (or clone the repo).
2. Save it anywhere on your computer — Desktop, Documents, wherever.
3. Double-click it. It opens in your web browser. That's the whole app.
4. Click **+ Add card** and enter each card once: nickname, last 4 digits
   (optional), credit limit, current balance, APR, payment due day, and minimum
   payment. Under **More options** you can also record a 0% intro APR, an
   annual fee, autopay, and notes.

**Tip:** Bookmark the page or pin the tab so it's always one click away.

> ⚠️ **Never enter your full card number.** The app doesn't need it and will
> reject it if you try. A nickname + last 4 digits is all it takes to track a card.

## The three tabs

### 📋 Dashboard — what do I do *right now?*

- **The focus banner** shows the single next card to pay, how many days you
  have, and a big **✓ Mark it paid** button. Red = due within 3 days, yellow =
  within a week, green = you're fine.
- **If you miss a due date it does not stay quiet.** The card flips to
  **⚠ OVERDUE** and the banner tells you to pay now — paying even a day late
  beats another day of late fees. (Missed payments used to silently roll to
  next month. Never again.)
- **Warning chips** appear before the traps spring: *"0% intro APR ends in 30
  days → 26.99% after"*, *"Annual fee $95 hits this month"*.
- **Autopay cards** are labeled ⚡ and never nag you — they're listed, but the
  banner skips them.
- **Totals**: balance, overall utilization (under 30% helps your credit score,
  and each card tells you exactly how much to pay to get there), minimum
  payments still due, estimated interest cost per month, and your **🔥 on-time
  streak**.
- **The plan follows you here.** Once you've set a budget on the Payoff Plan
  tab, each card shows *"Plan says $X/mo"*, the banner tells you the planned
  amount (not just the minimum), and the payment form comes prefilled with it.
  Zero monthly decision-making.
- **Debt paydown progress bar** — how far you've come from your peak debt,
  with celebrations when you cross 25%, 50%, 75%, and 100% paid off.
- **＋ Charge** lets you log new spending in two taps, so balances (and the
  Trends chart) stay honest between statements.
- **Recent activity** logs every payment, charge, and balance update, and can
  be **exported as CSV** for spreadsheets. Deleting a card offers **Undo** for
  a few seconds, so a slip of the finger costs nothing.
- Pay everything due this week and you get confetti. You earned it.
  (Respects your system's reduced-motion setting.)

### 🎯 Payoff Plan — how do I get out of debt?

Enter one number — what you can put toward all cards monthly — and pick a
strategy:

- **🏔 Avalanche**: highest interest rate first. Mathematically cheapest.
- **☃️ Snowball**: smallest balance first. Fastest wins, best for motivation.

You instantly get your **debt-free date**, **total interest you'll pay**, how
much you **save vs. paying minimums only** (often the answer is "minimums
would *never* pay this off"), the exact **payoff order**, and a chart of your
plan vs. the minimums-only slog. It even tells you what the *other* strategy
would cost, so you can choose with open eyes. The simulation respects 0% intro
APR periods and their end dates.

### 📈 Trends — is it working?

A chart of your total balance over time, built automatically from what you log,
plus: balance now, change over the last 30 days, and how much you paid in the
last 30 days. Watching the line go down is the point.

## 📅 Get reminders without opening the app

Click **Calendar** in the header. It downloads a `ccbgone-due-dates.ics` file —
open it and your phone/computer calendar (Google, Apple, Outlook, anything)
adds:

- a **repeating monthly event** for each card's due date, with alerts 2 days
  before and on the morning it's due,
- a **yearly reminder** before each annual fee hits,
- a **one-time warning** two weeks before a 0% intro APR expires.

Your calendar does the remembering. Re-export whenever you add or change cards.

## Little conveniences

- **🌓 Theme button** — auto (follows your system), light, or dark.
- **👁 Privacy button** — blurs every dollar amount on screen for when someone
  is looking over your shoulder. Hover an amount to peek; tap 👁 again to show.

## The monthly routine (about 2 minutes)

1. Open the app. The banner tells you what's next.
2. Pay that card in your banking app, then click **✓ Mark it paid** here.
3. Repeat until the banner celebrates.
4. Once in a while, hit **Update balance** on each card to match your latest
   statement — that's what feeds the Trends chart.

"Paid" resets automatically each cycle — nothing to manage.

## Where is my data? Is it private?

- Everything is stored in your browser's local storage **on your computer**.
  Nothing is ever sent to a server, an account, or the internet. There is no
  sign-up and no tracking. The entire app is one HTML file with no external
  code — it works in airplane mode.
- Because it's tied to one browser on one computer, use **⬇ Backup** now and
  then. It saves a `ccbgone-backup-YYYY-MM-DD.json` file to your Downloads
  folder. **⬆ Restore** loads it back — which also moves your data to a new
  computer or browser. Old backups from earlier versions restore fine.
- Clearing your browser's site data will erase the tracker's data — another
  good reason to keep a backup file.
