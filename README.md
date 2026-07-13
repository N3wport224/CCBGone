# 💳 CCBGone — Credit Card Balance, Gone

A simple, private credit card tracker that lives entirely on **your** computer.
Built to answer one question at a glance: **"What do I need to pay next?"**

Designed with ADHD in mind: one clear "next action" banner, color-coded urgency,
big obvious buttons, and a one-click "Mark it paid" so nothing slips through.

## How to use it

1. Download `index.html` from this repository (or clone the repo).
2. Save it anywhere on your computer — Desktop, Documents, wherever.
3. Double-click it. It opens in your web browser. That's the whole app.
4. Click **+ Add card** and enter each card once:
   - a nickname (e.g. "Chase Freedom")
   - the last 4 digits (optional, just to tell cards apart)
   - credit limit, current balance, APR (interest rate), payment due day, and minimum payment

**Tip:** Bookmark the page or pin the tab so it's always one click away.

> ⚠️ **Never enter your full card number.** The app doesn't need it and will
> warn you if you try. A nickname + last 4 digits is all it takes to track a card.

## What it shows you

- **The focus banner** — the single next card to pay, how many days you have,
  and a big "Mark it paid" button. Red = due within 3 days, yellow = within a week,
  green = you're fine.
- **Your totals** — total balance, overall credit utilization (keeping it under 30%
  helps your credit score), minimum payments still due this cycle, and an estimate
  of what carrying your balances costs you in interest each month.
- **Each card** — balance, limit, minimum payment, APR, a utilization bar, and its
  next due date. Cards are sorted so the most urgent is always on top.
- **Recent activity** — every payment and balance update you log, so you can look
  back at what you've actually done.

## The monthly routine (about 2 minutes)

1. Open the app. The banner tells you what's next.
2. Pay that card in your banking app, then click **✓ Mark it paid** here.
3. Repeat until the banner says 🎉 All caught up.
4. Once in a while, click **Update balance** on each card to match your latest
   statement (balances change as you spend, not just when you pay).

"Paid" automatically resets each month for the next cycle — nothing to manage.

## Where is my data? Is it private?

- Everything is stored in your browser's local storage **on your computer**.
  Nothing is ever sent to a server, an account, or the internet. There is no
  sign-up and no tracking.
- Because it's tied to one browser on one computer, use **⬇ Backup** now and then.
  It saves a `ccbgone-backup-YYYY-MM-DD.json` file to your Downloads folder —
  keep it wherever you keep important files. **⬆ Restore** loads it back, which
  also lets you move your data to a new computer or browser.
- Clearing your browser's site data/cookies will erase the tracker's data —
  another good reason to keep a backup file.

## No installation, no dependencies

The entire app is one HTML file with no external code, fonts, or connections.
You can open it in airplane mode and it works exactly the same.
