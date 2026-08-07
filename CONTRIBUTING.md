# Contributing

Thanks for helping keep this list useful. The bar is simple: would you send this link to a founder friend who asked for help?

## What belongs here

- Resources you have actually read, watched or used.
- Tools that a startup at any stage would plausibly adopt, not every tool in a category.
- Writing that still holds up. Age is fine; being outdated is not.

## What does not belong here

- Affiliate, referral or UTM-tagged links.
- Your own product, unless it is genuinely one of the best options in its category and you disclose the affiliation in the pull request.
- Marketing copy. Describe what the thing does, not why it is amazing.
- Contact details, sales pitches or calls to action.
- Paywalled resources without noting the paywall.

## Format

One entry per line, in the existing style:

```markdown
- [Name](https://example.com) - What it does, in one sentence, ending with a period.
```

Rules that keep the file consistent:

- Use `-` for bullets, never `*`.
- Use `https://` when the site supports it.
- Link to the canonical URL, not a redirect.
- Keep descriptions under about 25 words. Longer explanations belong in the linked resource.
- Add entries to the most specific existing section. Propose a new section only when you have three or more entries for it.
- Keep sections roughly alphabetical or ordered by usefulness, matching what is already there.

## Before opening a pull request

1. Check the link works and does not redirect elsewhere.
2. Search the file for the resource. Duplicates across sections are the most common problem with lists like this one.
3. Keep the pull request focused. One theme per pull request is easier to review than a large mixed change.

## Removing things

Removals are as valuable as additions. Open a pull request if a link is dead, a company has shut down or pivoted away from what we describe, or a tool no longer has a tier a startup can afford. Say what you verified in the description.

A [weekly GitHub Actions workflow](.github/workflows/link-check.yml) checks every link and opens an issue when something breaks, so you can also just pick up whatever it reports.
