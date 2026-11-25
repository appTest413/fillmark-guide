# Privacy and security

[← User guide](README.md)

## What stays where

- **Your journal** is stored on your device in an encrypted database. Its
  key is in Windows' secure storage (the Android Keystore on the phone).
- **Logins and API keys** (Tastytrade, Alpaca, Claude, ChatGPT, Gemini,
  OneDrive, Google Drive) stay in that secure storage: never in the
  database, never synced.
- **Sync** goes through your own OneDrive or Google Drive, end-to-end
  encrypted: the cloud holds files only your paired devices can read.
- **No account, no tracking, no ads.** Fillmark has no server of its own.

## What Fillmark never does

- **Never places, changes or cancels orders**, moves money or reads
  balances. Even with a Tastytrade login that can trade, the app can reach
  only Tastytrade's read addresses.
- Never sends your journal anywhere you didn't choose. The exceptions are
  ones you start: a question to a cloud AI (which sends the export you
  see; account numbers and broker names are left out), and a problem report
  (shown in full before sending).

## What leaves your device, and when

| What | Where | When |
|---|---|---|
| Market data requests | Tastytrade or Alpaca | While charts, scans and alerts run |
| Encrypted sync files | Your OneDrive or Google Drive | When sync is on |
| Your AI export and question | Anthropic, OpenAI or Google | Only when you ask a cloud AI; a local model sends nothing |
| A problem report | Fillmark's support | Only when you send one |

## Good habits

- **Pair in private**: the pairing QR code carries your sync key.
- Use a **read-only** Tastytrade API client.
- **Save a backup** before big cleanups (Journal → Fills → Clean up).
- On Android, install from Google Play (or a release build): test builds
  can be inspected over USB.

The full text is in the [privacy policy](privacy-policy.md).
