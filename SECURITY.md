# Security policy

Sekretar keeps congregation records in one SQLCipher-encrypted file on the user's own
machine. There is no account, no server and no network access, so a security problem here
is almost always about that file, the passphrase protecting it, or the installers published
on this repository.

## Supported versions

Only the most recent release receives fixes. Older builds are not patched — upgrade to the
[latest release](https://github.com/isalo/sekretar-app/releases/latest) before reporting.

## Reporting a vulnerability

**Do not open a public issue.**

Report it privately through GitHub:
[**Report a vulnerability**](https://github.com/isalo/sekretar-app/security/advisories/new).
The report is visible only to you and to the maintainer until a fix is published.

Useful to include:

- the app version and the operating system it ran on;
- what an attacker would gain, and what access they would need to start with;
- the steps to reproduce it, with invented data.

**Never attach real congregation data, a record file, a backup or a passphrase** to a
report — not even in a private advisory. If reproducing the problem needs a database,
create one with invented names.

You can expect an acknowledgement within about a week. Once a fix is released, the advisory
is published; tell me in the report if you would rather not be credited in it.

## Verifying a download

Every release carries a `SHA256SUMS` file. Check an installer before opening it:

```bash
sha256sum -c SHA256SUMS --ignore-missing
```

macOS builds are signed with an Apple Developer ID and notarized. Windows builds are not
signed yet, so SmartScreen warns on first run — that warning is expected, and the checksum
is what actually tells you the file is intact.

Installers are only official when they come from the
[releases page](https://github.com/isalo/sekretar-app/releases) of this repository or the
download buttons on [sekretar.cykor.net](https://sekretar.cykor.net), which link to it. A
build from anywhere else is not one I published.

## What is out of scope

- **A forgotten passphrase.** It cannot be recovered, by anyone, including me. That is the
  design, not a defect.
- **Someone with full access to an unlocked machine.** If an attacker is already running as
  the user with the database open, the encryption has nothing left to protect.
- **Reports about this repository's static site** that amount to missing headers on pages
  serving no user data, or automated scanner output with no demonstrated impact.
