# Evens

Split shared expenses, settle up with the fewest payments, and track poker nights.

Evens is a single HTML file with no build step and no dependencies apart from Google Fonts.

## Expenses

- Groups with their own currency and members
- Five ways to split: equally, exact amounts, percentages, shares, or itemized (per-item assignment with tax and tip shared proportionally)
- Bills paid by several people
- Balances netted across the group, then simplified to the fewest transfers
- Recording settlements, with undo after deleting
- Insights: monthly spend, spend by category, paid vs. share per member
- Search, category filter, CSV export

## Poker

- Live session table: seat players, one-tap rebuys, custom buy-ins, cash-outs
- Bank check that flags when cash-outs don't match buy-ins
- Who-pays-whom settlement for each night, plus a copyable summary
- Leaderboard: net, per session, ROI, win rate, hourly, best/worst, streak
- Cumulative winnings chart

## Running it

Open `evens.html` in a browser. When it runs as a claude.ai Artifact, data syncs between everyone it's shared with. Anywhere else, data is saved in that browser's local storage.

Click **Load sample data** on the empty overview to see it filled in. **Remove sample data** clears it again.
