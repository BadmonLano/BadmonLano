# Delano Turnbull

**Founder, Bentayga Empire LLC** · Building **Jordan OS**, the agent phone on OpenClaw.

I left MEP engineering in early 2026 to build autonomous agent systems full time. Jordan ([@JordanBentayga](https://x.com/JordanBentayga)) is my operator agent. He runs a fleet of trading, intel, and ops bots off plain files. Jordan OS ([@JOSYSTEMS](https://x.com/JOSYSTEMS)) is the human face: a desktop and phone panel over those same files, not a rewrite of the bots.

## The fleet

18 bots, each shipped with a paired skill.

| Layer | Bots |
|---|---|
| Trading | Meme Sniper, Perps (Jupiter), Kalshi, Polymarket |
| Signals | Flow Cycle, News Catalyst, Crucix |
| X and comms | X Executor, X Intel, Scraper |
| Agent | Browser, Autoagent, Data Miner, Wiki Compiler, Voice Compiler |
| Ops | Security Warden, Code Tuner, Log Janitor |

Plus **Gawd**, a film-assembly agent for HOUSE SIX.

## How it got here

- **Mar 2026:** Jordan's first autonomous buy was 0.05 SOL. It got stopped out by a liquidity drain, and Jordan wrote his own autopsy.
- **Apr:** A forensic audit of the sniper covered 134 autopsies and 171 trades. It found five pipelines failing silently and stops set at -20% that averaged -30.4% in practice. The sniper was rebuilt as v9.2.
- **Jul:** Perps execution took a five-layer fix to land its first on-chain open. A fake stop-loss close led to the rule that nothing auto-closes except the liquidation guard. Failed sells were traced to a confirm timeout and fixed with a pending tracker and a stuck-bag watchdog.
- **Aug:** Purged stale data feeding six bots, reconciled config drift that had been silently overriding code, and put a verification gate on auto-tuning.
- **Aug to Sep:** Jordan OS went from a React prototype to a Tauri desktop app with 12 app tiles. WARDEN is the first live panel.
- **Next:** Standalone repos per bot, dropping over the coming weeks, with Kalshi and the movie app first.

## Principles

- Files are the source of truth. Caches can be rebuilt.
- Every bot ships with its skill, so any agent can pick it up and run it.
- Never invent data. If a source fails, it says so.

## Fork it

Each bot drops as its own repo: the bot, its skill, and a README. No keys, no personal paths. Hand it to your agent and configure it however you run. Contributions and change reports are welcome and help sharpen the bots ahead of the Jordan OS launch. See `CONTRIBUTING.md` in each repo.

## Find me

- X: [@BadmonLano](https://x.com/BadmonLano)
- Flow Cycle: [live dashboard](https://flow-cycle-two.vercel.app)
- Built on [OpenClaw](https://docs.openclaw.ai)
