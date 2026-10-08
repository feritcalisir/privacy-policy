# Magnesia: Co-Op Survival

Local co-op auto-aim survivor built in Godot 4.7 — wave shop like Brotato, with dash, danger tiers, and sofa co-op.

## How to play

1. Open `project.godot` in Godot 4.7+
2. Press F5
3. Pick character(s) → **New Run**
4. **WASD** (P2: arrows) — move; weapons fire automatically
5. **Space / dash button** — short invulnerable dash
6. Collect grapes + XP; shop between waves; merge duplicates; evolve maxed weapons
7. Bosses on waves **10** and **20** (Giant / Oracle / Melon Warden rotation; every 5 waves in endless)
8. Clear wave 20 to win, or keep going in **Endless**

**Esc** / on-screen **II** — pause

## Content (approx.)

- **12** characters (passives + permanent levels; Defne / Can unlockable)
- **29** weapons + **20** evolutions; merge up to +3; one of each weapon id; shop merge pity
- **30** items, 7 of them cursed (tags / cursed stock); merge up to +3
- **19** enemy kinds (incl. three bosses), affixes, wave modifiers, arena events (grape storm / mesir mist), themes (vine / stone / ember)
- **Danger 0–5**, diamond store, vineyard (incl. status/dodge plots), daily/weekly/festival quests, **daily challenge run**, achievements
- **Local 2P**: shared wallet, bond buff, shared synergies, combined dash, revive
- **11** languages under `locale/`
- Skipable first-run tips for shop / dash / merge / revive

## Build

Windows + Android exports live in `export_presets.cfg`. See `.cursor/rules/build-both.mdc`.

Play / store notes: [`docs/STORE.md`](docs/STORE.md) · Privacy: [`docs/PRIVACY.md`](docs/PRIVACY.md) · Monetization stance: [`docs/MONETIZATION.md`](docs/MONETIZATION.md)
