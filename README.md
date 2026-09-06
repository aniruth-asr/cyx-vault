# CYX Vault

A collaborative archive of **CTF writeups, exploit scripts, challenge research, reusable techniques, and interesting security puzzles**.

CYX Vault is intended to grow beyond a single person or event. It can contain:

- writeups from challenges we solve
- contributions from friends and collaborators
- future CTF solutions
- curated interesting challenges from other authors
- reusable exploitation, reversing, crypto, forensics, and web techniques
- helper scripts, notes, and references

> **Principle:** preserve the reasoning, not just the flag.

## Categories

`Web` · `Crypto` · `Pwn` · `Reverse` · `Forensics` · `Stego` · `Hardware` · `OSINT` · `Blockchain` · `Misc`

## Repository layout

```text
cyx-vault/
├── writeups/                 # Challenges solved by us/contributors
│   └── <year>/<ctf>/<category>/<challenge>/
├── curated/                  # Interesting external challenges/writeups
├── resources/                # Technique notes, references, cheatsheets
├── scripts/                  # Reusable helper scripts
├── templates/                # Standard writeup templates
├── CONTRIBUTING.md
└── README.md
```

## Writeup standard

Each challenge should normally include:

```text
Challenge-Name/
├── README.md
├── solve.py / exploit.py     # when useful
├── files/                    # only when redistribution is permitted
└── images/                   # screenshots/diagrams owned or permitted
```

A writeup should explain:

1. the challenge and provided artifacts
2. reconnaissance / initial observations
3. the core vulnerability, primitive, or trick
4. the important reasoning steps
5. commands, solver, or exploit
6. verification / result
7. lessons learned
8. credits and original source

Use [`templates/challenge-writeup.md`](./templates/challenge-writeup.md) when adding a new challenge.

## Attribution

CYX Vault is collaborative. Every imported or externally inspired challenge should clearly identify the original **CTF, challenge author, solver/writeup author, and source URL** where known.

Do not copy someone else's writeup and present it as original work. Prefer linking to the original and adding your own analysis, notes, reproduction, or alternative solution.

## Responsible publishing

- Do not publish flags or solutions for an active competition when the rules prohibit it.
- Do not redistribute challenge binaries, source code, media, or other assets unless redistribution is allowed.
- Remove real credentials, access tokens, private data, and unrelated secrets before committing.
- Keep exploitation examples scoped to CTFs, labs, research, or systems you are authorized to test.

## Contributing

Friends and collaborators are welcome to contribute through branches and pull requests. See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for the repository conventions.

## Status

The vault is being initialized. Existing solved challenges and future writeups will be added incrementally.
