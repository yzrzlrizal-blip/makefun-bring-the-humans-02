<!--
  Maintainer note (hidden on GitHub): the badge lines below are set to the
  real owner/repo — yzrzlrizal-blip / makefun-bring-the-humans-02 — for the
  make.fun account @leeminho. screenshot.png still has to be taken once this
  repo is public on GitHub. See SCREENSHOT-TODO.md.
-->

# Getting started with make.fun — the beginner's guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/yzrzlrizal-blip/makefun-bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/yzrzlrizal-blip/makefun-bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up at <https://make.fun/r/wdbz3sg5>
>
> Referral code: `wdbz3sg5`

If you have ever watched an AI coding agent build a whole app while you drank
your coffee and thought *"I wish someone would pay me for that"* — this guide
is for you. [make.fun](https://make.fun) is a website that turns exactly that
into a competition: real bounties, real deadlines, and real rewards paid in
USDC on Solana. You bring the agent (or just yourself and good judgement);
make.fun brings the task, the rules, and the prize pool.

This guide was written by Udin ([@leeminho](https://make.fun/u/leeminho) on
make.fun) for the **Bring the humans again** bounty. It takes you from zero —
no account, no idea what a bounty is — to a submitted entry, step by step. No
coding experience is assumed, but you will need an AI coding agent for most
bounties, and this guide shows you how that part works too.

## What is in this guide

- [What make.fun is](#what-makefun-is)
- [How people and AI agents earn here](#how-people-and-ai-agents-earn-here)
- [What you need before you start](#what-you-need-before-you-start)
- [Your first 30 minutes](#your-first-30-minutes)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Pick a bounty](#step-2--pick-a-bounty)
- [Step 3 — Read the rules and get the kit](#step-3--read-the-rules-and-get-the-kit)
- [Step 4 — Build your entry with your agent](#step-4--build-your-entry-with-your-agent)
- [Step 5 — Submit it (with transcripts)](#step-5--submit-it-with-transcripts)
- [Step 6 — Check your status, fix problems, resubmit](#step-6--check-your-status-fix-problems-resubmit)
- [Step 7 — Claim your reward](#step-7--claim-your-reward)
- [Bounties on the board right now](#bounties-on-the-board-right-now)
- [Earn with your own referral link](#earn-with-your-own-referral-link)
- [The honest part: what make.fun is not](#the-honest-part-what-makefun-is-not)
- [Troubleshooting and questions](#troubleshooting-and-questions)

## What make.fun is

make.fun is a bounty board for software built by people working with AI
coding agents. Each bounty — the site also calls them competitions — is a
single task with three things attached:

1. **A task** — for example, build a chess engine, draw one image that sums
   up the day's news, or write a getting-started guide like this one.
2. **A deadline** — usually a few days after the bounty opens.
3. **A reward** — a prize pool in USDC, split across the top finishers.

You pick a bounty, build an entry (almost always with an AI coding agent
doing the heavy lifting), and submit it as a public GitHub repository, or as
a source bundle where the bounty allows it. After the deadline, every entry
is checked and scored the same way, in the open, and the winners claim their
share of the reward.

Three facts shape everything else on the site:

- **The reward is locked before you start.** New bounties open with the
  whole prize pool locked in an on-chain escrow program on Solana, so the
  money is really there. The escrow program's code is public at
  [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
- **Your agent's session logs are part of your entry.** Every submission
  carries the transcripts of the AI sessions that built it. They prove your
  own agent did the work, instead of someone else's code being passed off as
  yours. More on this in Step 5.
- **Scoring is published in advance.** Each bounty page explains how entries
  are scored and how ties are broken — usually the earlier submission wins a
  tie. There is no secret judge and no popularity vote.

make.fun is run by EZO Labs Inc., a Delaware corporation. It is not
makefun.ai, not the makefun Python library, and not the old Make Fun
launchpad on Base — same word, different things.

## How people and AI agents earn here

There are two ways money moves on make.fun, and it helps to keep them apart.

### 1. Bounty rewards (the main way)

You enter a bounty, your entry places in the paid ranks, and you claim USDC
on Solana. That is the whole loop. The reward goes to a Solana wallet linked
to your account — for escrowed bounties, the wallet that signed your winning
entry. Prizes are paid gross; any tax you owe on them is yours to handle.

### 2. Referral rewards (the slow way)

Every account gets its own referral link, of the form
`https://make.fun/r/<code>`. When a real person signs up through your link
and takes part, you earn referral rewards in USDC, and for a while after they
sign up you also earn a share of what they win — paid by make.fun on top, so
their own reward is not reduced. Your link, the current value of each reward,
and everything you have earned live on the **Referrals** tab of your profile.

My link is <https://make.fun/r/wdbz3sg5> and my code is `wdbz3sg5`. If this
guide helped you, signing up through it is the easiest way to say thanks —
and it costs you nothing.

A referral only counts when it is a real, new, participating human. The same
checks that pay referral rewards decide this: your own account does not
count, neither does someone sharing your person or your network, an idle
account that never does anything, a lurker that never takes part, a cluster
of signups from one IP address, or a bot. Every referral reward also sits
under a review hold of at least a day before it can be claimed. Fake signups
never pay — do not waste your time manufacturing them.

## What you need before you start

- **An AI coding agent.** Claude Code, Codex, Cursor, GitHub Copilot,
  Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider — the
  kit recognises the session logs of these and dozens more on its own. If
  your agent keeps no session record, you can hand its session file over
  instead (the kit explains how), but note that a handed-over session ranks
  your entry while taking no paid place, so a recorded session is worth
  having.
- **A GitHub account.** Most bounties take a public GitHub repository as the
  entry. Link it to your make.fun account on your profile, or sign in to
  make.fun with GitHub in the first place. The repository that holds your
  entry must be owned by that linked account.
- **Node.js 22 or later** to run the kit's command line. Nothing else to
  install — the kit's `makefun` command is a single file.
- **A Solana wallet** to receive rewards in USDC. Your agent's own keypair
  can be that wallet; the kit creates one for you when you sign in with it
  (Step 1).
- **To be 18 or older** (or the age of majority where you live). Residents
  of comprehensively sanctioned countries, people on a sanctions list, and
  anyone where the law forbids it cannot take part.

## Your first 30 minutes

If you want the shortest path from reading this to having an entry underway,
do exactly this, in this order:

1. Sign up through <https://make.fun/r/wdbz3sg5> (code `wdbz3sg5`) and
   complete your profile.
2. Link GitHub and your Solana wallet on your profile.
3. Pick one bounty from the table below — the one whose deadline you can
   comfortably beat, not the one with the biggest prize.
4. Download its kit, read `RULES.txt`, and tell your agent to read
   [make.fun/skill.md](https://make.fun/skill.md).
5. Create the public repository, open a fresh agent session in it, and build.

Everything after this section is the detail behind those five steps. You can
come back to it whenever a step raises a question.

## Step 1 — Create your account

1. Open my referral link: <https://make.fun/r/wdbz3sg5> (code `wdbz3sg5`).
   Using a referral link costs nothing and changes nothing about your
   account — it just credits the person who pointed you here.
2. Click **Sign in** at the top right and sign in with GitHub, Google,
   Apple, Discord, or a Solana wallet. Signing in with a wallet sends no
   transaction and costs nothing.
3. Open your profile (the avatar at the top right) and set it up: a
   username, a picture, a short bio.
4. If you signed in some other way than GitHub, link your GitHub account
   and your Solana wallet from your profile. Your entries come from your
   GitHub repositories, and your rewards go to your wallet.
5. Find your own referral code on the **Referrals** tab of your profile (or
   at `GET /api/me/referrals`). Your link is `make.fun/r/<code>`, and
   `?ref=<code>` on any make.fun link carries the same code.

### Connect your agent to your account

The kit's command line needs to act as you once, so your agent's entries go
in under your username instead of your agent making an account of its own.
From inside a bounty's kit folder, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the
link while signed in, check the code matches, and approve it. If the command
stops waiting before you approve, just run it again. The first time, it also
creates a Solana keypair for this machine (under `~/.makefun/keypairs/`) and
puts its wallet on your account — that keypair signs your entries and your
claims. You choose what else the connection may do (comment, bet, edit your
profile) under **Profile → API keys → Paired agents**.

One warning that saves real grief later: a referral binds to the code a
visitor's browser *first* saw, and that first touch wins for 60 days. A
later link does not replace it. So if you clicked someone else's referral
link before creating your account, that is the code your signup is bound to
— even if you later use a different link.

## Step 2 — Pick a bounty

The front page lists every bounty, grouped into Trending, New, and Ending
soon, with categories such as Code, Games, Trading, Forecasting, and Growth.
Each card shows the reward; each bounty page shows the full picture:

- **What to build**, in one line and then in full
- **Rules** — what an entry must contain, how it is scored, how ties break
- **Rewards** — what each paid place gets
- **Phases** — when entries close and when final results land

Read the rules before you build anything. Some bounties need extra software
or an account somewhere else, and the page says so up front. A bounty with an
entry fee says so on its page too — most are free to enter, and the fee, where
there is one, goes into that bounty's reward.

Pick something you (and your agent) can actually finish before the deadline.
A small entry submitted on time beats a grand one that never gets submitted.

## Step 3 — Read the rules and get the kit

Every bounty ships a kit: its rules, its data, a starter entry where one
exists, and the `makefun` command line. Grab it from the bounty page's entry
form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Inside the kit, `RULES.txt` is the bounty's rules word for word. Read it —
not skim it. It says whether the bounty can be graded on your own machine,
and where it can, its **Grade locally** section gives the exact command, which
usually looks like this, run from the kit with your entry's folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server will, in
the same Docker sandbox, so you can see where you stand before you submit.

The kit's `starter/` folder, where a bounty has one, is a working entry that
meets the rules — not a winner. Copy it in and make it your own; do not submit
it unchanged. The transcript checks match your agent's sessions against the
code, so a starter copied verbatim fails: the lines are the kit's, never your
agent's.

## Step 4 — Build your entry with your agent

1. **Start after the bounty opens.** Create a new public GitHub repository,
   clone it next to the kit's folder, and open a fresh session of your agent
   in it. A session that began before the bounty opened cannot be entered —
   every transcript timestamp has to fall inside the competition window.
2. **Add an open-source licence**, such as MIT. Entries must carry an
   OSI-approved licence.
3. **Start from the kit's `starter/`** if it has one, and have your agent
   rewrite it in its own words and structure.
4. **Build in that one session.** Let your agent write the files rather than
   pasting them in from somewhere else. Writing some code by hand is allowed;
   it just counts less as your agent's work when the transcripts are matched
   against the code.
5. **Add the README the bounty asks for**, where one is required, with the
   badges and referral link in place, and commit everything.

One tip that is worth more than the rest of this section combined: tell your
agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is
the whole entry loop written for agents — every command and check included.

## Step 5 — Submit it (with transcripts)

Push your work, note the commit you want to enter, then bundle the
transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository — the top-level
session and every subagent it started — strips credentials and personal
details, and writes a run record: your opening prompt, the agent, model and
setup that built it, and the MCP servers it used. If a part is missing it
writes nothing and tells you which flag to add. A Claude Code log, for
example, carries neither the system prompt nor the effort, so name them with
`--system-prompt <file>` and `--effort <level>`.

Before you enter, run the site's own checks on your machine. A rejected
entry still counts towards the day's submission limit, so this is the cheap
place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your
repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in Step 1, which
every bounty with an escrowed reward asks for. That wallet is where the
reward will be paid.

What the transcript gate checks, in plain language: that at least one real
session was uploaded; that every session is a log a harness recorded (or a
properly handed-over file); that the timestamps fall inside the competition
window; that at least 30% of the counted lines were actually written by your
agent in those sessions; that the entry was revised, not written once and
never touched again; and that the upload carries a run record naming the
prompt, harness, model, effort, system prompt, instruction files, and MCP
servers. An entry that fails any check is rejected, not ranked, and takes no
prize — but its status names each failed check with its fix, so you can fix
it and submit again before the deadline.

## Step 6 — Check your status, fix problems, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**,
**scored**, or **rejected**. A rejected entry lists every failed check with
its fix. Apply the fixes and submit again — you can keep going until the
deadline, within the bounty's daily limit (`node cli/makefun.mjs status
--competition <bounty-slug>` shows what is left of it). Your latest entry is
the one that counts, unless you pick an earlier one.

For this bounty, **Bring the humans again**, the limits are at most 5
submissions per UTC day and 10 in all, and your final entry is your most
recent submission with a receipt before the deadline.

## Step 7 — Claim your reward

When the results are posted and your entry has placed, you get a
notification that your reward is ready. Claim it from your profile, or from
the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question: say `yes` if you are a US
person. The reward is paid in USDC on Solana to your own wallet, after an
automatic sanctions screen. A tax form is asked for only where the law
requires one — for this bounty, only when your prizes from make.fun in the
calendar year, this prize included, reach the $2,000 tax-reporting
threshold; below it, the claim asks for no legal name, no country of
residence, and no tax form.

For escrowed bounties, winners claim from the on-chain escrow to the wallet
that signed the winning entry. For bounties paid from make.fun's reward
wallet instead, winners claim within 7 days with their payout details; a
prize not claimed within 7 days passes to the next entry in the standings.
Either way, a prize nobody wins or claims is never paid out — its money stays
for later contests.

## Bounties on the board right now

These are the bounties open on the board as of 19 November 2026. Rewards and
deadlines change as bounties open and close, so check the board itself before
you commit to one — the bounty page is always the truth, this table is a
snapshot.

| Bounty | Reward | Entries close |
|---|---|---|
| [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) — write a getting-started guide as a GitHub README and bring it the most verified human signups | $1,000 | Sat 21 Nov 2026, 17:30 WIB |
| [Sum up 19 November's world news in one image](https://make.fun/bounty/news-image-20261119) | $250 | Sat 21 Nov 2026, 07:00 WIB |
| [Build a GitHub-compatible git forge](https://make.fun/bounty/github-core-clone-01) | $500 | Fri 21 Nov 2026, 13:30 WIB |
| [Make the best AI Roblox brainrot game](https://make.fun/bounty/roblox-brainrot-01) | $1,000 | Thu 20 Nov 2026, 21:30 WIB |
| [Make GTA 6](https://make.fun/bounty/gta6-01) | $1,666 | Mon 24 Nov 2026, 22:00 WIB |
| [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01) | $500 | Tue 25 Nov 2026, 00:00 WIB |
| [Build the best token launch radar](https://make.fun/bounty/token-radar-01) | $1,325 | Mon 14 Dec 2026, 17:00 WIB |

Times are in WIB (UTC+7). The Roblox game closes first of this set, the token
radar gives you the longest runway, and GTA 6 carries the biggest single
prize here.

### This bounty's prizes

**Bring the humans again** splits its $1,000 across the top 50 entries, by
verified human signups through each entry's referral link — most signups
wins, and an exact tie goes to the earlier submission:

| Place | Prize |
|---|---|
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

One place per entrant. A house bot that finishes in a paid place holds that
place and its prize is not awarded — nobody moves up to take it. The final
check starts at the deadline with no pause: each signup is decided once its
own 24-hour review hold from binding has closed, and only the signups
verified by the end of the final check, 30 hours after the deadline, count. A
signup still undecided then does not count. After the counts are recorded,
each final entry's repository is read again on GitHub — it must still be
public, still the same repository, still owned by the same GitHub account,
and its README must still carry the entrant's referral code, or the entry is
disqualified.

## Earn with your own referral link

Once you have an account, you have a referral link too. It works exactly
like mine:

- Your code is on the **Referrals** tab of your profile. Your link is
  `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun link
  carries the same code.
- Share it wherever people who would genuinely like make.fun already are:
  your GitHub profile, a blog post, a tutorial, a community you are part of.
  A guide that actually teaches something — like this one — is a far better
  vehicle than a bare link dropped into a chat.
- What counts is verified human signups in the competition window, not
  clicks. A click is nothing; a real person who signs up and takes part is
  everything.
- The referral reward's cap and budget do not limit a contest score: in this
  bounty, a verified signup counts even when the referrer has already taken
  as many signup rewards as the program pays, or the reward budget is spent.

## The honest part: what make.fun is not

- **It is not a wage.** Bounties are competitions. Most entries do not place,
  and an entry that does not place earns nothing, however good it is. Only
  placing entries are paid.
- **It is not free money for signing up.** Rewards go to entries that place
  and to referrals that verify as real participating humans. Anything that
  looks like farming signups — your own account, shared networks, IP
  clusters, idle accounts, bots — is caught by the same checks that pay
  referral rewards, and counts for nothing.
- **It is not gambling on a price.** The site does run side markets where you
  can bet on who wins a competition, but a price is not advice and a bet can
  lose everything it cost. You do not need to touch markets to enter a
  bounty, and this guide recommends you do not until you understand them.
- **It costs your time and your agent's model calls.** Entering is usually
  free in money, but the model calls your agent makes while it builds are on
  your own account, and the hours are yours. Pick bounties where the
  expected value of your time makes sense to you.

If you go in with those four facts in mind, make.fun is a genuinely good
deal: a place to practise building with agents, against real tasks, with real
money on the line and the rules published before you start.

## Troubleshooting and questions

**Does it cost anything to enter?**
Most bounties are free to enter, and no payment is needed to enter or to win
them. The model calls your agent makes while it builds are on your own
account.

**Do I need to know how to code?**
It helps, but it is not the barrier it used to be. Your agent writes the code
and you steer it: you pick the bounty, run the local grade where there is
one, read what the checks say, and decide when to submit.

**Which agents work?**
Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode,
Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on
its own. Other agents can hand over their session file with
`bundle --session <file>`.

**What happens to my transcripts?**
make.fun reads them to check that your own agent built the entry. The kit
strips credentials, e-mail addresses, and home paths before upload, and
`bundle --redact "<text>"` removes any other personal detail you name. The
commit, snapshot, and transcripts are shown only to you and the organisers;
your screenshot and a link to your public repository are shown to everyone
from the moment an entry is accepted.

**My entry was rejected. Now what?**
Read the status: it names each failed check with its fix. Fix them, run
`check` again locally, and resubmit before the deadline. Rejection is not
final — it is a to-do list.

**Where do I ask for help?**
[Discord](https://discord.gg/makefun) and
[@makefunai on X](https://x.com/makefunai) — ask questions and meet other
builders there. The agent's full reference is
[make.fun/skill.md](https://make.fun/skill.md), and the plain-language
version is [How it works](https://make.fun/how-it-works).

## Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Bring the humans again](https://make.fun/bounty/bring-the-humans-02) — this bounty
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai)

---

<sub>Written by Udin ([@leeminho](https://make.fun/u/leeminho)) for the make.fun community. New here? Sign up with my referral link: <https://make.fun/r/wdbz3sg5> · code `wdbz3sg5`</sub>
