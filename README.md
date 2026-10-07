# HL2 x DoD:S mashup (working title, draft)

Solo Half-Life 2 campaign with Day of Defeat: Source weapons added alongside the HL2 guns.

- Host: Half-Life 2 (primary). DoD:S: secondary, found and read by the mod at runtime (not in Melty's catalog). Nothing from DoD:S is shipped.
- First playable: Garand, Thompson, Kar98k, MP40, MG42 for the player; iron sights + sway; prone + MG bipod; rebels with Allied guns, Combine with German guns.
- Source of truth: `sheets/*.json`. Run `python3 preflight.py` before every build. Empty cells are `null`.
- Status: design only. No code, no build, nothing uploaded to Melty. Melty and the PC were not reachable when this was written.
