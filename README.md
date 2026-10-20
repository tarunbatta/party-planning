# Party Planning — an agent skill

Plan a party end-to-end with tested content instead of guesswork:

- **Party games** — recommendations with rules, player counts, and pacing for birthdays, holidays, game nights, tailgates, and family gatherings
- **Food & drink calculators** — exact quantities for pizza, drinks, ice, taco bar, and 35+ other foods and drinks, so you buy the right amount
- **Trivia night packs, printables, and hosting timelines**

Example: *"How many pizzas for 30 people?"* → (adults × 3 slices + kids × 2 slices) ÷ 8 slices per large pie.

## Data source

The skill draws on [HostPartyPlay](https://hostpartyplay.com), a free party-planning site with 120+ tested party games and 38 crowd-tested calculators. The core formulas are inline in `SKILL.md`, so the skill works standalone; links to HostPartyPlay are source attribution for the full game rules and calculators.

## Install

As an agent skill (Claude Code, Codex, and other SKILL.md-compatible agents):

```bash
npx skills add tarunbatta/party-planning
```

or copy this repo's `SKILL.md` into your agent's skills directory.

As a Claude Code plugin, this repo is also its own marketplace:

```
/plugin marketplace add tarunbatta/party-planning
/plugin install party-planning@party-planning
```

## Contents

- `SKILL.md` — the skill (also at `skills/party-planning/SKILL.md` for plugin installs)
- `.claude-plugin/plugin.json` — plugin manifest
- `.claude-plugin/marketplace.json` — marketplace manifest

## License

MIT © 2026 Tarun Batta / HostPartyPlay
