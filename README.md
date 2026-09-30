# Raid: Shadow Legends Gemini Gem

This repository is a ready-made knowledge base and instruction pack for a Gemini-based assistant that helps plan progression and choose artifacts for champions in Raid: Shadow Legends.

## What this bot does

The bot is designed to:

- Recommend a progression path based on the champion and stage of the account
- Suggest the most useful artifacts for the champion's role and stats
- Prioritize stats such as Speed, Accuracy, Crit Rate, Crit Damage, HP, Defense, Attack, and support stats depending on the champion
- Match artifact sets and substats to the actual champion function in the game
- Provide an actionable recommendation for early, mid, and late progression

## Recommended use

Use the file `BOT_INSTRUCTIONS.md` as the system prompt or core instruction set for the Gemini Gem. Then use the data files in `data/` as context or upload them as a knowledge base.

## Repository structure

- `BOT_INSTRUCTIONS.md` — the exact prompt/instructions for the bot
- `data/champion_profiles.json` — example champion profiles, roles, and stat priorities
- `data/artifact_selection_guide.md` — artifact strategy guide and set recommendations
- `data/progression_paths.md` — progression planning framework for account stages

## Example bot input

The bot should receive input like:

- "Recommend a build for Kael"
- "What artifacts should I use for a speed lead support?"
- "Give me a progression path for my early-game team"
- "Choose the best artifact set for a tank with AoE cleanse"

## Important note

This repository is built as a practical planning framework, not as a replacement for the official game database. It is meant to help the bot reason consistently and make smart recommendations based on common Raid: Shadow Legends archetypes and player progression logic.

## Suggested Gemini setup

1. Create a custom Gemini Gem.
2. Paste the contents of `BOT_INSTRUCTIONS.md` as the main instruction prompt.
3. Upload or reference the `data/` folder as context.
4. Ask for a champion name and game stage when needed.

## Example output the bot should produce

- Champion role and archetype
- Priority stats and artifact sets
- Build order and upgrade path
- Recommended progression path
- Rationale tied to the champion's actual purpose in the game

---

This repository is intentionally structured so you can expand it over time by adding more champion entries, artifact sets, and account progression rules.
