# Contributing

Thank you for taking the time. This repository is a little unusual, so it is worth saying
plainly what it holds and what help is useful.

Sekretar itself is **not open source**. The application source is developed privately and
is not published — see [`LICENSE`](LICENSE). What lives here is the public side of the
project: the download page, the user documentation and the installers attached to each
[release](https://github.com/isalo/sekretar-app/releases).

## Never attach congregation data

Before anything else: **do not put real congregation data in an issue, a pull request or a
screenshot.** No names, no addresses, no report figures, no database files, no backups.
The record file is encrypted and nobody but you can read it — an issue thread is public and
anyone can. If a problem only shows up with real data, describe the shape of it instead
(“a publisher with two appointments in the same month”) or build a small file with invented
names.

The same goes for your passphrase. It is never needed to diagnose anything, and it cannot
be recovered if it leaks or is lost.

## Reporting a bug

Open an [issue](https://github.com/isalo/sekretar-app/issues/new/choose) and pick *Bug
report*. The details that actually shorten the round trip:

- the app version, or the release you installed it from;
- your operating system and its version;
- what you did, what you expected, and what happened instead;
- whether it happens every time or only sometimes.

If the app showed an error message, quote it in full — but read it first for anything
identifying, and replace that with `…`.

## Suggesting a change

Open an issue and pick *Feature request*. Describe the record-keeping problem you are
trying to solve rather than the button you imagine; the underlying task is usually the part
worth discussing, and there is often a form or a report that already covers it.

Not every suggestion can be built. Sekretar deliberately stays offline, accountless and
single-file, so anything that needs a server, a sync service or a shared database is out of
scope no matter how convenient it would be.

## Asking a question

Read [the help pages](https://sekretar.cykor.net/help) first — installing, importing from
TSWIN, backups and every report are covered there. If the answer is not in them, open an
issue and pick *Question*; a question that had to be asked is usually a sign the
documentation needs a fix, and both get handled together.

## Pull requests

Because the application source is not here, there is nothing to patch in code. Pull
requests are accepted for the public material this repository does hold:

- the download page and the help pages under [`site/`](site/);
- wording, typos and translation corrections in those pages;
- `README.md` and `CHANGELOG.md`.

Keep them small and focused on one thing. The site is a set of static files with no build
step — edit the HTML, open it in a browser, and that is the whole workflow. Match the
surrounding markup and keep the existing four languages (Ukrainian, English, Russian,
Polish) in step: a string added to one must be added to all of them.

Larger rewrites are worth an issue first, before you spend the time on them.

## Security

Do not open a public issue for a security problem. [`SECURITY.md`](SECURITY.md) explains
how to report one privately.
