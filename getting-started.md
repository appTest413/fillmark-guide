# Getting started

[← User guide](README.md)

Steps 1–4 are the minimum; the rest when you're ready. You don't need a
Tastytrade account: every broker works through file imports.

## 1. Install on the PC

Run `Fillmark_x.y.z_x64-setup.exe`. It installs for your user only (no
administrator rights) and opens Fillmark.

- Updating: quit Fillmark from its tray icon first (closing the window only
  hides it), then run the new installer. Your journal, settings, logins and
  sync stay as they are.
- The first 30 days everything works; see [License](license.md).

## 2. Choose where prices come from

**More → [Connections](connections.md)**, one of:

- **Tastytrade account**: real-time quotes, option chains, Build a trade
  and the company card.
- **No Tastytrade**: Alpaca, a free sign-up with no brokerage account, gives
  real-time stock quotes and charts, without option chains.
- **Neither**: charts show made-up prices labeled "Sample"; the journal,
  imports, Stats and Study still work.

## 3. Bring in your trades

- **Tastytrade**: **Journal → Fills → Check against Tastytrade** brings in
  your fills when you click it, no file needed.
- **Every other broker**: export a file and drag it onto Fillmark's window.
  - Schwab: Accounts → History → Export (dates only).
  - thinkorswim: Monitor → Account Statement → Export to File (exact times
    and fees).
- Import again whenever you've traded; re-importing never makes duplicates.

Details: [Fills and imports](fills.md).

## 4. Look at your journal

- **[Campaigns](campaigns.md)**: your positions from open to close. The open
  ones are what you hold now, as of your last import.
- **[Fills](fills.md)**: each buy or sell your broker reported.
- **[Snapshots](snapshots.md)**: the market at the moment you entered or
  exited.

When you enter a trade, record its setup and a one-line thesis with its [snapshot](snapshots.md); Study needs them later.

## 5. Set up your market view

Build a [Watchlist](watchlist.md). On [the chart](chart.md), read the trend
under the company name, turn on support/resistance and trend lines, draw a
level and put an [alert](alerts.md) on it.

## 6. Let it record in the background

**More → [Recording](recording.md)** → tick **Start Fillmark with Windows**,
so it starts in the tray each time you sign in. While it runs it keeps
price history and the options' IV history, runs Radar scans, watches your
alerts and snapshots your entries. When Fillmark isn't running none of that
happens, and those gaps can't be filled later.

## 7. Review your trading

[Stats](stats.md) for expectancy, win rate and worst losses;
[Study](study.md) to compare your trades with what the rules would have
done; [Study with AI](study-with-ai.md) to ask an AI.

## 8. Add your phone (optional)

Set up OneDrive or Google Drive, install the Android app and pair by QR code
in **More → Sync**: [Sync and the phone](sync.md).

## 9. Keep it safe

Save a backup before any big cleanup (**Journal → Fills → Clean up…**).
