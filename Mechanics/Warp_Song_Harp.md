# The Two-Doctrine Warp-Song Harp

> **Source:** CP-2 (gear Item rail) + Aradia Wisdom of the Wind (storm-symbols as effects).

## The Signature Asset

The demo's signature gear is a **warp-song harp** — 20 CP, `gear` item, Size Rank 0. It reads the Wisdom of Aradia: pluck the storm-symbols, and the planet responds with effects. Two doctrines, one chassis (mirrors psycho-frame/skiff/staff):

| Doctrine | Item | Effect | Flavor |
|---|---|---|---|
| **Sabaoth War-Harp** | `aradia_war_harp` | `{"kind":"stat_mod","acv_bonus":2,"ar":0,"note":"Sabaoth hunter's war-harp, storm-song"}` | The legal lane — the hunter's weapon |
| **Emissary Lull-Harp** | `aradia_lull_harp` | Same bonus + `Defect: Pacifist Vow` returning 2 CP → `Weapon Enhancement: Non-Lethal (Stun)` | The mission lane — the mentor's mercy |

Both: 20 CP, rank C, `item_type: gear`, granted as starting gear (not a market buyout).

## Attributes

- War-harp: storm-song weapons (ACV +2 via `stat_mod`)
- Lull-harp: non-lethal stun (Pacifist Vow + Stun enhancement)

## Engine Path

One `gear` row per doctrine in the `items` table, `effect_json` structured for `models.py`. No new engine field — exactly the CP-2 rail from Enid (chassis) / Cathedral (skiff) / Ikaris (staff).