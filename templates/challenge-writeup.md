# <Challenge Name>

| Field | Value |
|---|---|
| CTF | `<CTF / Event>` |
| Year | `<YYYY>` |
| Category | `<Web / Crypto / Pwn / Reverse / Forensics / ...>` |
| Points | `<points>` |
| Solves | `<optional>` |
| Challenge Author | `<author / unknown>` |
| Solver(s) | `<name(s)>` |
| Writeup Author | `<name>` |
| Source | `<URL or event page>` |

## Challenge

> Paste or summarize the challenge description here.

### Provided artifacts

- `<file>`
- `<remote service>`
- `<hint>`

## Initial analysis

Describe the first observations that mattered.

Useful questions:

- What does the challenge immediately suggest?
- What protections, encodings, formats, or technologies are present?
- Which clues look deliberate?
- What hypotheses were tested?

## Core idea

Explain the actual primitive, vulnerability, cryptographic weakness, reversing trick, forensic artifact, or puzzle mechanism.

This section should make the solution understandable before the reader sees the final script.

## Solution

Walk through the solve in reproducible steps.

### Step 1 — <short title>

```bash
# commands
```

Explain the output and why it matters.

### Step 2 — <short title>

Continue until the solution is complete.

## Solver / exploit

```python
#!/usr/bin/env python3

# Minimal, cleaned-up solver or exploit.
```

If a full script is stored separately, link it instead:

- [`solve.py`](./solve.py)
- [`exploit.py`](./exploit.py)

## Verification

```text
$ python3 solve.py
<important output>
```

## Flag / result

```text
<FLAG{...} or recovered result>
```

If publishing the flag is not permitted or useful, describe the successful result without exposing it.

## Lessons learned

- `<technique>`
- `<tool / insight>`
- `<reusable takeaway>`

## Credits

- Challenge author: `<name>`
- Solver(s): `<name(s)>`
- Original writeup/reference: `<URL if applicable>`

## References

- `<reference>`
