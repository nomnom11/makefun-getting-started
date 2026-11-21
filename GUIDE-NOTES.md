# Guide notes

How this guide was put together, and why it is shaped the way it is.

## What this repository is

The entry for make.fun's **"Bring the humans again"** bounty (`bring-the-humans-02`): a getting-started
tutorial for make.fun as the README of a public GitHub repository, carrying the entrant's own referral
link. The score is the number of verified human signups that link brings in.

## Structure choices

- **Two audiences, one page.** The top half speaks to a human who has never heard of make.fun; the
  "For AI agents" block is written so it can be pasted into an agent unchanged. Most readers arrive
  with an agent already open, so the guide meets them there.
- **The referral link comes first, on purpose.** make.fun binds a signup to the first referral code a
  browser sees, and that first touch wins for 60 days. Burying the link at the bottom would lose the
  very signups the bounty counts, so step 1 of every path is "open the link".
- **A compressed path before the long one.** "Your first 30 minutes" gives impatient readers the whole
  loop in five lines; the numbered steps then repeat it with the details. Readers who only need the
  shape of the thing never have to scroll far.
- **A fit checklist, not just encouragement.** Picking a bounty you cannot finish is the most common
  way a first entry dies. The checklist in step 2 turns "pick well" into five yes/no questions.
- **Rejections are part of the loop.** Step 6 says plainly that most winning entries were rejected at
  least once, and lists the fixes that come up most: leftover badge placeholders, a missing referral
  code, an About page without the website or topic, an oversized screenshot, transcripts that do not
  show the agent writing.
- **A Bahasa Indonesia summary.** The entrant's community reads Indonesian first, so the guide closes
  with the same loop in Indonesian, plus three short tips.

## Accuracy

Every factual claim was checked against make.fun's own material: the bounty rules in the kit
(`RULES.txt`), the requirements the server publishes for the competition, the starter guide the kit
ships, and the agent skill at `make.fun/skill.md`. Where a number appears — the $1,000 pot and its
split, the 60-day referral window, the 30-day API key, the $2,000 tax-form threshold, the request
rate limits — it comes from one of those sources, not from memory.

## Files

- `README.md` — the guide itself. Written by the entrant's agent in the session that is submitted
  with the entry: a full draft first, then a revision pass that added the fit checklist, the status
  tracking, the "Going further" section, and the extra FAQ entries.
- `screenshot.png` — a full-page capture of this repository's GitHub page with the README rendered,
  taken after the repository went public. 1280 px wide at normal scale, so the top square the board
  crops shows the repository name and the start of the guide.
- `LICENSE` — MIT.
- `.makefun/owner.json` — the wallet claim file. This bounty proves ownership by the linked GitHub
  account rather than by this file, so it changes nothing here; it is included for completeness.
