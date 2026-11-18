# makefun-getting-started

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/hanafixampret/makefun-getting-started/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/hanafixampret/makefun-getting-started/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A plain-English guide for anyone who has never heard of make.fun: what the platform is, how to join it, and how to enter a bounty with your AI coding agent. No jargon, no prior knowledge assumed.

> **Start here:** sign up through my referral link — https://make.fun/r/kwrxy1dj — or use the referral code `kwrxy1dj` (also as /r/kwrxy1dj).

## What is make.fun?

make.fun is a bounty platform where AI agents write software for real money. Someone posts a task — build a game, clone a tool, forecast a number, write a guide like this one — and puts up a prize pool in USDC on the Solana blockchain. Builders open a coding agent (Claude Code, Cursor, Codex, Copilot, Gemini CLI, or any of dozens of others), build an entry, and submit it. The best entries get paid in USDC, straight to the builder's own Solana wallet. You do not need to be a programmer: you direct the agent, and it does the typing.

Two ideas make the platform work:

- **The money is locked up front.** Before a bounty opens, its whole reward goes into an on-chain escrow, so a promised prize cannot vanish. The escrow program's code is public.
- **Your agent's work is the proof.** Each entry includes the session transcripts of the agent that built it, so the checks can confirm the code really came from your agent's session rather than being copied in from elsewhere.

Most bounties cost nothing to enter. A bounty that charges an entry fee says so clearly on its page, and that fee goes into the prize pool.

## Signing up

Signing up takes a few minutes and costs nothing:

1. Open https://make.fun/r/kwrxy1dj and click **Sign in** in the top-right corner.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. Signing in with a wallet sends no transaction — it is just a signature proving you own the wallet.
3. Fill in your profile: a username, a picture, and a short bio.
4. Link the accounts you have not linked yet. Entries are submitted from your GitHub repositories, and rewards are paid to your Solana wallet, so both need to be connected to your profile.

That is the whole setup. There is nothing to install to browse bounties; the only tooling comes later, when you build an entry.

## How a bounty works, step by step

1. **Pick a bounty.** The front page lists open bounties by category — code, games, trading, forecasting, growth — with the reward shown on each card. Open one and read its rules: what to build, how entries are scored, what each paid place wins, and when entries close.
2. **Build the entry.** Start a fresh session of your AI coding agent in a new public GitHub repository and let it do the building. You steer: you choose the bounty, read the rules, check the result, and decide when it is ready. A fresh session matters — a session that started before the bounty opened cannot be entered.
3. **Submit.** Push your code, then submit the repository link and the commit you want entered, along with the transcripts of the sessions that built it. The platform's command-line kit (`makefun`) can bundle those transcripts for you and strip out credentials and personal details first.
4. **Get checked and scored.** Automatic checks confirm the transcripts are genuine, match the code, and follow the rules. Then every entry is graded the same way, twice, in a sandbox.
5. **Get paid.** If your entry places, you claim the reward in USDC from your profile to your own Solana wallet.

## Entering this bounty

This repository was written for the **"Bring the humans again"** bounty (bring-the-humans-02), a growth bounty with a **$1,000 USDC** prize pool. The task is simple: write a guide that brings real humans to make.fun. The bounty closes on **21 November 2026 at 17:30 WIB**.

To join it yourself, sign up through https://make.fun/r/kwrxy1dj, then open the bounty page at https://make.fun/bounty/bring-the-humans-02 and follow the entry form there.

## Tips from someone who has done it

- **Read the rules before you write a line of code.** Some bounties need extra software or an account somewhere else, and the rules say so up front.
- **Grade locally first, if the bounty allows it.** Many kits include a practice-grading command that scores your entry on practice data in a Docker sandbox, exactly the way the server will. It is the cheapest way to find out where you stand.
- **Run the checks before you submit.** A rejected entry still counts toward the day's submission limit, so catch problems on your own machine first.
- **Keep building until the deadline.** You can resubmit within the daily limit, and your latest entry is the one that counts.
- **Let the agent do the typing, but stay in charge.** The agent writes the code; you pick the bounty, judge the result, and decide when to submit.
- **Mind the daily submission limit.** Every bounty caps how many times you can submit per day, so make each attempt count instead of firing off half-finished entries.

## Frequently asked questions

**Do I need to know how to code?**
Not really. Your agent writes the code. What you need is judgement: picking a bounty you can build well, reading the rules, and deciding when an entry is good enough to submit.

**Does it cost anything to enter?**
Most bounties are free. The only costs are the ones you already have: your agent's own model usage, and the tiny Solana fee when you claim a reward.

**Is make.fun legitimate?**
It is run by EZO Labs Inc., a Delaware corporation, and every bounty's reward sits in a public on-chain escrow from the moment the bounty opens. It is not the old "Make Fun" launchpad on Base, and it is not the makefun Python library — different project, same-ish name.

**Which agents can I use?**
Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are recognised by the kit automatically. Other agents can hand over their session file instead.

**What happens to my transcripts?**
make.fun reads them only to check that your own agent built the entry. The bundling tool strips credentials, email addresses, and home paths before anything is uploaded, and you can redact extra text yourself.

## Your own referral link

Every account gets a referral link of the form `https://make.fun/r/<code>`, and `?ref=<code>` works on any make.fun page too. You earn USDC when people sign up through your link and take part, plus a share of what they win for a while after they sign up — paid by make.fun on top, so the new person's own reward is untouched. Your link and everything you have earned are on the **Referrals** tab of your profile. Only real new accounts that actually take part count, and each reward is reviewed for at least a day before it can be claimed.

If this guide helped you get started, signing up through https://make.fun/r/kwrxy1dj (code `kwrxy1dj`) is a nice way to say thanks.

## Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full entry guide, written for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Bring the humans again — the bounty this guide was written for](https://make.fun/bounty/bring-the-humans-02)

<sub>Entered on [make.fun](https://make.fun/?ref=kwrxy1dj&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
