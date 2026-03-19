# League of Legends MCP Server

> Connect AI assistants to League of Legends data via MCP — player profiles, ranked stats, match history, champion mastery, live game analysis, and AI-powered coaching.

**[Try it on Apify Store](https://apify.com/mrbridge/lol-mcp-server?fpr=ebrunet001)** | Pay-per-event | Free tier available

## Features

- **26 MCP tools** for comprehensive LoL data access
- **No Riot API key needed** — built-in key, just connect and play
- Player profiles — search players by Riot ID across all regions
- Ranked stats — tier, rank, LP, win/loss ratio, league standings
- Match history — detailed stats with damage breakdown (physical/magic/true) and objectives
- Champion mastery — levels, points, progression to next level, season milestones
- Live game lookup — scout opponents in real time
- League standings — Challenger, Grandmaster, Master leaderboards and ranked entries
- Clash — tournament info, teams, and player registrations
- Challenges — player challenge progression, leaderboards, and configs
- AI-powered performance analysis — position-adjusted benchmarks, damage breakdown, personalized coaching
- Player comparison — side-by-side stats with damage type analysis
- Works with **Claude Desktop, Claude Code, ChatGPT** and any MCP-compatible client

## Quick Start

1. **[Open the Actor on Apify](https://apify.com/mrbridge/lol-mcp-server?fpr=ebrunet001)** and get your free API token
2. Connect your AI client using the MCP endpoint below
3. Start asking about any League of Legends player, match, or champion

### Claude Desktop

Go to **Settings → MCP Servers → Add Custom Connector** and paste:

```
https://mrbridge--lol-mcp-server.apify.actor/mcp?token=YOUR_APIFY_TOKEN
```

### Claude Code

Add the endpoint above to your MCP settings, then run `/permissions` and add `mcp__LoL__*` to the Allow list.

## Example Prompts

Once connected, your AI assistant can handle prompts like:

- *"Analyze my last 20 ranked games and tell me what I'm doing wrong"*
- *"Compare my stats with this Diamond player — what's the difference?"*
- *"I'm in game right now. Scout my opponents and tell me what to watch out for"*
- *"Based on my champion pool, which 3 champions should I focus on to climb?"*
- *"I just lost 3 games in a row. Am I repeating the same mistakes?"*

## Pricing

Pay-per-event — you only pay for the tools you actually use. The free tier gives you **$5 free credits every month**, enough for hundreds of tool calls.

## Links

- **Apify Store**: [League of Legends MCP Server](https://apify.com/mrbridge/lol-mcp-server?fpr=ebrunet001)
- **Author**: [mrbridge on Apify](https://apify.com/mrbridge?fpr=ebrunet001)

## Related MCP Servers

- [Teamfight Tactics MCP Server](https://apify.com/mrbridge/teamfight-tactics-mcp-server---ai-game-analysis?fpr=ebrunet001) — 10 tools for TFT compositions, augments, and AI coaching
- [ESPN MCP Server](https://apify.com/mrbridge/espn-mcp-server?fpr=ebrunet001) — Live scores, standings, and stats across 25+ sports leagues
- [Todoist MCP Server](https://apify.com/mrbridge/todoist-ai-assistant?fpr=ebrunet001) — 35 tools for AI-powered task management

---

*Built by [mrbridge](https://apify.com/mrbridge?fpr=ebrunet001) — Usage must comply with Riot Games API Terms and Conditions.*
