# Contributing

This list has one job: help a normal person, under stress, make the right move fast. Every contribution is judged against that job.

## The inclusion bar

An entry gets in only if it clears **all** of these:

1. **Actionable by a non-technical person.** If using it requires a command line, a developer account, or a computer-science vocabulary, it belongs in a different list.
2. **Primary source only.** Link to the tool's own site or the official government page — never a review roundup, a download mirror, or a blog post about it.
3. **Honestly priced.** Tag it `Free`, `Freemium` (the free tier must be genuinely usable, not a 7-day trial funnel), or `Paid`. If the price model changed, that's a bug worth a PR.
4. **No affiliate or referral links.** Ever. A recommendation you get paid for is an ad, and ads are how people get scammed.
5. **It earns its place.** One line must be enough to say what it does and why it beats doing nothing. "Also exists" is not a reason.

## What gets rejected

- Tools that demand sensitive data up front (SSN, full bank login) without a regulatory reason to exist.
- Anything crypto-yield, "recovery agent," or fee-for-fraud-recovery — the second-order scams that hunt victims of the first one.
- Browser extensions or apps with a history of selling user data, unless the entry is a warning.
- Dead links, abandoned tools (no update or response in 18+ months), and region-locked services without a region note.

## Entry format

```markdown
- **[Name](https://primary-source.example)** — What it does, in one plain sentence, ending with the action it enables. `Free`
```

- Plays (actions and rules, not tools) start with 📋 and link only when an official page exists.
- Keep the line under ~40 words. If it needs a paragraph, it's two entries or it's out.
- New sections need an issue first — sections are promises, and this list keeps its promises few and kept.

## The border rule

Three sister lists stay in their lanes. If your entry is about the *long fight* — disputes, complaints, opt-outs, rights — it belongs in **Consumer Revenge Kit**. If it's a veteran-specific benefit or program, it belongs in **Veteran Arsenal**. Cross-list entries live in exactly one home and get linked, not copied.

## Maintenance

Links are checked automatically every week (see `.github/workflows/link-check.yml`). A dead link on a failing check gets one fix cycle, then the entry is removed — a shorter list that works beats a longer list that doesn't.
