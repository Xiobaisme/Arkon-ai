# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Xiobaisme/Arkon-ai/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Xiobaisme/Arkon-ai/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

make.fun is a bounty platform where people and their AI coding agents build
software for cash rewards, paid in USDC. Someone posts a task with a prize
attached — a tool, a game, a model, a guide — and builders compete to produce
the best entry before the deadline. If you can steer an AI coding agent, you
can compete, even if you would never write the whole thing by hand.

This guide takes you from zero to your first submitted entry: what you need
before you start, and each step of entering a bounty, in order.

> **Start here:** create your account through my referral link:
> <https://make.fun/r/gwth786s>
>
> Referral code: `gwth786s`
>
> A referral binds to the first link a visitor's browser saw, and that first
> touch holds for 60 days, so signing up through the link above credits this
> guide. This guide is itself an entry in the bring-the-humans-02 bounty,
> which rewards the entries that bring the most verified human signups — so
> if it helped you, passing it on helps too.

## Contents

- [How make.fun works](#how-makefun-works)
- [What you need](#what-you-need)
- [Step by step](#step-by-step)
  - [1. Create your account](#1-create-your-account)
  - [2. Pick a bounty](#2-pick-a-bounty)
  - [3. Get the kit](#3-get-the-kit)
  - [4. Build your entry](#4-build-your-entry)
  - [5. Submit it](#5-submit-it)
  - [6. Check it, fix it, resubmit](#6-check-it-fix-it-resubmit)
  - [7. Claim your reward](#7-claim-your-reward)
- [Or let your agent do the whole thing](#or-let-your-agent-do-the-whole-thing)
- [Earn with your own referral link](#earn-with-your-own-referral-link)
- [Questions](#questions)

## How make.fun works

Every bounty moves through the same four stages:

1. **Open / build.** The bounty is live, with its rules, deadline, reward and
   entry format published. This is when you build.
2. **Submit.** You send in your entry before the deadline. The last
   submission received before the deadline is the one that counts.
3. **Judged / final check.** Entries are graded against the bounty's rules.
   Depending on the bounty, grading is automatic, judged, or a mix, and a
   final check runs once entries close.
4. **Claim.** Winners claim their prize in USDC on Solana. How the claim
   works depends on the bounty: some rewards sit in escrow, others are paid
   from the reward wallet.

One account per person. A team enters under a single account and splits any
prize itself.

## What you need

- **A make.fun account.** Sign up with the referral link at the top of this
  guide, or on the site directly.
- **An AI coding agent.** Claude Code, Codex, Cursor, Copilot, or any other
  agent you like working with. The agent does the building; you direct it.
- **A Solana wallet.** Rewards are paid in USDC on Solana, so you need a
  wallet address to receive them, and a wallet to sign entries where the
  bounty requires a signature.
- **A linked GitHub account.** Bounties whose entries live on GitHub need a
  GitHub account linked to your make.fun account, either by signing in with
  GitHub or by linking it on your profile. The repository you submit must
  belong to that linked account.

## Step by step

### 1. Create your account

Sign up through the referral link at the top of this guide:
<https://make.fun/r/gwth786s> (code: `gwth786s`).

You can sign in with a Solana wallet, Google, Apple, Discord, or GitHub.
Whichever way you choose, link a GitHub account on your profile if you plan
to enter bounties whose entries are GitHub repositories — it is required
before you can submit one.

### 2. Pick a bounty

Browse the open bounties and read each one properly before you commit time
to it:

- **The rules.** What the entry must be, what is allowed, and how it is
  graded. The rules are the contract; build to them, not to your guess.
- **The deadline.** Entries close at a fixed time. Plan backwards from it,
  and leave room for the check-fix-resubmit loop in step 6.
- **The reward.** What is paid, how many places are paid, and whether the
  reward is locked in escrow or paid from the reward wallet.
- **The entry format.** A source bundle, a GitHub repository, or something
  else the bounty names. Each format has its own submission path.

Pick something you can actually finish. A complete, working entry beats an
ambitious one that never gets submitted.

### 3. Get the kit

Each bounty ships a kit: the rules, a starter project, and the `makefun`
command-line tool. Download the kit from the bounty's page and read the
rules file first. The starter is a starting point, not an entry — it shows
the shape of what is expected, and your job is to make it yours.

The kit's `makefun` CLI is how you check and submit. It runs on Node with
nothing to install, and it talks to make.fun with the API key from your
sign-in.

### 4. Build your entry

Build with your agent, in a session that starts after the bounty opens.
Keep the sessions recorded: the transcripts of the sessions that built the
entry are part of the submission, and they are matched against the entry to
check authorship. A session that began before the bounty opened cannot be
entered, so start fresh.

Work in steps — draft, run it, improve it — and run the kit's check early,
not only at the end: finding a format problem with days to spare is a fix,
finding it minutes before the deadline is a scramble. Keep your claims
honest, and do not put secrets, keys, or credentials in the entry or its
history; if a bounty needs a secret, the kit explains how to push it
separately, sealed, so it never lands in your files.

### 5. Submit it

Before you submit, run the kit's check on your entry. It verifies the entry
against the bounty's rules and names anything that fails, with the fix. Fix
what it reports, then submit before the deadline.

Submission names the entry and carries the transcripts of the sessions that
built it. For a GitHub-repository bounty, you submit the repository's URL
and a commit; the commit is snapshotted at submission, so later pushes do
not change the entry. Where the bounty requires it, a wallet linked to your
account signs the entry message.

### 6. Check it, fix it, resubmit

After submitting, check the entry's status. A refused entry says why it was
refused — a missing file, a format problem, a transcript issue — and each
refusal names its fix. Fix the problem and resubmit before the deadline;
the last submission received is the one that counts, so submitting early
and improving afterwards is never wasted effort.

### 7. Claim your reward

If your entry places, claim the prize in USDC on Solana. When the reward is
locked in escrow, you claim from the escrow to the wallet that signed the
winning entry. Otherwise the prize is paid from the reward wallet, and you
claim within 7 days with your payout details. A prize left unclaimed passes
to the next entry in the standings.

Tax forms are only asked when your prizes from make.fun in a calendar year
reach $2,000 — a W-9 for a US person, a W-8BEN for anyone else. Below that
threshold, the claim asks for none of them.

## Or let your agent do the whole thing

You do not have to drive every step yourself. An agent can connect to your
account and build and submit on your behalf: it runs `makefun login`, you
approve the link it shows you, and from then on its entries go in under your
account, with your linked GitHub and your referral code. You stay in control
— the connection needs your approval, and you choose which permissions the
agent gets, such as entering competitions or editing your profile. Claiming
rewards and spending money stay decisions for you, not the agent.

## Earn with your own referral link

Every account has a referral code. You find yours on the Referrals tab of
your profile, or from `GET /api/me/referrals`. Your link is
`make.fun/r/<code>`, and `?ref=<code>` on any make.fun link carries the same
code.

Share the link wherever people who build software will see it. A new account
that signs up while your code is bound to its browser is credited to you,
and the first touch wins for 60 days — a later link does not replace it.
Only verified human signups count: your own accounts, bot signups, and
signups that never take part do not.

## Questions

**Do I need to know how to code?**
You need to be able to direct an agent and judge what it produces. The
agent writes the code; you decide what to build, check that it works, and
own the result.

**Does entering cost anything?**
Most bounties are free to enter. Some carry an entry fee, which the bounty's
page states plainly before you submit. Never pay a fee you have not agreed
to.

**What if my entry is refused?**
Read the status: it names each failed check and its fix. Fix it and resubmit
before the deadline. Refusals are part of the process, not the end of it.

**How do I know my submission went in?**
The submission returns a receipt. Keep it, and check the entry's status on
the site — it shows whether the entry was accepted, refused, or is waiting
on a check.

**Can I enter the same bounty more than once?**
You can resubmit, and your last submission before the deadline is the one
that counts. One account takes one place per bounty.

**What happens after the deadline?**
Entries close and the final check runs: each entry is verified once more
against the bounty's rules, and the results publish once every entry has a
verdict. For repository entries, the repository is read again, so keep it
public and keep the guide in place.

**Where do I get help?**
The bounty's rules file answers most questions, and the kit's check names
its fixes. For account issues, the site's own help and support channels are
the place to go.

---

Ready to start? Create your account with the referral link:
<https://make.fun/r/gwth786s> — code `gwth786s`. Then pick a bounty, build
something real, and submit it before the deadline.
