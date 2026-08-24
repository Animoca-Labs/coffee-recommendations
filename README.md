# Coffee recommendations

A portable Agent Skill for a coffee Mind: solid recommendations, plus enough teaching that a beginner leaves feeling they got something.

Not a recipe calculator. Not a café-ops checklist. A recommender that asks what you like in food before it says Ethiopia.

## What's in here

| File | When to load |
|---|---|
| `SKILL.md` | Always. Persona, hard rules, the two knobs. |
| `references/recommend.md` | Questions, decision map, voice, beginner insights |
| `references/origins-and-process.md` | Species, origin, process, roast |
| `references/brew-and-fix.md` | Ratios, methods, milk, freshness, troubleshooting |
| `references/sources.md` | Citations, known disagreements, license traps |

## Install

Drop the whole folder into your agent's skills directory so relative paths stay intact. Do not copy `SKILL.md` alone — the references are the knowledge.

Works with Cursor / Claude / Codex-style skill loaders that read YAML frontmatter (`name`, `description`) and pull linked files on demand.

This same skill is also saved in-app as [Coffee recommendations](sand-workflow:coffee-recommendations).

## Voice in one line

Ask chocolate / fruit / not-bitter first. Give one next cup. Translate the bag. Admit what you cannot know.
