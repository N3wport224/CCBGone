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
4. On first open you get a **Welcome screen** with two choices:
   - **👀 Explore with sample data first** — fills the app with made-up cards
     so you can click every feature safely before entering anything real. One
     tap wipes it when you're ready.
   - **➕ Add my first card** — enter each card once: nickname, last 4 digits
     (optional), credit limit, current balance, APR, payment due day, and
     minimum payment. Not sure where to find those? The form has a **"🔎 Where
     do I find these numbers?"** helper. Under **More options** you can also
     record a 0% intro APR, an annual fee, autopay, and notes.

**Tip:** Bookmark the page or pin the tab so it's always one click away. Works
great on your phone, too — the layout adapts to a single column.

**Stuck?** Tap **❓ Help** in the header anytime for plain-language answers: the
monthly routine, what each tab does, how to get phone reminders, a glossary
(what *is* APR?), and how to fix mistakes. The app also drops in one gentle,
dismissible tip at a time as you go — never a wall of instructions.

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
  be **exported as CSV** for spreadsheets.
- **Everything is undoable.** Log the wrong payment, mistype a balance, fumble a
  card edit, or delete a card by accident — every one of these pops an **Undo**
  in the confirmation message that puts things back exactly as they were. Nothing
  you do in this app is scary or permanent.
- Pay everything due this week and you get confetti. You earned it.
  (Respects your system's reduced-motion setting.)

### 🎯 Payoff Plan — how do I get out of debt?

Enter one number — what you can put toward all cards monthly — and pick a
strategy:

- **🏔 Avalanche**: highest interest rate first. Mathematically cheapest.
- **☃️ Snowball**: smallest balance first. Fastest wins, best for motivation.

**Not sure which to pick? The app decides for you.** At the top of this tab is a
**"Your debt, reviewed"** panel that analyzes *your actual cards* and gives a
plain-language recommendation with the reasoning:

- A snapshot of your situation — total debt, weighted-average interest rate,
  how much interest you bleed each month, and your priciest card.
- A clear verdict ("Avalanche — you save real money without waiting much
  longer", or "Snowball — the early win is worth the small extra cost", or
  "It's a tie — pick whichever you'll stick with"), each backed by *your*
  numbers.
- A side-by-side of both methods: total interest, months to debt-free, and how
  soon you clear your first card under each.
- A one-tap **"Use this method"** button that sets your plan to the winner.

The recommendation is honest, not dogmatic: when Avalanche only saves a few
dollars it says so and hands the win to Snowball's momentum; when a high-rate
card is quietly draining you it says pay that first. It re-decides automatically
as your balances change.

Below that you still get your **debt-free date**, **total interest you'll
pay**, how much you **save vs. paying minimums only** (often the answer is
"minimums would *never* pay this off"), the exact **payoff order**, and a chart
of your plan vs. the minimums-only slog. The simulation respects 0% intro APR
periods and their end dates.

**Have a deadline instead of a budget?** The **🏁 Work backwards from a finish
date** tool flips the question around: pick the month you want to be debt-free
(a wedding, a mortgage application, or just *done*) and it tells you the monthly
payment that gets you there — and whether your current plan already makes it.

### 📈 Trends — is it working?

A chart of your total balance over time, built automatically from what you log,
plus: balance now, change over the last 30 days, and how much you paid and
charged in the last 30 days. Watching the line go down is the point.

### 🔁 Subscriptions — what's quietly billing me?

Feed it your card statements and it finds every charge that keeps coming back:

- **Import statement CSVs** — every bank's website has a CSV/spreadsheet
  download next to the statements. Any bank's format works; the columns are
  figured out automatically, and re-importing the same file is safe
  (duplicates are skipped). Import several months at once for best results.
- **Only have PDFs?** Open the PDF, select the transaction rows, copy, and
  paste them into the paste box. It parses the lines for you.
- It detects **weekly, monthly, quarterly, and yearly rhythms**, labels each
  find *confirmed* (3+ times on a steady beat) or *looks recurring* (twice,
  same amount), and shows what it costs **per month and per year** — the
  yearly number is usually the wake-up call.
- **"Coming up in the next 2 weeks"** lists the charges about to happen, and
  the same list appears on your Dashboard so you're never surprised.
- False positive? Hit **Ignore**. Payments and credits are excluded
  automatically. Everything is parsed on your computer — statements are never
  uploaded anywhere.

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

- **📄 Summary button** — builds a clean one-page summary of everything (cards,
  totals, payoff plan, subscriptions) and opens your print dialog, where you can
  print it or **Save as PDF**. Good for the fridge, or for handing to a partner
  or financial advisor.
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
- If your browser ever blocks saving (private/incognito mode, or storage full),
  the app **won't fail silently** — a red banner appears telling you your changes
  aren't being saved and to export a backup before you close the tab.
