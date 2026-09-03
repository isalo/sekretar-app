# Changelog

The newest release is first. Everything under the top heading becomes the release notes on
GitHub and the "What's new" section on the landing page, so write it for the person using
the app, not for the person who wrote the commit.

## 0.1.0 — unreleased

First public build.

- Encrypted local database: one SQLCipher file, one passphrase, no account and no network.
- People, field service groups, appointments and relationships, all effective-dated so
  reassigning someone keeps the history.
- Monthly publisher reports and meeting attendance.
- Import from TSWIN: monthly CSV (UTF-8 or Windows-1251) and the XML export, staged and
  previewed before anything is committed.
- 27 reports with CSV, TSV, print and PDF output, including the official S-21 and S-88
  forms.
- Backups and restore, both encrypted with the same key as the live file.
- Ukrainian and English interface.
