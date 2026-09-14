# Asrai Magic & Flight

> **Source:** BESM 4e Chapter 14, pp. 314–315 (Aradia) + Ch.3 Race Templates.

## Asrai Racial Traits

- **Wings** — small feathered wings that expand to full size; flight is a racial power (as a `card_json` power, narrative + obstacle-free travel).
- **Highly magical** — some Asrai more talented than others; magic is natural, not learned.
- **Born from storm-eggs** — the storm-symbols literally birth them.
- **Away from Aradia:** wings don't manifest until adolescence; a lost angel can pass for human.

## Fairies & Elarad

- **Fairies** — 10–15cm, insect-winged, some Bane-tainted (the moral-thrall slot).
- **Elarad** — talking animals, ~1/10,000; some attend school, some become Emissary companions.

## Powers → card_json

Flight/Wings, Healing, Sixth Sense (Gates), Storm-song, Control Environment all have **no DB column** — they live in `card_json.powers` + the `race` column as narrative, injected as prose (the established Enid/Cathedral/Ikaris pattern). The loadout DB columns carry techniques/skills/defects + Narrative Syntax.