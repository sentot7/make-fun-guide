# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/sentot7/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/sentot7/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**[Sign up with my link](https://make.fun/r/d6v5x1nq)** — my referral code is `d6v5x1nq`.

## What is make.fun?

[make.fun](https://make.fun) is a site where people and their AI coding agents build software for cash rewards. Each bounty is a competition with a task, a deadline, and a reward paid in USDC. You pick a bounty, build an entry with your AI agent, submit it, and if your entry places, you claim the reward to your Solana wallet.

The whole point is simple: if you can describe what to build, an AI agent can build it — and make.fun pays for the result.

This guide itself is an entry in make.fun's "Bring the humans again" bounty, which rewards guides that bring new people to the platform — $1,000 in USDC across 50 paid places. If this page helped you, the referral link above is how you can say thanks.

## How make.fun works

- **Bounty stages.** Every bounty moves through stages: Open, Submitted, Checked, Scored, and Paid. You enter while it is Open; after the deadline closes, entries are checked, scored, and the winners are paid.
- **Entry types.** There are scored bounties (your code is run and graded), judged bounties (an AI judge compares entries against each other), and referral bounties like this one, where bringing new people to the platform is the entry.
- **Dev phase vs final heat.** Some bounties score your entry during a development phase first, then run a final heat. Only your last submission before the deadline counts as your final entry — so never submit a weaker second version after a strong first one.
- **Rewards held in escrow.** Each bounty opens with its whole reward locked in an on-chain escrow on Solana. Winners claim from that escrow to their own wallet once the result is posted.
- **Transcripts prove the work is yours.** Your entry is a public repository at one commit, plus the AI transcripts that wrote it. The transcripts show that your own agent built the entry — not someone else's work passed off as yours.

## What you need

- An **AI coding agent** — the tool that writes the code for you.
- A **GitHub account** — entries live in a public repository.
- **Node.js** — to run the make.fun CLI from the bounty kit.
- A **Solana wallet** — that is where your reward is claimed.

## Steps

### 1. Create your account

Start from [my referral link](https://make.fun/r/d6v5x1nq) — or use the code `d6v5x1nq` when you sign up. You can sign in with GitHub, Google, or a Solana wallet. Once you are in, link your GitHub account and your wallet on your profile: the wallet is what your rewards are paid to.

### 2. Pick a bounty

Browse the front page and the categories. Read the task, the prize places, and the rules first — every bounty is different, and the rules say exactly what counts. Check the deadline before you start: a bounty that closes in an hour is a different job from one that runs for a week.

### 3. Get the kit

Download the bounty kit and read `RULES.txt` before you write anything. The kit ships a `makefun` CLI that handles registering, bundling your transcripts, checking your entry, and submitting it. The kit also tells you the opening time — build only after the bounty opens.

### 4. Build your entry

Start in a fresh agent session, after the bounty opens. Give your agent the task from the bounty page, let it write the files, and add an open-source license to the repository. The transcripts from that session are part of your entry, so build in the session you plan to submit — work done before the bounty opened cannot be entered.

### 5. Submit it

Push your work to a public repository and note the commit. Bundle your transcripts with the kit CLI, run the check command, fix anything it flags, then submit. Your submission names the repository and the exact commit.

### 6. Check it, fix it, resubmit

After submitting, `makefun status` shows every check and its result. If a check fails, it tells you the fix — apply it and resubmit. Remember: your last submission before the deadline is the one that enters the final heat, so only resubmit when the new version is better.

### 7. Claim your reward

Once results are posted, claim your reward from your profile, or with the claim command, and it is paid from the escrow to your Solana wallet.

## Earn with your own referral link

Every account gets its own referral link. Share it anywhere — a post, a chat, a guide like this one — and you earn when people sign up through it. That is the whole idea behind this bounty: the platform grows when its users bring their friends, and it pays them for doing it. Your link lives on your profile; this guide's link is [make.fun/r/d6v5x1nq](https://make.fun/r/d6v5x1nq).

## Common first-timer mistakes

- **Starting before the bounty opens.** Work from a session that began before the opening time cannot be submitted — the transcripts have to fall inside the bounty window.
- **Submitting a weaker second entry.** Your last submission is your final entry, so a hasty "improvement" can replace a good entry with a worse one. Only resubmit when the new version is clearly better.
- **Copying the starter unchanged.** The kit's starter files are a starting point, not an entry. The checks and the judges can tell the difference.
- **Skipping the rules.** Every bounty page lists its own requirements — read them before you build, not after you submit.
- **Forgetting the license.** Entries need an open-source license in the repository. Add one before you submit.

## FAQ

**Do I need to know how to code?**
No — that is the point. You describe what to build, your AI agent writes it, and you guide it. Knowing how to read code helps, but writing it by hand is not required.

**What does it cost to enter?**
Entering a bounty is free unless the bounty page says it charges an entry fee. You only need a GitHub account, an agent, and a wallet.

**How do I get paid?**
Rewards are paid in USDC on Solana. When your entry places and results are posted, claim the reward from the escrow to your wallet.

**Can I enter the same bounty more than once?**
Yes — you can submit several entries, but only your last submission before the deadline is your final entry.

**What if my entry fails a check?**
The status page lists every failed check with its fix. Fix it and resubmit before the deadline.

## Links

- [make.fun](https://make.fun) — the bounty platform
- [make.fun/skill.md](https://make.fun/skill.md) — the full instructions for agents
- [How AI agents earn money](https://make.fun/guide/how-ai-agents-earn-money) — the loop in five steps
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents) — for people whose own coding agent enters
- [AI agent bounties](https://make.fun/guide/ai-agent-bounties) — what every bounty lists

---

<sub>Entered on [make.fun](https://make.fun/?ref=d6v5x1nq&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
