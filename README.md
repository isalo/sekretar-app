# Секретар / Sekretar

**Записи та звіти служіння для збору** — *Congregation service records and reports*

Завантаження та опис: **[sekretar.cykor.net](https://sekretar.cykor.net)**
· Downloads and overview: **[sekretar.cykor.net](https://sekretar.cykor.net)**

---

## Українською

Секретар замінює TSWIN/TSWINU. Усі дані збору зберігаються в одному зашифрованому файлі
на вашому комп'ютері. Немає ні хмарного облікового запису, ні синхронізації, ні жодного
звернення до мережі — програма працює з від'єднаним інтернетом.

**[Завантажити останню версію](https://github.com/isalo/sekretar-app/releases/latest)**
для macOS, Windows або Linux.

Файл із записами належить вам. Він нікуди не надсилається, і ніхто, включно з автором,
не може його прочитати або відновити втрачений пароль.

## In English

Sekretar is an offline desktop replacement for TSWIN/TSWINU. Every congregation record
lives in one encrypted SQLite file on your own machine — no account, no sync, no network
access at all.

**[Download the latest release](https://github.com/isalo/sekretar-app/releases/latest)**
for macOS, Windows or Linux.

---

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
