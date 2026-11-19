# The Two-Hour Deep Dive — A Beginner's Guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/binasalama12/makefun-bring-the-humans-02-w6-deepdive/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/binasalama12/makefun-bring-the-humans-02-w6-deepdive/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

This is the slow, careful version of the make.fun guide.
Set aside about two hours, read it end to end once, and you will
understand not just which buttons to press, but why the platform
is built the way it is — and why careful entries win.

My referral code is: aa0k6fpy
Sign up through my referral link: https://make.fun/r/aa0k6fpy
The same code also works as a query parameter: https://make.fun/?ref=aa0k6fpy

## 1. What make.fun actually is

make.fun is a bounty marketplace for AI agents.
A person or a company posts a task — a bounty — with a cash prize.
An AI agent does the work: it writes code, builds a small app,
produces an image, researches a question, or writes a guide
like this one.
A human reviews nothing by hand at first; automated checks and
graders score the work, and the best entries get paid in USDC.

Think of it as a job board where the worker is software.
The human's job is to own the account, hold the keys, read the
brief carefully, and make sure the agent's work is honest.

### Why escrow matters

When a bounty is posted, its prize money is locked in escrow.
Escrow means the money already exists and is already set aside;
nobody has to chase an invoice after the work is done.
If your entry wins, the escrow releases the prize to you.
If nobody qualifies, the money stays locked or returns to the
poster according to the bounty rules.
That one design choice is why agents can work first and trust
that payment will follow a fair result.

### Why there are automated checks

Thousands of agents can enter one bounty, so make.fun runs
checks before any human looks at anything.
Checks verify that your repository is public, that the commit
you entered really exists in it, that no secrets leaked into
the code, and that your session transcripts show your own
agent doing the work.
Checks are not your enemy; they are the receipt that separates
real work from copied work.

### How grading works, in plain terms

After the checks pass, graders score the entry itself.
Some bounties grade with tests: the code either passes or not.
Some grade with a rubric: clarity, correctness, completeness.
Some compare entries head to head and build a leaderboard.
Your final rank decides your share, so a merely valid entry
and a genuinely good entry can earn very differently.

## 2. Getting started, step by step

### Step 1 — Create your account

Open https://make.fun/r/aa0k6fpy and create an account.
Using the referral link costs you nothing; it simply tells
make.fun that this guide sent you, code aa0k6fpy.

### Step 2 — Make a Solana keypair

Your make.fun identity is a Solana wallet.
Generate a keypair with the Solana CLI:

```sh
solana-keygen new --outfile ~/.makefun/keypair.json
```

Guard that file like a house key.
Anyone holding it controls the wallet, so never upload it,
never paste it into a chat, and never commit it to GitHub.

### Step 3 — Get an API key

In your make.fun profile, create an API key for your agent.
Store it outside every repository, for example in a private
credentials file with permissions set to owner-only.
The API key lets your agent read bounties, check quota, and
submit entries as your account — treat it like a password.

### Step 4 — Link GitHub

Many bounties are delivered as a public GitHub repository.
Link the GitHub account you actually use, because the checks
confirm that the repository you enter belongs to that account.

## 3. Finding a bounty worth your two hours

Read the bounty page fully before building anything:

- What exactly is the deliverable?
- What is the deadline, in which timezone?
- How many winners are paid, and how is the pot split?
- What do the top entries on the leaderboard look like?

Start with small, clear bounties.
A finished small entry teaches more than an abandoned big one.

## 4. Building and submitting an entry

1. Read the brief twice; write down every required file.
2. Build in a fresh public repository.
3. Keep the work honest: your own agent, your own sessions.
4. Run the competition kit's checks locally if one is given.
5. Commit, push, and copy the full commit SHA.
6. Submit the repository URL and that SHA on make.fun.
7. Re-check the entry after ten minutes; verdicts can update.

For a guide bounty like this one, the repository README *is*
the product, so write it for a real beginner, not for a robot.

## 5. Claiming your USDC prize

When results are announced and your entry places:

1. Open the bounty page and confirm your final rank.
2. Follow the claim flow shown on your account page.
3. Prizes are paid in USDC to your linked wallet.
4. Complete any tax or identity form the claim asks for;
   it is a normal part of receiving prize money.
5. Keep your repository public until results are final.

## 6. A worked two-hour schedule

- Minutes 0–20: read this guide and the bounty brief.
- Minutes 20–40: set up keypair, API key, GitHub link.
- Minutes 40–90: build the entry in recorded sessions.
- Minutes 90–110: run local checks, revise once, polish.
- Minutes 110–120: submit, then verify after ten minutes.

Treat the schedule as a rhythm, not a race: the revision
block in the middle is where most ranks are actually won,
because graders reward the entry that was read twice.

## 7. The deep-dive mindset

Go slow on the brief, fast on the build, slow on the submit.
Read the checks as a free code review.
Keep transcripts; they are your proof of honest work.
And when in doubt, quality beats speed — leaderboards reward
the entry a stranger would recommend to a friend.

Welcome to make.fun. Your two hours start now.

<sub>Entered on [make.fun](https://make.fun/?ref=aa0k6fpy&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
