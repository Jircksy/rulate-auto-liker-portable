# Rulate Auto Liker Portable

Portable EXE build for Windows.

## Download

Download `rulate-auto-liker-portable-github-release.zip` from GitHub Releases, unpack it anywhere, then run:

```powershell
.\RulateAutoLiker.exe
```

Chromium is included in the archive. Python is not required.

## First Start

1. Choose `1. Первичная настройка + Telegram QR`.
2. Enter Telegram group ID and topic ID.
3. Choose what to do with books and chapters.
4. Scan Telegram QR.
5. Choose `2. Войти в Rulate`, log in, then press Enter in the console.

## Notes

- One portable folder stores one Rulate browser profile.
- For multiple accounts, use separate copies of the portable folder.
- Do not upload `data`, `config.json`, cookies, browser profiles, or Telegram sessions.
- Paid chapters are skipped by price marker when `Пропускать платные главы` is enabled.
- The normal run does not repeat already recorded likes, ratings, bookmarks, or viewed chapters.

## Release Asset

The full portable archive is not stored directly in git because it includes Chromium and is too large for a clean repository history.

Use GitHub Releases for the zip file:

```text
D:\Telegram\rulate-auto-liker-portable-github-release.zip
```
