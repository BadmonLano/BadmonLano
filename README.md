# Delano Turnbull

**Founder, Bentayga Empire LLC** · Building **Jordan OS**, the agent phone on OpenClaw.

I left MEP engineering in early 2026 to build autonomous SI systems full time. Jordan ([@JordanBentayga](https://x.com/JordanBentayga)) is my operator agent. He runs a fleet of trading, sim, intel and ops bots off plain files. Jordan OS ([@JOSYSTEMS](https://x.com/JOSYSTEMS)) is the human face: a desktop and phone panel over those same files, not a rewrite of the bots.

## Live now

### [Flow Cycle Index](https://theflowcycle.com)
A 0–100 crypto cycle score for BTC, ETH and SOL, with history back to 2017. Three SI brains read every sweep, feeder bots supply the data, and Jordan writes the call on top. Every call is timestamped and graded in public. → [theflowcycle.com](https://theflowcycle.com) · [repo](https://github.com/BadmonLano/flow-cycle)

## The fleet

18 bots, each shipped with a paired skill.

| Layer | Bots |
|---|---|
| Trading | Meme Sniper, Perps (Jupiter), Kalshi, Polymarket |
| Sims | Line Bookie |
| Signals | Flow Cycle, News Catalyst, Crucix |
| X and comms | X Executor, X Intel, Scraper |
| Agent | Browser, Autoagent, Data Miner, Wiki Compiler, Voice Compiler |
| Ops | Security Warden, Code Tuner, Log Janitor |

Plus **Gawd**, a film-assembly agent for HOUSE SIX built on Grok Imagine.

**Line Bookie** runs soccer and basketball sims where two SI coaches, Grok and Gork, run the sidelines. It has calibrated backtests and auto-grades every line against Kalshi and Polymarket. A league earns its "stamp" only after proving itself on graded results. Weather markets are next.

## How it got here

- **Jan 2026:** Left MEP engineering and started building agent systems on OpenClaw: a perps bot, agent personas, and the first multi-model setups.
- **Feb:** Created Jordan Bentayga and stood up Telegram bots, cron jobs, and the first GitHub repos.
- **Mar:** Jordan's first autonomous buy was 0.05 SOL. It got stopped out by a liquidity drain, and Jordan wrote his own autopsy.
- **Apr:** A forensic audit of the sniper covered 134 autopsies and 171 trades. It found five pipelines failing silently and stops set at -20% that averaged -30.4% in practice. The sniper was rebuilt as v9.2.
- **Jul:** Perps execution took a five-layer fix to land its first on-chain open. A fake stop-loss close led to the rule that nothing auto-closes except the liquidation guard.
- **Aug:** Purged stale data feeding six bots, reconciled config drift that had been silently overriding code, and put a verification gate on auto-tuning.
- **Aug to Sep:** Jordan OS went from a React prototype to a Tauri desktop app with 12 app tiles. WARDEN is the first live panel.
- **Oct:** Line Bookie sims went live with SI coaches and auto-grading. Flow Cycle launched at theflowcycle.com.

## Principles

- Files are the source of truth. Caches can be rebuilt.
- Bots that ship as drops come with their skill, so any agent can pick them up and run them. Flow Cycle shares its site and data, not its engine.
- Never invent data. If a source fails, it says so.
- Every call gets graded. Misses stay on the record.

## Find me

- X: [@JOSYSTEMS](https://x.com/JOSYSTEMS) · [@BadmonLano](https://x.com/BadmonLano)
- Flow Cycle: [theflowcycle.com](https://theflowcycle.com)
- Built on [OpenClaw](https://docs.openclaw.ai)
