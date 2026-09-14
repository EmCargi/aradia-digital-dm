# 💿 Aradia: The Living Heaven — Game Disc for Chronos Core

*Winged Asrai, the Council of Aeons, the Sabaoth warrior angels, the Whirl gate to Earth, and the Wormwood Blight.*

> **Source:** BESM 4e Chapter 14 (Anime Multiverse) — First-party canon, no third-party IP.
> All content authored from the canon hooks. Regenerable via the Chronos engine.

---

## 🎮 Boot (when ready)

```text
/setting besm_aradia       # swap discs in the TUI
/roster                      # Chorus column
/module aerial_path.json             # default starter module
```

| Contract layer | Status |
|---|---|
| **1 · Registration** | ✅ `besm_aradia` in `config/settings.json` → `aerial_path.json` |
| **2 · Module** | ✅ `modules/aerial_path.json` (validator-passed) |
| **3 · Roster** | ✅ Starter characters authored (`Characters/`, 50 CP, `besm_aradia`) |
| **4 · Economy** | ✅ Seed catalog + chassis as `Item` |
| **5 · Lore Vault** | 🏗️ `World/` `Characters/` `Factions/` `Locations/` `Mechanics/` |

> **Status: SCAFFOLDED** — disc directory + proposal exist. Layers 1–5 wired via Chronos Core engine.

## 🗂️ Structure

```
aradia-digital-dm/
├── README.md               ← this home page
├── Characters/             ← PC/NPC sheets (besm_aradia)
├── data/                   ← roster DB + catalog
├── Factions/               ← organizations & groups
├── Locations/              ← region & landmark sheets
├── Mechanics/              ← system rules & supplements
├── modules/                ← playable labyrinth modules
├── scripts/                ← import/parser utilities
└── World/                  ← lore vault
```

---

*Disc for the Chronos Core console. Swap via `/setting besm_aradia`.*
