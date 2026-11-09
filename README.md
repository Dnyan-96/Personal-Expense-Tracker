# CricExpense - Personal Expense Tracker (PWA with Auto-Backup)

A modern, 100% offline-first personal expense tracker with built-in **automated backup** to prevent data loss.

## New Features
1. **Silent Auto-Backup**: Every transaction, budget change, or debt update is automatically backed up in browser `localStorage` instantly.
2. **Auto-Restore**: If IndexedDB is ever cleared, the app automatically restores your complete dataset from the local backup snapshot.
3. **Manual Backup & Restore**: Easily download JSON backups or restore them via the top navigation bar.
4. **PWA Installable**: Fully configured with `manifest.json` and service workers for instant installation from Google Chrome.
