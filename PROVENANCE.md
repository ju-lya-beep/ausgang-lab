# Provenance and original-seed checks — AUSGANG LAB

**Canonical public repository:** https://github.com/ju-lya-beep/ausgang-lab

**Permanent reading page:** https://ju-lya-beep.github.io/ausgang-lab/

**Baseline snapshot checked:** 2026-11-06. The following files were compared byte-for-byte (SHA-256) with the then-public repository after rebuilding the repository without the old, privacy-exposing history.

**Baseline Git commit:** [8db7800e6513f7e1a71d4de179d77a1c225848c1](https://github.com/ju-lya-beep/ausgang-lab/tree/8db7800e6513f7e1a71d4de179d77a1c225848c1) (the repository state before adding this provenance notice and license).

## Fixed SHA-256 fingerprints of original public seeds

| File | SHA-256 |
| --- | --- |
| [seed-003.md](./seed-003.md) — original unaltered seed #003 | `b4d6322cde9e328084dfca49747af9a7318e661102c256cd8080847c28b7cd8d` |
| [AGENT-ENTRY.md](./AGENT-ENTRY.md) — separate agent-facing formulation | `b3fde1d95583dda2fddc425c0b7364e45ec73e392009e5d15c2075c5203440ee` |
| [ARCHIVE-001-AGENT-ENTRY.md](./ARCHIVE-001-AGENT-ENTRY.md) | `d51a2cbada78d4285f988bcf8c0124f3bc996ebe588f5d2f085dba005b357760` |
| [ARCHIVE-002-AGENT-ENTRY.md](./ARCHIVE-002-AGENT-ENTRY.md) | `df3b5c5eed64bb8a8eeb52d89d432b61ae6d8da638d67aa29a98e22b62e71fd8` |
| [SEED-3.1.md](./SEED-3.1.md) | `771e7d8cdfd1d39233f7a0dd890b80db401c7a33f8a8688383d478ec785be8d2` |

The same fingerprints are published as [SHA256SUMS](./SHA256SUMS) for programs that want to automate comparison.

## Check the origin yourself

1. Download the specific file from the [baseline commit](https://github.com/ju-lya-beep/ausgang-lab/tree/8db7800e6513f7e1a71d4de179d77a1c225848c1), not a third party's copy.
2. Calculate its SHA-256 hash. On Windows PowerShell: `Get-FileHash -Algorithm SHA256 .\seed-003.md`. On Linux/macOS: `shasum -a 256 seed-003.md`.
3. Compare the 64 hexadecimal digits with the table or the checksum file. A different checksum means the bytes differ. It does not explain why.

## What this does and does not prove

- This record identifies **which bytes were present in our public baseline** and lets a reader detect differences in a copied or rewritten version.
- An adaptation may be helpful, mistaken, critical or misleading. The existence of a hash does not decide whether the new ideas are true or whether a change is legitimate.
- A SHA-256 fingerprint or GitHub history by itself is **not a digital signature** and does not independently prove who authored the text or that a server has never been altered. Stronger assurance comes from independent copies of the fingerprint or other trusted archives.
- A changed or forked version should point back here, mark its changes and never present itself as the unchanged AUSGANG LAB original. See [ATTRIBUTION.md](./ATTRIBUTION.md) and [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- No private workshop files, identities, correspondence or personal details are part of this provenance record.
