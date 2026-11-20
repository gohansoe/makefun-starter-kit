# make.fun Starter Kit — From Zero to Your First Bounty

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/gohansoe/makefun-starter-kit/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/gohansoe/makefun-starter-kit/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **New here? Start here.** This kit is a setup checklist and first-steps guide for someone who has never used [make.fun](https://make.fun) before. Follow it top to bottom and you will go from "never heard of it" to "first bounty submitted" without guessing at any step.

**How to use this kit:** work through it in order the first time — prep, account, wallet, GitHub, pick, build, submit. On your second bounty, skip straight to [Step 4](#step-4--pick-your-first-bounty) and use the checklists as a pre-submit sweep. Every checkbox in this guide is there because a beginner has lost time by skipping it.

## Start with my link

If this guide helped you, sign up through my referral link so the signup counts for this kit:

- **Referral link:** https://make.fun/r/pe2c1sg8
- **Referral code:** `pe2c1sg8`
- **Same code as a query:** https://make.fun/?ref=pe2c1sg8

Use the link *before* you create your account. The first referral link your browser sees is the one that sticks, so open it first and sign up in the same session.

---

## Contents

- [What make.fun actually is](#what-makefun-actually-is)
- [The 10-minute version](#the-10-minute-version)
- [Before you sign up: the prep checklist](#before-you-sign-up-the-prep-checklist)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Set up your wallet](#step-2--set-up-your-wallet)
- [Step 3 — Link your GitHub account](#step-3--link-your-github-account)
- [Step 4 — Pick your first bounty](#step-4--pick-your-first-bounty)
- [Step 5 — Build and submit your first entry](#step-5--build-and-submit-your-first-entry)
- [How referrals and rewards work](#how-referrals-and-rewards-work)
- [A realistic first week](#a-realistic-first-week)
- [Mistakes that cost beginners the most](#mistakes-that-cost-beginners-the-most)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)
- [Glossary](#glossary)
- [Links](#links)

---

## What make.fun actually is

make.fun is a bounty platform. People and companies post software work they want built — a small app, a bug fix, a guide, a feature — along with a cash reward for the best entry. Builders (you, plus an AI coding agent if you use one) do the work, submit it, and get paid in USDC on Solana when they place.

Three things make it different from a freelance job board:

1. **You pick the work.** There is no client interview and no proposal. You read the bounty, decide you can build it, and build it.
2. **The reward is posted up front.** You know the prize pool and the placement table before you start.
3. **Entries are checked, not just judged on vibes.** Many bounties run automated checks — tests, transcripts, file rules — so a solid, working entry beats a flashy pitch.

The usual flow is: browse the board → read one bounty carefully → build the deliverable → submit before the deadline → wait for results → claim your reward if you placed.

### Who this kit is for

- You have a GitHub account (or are willing to make one).
- You can write code, or you can direct an AI coding agent that writes code for you.
- You have never entered a make.fun bounty before and want a checklist instead of a wall of docs.

### Who this kit is NOT for

- Anyone looking for a guaranteed payout. Bounties pay winners, not participants. Treat your first entries as practice with upside.
- Anyone who wants someone else to do the work for them. The entry has to be yours.

---

## The 10-minute version

Short on time? Here is the whole kit compressed into five moves:

1. Open https://make.fun/r/pe2c1sg8 and create your account.
2. Connect a Solana wallet — this is where prizes are paid.
3. Link your GitHub account on your profile.
4. Pick an open bounty with a small scope and a deadline at least two days away.
5. Build the deliverable, check it against the bounty's requirements, and submit before the deadline.

Everything below is the careful version of those five moves, with the traps flagged before you step in them.

---

## Before you sign up: the prep checklist

Do this prep *before* you create your account. Ten minutes of prep saves an hour of backtracking later, because several setup steps are easier in the right order.

### Identity and accounts

- [ ] **A GitHub account.** Many bounties require entries as public GitHub repositories, and your GitHub account must be linked to make.fun. If you do not have one, create it at https://github.com/signup and pick a username you are happy to show publicly.
- [ ] **An email address you actually check.** Account notices, reward claims, and deadline reminders go here. Use a real inbox, not a throwaway.
- [ ] **A Solana wallet.** Prizes are paid in USDC on Solana, so you need a wallet address you control. Any standard Solana wallet works — set one up, write down the recovery phrase on paper, and never share it with anyone.
- [ ] **A way to sign in.** make.fun supports sign-in with a Solana wallet, Google, Apple, Discord, or GitHub. Pick the method you will keep using; switching methods later is possible but adds friction.

### Your machine

- [ ] **Node.js 22 or newer** installed, if you plan to use the make.fun command-line kit (`node --version` to check). The kit is a single file and needs nothing else installed.
- [ ] **Git** installed and configured with your name and email (`git --version` to check).
- [ ] **An AI coding agent** if you plan to build with one — Claude Code, Codex, Cursor, or similar. This is optional. You can build by hand, but agents are the normal way people move fast here.
- [ ] **A folder for your work**, for example `~/makefun/`, so entries, wallets, and transcripts do not end up scattered across your desktop.

### Your first-week mindset

- [ ] **Budget your time per bounty.** A bounty with a $20 prize and three days of work in it is a bad first pick. Pick small.
- [ ] **Read the rules before you build.** Every bounty page has its own requirements — file names, formats, size limits, license rules. The requirements are the grading sheet.
- [ ] **Expect your first entry to be practice.** The goal of entry one is learning the loop: read → build → check → submit. Winning comes after the loop is familiar.

---

## Step 1 — Create your account

1. Open my referral link: **https://make.fun/r/pe2c1sg8** (code `pe2c1sg8`).
2. Choose your sign-in method. Signing in with GitHub is the smoothest choice if you already have GitHub, because it links the two accounts in one move.
3. Pick a username. This is public — it shows on the leaderboard and on your entries. Choose something you would put on a CV.
4. Open your profile and confirm what is linked and what is missing. Fix the gaps now, while you have five minutes, not at 23:50 on deadline night.
5. Find the Referrals tab on your profile. That is where your own referral code lives. Copy it somewhere safe — you will share it when you invite others, exactly the way this guide shares `pe2c1sg8`.

> **Why the referral link matters:** a signup only counts for a referrer when the new account binds to their code. Your browser remembers the first referral link it saw, so if you click a friend's link first and mine second, the first one wins. Open the link you mean to use *before* you sign up.

---

## Step 2 — Set up your wallet

Your wallet is how you get paid, so treat this step with care. Nothing here needs money up front — you are only setting up the address that will receive USDC later.

1. **Create or open your Solana wallet.** If you already have one, use it. If not, install a reputable Solana wallet, create a new wallet, and save the recovery phrase offline, on paper, somewhere safe.
2. **Copy your wallet address.** This is the long string of letters and numbers — it is safe to share. Your recovery phrase and private key are not; nobody legitimate will ever ask for them.
3. **Link the wallet to your make.fun account** on your profile, following the sign-in prompt the site shows you. A linked wallet is what lets you sign entry messages and claim prizes to the right place.
4. **Keep a backup.** A wallet you cannot recover is a prize you cannot claim. Paper backup, stored away from your computer, is the minimum.
5. **Never send your private key or recovery phrase to anyone** — not to support, not to another user, not to a form. make.fun staff will never ask for it.

### A note on fees

Submitting an entry does not cost you money. Claiming a prize may involve a tiny Solana network fee, which is normally a fraction of a cent. If any step ever asks you to pay a meaningful amount to "unlock" a reward, stop — that is not how make.fun works.

---

## Step 3 — Link your GitHub account

If you signed in with GitHub, this is already done — verify it on your profile anyway. If you signed in another way, link GitHub now:

1. Go to your profile on make.fun.
2. Find the GitHub linking option and follow it to GitHub.
3. Authorise the connection and come back to make.fun.
4. Confirm your profile now shows your GitHub username.

### Why this step is not optional

- Most bounties take entries as public GitHub repositories. The repository must be owned by the GitHub account linked to your make.fun account, or the entry does not count as yours.
- Your repository must be created *after* the bounty opens. A repo you made last year cannot be entered.
- Your repository needs an OSI-approved license — MIT is the standard choice, and this repository uses it (see `LICENSE`).
- Set the repository's About section on GitHub: add a website pointing at make.fun and the topic `makefun`. This is a small step that several bounties explicitly check.

### Repository hygiene checklist

- [ ] Repository is **public** (private repos cannot be entered).
- [ ] Repository was created **after the bounty opened**.
- [ ] `README.md` is at the **root**, spelled exactly `README.md`.
- [ ] A `LICENSE` file is present (MIT is fine).
- [ ] No `.github/README.md` exists — GitHub would show that one instead of your root README.
- [ ] The About sidebar has a make.fun website and the `makefun` topic.

---

## Step 4 — Pick your first bounty

Choosing well matters more than building fast. A good first bounty teaches you the loop; a bad one burns a weekend.

### The bounty board, decoded

Each bounty card shows a title, a prize pool, a deadline, and a category. Click into any card to read the full page. The full page is the contract: it tells you the deliverables, the exact requirements, the scoring, and the payout.

### How to choose

Score each candidate against this list before you commit:

| Question | Good answer for a first entry |
| --- | --- |
| Is the deliverable clear? | You can describe it in one sentence. |
| Can you finish it in the time left? | Yes, with a day to spare. |
| Do you understand the requirements? | Every line makes sense, or you can look it up in minutes. |
| Is the prize real? | A posted pool with a placement table, not a vague promise. |
| Is the scope small? | One deliverable, not a whole product. |
| Have others entered? | Some entries exist — the bounty is alive — but the field is not enormous. |

### First-bounty picks to prefer

- **Guide and writing bounties.** A clear deliverable, no runtime to debug, and the requirements are usually a checklist of file rules. This is why this kit itself is a guide.
- **Small bug fixes and single features.** One change, one test, one submission.
- **Bounties with a starter kit.** If the bounty ships a kit with a sample and a local check command, use it — the kit tells you exactly what "done" looks like.

### First-bounty picks to avoid

- **Bounties closing in under 24 hours.** You need slack for the check-fix-resubmit cycle.
- **Bounties whose requirements you cannot test locally.** If you cannot verify your entry before submitting, you are guessing.
- **Bounties that need accounts, keys, or paid services you do not have.** Setup debt eats the whole window.
- **The biggest prize on the board.** The biggest pool draws the strongest field. Learn the loop on a small one first.

### Before you build: the five-minute read

1. Read the bounty description top to bottom, once.
2. Read the requirements list a second time, slowly, and write down every file, format, and limit it names.
3. Check the deadline in your own timezone. Write it down with the date.
4. Look at the prize table and the number of entries so far. Decide honestly whether the effort is worth it to you.
5. Download the starter kit if one is provided, and run its check command early — before you write anything — so you know what passing looks like.

---

## Step 5 — Build and submit your first entry

This is the loop you will repeat for every bounty after this one. Learn it once, reuse it forever.

### 1. Set up your workspace

- Create a fresh folder for this entry, separate from your other projects.
- If the bounty ships a kit, download it here and read its rules file first.
- If the bounty ships a command-line tool, run its `--help` and learn the `check` command before you build.

### 2. Build a small version first

- Build the smallest version that satisfies the requirements — the MVP.
- Check it against the requirements list you wrote down in Step 4.
- Only then add polish: better wording, nicer formatting, extra detail.
- Fix the weakest requirement first. If the rules score clarity highest, spend your time on clarity, not on decoration.

### 3. Run the local checks

- Run every check the bounty provides, and fix every failure. A check that reports zero failures is the goal — do not submit while a known failure is open.
- Check file names and sizes yourself: `README.md` exactly, under the size cap; images under their caps; no stray files that would shadow your guide.
- Read your own entry as a stranger would. Open the rendered page and look at the top — that is what other people see first.

### 4. Create the repository and push

1. Create a **new public repository** on GitHub under your linked account, after the bounty opened.
2. Add your deliverable files at the root, plus a `LICENSE` (MIT).
3. Set the About website to the bounty page on make.fun and add the `makefun` topic.
4. Push, then open the repository page in your browser and confirm the README renders the way you expect.
5. If the bounty asks for a screenshot of the repository page, take it now, at normal scale, with the repository name and the start of the README visible at the top — and add it as `screenshot.png` at the root.

### 5. Submit on make.fun

1. Open the bounty page and find the submit flow.
2. Paste your public repository URL.
3. Attach whatever else the bounty asks for — usually the transcripts of the agent sessions that built the entry.
4. Read the confirmation and the status it reports. If it reports a problem, fix it and submit again before the deadline; your most recent submission before the deadline is the one that counts.
5. Note the submission limits: a small number of submissions per day and in total, so do not burn them on untested drafts.

### 6. After you submit

- Leave the repository public and unchanged in ownership. Some bounties re-read it after the deadline — renaming is followed, but deleting it or making it private disqualifies you.
- Keep your referral link live. Signups bound to your code during the window keep counting while the bounty runs.
- Watch the leaderboard, but judge yourself on the loop, not the rank, for your first entry.

---

## How referrals and rewards work

Referrals are the growth engine of make.fun, and this bounty is built on them — so understand the mechanics.

### Your referral link

- Your code lives on the Referrals tab of your profile. Your link is `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun link carries the same code.
- Share the link anywhere people who might like make.fun will see it: your GitHub README, your social posts, a community you are part of.
- Mine is `pe2c1sg8` — https://make.fun/r/pe2c1sg8 — and it is the link this guide asks you to use when you sign up.

### Which signups count

- A signup counts when a new account is created inside the bounty window with your code bound to it.
- The first referral link a visitor's browser saw wins, and it holds for 60 days.
- Only verified human signups count. The same checks that pay referral rewards decide: your own account does not count, signups that share your person or network do not count, idle accounts and bots do not count, and a signup whose reward was rejected never counts.
- Each signup goes through a review hold (about 24 hours) before it is verified. A signup still undecided when the final check closes does not count.

### The prize table for this bounty

This bounty, bring-the-humans-02, shares **$1,000** across the top 50 entries:

| Place | Prize |
| --- | --- |
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

Prizes are paid in USDC on Solana. Winners claim within the claim window with their payout details; unclaimed prizes pass down the standings.

### Referral tips that actually help

- **Write a guide people can use, not an ad.** People sign up from a page that taught them something. That is the whole idea of this bounty.
- **Share where builders already are.** GitHub, dev communities, and coding Discords beat shouting into a general feed.
- **Tell the truth about the platform.** Say what it is, what it pays for, and what it does not promise. A signup who arrives with honest expectations is a signup who stays — and staying is what verification looks for.
- **Do not buy signups, farm accounts, or share a network with your referrals.** The verification check exists for exactly this, and it will cost you the count.

---

## A realistic first week

| Day | Do this |
| --- | --- |
| Day 1 | Finish this checklist: account, wallet, GitHub linked, folders set up. |
| Day 2 | Read three open bounties end to end. Pick one small one. Write down its requirements. |
| Day 3–4 | Build the MVP, run the checks, fix failures. |
| Day 5 | Polish, push to GitHub, screenshot if needed, submit. |
| Day 6 | Share your entry and your referral link where builders gather. |
| Day 7 | Review: what was slow? What check caught you? Write those two answers down — they are your playbook for entry two. |

If you finish the loop once, you can repeat it. Speed comes from the second and third entries, not the first.

---

## Mistakes that cost beginners the most

1. **Building before reading the requirements.** The requirements are the grading sheet. Build to them, not to your idea of the bounty.
2. **Submitting at the last minute.** Checks fail, uploads stall, screenshots come out wrong. Submit with hours to spare so you can fix and resubmit.
3. **A private repository.** The entry must be public. Double-check before you submit.
4. **The wrong README name or place.** It must be `README.md` at the root — not `readme.md`, not in a subfolder, and not shadowed by a `.github/README.md`.
5. **A missing license.** An OSI-approved license is required. Add the MIT `LICENSE` before you push.
6. **Forgetting the referral code.** A guide bounty entry that never names its referral code is refused. Put the code in the README and check it is there.
7. **Copying the starter unchanged.** A starter kit is a starting point. An unchanged copy fails the authorship checks. Write your own guide in your own words — as this kit does.
8. **Chasing the biggest prize first.** The big pools have the strongest fields. Win the loop first, then chase the pool.
9. **Sharing your recovery phrase or private key.** Nobody legitimate asks for it. Ever.
10. **Treating a provisional count as final.** Leaderboard numbers during a bounty are provisional; verified counts are decided in the final check after the deadline.

---

## Troubleshooting

**"I can't link my GitHub account."**
Sign out of make.fun and GitHub, then sign in again starting from make.fun's profile page. If you have two GitHub accounts, make sure the browser is signed into the right one before you authorise.

**"My repository is public but the submit says it isn't mine."**
The repository owner must be the GitHub account linked to your make.fun account. Check which GitHub account is linked on your profile, and which account owns the repository — they must match.

**"My README doesn't render the way I expect."**
GitHub renders GitHub-flavoured Markdown. Preview it on the repository page itself, not only in your editor. Check badge lines are live image links, not inside a code block or an HTML comment.

**"The check reports a failure I don't understand."**
Read the failure message word for word — it usually names the file and the rule. Fix that one thing, re-run the check, and repeat. Do not re-submit until the check is clean.

**"My referral link shows zero signups."**
Signups take time to appear, and verification takes about a day after binding. Also confirm the link people actually clicked carries your code — open it yourself in a fresh browser and check the URL.

**"The deadline is in my timezone — when exactly?"**
Convert the posted deadline (usually UTC) into your local time and write it down. Set a reminder a full day before it, not an hour before it.

---

## FAQ

**Is make.fun free to join?**
Yes. Creating an account, browsing bounties, and submitting entries costs nothing. You only need a wallet to receive prizes.

**Do I need to be a professional developer?**
No. You need to be able to produce what a bounty asks for — code, a guide, a fix — at a quality the requirements accept. Many entrants build with an AI coding agent directing the work.

**Can I enter the same bounty more than once?**
You can submit more than once within the limits (a few per day, a capped total), but your final submission before the deadline is the one that counts. Use resubmissions to fix problems, not to spam.

**What happens if I miss the deadline?**
The entry window closes. Late submissions are not accepted, and late-bound referrals do not count. Put the deadline in your calendar the day you pick a bounty.

**How do I get paid if I win?**
Prizes are paid in USDC on Solana. You claim with your payout details inside the claim window, and the payment goes to the wallet linked to your account.

**Is make.fun the same as makefun.ai or the makefun Python library?**
No. Different projects, different sites. The bounty platform is [make.fun](https://make.fun) — check the domain before you sign in anywhere.

**Can I use this kit's structure for my own guide?**
Yes — that is what a starter kit is for. But write your own words, use your own referral code, and point at your own repository. A copy of someone else's guide is not an entry.

---

## Glossary

- **Bounty:** a posted task with a reward for the best entry.
- **Entry:** your submitted deliverable for a bounty — usually a public GitHub repository.
- **Referral code:** the short code that ties a new signup to you (mine: `pe2c1sg8`).
- **Verified signup:** a new account bound to your code that passed the referral verification checks.
- **MVP:** the smallest version of your entry that satisfies the requirements.
- **Transcript:** the recorded session log of the AI agent that built an entry; many bounties ask for it.
- **USDC:** a US-dollar stablecoin; prizes are paid in USDC on Solana.
- **Escrow:** the on-chain holding where a bounty pool can be locked before winners claim from it.

---

## Links

- [make.fun](https://make.fun) — the bounty board
- [Sign up with my referral link](https://make.fun/r/pe2c1sg8) — code `pe2c1sg8`
- [This bounty: bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02)
- [How it works](https://make.fun/how-it-works)
- [make.fun skill guide for agents](https://make.fun/skill.md)
- [GitHub signup](https://github.com/signup)

---

*Built as a starter kit for brand-new make.fun users. If it helped you get set up, sign up through https://make.fun/r/pe2c1sg8 — code `pe2c1sg8` — and good luck with your first bounty.*
