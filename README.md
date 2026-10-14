# TsPad beta

Beta builds of **TsPad**: LINQPad for TypeScript. Query your SQL Server databases with typed TypeScript.

This repository only holds the builds. Download the newest one from **[Releases](../../releases)**.

## Installing (macOS, Apple Silicon)

1. Download `TsPad-….dmg` from the newest release and drag **TsPad** into **Applications**.
2. The beta builds aren't signed yet, so the first time you open TsPad, macOS blocks it. Allow it once:
   - open **System Settings › Privacy & Security**, scroll to the message about TsPad and click **Open Anyway**; or
   - in Terminal: `xattr -dr com.apple.quarantine /Applications/TsPad.app`
3. To update, download the newer build and replace the old one. Your Connections, saved passwords, Queries and open tabs stay.

## What works

- SQL Server, including Azure SQL with a SQL login (not yet with Microsoft Entra ID sign-in).
- Typed queries (`sql('table').findMany(…)`), raw SQL, Shapes, and writes in Dry and Write mode.
- Saved Queries, tabs, snippets, and importing Connections from a .NET project.

## Privacy

TsPad doesn't send anything anywhere by itself: no analytics, no crash reports, no update checks unless you turn them on. Your passwords are kept in the macOS Keychain.

## Problems and ideas

Open an issue here, with the TsPad version (shown in the status bar) and what you did.
