# Contributing to CYX Vault

Thanks for contributing. CYX Vault is designed to be a collaborative CTF knowledge base, not just a flag archive.

## Preferred workflow

1. Create a branch for your contribution.
2. Add or update a writeup using the repository template.
3. Keep challenge-specific files inside that challenge directory.
4. Commit with a short descriptive message.
5. Open a pull request describing what was added or changed.

## Directory convention

Solved CTF challenges:

```text
writeups/<year>/<ctf>/<category>/<challenge>/
```

Curated/external challenges:

```text
curated/<category>/<challenge>/
```

Examples:

```text
writeups/2026/VITxCS/Crypto/Oblique-Manuscript/
writeups/2026/COMPFEST18/Web/Egg/
curated/crypto/interesting-rsa-challenge/
```

## Challenge README

Start from `templates/challenge-writeup.md`.

At minimum, include:

- CTF / event
- challenge name
- category
- challenge author, if known
- solver / writeup author
- original source or event URL, if available
- challenge description
- analysis
- solution
- scripts or commands where useful
- lessons learned
- credits

## Attribution rules

If the solution or challenge came from another person or website:

- credit the original author
- link the original source
- distinguish copied facts from your own analysis
- do not present another person's work as your own

When adapting an external writeup, prefer writing a concise summary plus your own reproduction, notes, improvements, or alternative solve path rather than duplicating the original article.

## Challenge files

Only commit binaries, archives, images, source code, or other challenge assets when redistribution is permitted by the organizer or author.

When in doubt, link the source instead.

## Secrets and active infrastructure

Never commit:

- real passwords
- API keys
- CTFd tokens
- session cookies
- private access URLs containing credentials
- personal/private data

Sanitize terminal output and solver scripts before committing.

## Active competitions

Respect the competition's publication rules. Do not publish a challenge solution or flag while the event is active when doing so is prohibited.

## Style

Prefer clear technical explanations over excessive prose. Include the important failed assumption only when it helps teach why the final approach works.

Code should be readable enough that another player can reproduce the solve.
