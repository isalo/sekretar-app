# Sekretar

**Congregation service records and reports** — an offline desktop app for macOS, Windows and Linux.

[![Latest release](https://img.shields.io/github/v/release/isalo/sekretar-app?label=release&sort=semver)](https://github.com/isalo/sekretar-app/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/isalo/sekretar-app/total?label=downloads)](https://github.com/isalo/sekretar-app/releases)
[![Platforms](https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-1f5670)](https://github.com/isalo/sekretar-app/releases/latest)
[![Offline](https://img.shields.io/badge/network%20access-none-2e7d32)](#about-this-repository)
[![Licence](https://img.shields.io/badge/licence-free%20of%20charge%2C%20not%20open%20source-lightgrey)](LICENSE)
[![Website](https://img.shields.io/badge/website-sekretar.cykor.net-3480a6)](https://sekretar.cykor.net)

Downloads and overview: **[sekretar.cykor.net](https://sekretar.cykor.net)**

---

Every congregation record lives in one encrypted SQLite file on your own machine — no
account, no sync, no network access at all. The interface is available in Ukrainian and
English.

**[Download the latest release](https://github.com/isalo/sekretar-app/releases/latest)**
for macOS, Windows or Linux.

Coming from TSWIN? The monthly CSV and the XML export both import, staged and previewed
so you see what will change before anything is written.

The record file belongs to you. It is never sent anywhere, and nobody — the author
included — can read it or recover a lost passphrase.

## Installing

**macOS** — open the `.dmg` and drag Sekretar to Applications. The builds are signed with
an Apple Developer ID and notarized, so they open normally.

**Windows** — run the installer. It is not signed yet, so SmartScreen asks first; choose
*More info* → *Run anyway*.

**Linux** — the `.AppImage` runs after `chmod +x`; the `.deb` installs with
`sudo apt install ./Sekretar-*.deb`.

Every release carries a `SHA256SUMS` file. To check a download before opening it:

```bash
sha256sum -c SHA256SUMS --ignore-missing
```

## What changed

[`CHANGELOG.md`](CHANGELOG.md), and the notes on each
[release](https://github.com/isalo/sekretar-app/releases).

## About this repository

This one carries the download page, the user documentation and the installers. The source
is developed privately and is not published; see [`LICENSE`](LICENSE) — the app is free of
charge, but it is not open source.

Found a problem or have a question? Open an
[issue](https://github.com/isalo/sekretar-app/issues). Please do not attach real
congregation data to it.
