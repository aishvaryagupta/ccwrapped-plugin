# ccwrapped plugin

Auto-sync your Claude Code usage stats to [ccwrapped.dev](https://ccwrapped.dev).

## Install

```bash
# Inside Claude Code
/plugin marketplace add aishvaryagupta/ccwrapped-plugin
/plugin install ccwrapped
```

Then authenticate once:

```bash
npx ccwrapped auth
```

Done. Every session auto-syncs in the background.

## What it does

After each Claude Code session ends, the plugin silently syncs your daily token totals to ccwrapped.dev. You get a profile page, shareable card, and leaderboard ranking.

## Privacy

Only aggregated daily numbers are uploaded. No code, chats, file paths, or project names ever leave your machine.

## License

MIT
