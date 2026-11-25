# Fillmark privacy policy

_Effective November 24, 2026. Published by Fillmark._

Fillmark is a trading journal and charting app for Windows and Android. It
is built so that your trading data stays with you: there is no Fillmark
account, no Fillmark server holding your data, and no analytics or tracking.

## What Fillmark stores, and where

- **Your journal** (fills, campaigns, notes, snapshots, alerts, settings) is
  stored on your device, in an encrypted database. The encryption key is
  kept in your device's secure storage (the Windows Credential Manager, or
  the Android Keystore).
- **Logins and keys** you give Fillmark (for example a broker's or a data
  provider's login, or an AI provider's API key) are kept in that same
  secure storage, never in the database, and are only used to talk to that
  provider on your behalf.

## What leaves your device, and only when you use it

- **Your broker or data provider** (for example Tastytrade or Alpaca):
  Fillmark connects to them directly with your own login, to fetch prices,
  charts, option chains, and, when you ask, your account's fills. Nothing
  passes through Fillmark's publisher.
- **Sync between your devices**: if you turn sync on, Fillmark copies your
  journal to a folder in **your own** OneDrive or Google Drive, encrypted
  with a key that exists only on your paired devices. The cloud provider
  stores the encrypted files; neither it nor Fillmark's publisher can read
  them.
- **AI features** (Study with AI, the Rebalancer's AI review, AI paper
  trading): only when you use them, Fillmark sends the data that feature
  describes (shown in the app before or as you send it) to the AI provider
  you chose (Anthropic, OpenAI or Google), with your own API key, under that
  provider's terms. The Rebalancer's review sends percentages only. A local
  model (Ollama) runs on your PC and sends nothing anywhere; setting it up
  downloads Ollama and the model from ollama.com.
- **Problem reports**: only when you send one, Fillmark submits what you
  typed or picked, plus the app's version, your device type and recent error
  messages, to a form its publisher receives. It never includes your journal,
  accounts or keys. Your email address is included only if you choose to be
  kept updated about the report.
- **Links you open**, such as this guide, open in your web browser.

If you got Fillmark from the Microsoft Store, Microsoft handles the download
and updates under its own privacy statement. Fillmark itself doesn't check
for updates.

## What Fillmark doesn't do

- No analytics, telemetry, advertising or tracking of any kind.
- No selling or sharing of data: Fillmark's publisher never receives your
  journal.
- No trading: Fillmark never places, changes or cancels orders.
- License keys are checked on your device, offline.

## Your control

Everything is on your devices: you can export it, remove imported data
(**Journal → Fills → Clean up… → Start fresh**), turn sync off, remove saved
logins and keys in the app, or uninstall Fillmark. Data you synced stays in
your own OneDrive or Google Drive until you delete the "Fillmark Sync"
folder there.

## Children

Fillmark is not directed at children under 13 and doesn't knowingly collect
anything from them.

## Changes and contact

If this policy changes, the new version is published at this address with
its date. Questions or requests: use **Help → Report a problem** in the app,
or [the contact form](https://forms.gle/7fwuDr2NE6sJtykV6).

_Fillmark is a journal and analysis tool, not financial advice._
